# Overview: prod
*Last updated: 2026-05-21 23:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T23:00 (321 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,594 | avg: 15,784 | max: 84,644 | trend: INCREASING (+8.83/hr))
```
▁▁▁▃▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 199.7MB | avg: 242.0MB | max: 1896.6MB | trend: stable (+0.36MB/hr))
```
▁▁▁▂▇▂▂▁▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▁▁▁▂▂▁▄▂▁▁▂▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▂▃▁▁▃▃▁▁▁▂▂▁▁▂▂▂▃▃▂▂▁▂▂▂▂▂▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,594 | 16,140 | -1546 | 15,784 | 84,644 | INCREASING (+8.83/hr) |
| Heap InUse | 199.7MB | 301.7MB | -102.0MB | 242.0MB | 1896.6MB | stable (+0.36MB/hr) |
| Heap Sys | 4885.2MB | 4884.9MB | +0.3MB | 4269.6MB | 6579.6MB | |
| Heap Objects | 678,858 | 1,262,813 | -583955 | 1,014,393 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 65 | 16,108 | 267.4MB | 501.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 35.36MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 7.0MB |
| 5 | `bytes.growSlice` | 4.71MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 8 | `compress/flate.NewWriter` | 1.76MB |
| 9 | `segmentio/kafka-go.makePartitions` | 1.53MB |
| 10 | `reflect.unsafe_NewArray` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 254.62GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 152.8GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 152.37GB |
| 4 | `experiment/local.topologicalSort` | 100.92GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 79.64GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 48.38GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 39.54GB |
| 8 | `fmt.Sprintf` | 26.69GB |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 18.24GB |
| 10 | `segmentio/kafka-go.makePartitions` | 17.22GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.01MB | 8/321 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.22MB | 14/321 | `███████████░░░░ 79%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 319/321 | `█████████░░░░░░ 63%` |
| 4 | `database/sql.convertAssignRows` | 32.63MB | 16/321 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 25.01MB | 319/321 | `██████░░░░░░░░░ 43%` |
| 6 | `bytes.growSlice` | 13.93MB | 230/321 | `███░░░░░░░░░░░░ 24%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/321 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/321 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/321 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.66MB | 46/321 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 118.03GB | 310/321 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 70.09GB | 316/321 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 70.07GB | 316/321 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 52.82GB | 297/321 | `██████░░░░░░░░░ 44%` |
| 5 | `experiment/local.topologicalSort` | 48.58GB | 298/321 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 42.19GB | 266/321 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 27.29GB | 242/321 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 25.76GB | 260/321 | `███░░░░░░░░░░░░ 21%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/321 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.Sprintf` | 17.46GB | 145/321 | `██░░░░░░░░░░░░░ 14%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
