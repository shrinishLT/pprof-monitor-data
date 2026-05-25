# Overview: prod
*Last updated: 2026-05-26 00:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-26T00:02 (519 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,256 | avg: 15,591 | max: 84,644 | trend: decreasing (-1.16/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▇▁▁▁▁▁▂▃▁▃▁▁▃▁▁▂▂▁▂▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 232.8MB | avg: 230.9MB | max: 1896.6MB | trend: stable (-0.06MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▂▇▃▃▃▂▄▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▂▁▂▁▁▁▁▂▂▅▂▄▂▂▃▃▅▃▄▃▂▄▂▂▃▃▃▄▂▂▂▂▃▂▂▂▃▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,256 | 15,156 | -900 | 15,591 | 84,644 | decreasing (-1.16/hr) |
| Heap InUse | 232.8MB | 300.4MB | -67.6MB | 230.9MB | 1896.6MB | stable (-0.06MB/hr) |
| Heap Sys | 6109.4MB | 6107.3MB | +2.1MB | 4226.6MB | 6883.9MB | |
| Heap Objects | 1,002,407 | 1,339,547 | -337140 | 986,557 | 8,100,802 | |

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
| 2026-05-22 | 50 | 16,200 | 234.4MB | 962.7MB |
| 2026-05-23 | 48 | 14,757 | 174.9MB | 359.1MB |
| 2026-05-24 | 48 | 14,694 | 189.5MB | 689.3MB |
| 2026-05-25 | 48 | 15,445 | 248.9MB | 478.8MB |
| 2026-05-26 | 1 | 14,256 | 232.8MB | 232.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 58.12MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.5MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `bytes.growSlice` | 2.64MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `reflect.unsafe_NewArray` | 1.5MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 100.72GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 38.51GB |
| 3 | `reflect.growslice` | 30.24GB |
| 4 | `jackskj/carta.getUniqueId` | 27.55GB |
| 5 | `segmentio/kafka-go.makePartitions` | 26.48GB |
| 6 | `reflect.unsafe_New` | 24.11GB |
| 7 | `fmt.Sprintf` | 21.72GB |
| 8 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 19.32GB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 17.43GB |
| 10 | `carta/value.NewCell` | 17.41GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 47.44MB | 20/519 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 47.14MB | 13/519 | `██████████████░ 99%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 517/519 | `███████████░░░░ 77%` |
| 4 | `database/sql.convertAssignRows` | 28.6MB | 25/519 | `█████████░░░░░░ 60%` |
| 5 | `runtime.mallocgc` | 23.45MB | 517/519 | `███████░░░░░░░░ 49%` |
| 6 | `bytes.growSlice` | 13.27MB | 346/519 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*Transport).dialConn` | 12.08MB | 6/519 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.08MB | 7/519 | `███░░░░░░░░░░░░ 23%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/519 | `███░░░░░░░░░░░░ 22%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/519 | `███░░░░░░░░░░░░ 22%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/519 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/519 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/519 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 52.4GB | 494/519 | `██████░░░░░░░░░ 41%` |
| 5 | `experiment/local.topologicalSort` | 51.23GB | 375/519 | `██████░░░░░░░░░ 40%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/519 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/519 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 23.74GB | 451/519 | `██░░░░░░░░░░░░░ 18%` |
| 9 | `fmt.Sprintf` | 18.12GB | 221/519 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `segmentio/kafka-go.makePartitions` | 15.6GB | 319/519 | `█░░░░░░░░░░░░░░ 12%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.2x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.7x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.3x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
