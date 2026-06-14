# Overview: prod
*Last updated: 2026-06-14 17:20 IST*
*Data range: 2026-05-15T16:03 to 2026-06-14T17:20 (4041 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,166 | avg: 14,703 | max: 84,644 | trend: INCREASING (+2.83/hr))
```
▁▁▁▁▁▁▁▁▁▂▃▄▂▄▆▇▇█▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 258.9MB | avg: 242.8MB | max: 3154.1MB | trend: stable (+0.07MB/hr))
```
▁▁▁▁▁▁▁▁▂▃▂▄▃▄▆▆▆█▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,166 | 14,110 | +56 | 14,703 | 84,644 | INCREASING (+2.83/hr) |
| Heap InUse | 258.9MB | 257.7MB | +1.2MB | 242.8MB | 3154.1MB | stable (+0.07MB/hr) |
| Heap Sys | 2408.2MB | 2408.2MB | +0.0MB | 2532.7MB | 6883.9MB | |
| Heap Objects | 970,451 | 1,634,928 | -664477 | 1,042,769 | 17,165,538 | |

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
| 2026-06-14 | 209 | 16,437 | 283.7MB | 1419.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 32.36MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.56MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 9 | `reflect.mapassign_faststr0` | 1.5MB |
| 10 | `encoding/json.(*decodeState).literalStore` | 1.04MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 90.26GB |
| 2 | `reflect.growslice` | 78.16GB |
| 3 | `segmentio/kafka-go.makePartitions` | 73.17GB |
| 4 | `jackskj/carta.getUniqueId` | 71.88GB |
| 5 | `reflect.unsafe_New` | 62.35GB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 54.38GB |
| 7 | `fmt.Sprintf` | 54.08GB |
| 8 | `fmt.(*buffer).writeString` | 48.73GB |
| 9 | `carta/value.NewCell` | 45.22GB |
| 10 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 44.74GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 2.83GB | 2.83GB | 2.76GB | 0B |
| `evaluation.mergeMetadata` | 1.45GB | 1.45GB | 1.41GB | 0B |
| `local.(*Client).EvaluateV2` | 4.35GB | 4.34GB | 4.23GB | 0B |
| `local.topologicalSort` | 634.97MB | 634.47MB | 618.52MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 4.30GB | 4.30GB | 4.20GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 490.82MB | 489.78MB | 468.97MB | 0B |
| `localEvaluation.getMapOfValue` | 4.30GB | 4.30GB | 4.20GB | 0B |
| `utils.ParseFeatureFlag` | 4.31GB | 4.31GB | 4.21GB | 0B |

**Total FF alloc (current snapshot):** 22.63GB  |  **24h avg:** 22.07GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 45.26MB | 81/4041 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 40.7MB | 111/4041 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3692/4041 | `████████████░░░ 80%` |
| 4 | `runtime.mallocgc` | 31.25MB | 3692/4041 | `██████████░░░░░ 69%` |
| 5 | `database/sql.convertAssignRows` | 22.86MB | 131/4041 | `███████░░░░░░░░ 50%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4041 | `█████░░░░░░░░░░ 39%` |
| 7 | `bytes.growSlice` | 15.89MB | 2909/4041 | `█████░░░░░░░░░░ 35%` |
| 8 | `net/http.(*Transport).dialConn` | 13.32MB | 108/4041 | `████░░░░░░░░░░░ 29%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/4041 | `███░░░░░░░░░░░░ 26%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4041 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4041 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4041 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4041 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 69.59GB | 2230/4041 | `████████░░░░░░░ 55%` |
| 5 | `reflect.growslice` | 59.34GB | 3253/4041 | `███████░░░░░░░░ 47%` |
| 6 | `segmentio/kafka-go.makePartitions` | 59.28GB | 3415/4041 | `███████░░░░░░░░ 47%` |
| 7 | `jackskj/carta.getUniqueId` | 52.81GB | 3269/4041 | `██████░░░░░░░░░ 42%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/4041 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 50.02GB | 3033/4041 | `█████░░░░░░░░░░ 39%` |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 45.9GB | 1498/4041 | `█████░░░░░░░░░░ 36%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.8x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.2x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (3.9x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.3x avg)
