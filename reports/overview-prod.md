# Overview: prod
*Last updated: 2026-06-08 07:25 IST*
*Data range: 2026-05-15T16:03 to 2026-06-08T07:25 (2195 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,222 | avg: 13,279 | max: 84,644 | trend: INCREASING (+3.70/hr))
```
▂▃▁▁▁▁▁▄▄▂▃▁▁▁▁▁▁▁▁▂▁▁▃▁▂▃▁▁▂▄▅▃▁▃▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▂▃▂▂▂▁▃▂▃▁▁▁▁▂▁▁▁▁▂▃▁▃█▆▅▁▁▁▁▁▄▃▃▄▄▂▄▂▁▁▁▂▂▂▂▁▁
```

**Heap InUse** (current: 249.0MB | avg: 199.4MB | max: 3154.1MB | trend: stable (+0.06MB/hr))
```
▄▆▅▄▅▃▃▅▄▅▆▃▂▁▁▁▁▁▃▁▃▁▄▂▂▃▂▁▃▆▅▃▄▇▁▄▄▅▅▂▅▁▃▂▂▂▃▅▄▂▅▄▃▂▅▃▄▅▁▂▂▄▃▁▃▄▃▅▅▅▅▅▆█▄▁▂▄▁▆▃▄▄▄▄▄▄▂▁▃▂▃▃▃▂▄
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,222 | 14,317 | -95 | 13,279 | 84,644 | INCREASING (+3.70/hr) |
| Heap InUse | 249.0MB | 208.5MB | +40.5MB | 199.4MB | 3154.1MB | stable (+0.06MB/hr) |
| Heap Sys | 3223.9MB | 3223.7MB | +0.2MB | 2340.6MB | 6883.9MB | |
| Heap Objects | 1,261,053 | 712,160 | +548893 | 896,520 | 17,165,538 | |

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
| 2026-06-08 | 90 | 14,476 | 236.6MB | 333.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 49.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 7 | `aws/endpoints.init` | 2.0MB |
| 8 | `reflect.mapassign_faststr0` | 2.0MB |
| 9 | `compress/flate.NewWriter` | 1.76MB |
| 10 | `reflect.growslice` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 57.53GB |
| 2 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 48.22GB |
| 3 | `reflect.growslice` | 48.07GB |
| 4 | `jackskj/carta.getUniqueId` | 40.09GB |
| 5 | `reflect.unsafe_New` | 36.51GB |
| 6 | `fmt.(*buffer).writeString` | 30.52GB |
| 7 | `reflect.unsafe_NewArray` | 29.42GB |
| 8 | `carta/value.NewCell` | 25.95GB |
| 9 | `fmt.Sprintf` | 21.18GB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 20.95GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.58GB | 1.57GB | 1.48GB | 0B |
| `evaluation.mergeMetadata` | 833.70MB | 831.20MB | 783.82MB | 0B |
| `local.(*Client).EvaluateV2` | 2.39GB | 2.38GB | 2.24GB | 0B |
| `local.topologicalSort` | 326.02MB | 324.50MB | 304.92MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.39GB | 2.38GB | 2.24GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 248.92MB | 247.40MB | 235.47MB | 0B |
| `localEvaluation.getMapOfValue` | 2.39GB | 2.38GB | 2.24GB | 0B |
| `utils.ParseFeatureFlag` | 2.39GB | 2.39GB | 2.24GB | 0B |

**Total FF alloc (current snapshot):** 12.52GB  |  **24h avg:** 11.72GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 83.58MB | 38/2195 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 64.17MB | 64/2195 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1846/2195 | `██████░░░░░░░░░ 43%` |
| 4 | `database/sql.convertAssignRows` | 31.29MB | 87/2195 | `█████░░░░░░░░░░ 37%` |
| 5 | `runtime.mallocgc` | 21.11MB | 1846/2195 | `███░░░░░░░░░░░░ 25%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2195 | `███░░░░░░░░░░░░ 21%` |
| 7 | `bytes.growSlice` | 14.34MB | 1336/2195 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `net/http.(*Transport).dialConn` | 13.47MB | 37/2195 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2195 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 10.48MB | 38/2195 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2195 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2195 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2195 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2195 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2195 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2195 | `███░░░░░░░░░░░░ 22%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2195 | `███░░░░░░░░░░░░ 21%` |
| 8 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 21.84GB | 712/2195 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `segmentio/kafka-go.makePartitions` | 17.0GB | 1569/2195 | `██░░░░░░░░░░░░░ 13%` |
| 10 | `reflect.growslice` | 14.9GB | 1407/2195 | `█░░░░░░░░░░░░░░ 11%` |

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
