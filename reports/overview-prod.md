# Overview: prod
*Last updated: 2026-06-10 19:46 IST*
*Data range: 2026-05-15T16:03 to 2026-06-10T19:45 (2918 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,876 | avg: 14,104 | max: 84,644 | trend: INCREASING (+4.08/hr))
```
▁▁▁▁▁▁▁▁▁▃▃▃▂▁▁▂▂▂▃▂▂▁▁▁▁▄▇█▇▆▂▁▁▁▂▂▂▂▁▂▁▁▃▂▁▂▂▁▂▂▂▁▁▁▂▂▂▂▁▁▁▂▅▂▁▁▁▁▁▁▁▃▄▁▂▃▃▃▂▂▂▂▂▂▂▂▂▂▁▁▂▁▁▂▁▂
```

**Heap InUse** (current: 285.1MB | avg: 228.1MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▄▁▁▂▂▂▂▂▄▄▄▃▅▂▂▂▃▄▅▃▃▄▁▁▁▆█▆▆▆▆▃▄▂▃▂▃▃▂▆▂▂▃▃▄▃▂▂▃▂▂▂▁▃▄▃▅▂▃▂▃▄▅▄▂▁▃▁▃▁▁▃▅▂▂▄▆▅▄▄▄▂▃▂▂▂▄▅▄▄▅▂▁▃▅▃
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,876 | 14,266 | +610 | 14,104 | 84,644 | INCREASING (+4.08/hr) |
| Heap InUse | 285.1MB | 326.3MB | -41.2MB | 228.1MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3344.9MB | 3345.5MB | -0.6MB | 2581.0MB | 6883.9MB | |
| Heap Objects | 1,353,534 | 2,093,967 | -740433 | 987,565 | 17,165,538 | |

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
| 2026-06-10 | 237 | 16,680 | 310.0MB | 1442.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `bytes.growSlice` | 4.66MB |
| 6 | `bufio.NewWriterSize` | 3.53MB |
| 7 | `bufio.NewReaderSize` | 3.03MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `compress/flate.NewWriter` | 1.76MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 140.28GB |
| 2 | `reflect.growslice` | 138.43GB |
| 3 | `jackskj/carta.getUniqueId` | 123.88GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 112.78GB |
| 5 | `reflect.unsafe_New` | 109.64GB |
| 6 | `fmt.Sprintf` | 95.93GB |
| 7 | `fmt.(*buffer).writeString` | 87.33GB |
| 8 | `carta/value.NewCell` | 78.38GB |
| 9 | `reflect.unsafe_NewArray` | 71.69GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 58.53GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 7.27GB | 7.26GB | 7.07GB | 0B |
| `evaluation.mergeMetadata` | 3.82GB | 3.81GB | 3.72GB | 0B |
| `local.(*Client).EvaluateV2` | 11.09GB | 11.08GB | 10.79GB | 0B |
| `local.topologicalSort` | 1.54GB | 1.54GB | 1.50GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 10.57GB | 10.56GB | 10.30GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.53GB | 1.53GB | 1.48GB | 0B |
| `localEvaluation.getMapOfValue` | 10.57GB | 10.56GB | 10.30GB | 0B |
| `utils.ParseFeatureFlag` | 10.59GB | 10.58GB | 10.32GB | 512.56kB |

**Total FF alloc (current snapshot):** 56.99GB  |  **24h avg:** 55.48GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 66.73MB | 52/2918 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 54.51MB | 80/2918 | `████████████░░░ 81%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2569/2918 | `████████░░░░░░░ 54%` |
| 4 | `runtime.mallocgc` | 29.36MB | 2569/2918 | `██████░░░░░░░░░ 43%` |
| 5 | `database/sql.convertAssignRows` | 28.37MB | 101/2918 | `██████░░░░░░░░░ 42%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2918 | `████░░░░░░░░░░░ 26%` |
| 7 | `bytes.growSlice` | 15.7MB | 1977/2918 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).dialConn` | 14.56MB | 60/2918 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2918 | `███░░░░░░░░░░░░ 21%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2918 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2918 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2918 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2918 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 52.16GB | 1435/2918 | `██████░░░░░░░░░ 41%` |
| 5 | `experiment/local.topologicalSort` | 51.23GB | 375/2918 | `██████░░░░░░░░░ 40%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2918 | `█████░░░░░░░░░░ 34%` |
| 7 | `segmentio/kafka-go.makePartitions` | 42.84GB | 2292/2918 | `█████░░░░░░░░░░ 34%` |
| 8 | `reflect.growslice` | 41.93GB | 2130/2918 | `█████░░░░░░░░░░ 33%` |
| 9 | `jackskj/carta.getUniqueId` | 36.58GB | 2146/2918 | `████░░░░░░░░░░░ 29%` |
| 10 | `reflect.unsafe_New` | 35.97GB | 1910/2918 | `████░░░░░░░░░░░ 28%` |

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
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.5x avg)
