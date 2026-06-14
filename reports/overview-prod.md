# Overview: prod
*Last updated: 2026-06-15 03:05 IST*
*Data range: 2026-05-15T16:03 to 2026-06-15T03:05 (4158 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,164 | avg: 14,692 | max: 84,644 | trend: INCREASING (+2.57/hr))
```
▁▁▁▃▂▁▁▁▁▁▁▄▂▁▁▁▂▂▂▂▁▃▂▂▁▁▁▇▂▂▂▁▁▁▁▄▁▁▆▁▁▁▁▁▁▁▂▂▃▁▆▁▁▂▁▁▂▁▅▂▁▁▃▁▁▁▁▁▁▁▃▁▁▁▁▄▁▃▂▁▂▇█▄▂▇▁▂▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 246.1MB | avg: 242.1MB | max: 3154.1MB | trend: stable (+0.06MB/hr))
```
▅▄▁▃▃▂▄▁▂▃▁▄▃▁▄▂▂▆▃▂▃▇▂▄▃▁▁▇▅▃▂▁▃▅▂▃▁▃▄▃▅▅▁▄▁▃▄▂▂▃▄▃▁▃▂▂▄▂▅▂▃▄▃▁▄▂▄▂▅▁▄▂▄▄▁▅▄▁▅▂▂▃▆▆▁█▂▄▁▅▅▄▁▃▁▄
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,164 | 14,098 | +66 | 14,692 | 84,644 | INCREASING (+2.57/hr) |
| Heap InUse | 246.1MB | 175.9MB | +70.2MB | 242.1MB | 3154.1MB | stable (+0.06MB/hr) |
| Heap Sys | 2411.7MB | 2411.6MB | +0.1MB | 2529.2MB | 6883.9MB | |
| Heap Objects | 1,551,787 | 664,522 | +887265 | 1,041,375 | 17,165,538 | |

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
| 2026-06-14 | 288 | 15,854 | 265.3MB | 1419.6MB |
| 2026-06-15 | 38 | 14,308 | 221.9MB | 323.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 32.36MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.53MB |
| 7 | `reflect.unsafe_NewArray` | 2.51MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `bytes.growSlice` | 2.01MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 91.38GB |
| 2 | `segmentio/kafka-go.makePartitions` | 86.47GB |
| 3 | `reflect.growslice` | 80.87GB |
| 4 | `jackskj/carta.getUniqueId` | 74.04GB |
| 5 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 66.41GB |
| 6 | `reflect.unsafe_New` | 64.57GB |
| 7 | `fmt.Sprintf` | 56.57GB |
| 8 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 54.6GB |
| 9 | `fmt.(*buffer).writeString` | 50.17GB |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 48.3GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 3.20GB | 3.19GB | 3.12GB | 0B |
| `evaluation.mergeMetadata` | 1.64GB | 1.64GB | 1.60GB | 0B |
| `local.(*Client).EvaluateV2` | 4.91GB | 4.91GB | 4.80GB | 0B |
| `local.topologicalSort` | 714.39MB | 713.89MB | 701.34MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 4.81GB | 4.81GB | 4.70GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 589.90MB | 589.90MB | 581.03MB | 0B |
| `localEvaluation.getMapOfValue` | 4.81GB | 4.81GB | 4.70GB | 0B |
| `utils.ParseFeatureFlag` | 4.82GB | 4.82GB | 4.71GB | 0B |

**Total FF alloc (current snapshot):** 25.47GB  |  **24h avg:** 24.89GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 43.86MB | 84/4158 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 39.42MB | 115/4158 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3809/4158 | `████████████░░░ 83%` |
| 4 | `runtime.mallocgc` | 31.28MB | 3809/4158 | `██████████░░░░░ 71%` |
| 5 | `database/sql.convertAssignRows` | 22.27MB | 135/4158 | `███████░░░░░░░░ 50%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4158 | `██████░░░░░░░░░ 41%` |
| 7 | `bytes.growSlice` | 15.67MB | 2966/4158 | `█████░░░░░░░░░░ 35%` |
| 8 | `net/http.(*Transport).dialConn` | 13.32MB | 108/4158 | `████░░░░░░░░░░░ 30%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/4158 | `████░░░░░░░░░░░ 26%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4158 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4158 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4158 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4158 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 70.62GB | 2347/4158 | `████████░░░░░░░ 56%` |
| 5 | `reflect.growslice` | 60.01GB | 3370/4158 | `███████░░░░░░░░ 47%` |
| 6 | `segmentio/kafka-go.makePartitions` | 59.96GB | 3532/4158 | `███████░░░░░░░░ 47%` |
| 7 | `jackskj/carta.getUniqueId` | 53.48GB | 3386/4158 | `██████░░░░░░░░░ 42%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/4158 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 50.49GB | 3150/4158 | `██████░░░░░░░░░ 40%` |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 45.9GB | 1498/4158 | `█████░░░░░░░░░░ 36%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.8x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.3x avg)
