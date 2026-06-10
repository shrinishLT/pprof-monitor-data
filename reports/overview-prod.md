# Overview: prod
*Last updated: 2026-06-10 14:57 IST*
*Data range: 2026-05-15T16:03 to 2026-06-10T14:57 (2860 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,881 | avg: 14,086 | max: 84,644 | trend: INCREASING (+4.25/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▄▃▄▅▆█▇▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 283.5MB | avg: 227.2MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▄▃▆▅▆█▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,881 | 15,569 | -688 | 14,086 | 84,644 | INCREASING (+4.25/hr) |
| Heap InUse | 283.5MB | 269.8MB | +13.7MB | 227.2MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3336.0MB | 3336.5MB | -0.5MB | 2565.6MB | 6883.9MB | |
| Heap Objects | 1,245,443 | 591,499 | +653944 | 984,743 | 17,165,538 | |

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
| 2026-06-10 | 179 | 17,228 | 321.8MB | 1442.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 11.42MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 6 | `bufio.NewWriterSize` | 5.03MB |
| 7 | `segmentio/kafka-go.makePartitions` | 5.02MB |
| 8 | `fmt.(*buffer).writeString` | 2.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 137.63GB |
| 2 | `segmentio/kafka-go.makePartitions` | 133.68GB |
| 3 | `jackskj/carta.getUniqueId` | 122.83GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 112.6GB |
| 5 | `reflect.unsafe_New` | 108.81GB |
| 6 | `fmt.Sprintf` | 92.52GB |
| 7 | `fmt.(*buffer).writeString` | 86.88GB |
| 8 | `carta/value.NewCell` | 77.84GB |
| 9 | `reflect.unsafe_NewArray` | 68.34GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 57.89GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 6.74GB | 6.73GB | 6.52GB | 0B |
| `evaluation.mergeMetadata` | 3.54GB | 3.53GB | 3.42GB | 0B |
| `local.(*Client).EvaluateV2` | 10.27GB | 10.25GB | 9.94GB | 0B |
| `local.topologicalSort` | 1.43GB | 1.43GB | 1.39GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 9.83GB | 9.81GB | 9.51GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.38GB | 1.38GB | 1.34GB | 0B |
| `localEvaluation.getMapOfValue` | 9.83GB | 9.81GB | 9.51GB | 0B |
| `utils.ParseFeatureFlag` | 9.85GB | 9.83GB | 9.53GB | 0B |

**Total FF alloc (current snapshot):** 52.86GB  |  **24h avg:** 51.15GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 71.38MB | 48/2860 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 56.12MB | 77/2860 | `███████████░░░░ 78%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2511/2860 | `███████░░░░░░░░ 51%` |
| 4 | `runtime.mallocgc` | 28.87MB | 2511/2860 | `██████░░░░░░░░░ 40%` |
| 5 | `database/sql.convertAssignRows` | 28.64MB | 99/2860 | `██████░░░░░░░░░ 40%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2860 | `███░░░░░░░░░░░░ 25%` |
| 7 | `bytes.growSlice` | 15.91MB | 1923/2860 | `███░░░░░░░░░░░░ 22%` |
| 8 | `net/http.(*Transport).dialConn` | 14.56MB | 60/2860 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2860 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2860 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2860 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2860 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2860 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2860 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 49.61GB | 1377/2860 | `█████░░░░░░░░░░ 39%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2860 | `█████░░░░░░░░░░ 34%` |
| 7 | `segmentio/kafka-go.makePartitions` | 40.39GB | 2234/2860 | `████░░░░░░░░░░░ 32%` |
| 8 | `reflect.growslice` | 39.24GB | 2072/2860 | `████░░░░░░░░░░░ 31%` |
| 9 | `jackskj/carta.getUniqueId` | 34.16GB | 2088/2860 | `████░░░░░░░░░░░ 27%` |
| 10 | `reflect.unsafe_New` | 33.68GB | 1852/2860 | `████░░░░░░░░░░░ 26%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.0x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.5x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.2x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.7x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.4x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.5x avg)
