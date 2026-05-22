# Overview: prod
*Last updated: 2026-05-22 05:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-22T05:30 (338 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,132 | avg: 15,759 | max: 84,644 | trend: INCREASING (+6.70/hr))
```
▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 173.7MB | avg: 241.7MB | max: 1896.6MB | trend: stable (+0.30MB/hr))
```
▃▁▁▁▂▁▂▄▂▂█▁▁▁▁▁▂▂▁▄▂▁▁▂▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▂▃▁▁▃▃▁▁▁▂▂▁▁▂▂▂▃▃▂▂▁▂▂▂▂▂▁▂▂▂▁▂▂▂▂▃▂▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,132 | 14,166 | -34 | 15,759 | 84,644 | INCREASING (+6.70/hr) |
| Heap InUse | 173.7MB | 165.6MB | +8.1MB | 241.7MB | 1896.6MB | stable (+0.30MB/hr) |
| Heap Sys | 5049.8MB | 4873.7MB | +176.1MB | 4300.7MB | 6579.6MB | |
| Heap Objects | 617,519 | 546,275 | +71244 | 1,008,740 | 8,100,802 | |

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
| 2026-05-22 | 14 | 15,286 | 231.6MB | 432.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 35.36MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `reflect.growslice` | 9.17MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 7.0MB |
| 6 | `reflect.unsafe_New` | 5.0MB |
| 7 | `jackskj/carta.getUniqueId` | 4.0MB |
| 8 | `segmentio/kafka-go.makePartitions` | 3.03MB |
| 9 | `compress/flate.NewWriter` | 2.64MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 322.24GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 193.1GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 192.83GB |
| 4 | `experiment/local.topologicalSort` | 127.73GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 100.71GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 70.57GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 61.2GB |
| 8 | `fmt.Sprintf` | 33.59GB |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 32.67GB |
| 10 | `segmentio/kafka-go.makePartitions` | 25.79GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.01MB | 8/338 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 43.74MB | 15/338 | `███████████░░░░ 75%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 336/338 | `█████████░░░░░░ 63%` |
| 4 | `database/sql.convertAssignRows` | 30.82MB | 17/338 | `███████░░░░░░░░ 53%` |
| 5 | `runtime.mallocgc` | 25.54MB | 336/338 | `██████░░░░░░░░░ 44%` |
| 6 | `bytes.growSlice` | 14.02MB | 237/338 | `███░░░░░░░░░░░░ 24%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/338 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/338 | `███░░░░░░░░░░░░ 20%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.93MB | 48/338 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/338 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 127.01GB | 327/338 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 75.39GB | 333/338 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 75.39GB | 333/338 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 52.88GB | 314/338 | `██████░░░░░░░░░ 41%` |
| 5 | `experiment/local.topologicalSort` | 52.17GB | 315/338 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 45.12GB | 283/338 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 29.13GB | 259/338 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 25.71GB | 277/338 | `███░░░░░░░░░░░░ 20%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/338 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprintf` | 18.82GB | 162/338 | `██░░░░░░░░░░░░░ 14%` |

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
