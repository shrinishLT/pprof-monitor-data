# Overview: prod
*Last updated: 2026-06-12 19:37 IST*
*Data range: 2026-05-15T16:03 to 2026-06-12T19:37 (3492 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,738 | avg: 14,442 | max: 84,644 | trend: INCREASING (+3.36/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▃▅▄▅▃▂▂▃▄▂▅▁▂▁▂▁▁▂▁▁▁▄▂▃▂▂▂▃▂▆█▅▄▄▃▃▃▃▃▅▃▄▁▂▃▁▁▃▂▁▁▁▁▁▁▁▁▂▃▁▃▁▁▁▁▃▃▁▁▁▂▂▃▁▂▂▃▂▂▁▁▁▁▂
```

**Heap InUse** (current: 165.5MB | avg: 238.4MB | max: 3154.1MB | trend: stable (+0.09MB/hr))
```
▅▇▆▂▂▁▂▂▁▂▁▂▅▅▃▆▆▂▃▄▆▅▅▂▃▃▃▂▃▄▂▆▃▄▂▄▅▄▃▃▅█▅▆▄▄▄▄▆▄▄▅▃▄▄▃▃▅▄▃▄▂▃▃▄▃▂▂▄▂▅▃▄▂▃▂▂▃▄▂▂▂▃▅▃▄▄▃▄▂▃▂▂▂▁▃
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,738 | 14,319 | +419 | 14,442 | 84,644 | INCREASING (+3.36/hr) |
| Heap InUse | 165.5MB | 133.1MB | +32.4MB | 238.4MB | 3154.1MB | stable (+0.09MB/hr) |
| Heap Sys | 694.3MB | 694.8MB | -0.5MB | 2630.7MB | 6883.9MB | |
| Heap Objects | 675,970 | 543,403 | +132567 | 1,023,610 | 17,165,538 | |

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
| 2026-06-12 | 236 | 16,043 | 263.6MB | 1418.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 4 | `runtime.mallocgc` | 8.01MB |
| 5 | `bytes.growSlice` | 5.03MB |
| 6 | `compress/flate.NewWriter` | 4.41MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aes/gcm.NewGCMForTLS13` | 2.0MB |
| 9 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 10 | `segmentio/kafka-go.makePartitions` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 10.48GB |
| 2 | `fmt.Sprintf` | 6.96GB |
| 3 | `reflect.unsafe_NewArray` | 5.35GB |
| 4 | `jackskj/carta.getUniqueId` | 5.12GB |
| 5 | `reflect.growslice` | 5.06GB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 4.96GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 4.93GB |
| 8 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 4.86GB |
| 9 | `reflect.unsafe_New` | 4.3GB |
| 10 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 4.16GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 761.16MB | 747.49MB | 560.29MB | 0B |
| `evaluation.mergeMetadata` | 392.60MB | 387.60MB | 291.06MB | 0B |
| `local.(*Client).EvaluateV2` | 1.15GB | 1.13GB | 868.60MB | 0B |
| `local.topologicalSort` | 170.17MB | 169.67MB | 126.35MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.06GB | 1.05GB | 803.01MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 187.75MB | 185.25MB | 133.34MB | 0B |
| `localEvaluation.getMapOfValue` | 1.06GB | 1.05GB | 803.01MB | 0B |
| `utils.ParseFeatureFlag` | 1.07GB | 1.05GB | 806.23MB | 0B |

**Total FF alloc (current snapshot):** 5.82GB  |  **24h avg:** 4.29GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 52.6MB | 68/3492 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 47.12MB | 94/3492 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3143/3492 | `██████████░░░░░ 69%` |
| 4 | `runtime.mallocgc` | 31.96MB | 3143/3492 | `█████████░░░░░░ 60%` |
| 5 | `database/sql.convertAssignRows` | 24.89MB | 118/3492 | `███████░░░░░░░░ 47%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3492 | `█████░░░░░░░░░░ 34%` |
| 7 | `bytes.growSlice` | 15.63MB | 2482/3492 | `████░░░░░░░░░░░ 29%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3492 | `████░░░░░░░░░░░ 26%` |
| 9 | `net/http.(*Transport).dialConn` | 14.04MB | 81/3492 | `████░░░░░░░░░░░ 26%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3492 | `███░░░░░░░░░░░░ 20%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3492 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3492 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3492 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 72.99GB | 1922/3492 | `████████░░░░░░░ 58%` |
| 5 | `reflect.growslice` | 63.35GB | 2704/3492 | `███████░░░░░░░░ 50%` |
| 6 | `segmentio/kafka-go.makePartitions` | 62.63GB | 2866/3492 | `███████░░░░░░░░ 50%` |
| 7 | `jackskj/carta.getUniqueId` | 56.13GB | 2720/3492 | `██████░░░░░░░░░ 44%` |
| 8 | `reflect.unsafe_New` | 54.0GB | 2484/3492 | `██████░░░░░░░░░ 43%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/3492 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 48.65GB | 2183/3492 | `█████░░░░░░░░░░ 38%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
