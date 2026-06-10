# Overview: prod
*Last updated: 2026-06-10 08:50 IST*
*Data range: 2026-05-15T16:03 to 2026-06-10T08:50 (2788 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,154 | avg: 13,962 | max: 84,644 | trend: INCREASING (+4.05/hr))
```
▁▁▁▂▅█▇▅▂▁▁▄▃▃▄▄▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 222.2MB | avg: 223.7MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▁▁▁▂▅█▆▅▃▁▁▄▃▃▄▄▃▃▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,154 | 14,143 | +11 | 13,962 | 84,644 | INCREASING (+4.05/hr) |
| Heap InUse | 222.2MB | 281.3MB | -59.1MB | 223.7MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3346.2MB | 3346.3MB | -0.1MB | 2546.2MB | 6883.9MB | |
| Heap Objects | 1,067,507 | 1,849,088 | -781581 | 975,487 | 17,165,538 | |

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
| 2026-06-10 | 107 | 16,110 | 295.4MB | 1004.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `compress/flate.(*compressor).initDeflate` | 2.67MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `bytes.growSlice` | 1.57MB |
| 10 | `segmentio/kafka-go.makePartitions` | 1.53MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 125.19GB |
| 2 | `reflect.growslice` | 119.86GB |
| 3 | `jackskj/carta.getUniqueId` | 106.22GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 98.72GB |
| 5 | `reflect.unsafe_New` | 94.34GB |
| 6 | `fmt.Sprintf` | 83.55GB |
| 7 | `fmt.(*buffer).writeString` | 76.21GB |
| 8 | `carta/value.NewCell` | 67.32GB |
| 9 | `reflect.unsafe_NewArray` | 64.03GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 51.87GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 6.17GB | 6.17GB | 6.06GB | 0B |
| `evaluation.mergeMetadata` | 3.24GB | 3.24GB | 3.19GB | 0B |
| `local.(*Client).EvaluateV2` | 9.41GB | 9.40GB | 9.24GB | 0B |
| `local.topologicalSort` | 1.31GB | 1.30GB | 1.28GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 8.99GB | 8.98GB | 8.81GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.28GB | 1.28GB | 1.27GB | 0B |
| `localEvaluation.getMapOfValue` | 8.99GB | 8.98GB | 8.81GB | 0B |
| `utils.ParseFeatureFlag` | 9.00GB | 8.99GB | 8.83GB | 0B |

**Total FF alloc (current snapshot):** 48.39GB  |  **24h avg:** 47.49GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 72.79MB | 47/2788 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 56.76MB | 76/2788 | `███████████░░░░ 77%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2439/2788 | `███████░░░░░░░░ 50%` |
| 4 | `database/sql.convertAssignRows` | 28.88MB | 98/2788 | `█████░░░░░░░░░░ 39%` |
| 5 | `runtime.mallocgc` | 28.24MB | 2439/2788 | `█████░░░░░░░░░░ 38%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2788 | `███░░░░░░░░░░░░ 24%` |
| 7 | `bytes.growSlice` | 15.41MB | 1856/2788 | `███░░░░░░░░░░░░ 21%` |
| 8 | `net/http.(*Transport).dialConn` | 14.27MB | 55/2788 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2788 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2788 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2788 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2788 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2788 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2788 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 46.36GB | 1305/2788 | `█████░░░░░░░░░░ 37%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2788 | `█████░░░░░░░░░░ 34%` |
| 7 | `segmentio/kafka-go.makePartitions` | 37.43GB | 2162/2788 | `████░░░░░░░░░░░ 29%` |
| 8 | `reflect.growslice` | 35.92GB | 2000/2788 | `████░░░░░░░░░░░ 28%` |
| 9 | `jackskj/carta.getUniqueId` | 31.21GB | 2016/2788 | `███░░░░░░░░░░░░ 24%` |
| 10 | `reflect.unsafe_New` | 30.84GB | 1780/2788 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.5x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.1x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.0x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.0x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.5x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.3x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.8x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.5x avg)
