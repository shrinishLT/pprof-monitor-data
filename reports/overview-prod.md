# Overview: prod
*Last updated: 2026-06-10 21:51 IST*
*Data range: 2026-05-15T16:03 to 2026-06-10T21:50 (2943 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,453 | avg: 14,114 | max: 84,644 | trend: INCREASING (+4.01/hr))
```
▄▇█▇▆▂▁▁▁▂▂▂▂▁▂▁▁▃▂▁▂▂▁▂▂▂▁▁▁▂▂▂▂▁▁▁▂▅▂▁▁▁▁▁▁▁▃▄▁▂▃▃▃▂▂▂▂▂▂▂▂▂▂▁▁▂▁▁▂▁▂▁▁▁▆▁▃▄▃▃▄▂▁▁▃▄▂▁▁▂▁▁▁▁▁▁
```

**Heap InUse** (current: 210.0MB | avg: 228.6MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▆█▆▆▆▆▃▄▂▃▂▃▃▂▆▂▂▃▃▄▃▂▂▃▂▂▂▁▃▄▃▅▂▃▂▃▄▅▄▂▁▃▁▃▁▁▃▅▂▂▄▆▅▄▄▄▂▃▂▂▂▄▅▄▄▅▂▁▃▅▃▄▃▁▆▃▄▄▄▄▇▄▂▁▃▇▃▄▂▅▄▃▁▁▂▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,453 | 14,504 | -51 | 14,114 | 84,644 | INCREASING (+4.01/hr) |
| Heap InUse | 210.0MB | 228.7MB | -18.7MB | 228.6MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3343.6MB | 3343.3MB | +0.3MB | 2587.4MB | 6883.9MB | |
| Heap Objects | 532,997 | 844,495 | -311498 | 988,350 | 17,165,538 | |

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
| 2026-06-10 | 262 | 16,545 | 307.4MB | 1442.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `bytes.growSlice` | 2.3MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `compress/flate.(*compressor).initDeflate` | 1.6MB |
| 10 | `segmentio/kafka-go.makePartitions` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 143.19GB |
| 2 | `reflect.growslice` | 138.94GB |
| 3 | `jackskj/carta.getUniqueId` | 124.63GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 112.87GB |
| 5 | `reflect.unsafe_New` | 110.2GB |
| 6 | `fmt.Sprintf` | 98.52GB |
| 7 | `fmt.(*buffer).writeString` | 87.48GB |
| 8 | `carta/value.NewCell` | 78.78GB |
| 9 | `reflect.unsafe_NewArray` | 73.19GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 59.45GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 7.51GB | 7.50GB | 7.29GB | 0B |
| `evaluation.mergeMetadata` | 3.93GB | 3.93GB | 3.83GB | 0B |
| `local.(*Client).EvaluateV2` | 11.45GB | 11.43GB | 11.12GB | 0B |
| `local.topologicalSort` | 1.59GB | 1.59GB | 1.55GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 10.89GB | 10.87GB | 10.60GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.60GB | 1.60GB | 1.54GB | 0B |
| `localEvaluation.getMapOfValue` | 10.89GB | 10.87GB | 10.60GB | 0B |
| `utils.ParseFeatureFlag` | 10.90GB | 10.89GB | 10.61GB | 0B |

**Total FF alloc (current snapshot):** 58.75GB  |  **24h avg:** 57.13GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 65.57MB | 53/2943 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 54.51MB | 80/2943 | `████████████░░░ 83%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2594/2943 | `████████░░░░░░░ 55%` |
| 4 | `runtime.mallocgc` | 29.57MB | 2594/2943 | `██████░░░░░░░░░ 45%` |
| 5 | `database/sql.convertAssignRows` | 28.12MB | 102/2943 | `██████░░░░░░░░░ 42%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2943 | `████░░░░░░░░░░░ 27%` |
| 7 | `bytes.growSlice` | 15.64MB | 2000/2943 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).dialConn` | 14.56MB | 60/2943 | `███░░░░░░░░░░░░ 22%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2943 | `███░░░░░░░░░░░░ 21%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2943 | `██░░░░░░░░░░░░░ 16%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2943 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2943 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2943 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 53.2GB | 1460/2943 | `██████░░░░░░░░░ 42%` |
| 5 | `experiment/local.topologicalSort` | 51.23GB | 375/2943 | `██████░░░░░░░░░ 40%` |
| 6 | `segmentio/kafka-go.makePartitions` | 43.9GB | 2317/2943 | `█████░░░░░░░░░░ 35%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2943 | `█████░░░░░░░░░░ 34%` |
| 8 | `reflect.growslice` | 43.06GB | 2155/2943 | `█████░░░░░░░░░░ 34%` |
| 9 | `jackskj/carta.getUniqueId` | 37.59GB | 2171/2943 | `████░░░░░░░░░░░ 30%` |
| 10 | `reflect.unsafe_New` | 36.93GB | 1935/2943 | `████░░░░░░░░░░░ 29%` |

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
