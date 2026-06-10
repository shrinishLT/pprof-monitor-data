# Overview: prod
*Last updated: 2026-06-11 00:31 IST*
*Data range: 2026-05-15T16:03 to 2026-06-11T00:30 (2975 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,679 | avg: 14,127 | max: 84,644 | trend: INCREASING (+3.94/hr))
```
▁▁▁▁▁▃▁▁▁▁▁▁▁▁▂▂▁▁▂▂▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▃▁▂▂▂▂▂▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▅█▂▂▂▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 214.8MB | avg: 229.2MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▁▂▁▂▃▃▂▁▁▂▁▂▁▁▂▃▁▂▃▄▃▂▃▃▂▂▁▂▂▃▃▂▃▃▂▁▂▃▂▃▂▁▄▂▂▃▃▃▄▃▁▁▂▄▂▃▂▄▃▂▁▁▁▁▂▃▂▁▁▂▃▂▁▁▂▃▃▂▁▁▅█▆▂▃▂▃▁▂▂▂▂▁▂▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,679 | 14,510 | +169 | 14,127 | 84,644 | INCREASING (+3.94/hr) |
| Heap InUse | 214.8MB | 243.9MB | -29.1MB | 229.2MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3328.1MB | 3326.3MB | +1.8MB | 2595.5MB | 6883.9MB | |
| Heap Objects | 414,798 | 882,830 | -468032 | 990,171 | 17,165,538 | |

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
| 2026-06-11 | 7 | 14,659 | 259.1MB | 293.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `bytes.growSlice` | 7.11MB |
| 6 | `bufio.NewWriterSize` | 3.54MB |
| 7 | `bufio.NewReaderSize` | 3.03MB |
| 8 | `compress/flate.NewWriter` | 2.64MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 146.9GB |
| 2 | `reflect.growslice` | 139.75GB |
| 3 | `jackskj/carta.getUniqueId` | 125.84GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 113.16GB |
| 5 | `reflect.unsafe_New` | 111.2GB |
| 6 | `fmt.Sprintf` | 101.13GB |
| 7 | `fmt.(*buffer).writeString` | 87.77GB |
| 8 | `carta/value.NewCell` | 79.48GB |
| 9 | `reflect.unsafe_NewArray` | 75.04GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 60.6GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 7.73GB | 7.72GB | 7.56GB | 0B |
| `evaluation.mergeMetadata` | 4.05GB | 4.04GB | 3.96GB | 0B |
| `local.(*Client).EvaluateV2` | 11.79GB | 11.78GB | 11.53GB | 0B |
| `local.topologicalSort` | 1.63GB | 1.63GB | 1.60GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 11.21GB | 11.20GB | 10.97GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.65GB | 1.65GB | 1.61GB | 0B |
| `localEvaluation.getMapOfValue` | 11.21GB | 11.20GB | 10.97GB | 0B |
| `utils.ParseFeatureFlag` | 11.23GB | 11.22GB | 10.98GB | 0B |

**Total FF alloc (current snapshot):** 60.50GB  |  **24h avg:** 59.18GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 64.46MB | 54/2975 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 53.93MB | 81/2975 | `████████████░░░ 83%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2626/2975 | `████████░░░░░░░ 56%` |
| 4 | `runtime.mallocgc` | 29.82MB | 2626/2975 | `██████░░░░░░░░░ 46%` |
| 5 | `database/sql.convertAssignRows` | 27.89MB | 103/2975 | `██████░░░░░░░░░ 43%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2975 | `████░░░░░░░░░░░ 27%` |
| 7 | `bytes.growSlice` | 15.55MB | 2030/2975 | `███░░░░░░░░░░░░ 24%` |
| 8 | `net/http.(*Transport).dialConn` | 14.56MB | 60/2975 | `███░░░░░░░░░░░░ 22%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2975 | `███░░░░░░░░░░░░ 21%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2975 | `██░░░░░░░░░░░░░ 16%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2975 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2975 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2975 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 54.48GB | 1492/2975 | `██████░░░░░░░░░ 43%` |
| 5 | `experiment/local.topologicalSort` | 51.23GB | 375/2975 | `██████░░░░░░░░░ 40%` |
| 6 | `segmentio/kafka-go.makePartitions` | 45.28GB | 2349/2975 | `█████░░░░░░░░░░ 36%` |
| 7 | `reflect.growslice` | 44.46GB | 2187/2975 | `█████░░░░░░░░░░ 35%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2975 | `█████░░░░░░░░░░ 34%` |
| 9 | `jackskj/carta.getUniqueId` | 38.86GB | 2203/2975 | `████░░░░░░░░░░░ 31%` |
| 10 | `reflect.unsafe_New` | 38.13GB | 1967/2975 | `████░░░░░░░░░░░ 30%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.2x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.7x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.4x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
