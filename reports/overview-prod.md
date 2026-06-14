# Overview: prod
*Last updated: 2026-06-14 07:40 IST*
*Data range: 2026-05-15T16:03 to 2026-06-14T07:40 (3925 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,179 | avg: 14,632 | max: 84,644 | trend: INCREASING (+2.87/hr))
```
▃▃▄▄▅▄▄▆▆▆▄▇▅▅▅▆▅▆▆▆▇▆▇▅▇▆▇▇▇▅▇▆▅▆▅▅▅▅▅▇▆▅▇▄▅▅▇▆▅▆▅▇▅█▅▄▄▃▅▄▄▄▄▇▅▄▃▅▄▅▂▁▁▁▁▁▂▂▂▃▇▂▃▁▁▁▁▂▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 199.6MB | avg: 241.2MB | max: 3154.1MB | trend: stable (+0.07MB/hr))
```
▂▂▂▂▄▂▂▂▂▄▂▄▃▂▄▄▂▂▄▂▃▃▄▄▃▃▃▃▃▃▃▄▂▂▂▃▂▂▃▄▃▂▃▃▂▂▄▂▂▂▄▃▃▃▃█▃▂▂▂▃▂▃▂▄▃▂▃▃▂▁▁▁▂▁▂▂▂▁▃▄▂▃▂▁▁▁▂▂▁▂▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,179 | 14,251 | -72 | 14,632 | 84,644 | INCREASING (+2.87/hr) |
| Heap InUse | 199.6MB | 203.6MB | -4.0MB | 241.2MB | 3154.1MB | stable (+0.07MB/hr) |
| Heap Sys | 2297.8MB | 2297.7MB | +0.1MB | 2539.1MB | 6883.9MB | |
| Heap Objects | 970,620 | 1,059,029 | -88409 | 1,036,261 | 17,165,538 | |

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
| 2026-05-26 | 46 | 15,843 | 216.2MB | 639.8MB |
| 2026-05-27 | 47 | 11,771 | 179.8MB | 615.8MB |
| 2026-05-28 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-05-29 | 49 | 370 | 6.8MB | 333.9MB |
| 2026-05-30 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-05-31 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-06-01 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-06-02 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-06-03 | 54 | 2,097 | 29.7MB | 299.4MB |
| 2026-06-04 | 288 | 16,555 | 265.7MB | 2823.8MB |
| 2026-06-05 | 287 | 15,969 | 239.1MB | 3154.1MB |
| 2026-06-06 | 288 | 15,841 | 221.6MB | 1932.8MB |
| 2026-06-07 | 288 | 15,421 | 234.3MB | 1942.9MB |
| 2026-06-08 | 288 | 16,327 | 305.6MB | 2130.6MB |
| 2026-06-09 | 288 | 16,163 | 304.7MB | 1487.7MB |
| 2026-06-10 | 287 | 16,453 | 305.9MB | 1442.9MB |
| 2026-06-11 | 288 | 16,393 | 314.0MB | 1403.5MB |
| 2026-06-12 | 288 | 16,142 | 260.8MB | 1418.7MB |
| 2026-06-13 | 288 | 16,274 | 264.7MB | 1566.3MB |
| 2026-06-14 | 93 | 15,587 | 268.7MB | 547.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 30.86MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `compress/flate.NewWriter` | 6.17MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 8 | `bytes.growSlice` | 1.51MB |
| 9 | `internal/sync.runtime_SemacquireMutex` | 1.5MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 1.06MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 59.85GB |
| 2 | `reflect.growslice` | 59.39GB |
| 3 | `jackskj/carta.getUniqueId` | 54.57GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 53.83GB |
| 5 | `reflect.unsafe_New` | 47.47GB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 47.01GB |
| 7 | `fmt.Sprintf` | 44.81GB |
| 8 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 38.66GB |
| 9 | `fmt.(*buffer).writeString` | 37.23GB |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 36.51GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 2.47GB | 2.47GB | 2.39GB | 0B |
| `evaluation.mergeMetadata` | 1.27GB | 1.27GB | 1.23GB | 0B |
| `local.(*Client).EvaluateV2` | 3.79GB | 3.79GB | 3.68GB | 0B |
| `local.topologicalSort` | 550.92MB | 550.41MB | 537.02MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 3.73GB | 3.72GB | 3.61GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 441.69MB | 441.69MB | 433.21MB | 0B |
| `localEvaluation.getMapOfValue` | 3.73GB | 3.72GB | 3.61GB | 0B |
| `utils.ParseFeatureFlag` | 3.74GB | 3.73GB | 3.62GB | 0B |

**Total FF alloc (current snapshot):** 19.70GB  |  **24h avg:** 19.10GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 46.31MB | 79/3925 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 41.22MB | 109/3925 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3576/3925 | `███████████░░░░ 79%` |
| 4 | `runtime.mallocgc` | 31.23MB | 3576/3925 | `██████████░░░░░ 67%` |
| 5 | `database/sql.convertAssignRows` | 23.09MB | 129/3925 | `███████░░░░░░░░ 49%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3925 | `█████░░░░░░░░░░ 38%` |
| 7 | `bytes.growSlice` | 15.7MB | 2822/3925 | `█████░░░░░░░░░░ 33%` |
| 8 | `net/http.(*Transport).dialConn` | 13.13MB | 102/3925 | `████░░░░░░░░░░░ 28%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/3925 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3925 | `███░░░░░░░░░░░░ 22%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3925 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3925 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3925 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 69.3GB | 2114/3925 | `████████░░░░░░░ 55%` |
| 5 | `segmentio/kafka-go.makePartitions` | 59.02GB | 3299/3925 | `███████░░░░░░░░ 47%` |
| 6 | `reflect.growslice` | 58.9GB | 3137/3925 | `███████░░░░░░░░ 47%` |
| 7 | `jackskj/carta.getUniqueId` | 52.35GB | 3153/3925 | `██████░░░░░░░░░ 41%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/3925 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 49.74GB | 2917/3925 | `█████░░░░░░░░░░ 39%` |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 45.9GB | 1498/3925 | `█████░░░░░░░░░░ 36%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.8x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.3x avg)
