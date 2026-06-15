# Overview: prod
*Last updated: 2026-06-15 12:11 IST*
*Data range: 2026-05-15T16:03 to 2026-06-15T12:10 (4267 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,433 | avg: 14,753 | max: 84,644 | trend: INCREASING (+2.54/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▃▅▆▇█▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 278.2MB | avg: 243.4MB | max: 3154.1MB | trend: stable (+0.06MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▃▄▄▆▆█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,433 | 15,101 | +332 | 14,753 | 84,644 | INCREASING (+2.54/hr) |
| Heap InUse | 278.2MB | 284.4MB | -6.2MB | 243.4MB | 3154.1MB | stable (+0.06MB/hr) |
| Heap Sys | 2389.8MB | 2390.8MB | -1.0MB | 2525.9MB | 6883.9MB | |
| Heap Objects | 1,223,354 | 1,452,860 | -229506 | 1,045,974 | 17,165,538 | |

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
| 2026-06-15 | 147 | 16,342 | 274.8MB | 1342.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 32.36MB |
| 3 | `bytes.growSlice` | 9.57MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 6 | `compress/flate.NewWriter` | 4.41MB |
| 7 | `bufio.NewReaderSize` | 4.02MB |
| 8 | `bufio.NewWriterSize` | 2.52MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 106.47GB |
| 2 | `reflect.growslice` | 104.34GB |
| 3 | `segmentio/kafka-go.makePartitions` | 98.82GB |
| 4 | `jackskj/carta.getUniqueId` | 93.93GB |
| 5 | `reflect.unsafe_New` | 82.5GB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 76.82GB |
| 7 | `fmt.(*buffer).writeString` | 64.34GB |
| 8 | `fmt.Sprintf` | 64.34GB |
| 9 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 63.13GB |
| 10 | `carta/value.NewCell` | 59.79GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 3.72GB | 3.71GB | 3.56GB | 0B |
| `evaluation.mergeMetadata` | 1.92GB | 1.92GB | 1.83GB | 0B |
| `local.(*Client).EvaluateV2` | 5.70GB | 5.69GB | 5.48GB | 0B |
| `local.topologicalSort` | 825.16MB | 822.12MB | 792.66MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 5.64GB | 5.63GB | 5.41GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 645.02MB | 641.91MB | 625.76MB | 0B |
| `localEvaluation.getMapOfValue` | 5.64GB | 5.63GB | 5.41GB | 0B |
| `utils.ParseFeatureFlag` | 5.65GB | 5.64GB | 5.42GB | 0B |

**Total FF alloc (current snapshot):** 29.70GB  |  **24h avg:** 28.49GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 42.64MB | 87/4267 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 37.69MB | 121/4267 | `█████████████░░ 88%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3918/4267 | `████████████░░░ 85%` |
| 4 | `runtime.mallocgc` | 31.31MB | 3918/4267 | `███████████░░░░ 73%` |
| 5 | `database/sql.convertAssignRows` | 21.35MB | 142/4267 | `███████░░░░░░░░ 50%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4267 | `██████░░░░░░░░░ 42%` |
| 7 | `bytes.growSlice` | 15.84MB | 3042/4267 | `█████░░░░░░░░░░ 37%` |
| 8 | `net/http.(*Transport).dialConn` | 13.44MB | 116/4267 | `████░░░░░░░░░░░ 31%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/4267 | `████░░░░░░░░░░░ 27%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4267 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4267 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4267 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4267 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 71.84GB | 2456/4267 | `████████░░░░░░░ 57%` |
| 5 | `reflect.growslice` | 61.01GB | 3479/4267 | `███████░░░░░░░░ 48%` |
| 6 | `segmentio/kafka-go.makePartitions` | 60.94GB | 3641/4267 | `███████░░░░░░░░ 48%` |
| 7 | `jackskj/carta.getUniqueId` | 54.4GB | 3495/4267 | `██████░░░░░░░░░ 43%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/4267 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 51.23GB | 3259/4267 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 46.23GB | 2813/4267 | `█████░░░░░░░░░░ 36%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.7x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.2x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (3.9x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.3x avg)
