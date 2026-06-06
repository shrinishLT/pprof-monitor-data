# Overview: prod
*Last updated: 2026-06-06 16:35 IST*
*Data range: 2026-05-15T16:03 to 2026-06-06T16:35 (1729 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,172 | avg: 12,811 | max: 84,644 | trend: INCREASING (+3.46/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▄▇█▇▄▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 116.5MB | avg: 194.2MB | max: 3154.1MB | trend: stable (+0.06MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▄▆▇█▄▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 1%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,172 | 14,313 | -141 | 12,811 | 84,644 | INCREASING (+3.46/hr) |
| Heap InUse | 116.5MB | 175.0MB | -58.5MB | 194.2MB | 3154.1MB | stable (+0.06MB/hr) |
| Heap Sys | 852.6MB | 852.5MB | +0.1MB | 2395.8MB | 6883.9MB | |
| Heap Objects | 494,638 | 1,107,986 | -613348 | 862,679 | 17,165,538 | |

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
| 2026-06-06 | 200 | 16,547 | 253.8MB | 1932.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.58MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.03MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 1.5MB |
| 10 | `net/http.init.func16` | 1.03MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 4.54GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 2.75GB |
| 3 | `reflect.unsafe_NewArray` | 2.3GB |
| 4 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 2.28GB |
| 5 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 1.85GB |
| 6 | `reflect.growslice` | 1.81GB |
| 7 | `jackskj/carta.getUniqueId` | 1.72GB |
| 8 | `reflect.unsafe_New` | 1.43GB |
| 9 | `reflect.MakeSlice` | 1.3GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 1.2GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 179.79MB | 175.75MB | 339.23MB | 0B |
| `evaluation.mergeMetadata` | 88.52MB | 85.52MB | 173.62MB | 0B |
| `local.(*Client).EvaluateV2` | 269.68MB | 264.62MB | 513.73MB | 0B |
| `local.topologicalSort` | 38.45MB | 37.94MB | 71.50MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 267.10MB | 262.55MB | 503.41MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 26.58MB | 25.56MB | 58.04MB | 0B |
| `localEvaluation.getMapOfValue` | 267.10MB | 262.55MB | 503.41MB | 0B |
| `utils.ParseFeatureFlag` | 267.10MB | 262.55MB | 504.07MB | 0B |

**Total FF alloc (current snapshot):** 1.37GB  |  **24h avg:** 2.60GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 88.01MB | 36/1729 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 70.26MB | 58/1729 | `███████████░░░░ 79%` |
| 3 | `database/sql.convertAssignRows` | 37.7MB | 71/1729 | `██████░░░░░░░░░ 42%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1380/1729 | `██████░░░░░░░░░ 41%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1729 | `███░░░░░░░░░░░░ 20%` |
| 6 | `runtime.mallocgc` | 17.33MB | 1380/1729 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `bytes.growSlice` | 15.32MB | 1070/1729 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `net/http.(*Transport).dialConn` | 12.61MB | 32/1729 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1729 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1729 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1729 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1729 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1729 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1729 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1729 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 29.9GB | 1143/1729 | `███░░░░░░░░░░░░ 23%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1729 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.36GB | 960/1729 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 12.86GB | 401/1729 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `fmt.Sprintf` | 12.8GB | 873/1729 | `█░░░░░░░░░░░░░░ 10%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.6x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.2x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.5x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.4x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.1x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.1x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.9x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.6x avg)
