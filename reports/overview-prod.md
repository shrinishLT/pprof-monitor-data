# Overview: prod
*Last updated: 2026-06-10 19:31 IST*
*Data range: 2026-05-15T16:03 to 2026-06-10T19:30 (2915 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,171 | avg: 14,103 | max: 84,644 | trend: INCREASING (+4.08/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▃▃▃▂▁▁▂▂▂▃▂▂▁▁▁▁▄▇█▇▆▂▁▁▁▂▂▂▂▁▂▁▁▃▂▁▂▂▁▂▂▂▁▁▁▂▂▂▂▁▁▁▂▅▂▁▁▁▁▁▁▁▃▄▁▂▃▃▃▂▂▂▂▂▂▂▂▂▂▁▁▂▁▁
```

**Heap InUse** (current: 223.2MB | avg: 228.0MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▂▃▁▄▁▁▂▂▂▂▂▄▄▄▃▅▃▃▃▃▄▅▃▃▄▁▁▁▆█▇▆▆▆▃▄▂▃▂▃▃▂▆▂▂▃▃▄▃▃▂▄▂▂▃▁▃▅▄▅▂▃▂▃▄▅▄▂▁▃▁▃▁▁▃▅▂▂▄▆▅▄▄▄▃▃▂▃▂▄▅▄▄▅▃▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,171 | 14,360 | -189 | 14,103 | 84,644 | INCREASING (+4.08/hr) |
| Heap InUse | 223.2MB | 254.2MB | -31.0MB | 228.0MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3345.5MB | 3345.2MB | +0.3MB | 2580.2MB | 6883.9MB | |
| Heap Objects | 982,280 | 1,231,386 | -249106 | 987,039 | 17,165,538 | |

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
| 2026-06-10 | 234 | 16,703 | 310.2MB | 1442.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `bytes.growSlice` | 2.28MB |
| 8 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 2.13MB |
| 9 | `bufio.NewWriterSize` | 2.02MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 139.93GB |
| 2 | `reflect.growslice` | 138.41GB |
| 3 | `jackskj/carta.getUniqueId` | 123.87GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 112.78GB |
| 5 | `reflect.unsafe_New` | 109.62GB |
| 6 | `fmt.Sprintf` | 95.84GB |
| 7 | `fmt.(*buffer).writeString` | 87.32GB |
| 8 | `carta/value.NewCell` | 78.37GB |
| 9 | `reflect.unsafe_NewArray` | 71.51GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 58.52GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 7.25GB | 7.24GB | 7.05GB | 0B |
| `evaluation.mergeMetadata` | 3.81GB | 3.80GB | 3.70GB | 0B |
| `local.(*Client).EvaluateV2` | 11.05GB | 11.05GB | 10.75GB | 0B |
| `local.topologicalSort` | 1.54GB | 1.54GB | 1.50GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 10.54GB | 10.53GB | 10.26GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.52GB | 1.52GB | 1.47GB | 0B |
| `localEvaluation.getMapOfValue` | 10.54GB | 10.53GB | 10.26GB | 0B |
| `utils.ParseFeatureFlag` | 10.55GB | 10.55GB | 10.28GB | 0B |

**Total FF alloc (current snapshot):** 56.80GB  |  **24h avg:** 55.27GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 66.73MB | 52/2915 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 54.51MB | 80/2915 | `████████████░░░ 81%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2566/2915 | `████████░░░░░░░ 54%` |
| 4 | `runtime.mallocgc` | 29.34MB | 2566/2915 | `██████░░░░░░░░░ 43%` |
| 5 | `database/sql.convertAssignRows` | 28.37MB | 101/2915 | `██████░░░░░░░░░ 42%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2915 | `████░░░░░░░░░░░ 26%` |
| 7 | `bytes.growSlice` | 15.72MB | 1974/2915 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).dialConn` | 14.56MB | 60/2915 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2915 | `███░░░░░░░░░░░░ 21%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2915 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2915 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2915 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2915 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 52.03GB | 1432/2915 | `██████░░░░░░░░░ 41%` |
| 5 | `experiment/local.topologicalSort` | 51.23GB | 375/2915 | `██████░░░░░░░░░ 40%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2915 | `█████░░░░░░░░░░ 34%` |
| 7 | `segmentio/kafka-go.makePartitions` | 42.71GB | 2289/2915 | `█████░░░░░░░░░░ 34%` |
| 8 | `reflect.growslice` | 41.8GB | 2127/2915 | `█████░░░░░░░░░░ 33%` |
| 9 | `jackskj/carta.getUniqueId` | 36.46GB | 2143/2915 | `████░░░░░░░░░░░ 29%` |
| 10 | `reflect.unsafe_New` | 35.86GB | 1907/2915 | `████░░░░░░░░░░░ 28%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.5x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.2x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.7x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.4x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.5x avg)
