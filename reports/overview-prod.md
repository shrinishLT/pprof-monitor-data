# Overview: prod
*Last updated: 2026-06-07 15:30 IST*
*Data range: 2026-05-15T16:03 to 2026-06-07T15:30 (2004 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,266 | avg: 13,177 | max: 84,644 | trend: INCREASING (+4.18/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▅█▆▆▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 271.7MB | avg: 196.0MB | max: 3154.1MB | trend: stable (+0.05MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▅█▇▅▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,266 | 14,476 | -210 | 13,177 | 84,644 | INCREASING (+4.18/hr) |
| Heap InUse | 271.7MB | 344.5MB | -72.8MB | 196.0MB | 3154.1MB | stable (+0.05MB/hr) |
| Heap Sys | 3218.2MB | 3218.5MB | -0.3MB | 2256.6MB | 6883.9MB | |
| Heap Objects | 1,227,032 | 970,490 | +256542 | 881,644 | 17,165,538 | |

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
| 2026-06-07 | 187 | 16,053 | 234.6MB | 1942.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 49.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `bytes.growSlice` | 2.8MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `reflect.mapassign_faststr0` | 2.0MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 1.6MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 40.03GB |
| 2 | `segmentio/kafka-go.makePartitions` | 35.82GB |
| 3 | `reflect.growslice` | 34.09GB |
| 4 | `jackskj/carta.getUniqueId` | 29.42GB |
| 5 | `reflect.unsafe_New` | 26.32GB |
| 6 | `fmt.(*buffer).writeString` | 21.29GB |
| 7 | `carta/value.NewCell` | 18.88GB |
| 8 | `reflect.unsafe_NewArray` | 18.33GB |
| 9 | `fmt.Sprintf` | 15.88GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 14.0GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.00GB | 1.00GB | 931.02MB | 0B |
| `evaluation.mergeMetadata` | 524.13MB | 523.63MB | 476.57MB | 0B |
| `local.(*Client).EvaluateV2` | 1.53GB | 1.53GB | 1.38GB | 0B |
| `local.topologicalSort` | 211.03MB | 210.51MB | 191.39MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.57GB | 1.56GB | 1.43GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 129.36MB | 129.36MB | 109.88MB | 0B |
| `localEvaluation.getMapOfValue` | 1.57GB | 1.56GB | 1.43GB | 0B |
| `utils.ParseFeatureFlag` | 1.57GB | 1.57GB | 1.43GB | 0B |

**Total FF alloc (current snapshot):** 8.07GB  |  **24h avg:** 7.34GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 85.72MB | 37/2004 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 66.16MB | 62/2004 | `███████████░░░░ 77%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1655/2004 | `██████░░░░░░░░░ 42%` |
| 4 | `database/sql.convertAssignRows` | 34.56MB | 78/2004 | `██████░░░░░░░░░ 40%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2004 | `███░░░░░░░░░░░░ 20%` |
| 6 | `runtime.mallocgc` | 17.84MB | 1655/2004 | `███░░░░░░░░░░░░ 20%` |
| 7 | `bytes.growSlice` | 15.26MB | 1228/2004 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `net/http.(*Transport).dialConn` | 13.79MB | 36/2004 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2004 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 10.48MB | 38/2004 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2004 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2004 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2004 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2004 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2004 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2004 | `███░░░░░░░░░░░░ 22%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2004 | `███░░░░░░░░░░░░ 21%` |
| 8 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 14.71GB | 521/2004 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 14.23GB | 969/2004 | `█░░░░░░░░░░░░░░ 11%` |
| 10 | `segmentio/kafka-go.makePartitions` | 12.87GB | 1378/2004 | `█░░░░░░░░░░░░░░ 10%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.7x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.4x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.1x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.4x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.4x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.0x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.0x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.9x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.6x avg)
