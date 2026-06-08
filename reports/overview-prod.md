# Overview: prod
*Last updated: 2026-06-08 08:40 IST*
*Data range: 2026-05-15T16:03 to 2026-06-08T08:40 (2210 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,689 | avg: 13,289 | max: 84,644 | trend: INCREASING (+3.68/hr))
```
▁▁▁▁▁▁▁▃▁▁▂▁▁▂▄▄▃▁▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▂▂▂▁▁▁▂▂▂▁▁▁▁▂▁▁▁▁▂▂▁▃▆▅▄▁▁▁▁▁▄▂▂▃▃▂▄▂▁▁▁▂▂▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▇█▃▂
```

**Heap InUse** (current: 290.2MB | avg: 199.8MB | max: 3154.1MB | trend: stable (+0.06MB/hr))
```
▁▁▁▃▁▃▁▄▂▂▃▂▁▃▆▅▃▄▇▁▄▄▅▅▂▅▁▃▂▂▂▃▅▄▂▅▄▃▂▅▃▄▅▁▂▂▄▃▁▃▄▃▅▅▅▅▅▆█▄▁▂▄▁▆▃▄▄▄▄▄▄▂▁▃▂▃▃▃▂▄▂▄▄▃▄▆▄▁▂▃▅▆▆▅▆
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,689 | 15,134 | -445 | 13,289 | 84,644 | INCREASING (+3.68/hr) |
| Heap InUse | 290.2MB | 274.4MB | +15.8MB | 199.8MB | 3154.1MB | stable (+0.06MB/hr) |
| Heap Sys | 3218.2MB | 3217.6MB | +0.6MB | 2346.6MB | 6883.9MB | |
| Heap Objects | 1,677,146 | 1,124,122 | +553024 | 898,179 | 17,165,538 | |

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
| 2026-06-08 | 105 | 14,506 | 239.0MB | 333.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 49.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `bytes.growSlice` | 5.03MB |
| 6 | `compress/flate.NewWriter` | 4.41MB |
| 7 | `bufio.NewReaderSize` | 3.01MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `bufio.NewWriterSize` | 2.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 59.26GB |
| 2 | `reflect.growslice` | 48.39GB |
| 3 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 48.25GB |
| 4 | `jackskj/carta.getUniqueId` | 40.47GB |
| 5 | `reflect.unsafe_New` | 36.78GB |
| 6 | `fmt.(*buffer).writeString` | 30.66GB |
| 7 | `reflect.unsafe_NewArray` | 30.28GB |
| 8 | `carta/value.NewCell` | 26.15GB |
| 9 | `fmt.Sprintf` | 21.74GB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 20.95GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.67GB | 1.66GB | 1.54GB | 0B |
| `evaluation.mergeMetadata` | 883.71MB | 879.21MB | 816.98MB | 0B |
| `local.(*Client).EvaluateV2` | 2.53GB | 2.52GB | 2.34GB | 0B |
| `local.topologicalSort` | 344.24MB | 343.23MB | 318.45MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.54GB | 2.53GB | 2.34GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 252.02MB | 252.02MB | 242.69MB | 0B |
| `localEvaluation.getMapOfValue` | 2.54GB | 2.53GB | 2.34GB | 0B |
| `utils.ParseFeatureFlag` | 2.55GB | 2.54GB | 2.34GB | 0B |

**Total FF alloc (current snapshot):** 13.29GB  |  **24h avg:** 12.23GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 83.58MB | 38/2210 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 64.17MB | 64/2210 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1861/2210 | `██████░░░░░░░░░ 43%` |
| 4 | `database/sql.convertAssignRows` | 31.29MB | 87/2210 | `█████░░░░░░░░░░ 37%` |
| 5 | `runtime.mallocgc` | 21.34MB | 1861/2210 | `███░░░░░░░░░░░░ 25%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2210 | `███░░░░░░░░░░░░ 21%` |
| 7 | `bytes.growSlice` | 14.26MB | 1347/2210 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `net/http.(*Transport).dialConn` | 13.47MB | 37/2210 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2210 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 10.48MB | 38/2210 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2210 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2210 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2210 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2210 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2210 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2210 | `███░░░░░░░░░░░░ 22%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2210 | `███░░░░░░░░░░░░ 21%` |
| 8 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 22.39GB | 727/2210 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `segmentio/kafka-go.makePartitions` | 17.39GB | 1584/2210 | `██░░░░░░░░░░░░░ 13%` |
| 10 | `reflect.growslice` | 15.25GB | 1422/2210 | `█░░░░░░░░░░░░░░ 12%` |

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
