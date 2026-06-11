# Overview: prod
*Last updated: 2026-06-11 12:21 IST*
*Data range: 2026-05-15T16:03 to 2026-06-11T12:20 (3117 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,256 | avg: 14,243 | max: 84,644 | trend: INCREASING (+3.86/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▃▄▆▆█▇▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 291.3MB | avg: 233.0MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▃▃▃▅▇▇█▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,256 | 14,230 | +26 | 14,243 | 84,644 | INCREASING (+3.86/hr) |
| Heap InUse | 291.3MB | 266.6MB | +24.7MB | 233.0MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3313.2MB | 3313.2MB | +0.0MB | 2628.9MB | 6883.9MB | |
| Heap Objects | 1,679,437 | 1,413,353 | +266084 | 1,005,797 | 17,165,538 | |

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
| 2026-06-11 | 149 | 16,579 | 311.7MB | 1403.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `compress/flate.NewWriter` | 5.29MB |
| 6 | `bufio.NewWriterSize` | 3.07MB |
| 7 | `jackskj/carta.getUniqueId` | 3.0MB |
| 8 | `bytes.growSlice` | 2.52MB |
| 9 | `segmentio/kafka-go.makePartitions` | 2.52MB |
| 10 | `reflect.growslice` | 2.37MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 172.8GB |
| 2 | `segmentio/kafka-go.makePartitions` | 163.22GB |
| 3 | `jackskj/carta.getUniqueId` | 156.18GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 141.06GB |
| 5 | `reflect.unsafe_New` | 137.71GB |
| 6 | `fmt.Sprintf` | 119.78GB |
| 7 | `fmt.(*buffer).writeString` | 109.14GB |
| 8 | `carta/value.NewCell` | 98.4GB |
| 9 | `reflect.unsafe_NewArray` | 83.34GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 78.79GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 8.58GB | 8.58GB | 8.42GB | 0B |
| `evaluation.mergeMetadata` | 4.48GB | 4.48GB | 4.40GB | 0B |
| `local.(*Client).EvaluateV2` | 13.08GB | 13.08GB | 12.82GB | 0B |
| `local.topologicalSort` | 1.82GB | 1.82GB | 1.77GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 12.52GB | 12.51GB | 12.26GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.76GB | 1.76GB | 1.74GB | 0B |
| `localEvaluation.getMapOfValue` | 12.52GB | 12.51GB | 12.26GB | 0B |
| `utils.ParseFeatureFlag` | 12.54GB | 12.53GB | 12.28GB | 0B |

**Total FF alloc (current snapshot):** 67.30GB  |  **24h avg:** 65.95GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 59.59MB | 59/3117 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 51.07MB | 86/3117 | `████████████░░░ 85%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2768/3117 | `█████████░░░░░░ 61%` |
| 4 | `runtime.mallocgc` | 30.88MB | 2768/3117 | `███████░░░░░░░░ 51%` |
| 5 | `database/sql.convertAssignRows` | 27.21MB | 106/3117 | `██████░░░░░░░░░ 45%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3117 | `████░░░░░░░░░░░ 30%` |
| 7 | `bytes.growSlice` | 15.74MB | 2144/3117 | `███░░░░░░░░░░░░ 26%` |
| 8 | `net/http.(*Transport).dialConn` | 14.43MB | 69/3117 | `███░░░░░░░░░░░░ 24%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3117 | `███░░░░░░░░░░░░ 23%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3117 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3117 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3117 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3117 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 60.61GB | 1634/3117 | `███████░░░░░░░░ 48%` |
| 5 | `segmentio/kafka-go.makePartitions` | 51.54GB | 2491/3117 | `██████░░░░░░░░░ 41%` |
| 6 | `experiment/local.topologicalSort` | 51.23GB | 375/3117 | `██████░░░░░░░░░ 40%` |
| 7 | `reflect.growslice` | 51.19GB | 2329/3117 | `██████░░░░░░░░░ 40%` |
| 8 | `jackskj/carta.getUniqueId` | 44.96GB | 2345/3117 | `█████░░░░░░░░░░ 35%` |
| 9 | `reflect.unsafe_New` | 43.86GB | 2109/3117 | `█████░░░░░░░░░░ 35%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/3117 | `█████░░░░░░░░░░ 34%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.7x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.3x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
