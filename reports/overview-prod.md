# Overview: prod
*Last updated: 2026-05-19 21:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T21:31 (204 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,593 | avg: 15,395 | max: 84,644 | trend: decreasing (-2.61/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▅▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▂▃▄▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▄▁▁▁▁▁▁▁▁▁▂▁▁▂▁▃▁▁▁
```

**Heap InUse** (current: 184.3MB | avg: 230.8MB | max: 1896.6MB | trend: stable (+0.17MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▃▃▅▃▂▃▂▂▃▄▃▃▂▃▄▃▃▂▄▄▄▃█▂▃▃▂▃▃▃▂▃▂▂▄▁▁▁▁▁▁▁▄▁▁▁▁▁▁▂▇▂▁▂▁▅▁▁▂▂▂▁▂▃▅▃▂▁▂▂▃▂▃▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,593 | 15,273 | -680 | 15,395 | 84,644 | decreasing (-2.61/hr) |
| Heap InUse | 184.3MB | 280.2MB | -95.9MB | 230.8MB | 1896.6MB | stable (+0.17MB/hr) |
| Heap Sys | 4942.8MB | 4941.7MB | +1.1MB | 4509.7MB | 6579.6MB | |
| Heap Objects | 762,447 | 1,317,574 | -555127 | 985,193 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 44 | 15,328 | 232.4MB | 661.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 20.22MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `bytes.growSlice` | 4.02MB |
| 6 | `reflect.unsafe_NewArray` | 3.52MB |
| 7 | `internal/evaluation.mergeMetadata` | 3.5MB |
| 8 | `bufio.NewReaderSize` | 2.52MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `experiment/local.(*Client).EvaluateV2` | 2.16MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 216.29GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 130.05GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 129.79GB |
| 4 | `experiment/local.topologicalSort` | 86.19GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 67.34GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 61.73GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 41.05GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 28.37GB |
| 9 | `fmt.Sprintf` | 22.01GB |
| 10 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 20.91GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 69.11MB | 6/204 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.54MB | 11/204 | `█████████░░░░░░ 65%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 202/204 | `███████░░░░░░░░ 53%` |
| 4 | `database/sql.convertAssignRows` | 35.58MB | 12/204 | `███████░░░░░░░░ 51%` |
| 5 | `runtime.mallocgc` | 25.72MB | 202/204 | `█████░░░░░░░░░░ 37%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/204 | `████░░░░░░░░░░░ 26%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/204 | `██░░░░░░░░░░░░░ 19%` |
| 8 | `bytes.growSlice` | 11.97MB | 127/204 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.05MB | 21/204 | `██░░░░░░░░░░░░░ 15%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 200/204 | `██░░░░░░░░░░░░░ 13%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 121.1GB | 193/204 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.43GB | 199/204 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.34GB | 199/204 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 66.25GB | 194/204 | `████████░░░░░░░ 54%` |
| 5 | `experiment/local.topologicalSort` | 50.9GB | 181/204 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 47.46GB | 149/204 | `█████░░░░░░░░░░ 39%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 32.19GB | 127/204 | `███░░░░░░░░░░░░ 26%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 30.02GB | 185/204 | `███░░░░░░░░░░░░ 24%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/204 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `fmt.Sprintf` | 23.4GB | 64/204 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
