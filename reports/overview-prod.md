# Overview: prod
*Last updated: 2026-05-19 22:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T22:30 (206 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,231 | avg: 15,388 | max: 84,644 | trend: decreasing (-2.98/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▅▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▂▃▄▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▄▁▁▁▁▁▁▁▁▁▂▁▁▂▁▃▁▁▁▁▁
```

**Heap InUse** (current: 171.0MB | avg: 230.3MB | max: 1896.6MB | trend: stable (+0.13MB/hr))
```
▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▃▃▅▃▂▃▂▂▃▄▃▃▂▃▄▃▃▂▄▄▄▃█▂▃▃▂▃▃▃▂▃▂▂▄▁▁▁▁▁▁▁▄▁▁▁▁▁▁▂▇▂▁▂▁▅▁▁▂▂▂▁▂▃▅▃▂▁▂▂▃▂▃▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,231 | 14,985 | -754 | 15,388 | 84,644 | decreasing (-2.98/hr) |
| Heap InUse | 171.0MB | 191.5MB | -20.5MB | 230.3MB | 1896.6MB | stable (+0.13MB/hr) |
| Heap Sys | 4943.7MB | 4943.9MB | -0.2MB | 4513.9MB | 6579.6MB | |
| Heap Objects | 802,164 | 649,972 | +152192 | 982,677 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 46 | 15,297 | 230.2MB | 661.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 20.22MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 5.29MB |
| 6 | `bufio.NewReaderSize` | 3.04MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `bytes.growSlice` | 2.01MB |
| 9 | `reflect.unsafe_NewArray` | 1.51MB |
| 10 | `aws/endpoints.init` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 228.23GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 137.2GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 136.97GB |
| 4 | `experiment/local.topologicalSort` | 90.99GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 70.98GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 61.76GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 43.31GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 28.39GB |
| 9 | `fmt.Sprintf` | 23.3GB |
| 10 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 21.19GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 69.11MB | 6/206 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.54MB | 11/206 | `█████████░░░░░░ 65%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 204/206 | `███████░░░░░░░░ 53%` |
| 4 | `database/sql.convertAssignRows` | 35.58MB | 12/206 | `███████░░░░░░░░ 51%` |
| 5 | `runtime.mallocgc` | 25.67MB | 204/206 | `█████░░░░░░░░░░ 37%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/206 | `████░░░░░░░░░░░ 26%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/206 | `██░░░░░░░░░░░░░ 19%` |
| 8 | `bytes.growSlice` | 11.85MB | 129/206 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.05MB | 21/206 | `██░░░░░░░░░░░░░ 15%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 202/206 | `██░░░░░░░░░░░░░ 13%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 122.18GB | 195/206 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 72.08GB | 201/206 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.99GB | 201/206 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 66.2GB | 196/206 | `████████░░░░░░░ 54%` |
| 5 | `experiment/local.topologicalSort` | 51.33GB | 183/206 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 47.77GB | 151/206 | `█████░░░░░░░░░░ 39%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 32.36GB | 129/206 | `███░░░░░░░░░░░░ 26%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 30.0GB | 187/206 | `███░░░░░░░░░░░░ 24%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/206 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `fmt.Sprintf` | 23.4GB | 66/206 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
