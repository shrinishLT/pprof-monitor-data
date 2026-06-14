# Overview: prod
*Last updated: 2026-06-15 05:11 IST*
*Data range: 2026-05-15T16:03 to 2026-06-15T05:11 (4183 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,298 | avg: 14,690 | max: 84,644 | trend: INCREASING (+2.52/hr))
```
▁▁▇▂▁▂▁▁▁▁▄▁▁▆▁▁▁▁▁▁▁▂▂▂▁▆▁▁▂▁▁▂▁▅▁▁▁▃▁▁▁▁▁▁▁▃▁▁▁▁▄▁▃▂▁▂▇█▄▂▇▁▂▁▁▁▁▁▁▁▁▁▃▁▁▁▃▃▃▂▂▂▆▆▂▁▁▁▁▃▁▁▁▁▂▂
```

**Heap InUse** (current: 199.0MB | avg: 241.9MB | max: 3154.1MB | trend: stable (+0.06MB/hr))
```
▁▁▇▅▃▂▁▃▅▂▃▁▃▄▃▄▅▁▄▁▃▄▂▂▃▄▃▁▃▂▂▄▂▅▂▃▄▂▁▄▂▄▂▄▁▄▂▄▄▁▄▃▁▅▂▂▃▆▆▁█▂▄▁▅▅▄▁▃▁▄▁▅▁▃▁▃▃▂▂▂▂▃▄▃▃▁▂▄▄▃▃▂▄▃▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,298 | 14,386 | -88 | 14,690 | 84,644 | INCREASING (+2.52/hr) |
| Heap InUse | 199.0MB | 217.3MB | -18.3MB | 241.9MB | 3154.1MB | stable (+0.06MB/hr) |
| Heap Sys | 2414.8MB | 2414.4MB | +0.4MB | 2528.5MB | 6883.9MB | |
| Heap Objects | 802,904 | 912,393 | -109489 | 1,040,370 | 17,165,538 | |

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
| 2026-06-15 | 63 | 14,318 | 216.4MB | 323.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 32.36MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `bufio.NewWriterSize` | 2.54MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 9 | `compress/flate.(*compressor).initDeflate` | 1.6MB |
| 10 | `bytes.growSlice` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 91.48GB |
| 2 | `segmentio/kafka-go.makePartitions` | 89.29GB |
| 3 | `reflect.growslice` | 82.07GB |
| 4 | `jackskj/carta.getUniqueId` | 74.9GB |
| 5 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 69.31GB |
| 6 | `reflect.unsafe_New` | 65.41GB |
| 7 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 56.98GB |
| 8 | `fmt.Sprintf` | 56.96GB |
| 9 | `fmt.(*buffer).writeString` | 50.86GB |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 49.29GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 3.25GB | 3.25GB | 3.20GB | 0B |
| `evaluation.mergeMetadata` | 1.67GB | 1.67GB | 1.64GB | 0B |
| `local.(*Client).EvaluateV2` | 5.00GB | 5.00GB | 4.91GB | 0B |
| `local.topologicalSort` | 724.01MB | 724.01MB | 713.91MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 4.91GB | 4.91GB | 4.82GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 594.47MB | 594.47MB | 589.91MB | 0B |
| `localEvaluation.getMapOfValue` | 4.91GB | 4.91GB | 4.82GB | 0B |
| `utils.ParseFeatureFlag` | 4.92GB | 4.92GB | 4.82GB | 0B |

**Total FF alloc (current snapshot):** 25.95GB  |  **24h avg:** 25.48GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 43.86MB | 84/4183 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 39.42MB | 115/4183 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3834/4183 | `████████████░░░ 83%` |
| 4 | `runtime.mallocgc` | 31.29MB | 3834/4183 | `██████████░░░░░ 71%` |
| 5 | `database/sql.convertAssignRows` | 22.27MB | 135/4183 | `███████░░░░░░░░ 50%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4183 | `██████░░░░░░░░░ 41%` |
| 7 | `bytes.growSlice` | 15.61MB | 2980/4183 | `█████░░░░░░░░░░ 35%` |
| 8 | `net/http.(*Transport).dialConn` | 13.32MB | 108/4183 | `████░░░░░░░░░░░ 30%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/4183 | `████░░░░░░░░░░░ 26%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4183 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4183 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4183 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4183 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 70.84GB | 2372/4183 | `████████░░░░░░░ 56%` |
| 5 | `reflect.growslice` | 60.17GB | 3395/4183 | `███████░░░░░░░░ 48%` |
| 6 | `segmentio/kafka-go.makePartitions` | 60.16GB | 3557/4183 | `███████░░░░░░░░ 48%` |
| 7 | `jackskj/carta.getUniqueId` | 53.64GB | 3411/4183 | `██████░░░░░░░░░ 42%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/4183 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 50.6GB | 3175/4183 | `██████░░░░░░░░░ 40%` |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 45.9GB | 1498/4183 | `█████░░░░░░░░░░ 36%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.8x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.3x avg)
