# Overview: prod
*Last updated: 2026-05-21 13:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T13:31 (292 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,312 | avg: 15,700 | max: 84,644 | trend: INCREASING (+7.88/hr))
```
▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 185.0MB | avg: 236.3MB | max: 1896.6MB | trend: stable (+0.23MB/hr))
```
▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▇▂▂▁▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▂▁▁▂▂▁▄▂▁▁▂▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,312 | 16,134 | -1822 | 15,700 | 84,644 | INCREASING (+7.88/hr) |
| Heap InUse | 185.0MB | 268.8MB | -83.8MB | 236.3MB | 1896.6MB | stable (+0.23MB/hr) |
| Heap Sys | 4891.0MB | 4085.5MB | +805.5MB | 4208.9MB | 6579.6MB | |
| Heap Objects | 624,647 | 1,044,963 | -420316 | 996,279 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 36 | 15,689 | 241.7MB | 501.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 35.36MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 7.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `bufio.NewReaderSize` | 3.01MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 9 | `reflect.growslice` | 1.7MB |
| 10 | `bytes.growSlice` | 1.59MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 66.09GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 39.64GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 39.63GB |
| 4 | `experiment/local.topologicalSort` | 26.22GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 20.82GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 12.74GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 12.11GB |
| 8 | `reflect.growslice` | 6.77GB |
| 9 | `jackskj/carta.getUniqueId` | 6.49GB |
| 10 | `fmt.Sprintf` | 6.1GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.01MB | 8/292 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.22MB | 14/292 | `███████████░░░░ 79%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 290/292 | `█████████░░░░░░ 63%` |
| 4 | `database/sql.convertAssignRows` | 32.63MB | 16/292 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 23.98MB | 290/292 | `██████░░░░░░░░░ 41%` |
| 6 | `net/http.(*Transport).dialConn` | 13.7MB | 5/292 | `███░░░░░░░░░░░░ 23%` |
| 7 | `bytes.growSlice` | 13.64MB | 201/292 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 13.61MB | 5/292 | `███░░░░░░░░░░░░ 23%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.99MB | 43/292 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/292 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 113.86GB | 281/292 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 67.57GB | 287/292 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 67.55GB | 287/292 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 55.76GB | 268/292 | `███████░░░░░░░░ 48%` |
| 5 | `experiment/local.topologicalSort` | 47.04GB | 269/292 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 41.28GB | 237/292 | `█████░░░░░░░░░░ 36%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 27.05GB | 237/292 | `███░░░░░░░░░░░░ 23%` |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 26.9GB | 213/292 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/292 | `███░░░░░░░░░░░░ 21%` |
| 10 | `segmentio/kafka-go.makePartitions` | 17.89GB | 145/292 | `██░░░░░░░░░░░░░ 15%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.3x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
