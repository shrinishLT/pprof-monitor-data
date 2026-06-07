# Overview: prod
*Last updated: 2026-06-07 22:40 IST*
*Data range: 2026-05-15T16:03 to 2026-06-07T22:40 (2090 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,090 | avg: 13,221 | max: 84,644 | trend: INCREASING (+3.93/hr))
```
▁▂▅▃▃▅▃▂▃▂▂▃▂▆█▄▆▁▁▁▁▃▂▁▁▁▁▁▂▁▁▁▂▁▁▁▁▁▁▁▃▁▁▁▂▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▂▁▁▂▂▂▁▂▁▂▄▂▂▂▂▁▁▁▁▁▁▁▂▁▁▁▁
```

**Heap InUse** (current: 250.7MB | avg: 197.5MB | max: 3154.1MB | trend: stable (+0.05MB/hr))
```
▂▄▃▄▂▃▆▂█▅▅▄▂▅▅▆▄▁▃▂▅▅▃▄▁▅▂▅▁▁▃▃▃▄▁▂▃▃▃▄▂▁▃▁▂▁▂▃▃▃▁▁▄▅▄▁▅▂▁▅▄▂▂▁▁▄▄▁▄▂▂▂▂▂▃▄▆▅▂▃▅▂▅▂▂▂▂▃▄▄▃▃▃▄▄▄
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,090 | 14,096 | -6 | 13,221 | 84,644 | INCREASING (+3.93/hr) |
| Heap InUse | 250.7MB | 264.6MB | -13.9MB | 197.5MB | 3154.1MB | stable (+0.05MB/hr) |
| Heap Sys | 3221.2MB | 3221.2MB | +0.0MB | 2296.2MB | 6883.9MB | |
| Heap Objects | 1,599,134 | 1,787,679 | -188545 | 890,370 | 17,165,538 | |

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
| 2026-06-07 | 273 | 15,487 | 234.0MB | 1942.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 49.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.52MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `reflect.unsafe_NewArray` | 1.51MB |
| 10 | `segmentio/kafka-go.makeLayout` | 1.03MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 45.62GB |
| 2 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 40.04GB |
| 3 | `reflect.growslice` | 34.42GB |
| 4 | `jackskj/carta.getUniqueId` | 29.58GB |
| 5 | `reflect.unsafe_New` | 26.59GB |
| 6 | `reflect.unsafe_NewArray` | 23.32GB |
| 7 | `fmt.(*buffer).writeString` | 21.36GB |
| 8 | `carta/value.NewCell` | 19.01GB |
| 9 | `fmt.Sprintf` | 16.97GB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 16.3GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.26GB | 1.26GB | 1.19GB | 0B |
| `evaluation.mergeMetadata` | 661.16MB | 661.16MB | 629.47MB | 0B |
| `local.(*Client).EvaluateV2` | 1.90GB | 1.90GB | 1.80GB | 0B |
| `local.topologicalSort` | 255.11MB | 255.11MB | 243.98MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.89GB | 1.89GB | 1.80GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 207.52MB | 207.52MB | 191.27MB | 0B |
| `localEvaluation.getMapOfValue` | 1.89GB | 1.89GB | 1.80GB | 0B |
| `utils.ParseFeatureFlag` | 1.89GB | 1.89GB | 1.80GB | 0B |

**Total FF alloc (current snapshot):** 9.92GB  |  **24h avg:** 9.43GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 85.72MB | 37/2090 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 65.15MB | 63/2090 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1741/2090 | `██████░░░░░░░░░ 42%` |
| 4 | `database/sql.convertAssignRows` | 33.39MB | 81/2090 | `█████░░░░░░░░░░ 38%` |
| 5 | `runtime.mallocgc` | 19.4MB | 1741/2090 | `███░░░░░░░░░░░░ 22%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2090 | `███░░░░░░░░░░░░ 20%` |
| 7 | `bytes.growSlice` | 14.84MB | 1272/2090 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `net/http.(*Transport).dialConn` | 13.47MB | 37/2090 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2090 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 10.48MB | 38/2090 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2090 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2090 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2090 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2090 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2090 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2090 | `███░░░░░░░░░░░░ 22%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2090 | `███░░░░░░░░░░░░ 21%` |
| 8 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 18.3GB | 607/2090 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `segmentio/kafka-go.makePartitions` | 14.51GB | 1464/2090 | `█░░░░░░░░░░░░░░ 11%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 14.23GB | 969/2090 | `█░░░░░░░░░░░░░░ 11%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.6x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.4x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.1x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.4x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.3x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.0x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.0x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.9x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.5x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (3.1x avg)
