# Overview: prod
*Last updated: 2026-05-21 23:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T23:02 (322 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,543 | avg: 15,780 | max: 84,644 | trend: INCREASING (+8.61/hr))
```
▁▁▃▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 255.3MB | avg: 242.0MB | max: 1896.6MB | trend: stable (+0.36MB/hr))
```
▁▁▂▇▂▂▁▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▁▁▁▂▂▁▄▂▁▁▂▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▂▃▁▁▃▃▁▁▁▂▂▁▁▂▂▂▃▃▂▂▁▂▂▂▂▂▁▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,543 | 14,594 | -51 | 15,780 | 84,644 | INCREASING (+8.61/hr) |
| Heap InUse | 255.3MB | 199.7MB | +55.6MB | 242.0MB | 1896.6MB | stable (+0.36MB/hr) |
| Heap Sys | 4885.7MB | 4885.2MB | +0.5MB | 4271.5MB | 6579.6MB | |
| Heap Objects | 1,216,261 | 678,858 | +537403 | 1,015,020 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 66 | 16,085 | 267.2MB | 501.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 35.36MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 7.0MB |
| 5 | `bytes.growSlice` | 5.21MB |
| 6 | `internal/evaluation.mergeMetadata` | 4.5MB |
| 7 | `experiment/local.(*Client).EvaluateV2` | 3.13MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.51MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `internal/evaluation.(*Engine).Evaluate` | 2.09MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 254.8GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 152.9GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 152.47GB |
| 4 | `experiment/local.topologicalSort` | 100.99GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 79.7GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 48.41GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 39.54GB |
| 8 | `fmt.Sprintf` | 26.72GB |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 18.24GB |
| 10 | `segmentio/kafka-go.makePartitions` | 17.26GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.01MB | 8/322 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.22MB | 14/322 | `███████████░░░░ 79%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 320/322 | `█████████░░░░░░ 63%` |
| 4 | `database/sql.convertAssignRows` | 32.63MB | 16/322 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 25.05MB | 320/322 | `██████░░░░░░░░░ 43%` |
| 6 | `bytes.growSlice` | 13.9MB | 231/322 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/322 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/322 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/322 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.53MB | 47/322 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 118.47GB | 311/322 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 70.35GB | 317/322 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 70.34GB | 317/322 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 52.78GB | 298/322 | `██████░░░░░░░░░ 44%` |
| 5 | `experiment/local.topologicalSort` | 48.75GB | 299/322 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 42.33GB | 267/322 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 27.38GB | 243/322 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 25.73GB | 261/322 | `███░░░░░░░░░░░░ 21%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/322 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.Sprintf` | 17.52GB | 146/322 | `██░░░░░░░░░░░░░ 14%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
