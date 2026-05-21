# Overview: prod
*Last updated: 2026-05-22 05:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-22T05:00 (337 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,166 | avg: 15,764 | max: 84,644 | trend: INCREASING (+6.93/hr))
```
▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁
```

**Heap InUse** (current: 165.6MB | avg: 241.9MB | max: 1896.6MB | trend: stable (+0.31MB/hr))
```
▁▃▁▁▁▂▁▂▄▂▂█▁▁▁▁▁▂▂▁▄▂▁▁▂▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▂▃▁▁▃▃▁▁▁▂▂▁▁▂▂▂▃▃▂▂▁▂▂▂▂▂▁▂▂▂▁▂▂▂▂▃▂▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,166 | 14,130 | +36 | 15,764 | 84,644 | INCREASING (+6.93/hr) |
| Heap InUse | 165.6MB | 195.6MB | -30.0MB | 241.9MB | 1896.6MB | stable (+0.31MB/hr) |
| Heap Sys | 4873.7MB | 4873.7MB | +0.0MB | 4298.5MB | 6579.6MB | |
| Heap Objects | 546,275 | 967,137 | -420862 | 1,009,901 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 68 | 16,073 | 267.1MB | 501.2MB |
| 2026-05-22 | 13 | 15,375 | 236.1MB | 432.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 35.36MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 7.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `reflect.mapassign_faststr0` | 2.0MB |
| 8 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 9 | `reflect.unsafe_NewArray` | 1.51MB |
| 10 | `encoding/json.typeFields` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 320.58GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 192.1GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 191.84GB |
| 4 | `experiment/local.topologicalSort` | 127.08GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 100.2GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 65.64GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 60.88GB |
| 8 | `fmt.Sprintf` | 33.41GB |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 30.39GB |
| 10 | `segmentio/kafka-go.makePartitions` | 25.14GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.01MB | 8/337 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 43.74MB | 15/337 | `███████████░░░░ 75%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 335/337 | `█████████░░░░░░ 63%` |
| 4 | `database/sql.convertAssignRows` | 30.82MB | 17/337 | `███████░░░░░░░░ 53%` |
| 5 | `runtime.mallocgc` | 25.51MB | 335/337 | `██████░░░░░░░░░ 43%` |
| 6 | `bytes.growSlice` | 14.02MB | 237/337 | `███░░░░░░░░░░░░ 24%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/337 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/337 | `███░░░░░░░░░░░░ 20%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.93MB | 48/337 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/337 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 126.41GB | 326/337 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 75.04GB | 332/337 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 75.03GB | 332/337 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 52.82GB | 313/337 | `██████░░░░░░░░░ 41%` |
| 5 | `experiment/local.topologicalSort` | 51.93GB | 314/337 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 44.92GB | 282/337 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 29.0GB | 258/337 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 25.68GB | 276/337 | `███░░░░░░░░░░░░ 20%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/337 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `fmt.Sprintf` | 18.73GB | 161/337 | `██░░░░░░░░░░░░░ 14%` |

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
