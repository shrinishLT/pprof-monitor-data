# Overview: prod
*Last updated: 2026-06-16 05:16 IST*
*Data range: 2026-05-15T16:03 to 2026-06-16T05:15 (4470 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,350 | avg: 14,800 | max: 84,644 | trend: INCREASING (+2.33/hr))
```
▁▁▁▃▆▄▃▂▁▁▁▁▁▁▂▁▁▁▁▁▁▂▁▄▆▂▂▃▁▁▁▄▁▁▂▅▃▁▄▇▂▁█▄▃▂▄▂▁▁▁▃▁▁▁▃▂▂▁▁▁▁▃▃▁▂▁▁▄▄▁▁▁▁▁▂▁▁▁▁▃▂▁▁▁▁▁▁▁▂▁▁▁▂▁▁
```

**Heap InUse** (current: 237.9MB | avg: 245.1MB | max: 3154.1MB | trend: stable (+0.06MB/hr))
```
▁▂▁▃▇▄▄▃▃▃▂▃▂▂▄▁▂▃▂▂▂▂▂▃█▂▂▄▁▁▁▃▂▂▃▄▄▂▄▆▂▃▆▅▂▃▅▃▁▂▂▂▃▁▂▂▂▂▁▁▃▂▃▄▂▂▂▂▄▅▂▂▂▁▂▃▁▁▂▃▃▂▃▁▁▁▃▂▁▂▂▁▂▃▂▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,350 | 14,198 | +152 | 14,800 | 84,644 | INCREASING (+2.33/hr) |
| Heap InUse | 237.9MB | 260.5MB | -22.6MB | 245.1MB | 3154.1MB | stable (+0.06MB/hr) |
| Heap Sys | 2431.9MB | 2432.2MB | -0.3MB | 2521.2MB | 6883.9MB | |
| Heap Objects | 1,204,548 | 1,698,707 | -494159 | 1,049,739 | 17,165,538 | |

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
| 2026-06-15 | 286 | 16,144 | 281.9MB | 1342.8MB |
| 2026-06-16 | 64 | 15,487 | 264.6MB | 455.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 32.36MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `reflect.unsafe_New` | 5.0MB |
| 6 | `jackskj/carta.getUniqueId` | 4.5MB |
| 7 | `compress/flate.NewWriter` | 3.53MB |
| 8 | `segmentio/kafka-go.makePartitions` | 3.51MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `reflect.unsafe_NewArray` | 2.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 122.25GB |
| 2 | `reflect.growslice` | 114.69GB |
| 3 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 111.07GB |
| 4 | `jackskj/carta.getUniqueId` | 104.43GB |
| 5 | `reflect.unsafe_New` | 91.38GB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 88.47GB |
| 7 | `fmt.Sprintf` | 85.68GB |
| 8 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 72.76GB |
| 9 | `fmt.(*buffer).writeString` | 70.85GB |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 66.49GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 5.49GB | 5.49GB | 5.36GB | 0B |
| `evaluation.mergeMetadata` | 2.85GB | 2.85GB | 2.78GB | 0B |
| `local.(*Client).EvaluateV2` | 8.45GB | 8.44GB | 8.25GB | 0B |
| `local.topologicalSort` | 1.20GB | 1.19GB | 1.17GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 8.19GB | 8.18GB | 7.98GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.06GB | 1.06GB | 1.04GB | 0B |
| `localEvaluation.getMapOfValue` | 8.19GB | 8.18GB | 7.98GB | 0B |
| `utils.ParseFeatureFlag` | 8.20GB | 8.20GB | 7.99GB | 0B |

**Total FF alloc (current snapshot):** 43.62GB  |  **24h avg:** 42.55GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 41.59MB | 92/4470 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 37.49MB | 125/4470 | `█████████████░░ 90%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 4121/4470 | `█████████████░░ 88%` |
| 4 | `runtime.mallocgc` | 31.36MB | 4121/4470 | `███████████░░░░ 75%` |
| 5 | `database/sql.convertAssignRows` | 21.38MB | 146/4470 | `███████░░░░░░░░ 51%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4470 | `██████░░░░░░░░░ 43%` |
| 7 | `bytes.growSlice` | 15.71MB | 3235/4470 | `█████░░░░░░░░░░ 37%` |
| 8 | `net/http.(*Transport).dialConn` | 13.21MB | 119/4470 | `████░░░░░░░░░░░ 31%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/4470 | `████░░░░░░░░░░░ 28%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4470 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4470 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 74.74GB | 2659/4470 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4470 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4470 | `████████░░░░░░░ 59%` |
| 5 | `reflect.growslice` | 63.74GB | 3682/4470 | `███████░░░░░░░░ 50%` |
| 6 | `segmentio/kafka-go.makePartitions` | 63.56GB | 3844/4470 | `███████░░░░░░░░ 50%` |
| 7 | `jackskj/carta.getUniqueId` | 56.92GB | 3698/4470 | `██████░░░░░░░░░ 45%` |
| 8 | `reflect.unsafe_New` | 53.37GB | 3462/4470 | `██████░░░░░░░░░ 42%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/4470 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 47.71GB | 3016/4470 | `█████░░░░░░░░░░ 38%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.7x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.7x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.7x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.2x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (3.9x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.5x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.3x avg)
