# Overview: prod
*Last updated: 2026-05-25 03:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-25T03:30 (478 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,183 | avg: 15,587 | max: 84,644 | trend: decreasing (-1.59/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 153.8MB | avg: 227.8MB | max: 1896.6MB | trend: stable (-0.17MB/hr))
```
▁▁▁▁▄▁▁▁▁▁▁▂▃▂▂▂▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▂▇▃▃▃▂▄▁▁▁▂▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,183 | 14,082 | +101 | 15,587 | 84,644 | decreasing (-1.59/hr) |
| Heap InUse | 153.8MB | 115.7MB | +38.1MB | 227.8MB | 1896.6MB | stable (-0.17MB/hr) |
| Heap Sys | 3571.9MB | 730.7MB | +2841.2MB | 4160.5MB | 6883.9MB | |
| Heap Objects | 991,682 | 579,115 | +412567 | 981,153 | 8,100,802 | |

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
| 2026-05-25 | 8 | 14,308 | 154.0MB | 208.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 9.58MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 7.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.04MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 3.0MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `reflect.unsafe_NewArray` | 2.0MB |
| 10 | `reflect.mapassign_faststr0` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 7.68GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 2.93GB |
| 3 | `segmentio/kafka-go.makePartitions` | 1.62GB |
| 4 | `go-sql-driver/mysql.(*binaryRows).readRow` | 1.06GB |
| 5 | `database/sql.convertAssignRows` | 893.54MB |
| 6 | `reflect.unsafe_NewArray` | 879.75MB |
| 7 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 749.56MB |
| 8 | `reflect.growslice` | 713.13MB |
| 9 | `jackskj/carta.getUniqueId` | 611.09MB |
| 10 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 603.57MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 52.69MB | 11/478 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 48.2MB | 18/478 | `█████████████░░ 91%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 476/478 | `██████████░░░░░ 69%` |
| 4 | `database/sql.convertAssignRows` | 30.41MB | 22/478 | `████████░░░░░░░ 57%` |
| 5 | `runtime.mallocgc` | 21.78MB | 476/478 | `██████░░░░░░░░░ 41%` |
| 6 | `bytes.growSlice` | 13.49MB | 310/478 | `███░░░░░░░░░░░░ 25%` |
| 7 | `net/http.(*Transport).dialConn` | 12.08MB | 6/478 | `███░░░░░░░░░░░░ 22%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.08MB | 7/478 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/478 | `███░░░░░░░░░░░░ 20%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/478 | `███░░░░░░░░░░░░ 20%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/478 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/478 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/478 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 51.41GB | 453/478 | `██████░░░░░░░░░ 41%` |
| 5 | `experiment/local.topologicalSort` | 51.23GB | 375/478 | `██████░░░░░░░░░ 40%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/478 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/478 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 23.7GB | 410/478 | `██░░░░░░░░░░░░░ 18%` |
| 9 | `fmt.Sprintf` | 18.14GB | 201/478 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `segmentio/kafka-go.makePartitions` | 15.72GB | 284/478 | `█░░░░░░░░░░░░░░ 12%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.5x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.2x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.2x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.7x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.4x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
