# Overview: prod
*Last updated: 2026-06-14 17:00 IST*
*Data range: 2026-05-15T16:03 to 2026-06-14T17:00 (4037 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,553 | avg: 14,704 | max: 84,644 | trend: INCREASING (+2.84/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▄▆▇▇█▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 236.6MB | avg: 242.8MB | max: 3154.1MB | trend: stable (+0.07MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▂▃▂▄▃▄▆▆▆█▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,553 | 14,198 | +355 | 14,704 | 84,644 | INCREASING (+2.84/hr) |
| Heap InUse | 236.6MB | 174.7MB | +61.9MB | 242.8MB | 3154.1MB | stable (+0.07MB/hr) |
| Heap Sys | 2407.3MB | 2407.9MB | -0.6MB | 2532.8MB | 6883.9MB | |
| Heap Objects | 1,047,389 | 496,234 | +551155 | 1,042,797 | 17,165,538 | |

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
| 2026-06-14 | 205 | 16,480 | 284.7MB | 1419.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 32.36MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `compress/flate.NewWriter` | 5.29MB |
| 6 | `reflect.unsafe_NewArray` | 3.53MB |
| 7 | `bytes.growSlice` | 3.01MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 10 | `reflect.mapassign_faststr0` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 90.26GB |
| 2 | `reflect.growslice` | 78.14GB |
| 3 | `segmentio/kafka-go.makePartitions` | 72.68GB |
| 4 | `jackskj/carta.getUniqueId` | 71.87GB |
| 5 | `reflect.unsafe_New` | 62.34GB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 54.38GB |
| 7 | `fmt.Sprintf` | 53.99GB |
| 8 | `fmt.(*buffer).writeString` | 48.69GB |
| 9 | `carta/value.NewCell` | 45.22GB |
| 10 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 44.74GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 2.81GB | 2.81GB | 2.74GB | 0B |
| `evaluation.mergeMetadata` | 1.44GB | 1.43GB | 1.41GB | 0B |
| `local.(*Client).EvaluateV2` | 4.32GB | 4.32GB | 4.22GB | 0B |
| `local.topologicalSort` | 631.95MB | 631.95MB | 615.56MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 4.28GB | 4.27GB | 4.18GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 485.22MB | 484.72MB | 465.83MB | 0B |
| `localEvaluation.getMapOfValue` | 4.28GB | 4.27GB | 4.18GB | 0B |
| `utils.ParseFeatureFlag` | 4.29GB | 4.28GB | 4.19GB | 0B |

**Total FF alloc (current snapshot):** 22.51GB  |  **24h avg:** 21.97GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 45.26MB | 81/4037 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 40.7MB | 111/4037 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3688/4037 | `████████████░░░ 80%` |
| 4 | `runtime.mallocgc` | 31.25MB | 3688/4037 | `██████████░░░░░ 69%` |
| 5 | `database/sql.convertAssignRows` | 22.86MB | 131/4037 | `███████░░░░░░░░ 50%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4037 | `█████░░░░░░░░░░ 39%` |
| 7 | `bytes.growSlice` | 15.9MB | 2907/4037 | `█████░░░░░░░░░░ 35%` |
| 8 | `net/http.(*Transport).dialConn` | 13.32MB | 108/4037 | `████░░░░░░░░░░░ 29%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/4037 | `███░░░░░░░░░░░░ 26%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4037 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4037 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4037 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4037 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 69.55GB | 2226/4037 | `████████░░░░░░░ 55%` |
| 5 | `reflect.growslice` | 59.32GB | 3249/4037 | `███████░░░░░░░░ 47%` |
| 6 | `segmentio/kafka-go.makePartitions` | 59.27GB | 3411/4037 | `███████░░░░░░░░ 47%` |
| 7 | `jackskj/carta.getUniqueId` | 52.79GB | 3265/4037 | `██████░░░░░░░░░ 42%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/4037 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 50.0GB | 3029/4037 | `█████░░░░░░░░░░ 39%` |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 45.9GB | 1498/4037 | `█████░░░░░░░░░░ 36%` |

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
