# Overview: prod
*Last updated: 2026-06-08 07:00 IST*
*Data range: 2026-05-15T16:03 to 2026-06-08T07:00 (2190 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,499 | avg: 13,277 | max: 84,644 | trend: INCREASING (+3.71/hr))
```
▁▁▁▁▁▂▃▁▁▁▁▁▄▄▂▃▁▁▁▁▁▁▁▁▂▁▁▃▁▂▃▁▁▂▄▅▃▁▃▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▂▃▂▂▂▁▃▂▃▁▁▁▁▂▁▁▁▁▂▃▁▃█▆▅▁▁▁▁▁▄▃▃▄▄▂▄▂▁▁▁▂
```

**Heap InUse** (current: 218.1MB | avg: 199.3MB | max: 3154.1MB | trend: stable (+0.06MB/hr))
```
▂▂▆▄▄▄▆▅▄▅▃▃▅▄▅▆▃▂▁▁▁▁▁▃▁▃▁▄▂▂▃▂▁▃▆▅▃▄▇▁▄▄▅▅▂▅▁▃▂▂▂▃▅▄▂▅▄▃▂▅▃▄▅▁▂▂▄▃▁▃▄▃▅▅▅▅▅▆█▄▁▂▄▁▆▃▄▄▄▄▄▄▂▁▃▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,499 | 14,156 | +343 | 13,277 | 84,644 | INCREASING (+3.71/hr) |
| Heap InUse | 218.1MB | 235.0MB | -16.9MB | 199.3MB | 3154.1MB | stable (+0.06MB/hr) |
| Heap Sys | 3223.4MB | 3223.8MB | -0.4MB | 2338.6MB | 6883.9MB | |
| Heap Objects | 958,982 | 1,245,418 | -286436 | 896,428 | 17,165,538 | |

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
| 2026-06-08 | 85 | 14,481 | 237.2MB | 333.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 49.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 7.49MB |
| 6 | `database/sql.convertAssignRows` | 4.0MB |
| 7 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 3.65MB |
| 8 | `bytes.growSlice` | 3.02MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `segmentio/kafka-go.makePartitions` | 2.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 57.0GB |
| 2 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 48.21GB |
| 3 | `reflect.growslice` | 47.91GB |
| 4 | `jackskj/carta.getUniqueId` | 39.91GB |
| 5 | `reflect.unsafe_New` | 36.36GB |
| 6 | `fmt.(*buffer).writeString` | 30.45GB |
| 7 | `reflect.unsafe_NewArray` | 29.13GB |
| 8 | `carta/value.NewCell` | 25.87GB |
| 9 | `fmt.Sprintf` | 21.07GB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 20.91GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.55GB | 1.54GB | 1.46GB | 0B |
| `evaluation.mergeMetadata` | 821.70MB | 817.70MB | 774.03MB | 0B |
| `local.(*Client).EvaluateV2` | 2.35GB | 2.34GB | 2.21GB | 0B |
| `local.topologicalSort` | 320.46MB | 318.95MB | 300.54MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.35GB | 2.34GB | 2.21GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 245.82MB | 245.82MB | 233.27MB | 0B |
| `localEvaluation.getMapOfValue` | 2.35GB | 2.34GB | 2.21GB | 0B |
| `utils.ParseFeatureFlag` | 2.35GB | 2.34GB | 2.21GB | 0B |

**Total FF alloc (current snapshot):** 12.30GB  |  **24h avg:** 11.57GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 83.58MB | 38/2190 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 64.17MB | 64/2190 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1841/2190 | `██████░░░░░░░░░ 43%` |
| 4 | `database/sql.convertAssignRows` | 31.29MB | 87/2190 | `█████░░░░░░░░░░ 37%` |
| 5 | `runtime.mallocgc` | 21.03MB | 1841/2190 | `███░░░░░░░░░░░░ 25%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2190 | `███░░░░░░░░░░░░ 21%` |
| 7 | `bytes.growSlice` | 14.36MB | 1333/2190 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `net/http.(*Transport).dialConn` | 13.47MB | 37/2190 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2190 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 10.48MB | 38/2190 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2190 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2190 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2190 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2190 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2190 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2190 | `███░░░░░░░░░░░░ 22%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2190 | `███░░░░░░░░░░░░ 21%` |
| 8 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 21.66GB | 707/2190 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `segmentio/kafka-go.makePartitions` | 16.87GB | 1564/2190 | `██░░░░░░░░░░░░░ 13%` |
| 10 | `reflect.growslice` | 14.78GB | 1402/2190 | `█░░░░░░░░░░░░░░ 11%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.5x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.4x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.1x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.4x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.3x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.0x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.9x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.8x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.5x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (3.1x avg)
