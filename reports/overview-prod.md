# Overview: prod
*Last updated: 2026-06-05 04:15 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T04:15 (1294 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,379 | avg: 11,620 | max: 84,644 | trend: decreasing (-6.46/hr))
```
▅▄▂▂▃▁▂▁▁▁▁▁▁▃▅█▇▅▆▂▂▂▁▁▁▁▁▁▂▁▁▁▁▁▁▁▂▄▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▄▂▁▁▁▁▁▁▁▁▂▂▁▂▂▂▁▁▁▁▂▁▁▁▂▁▁▁▂▁▁▁▁▁▂▂▂▂▃▃▁▁▁
```

**Heap InUse** (current: 156.3MB | avg: 177.6MB | max: 3154.1MB | trend: stable (-0.06MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,379 | 14,345 | +34 | 11,620 | 84,644 | decreasing (-6.46/hr) |
| Heap InUse | 156.3MB | 142.8MB | +13.5MB | 177.6MB | 3154.1MB | stable (-0.06MB/hr) |
| Heap Sys | 3172.4MB | 3172.1MB | +0.3MB | 2667.2MB | 6883.9MB | |
| Heap Objects | 779,684 | 547,383 | +232301 | 781,219 | 17,165,538 | |

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
| 2026-06-05 | 52 | 14,966 | 256.2MB | 3154.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 7.51MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `compress/flate.NewWriter` | 5.29MB |
| 6 | `segmentio/kafka-go.makePartitions` | 4.02MB |
| 7 | `bytes.growSlice` | 3.52MB |
| 8 | `bufio.NewReaderSize` | 3.04MB |
| 9 | `reflect.mapassign_faststr0` | 2.5MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 8.19GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 3.26GB |
| 3 | `segmentio/kafka-go.makePartitions` | 2.38GB |
| 4 | `reflect.unsafe_NewArray` | 1.25GB |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 1.16GB |
| 6 | `fmt.Sprintf` | 1.15GB |
| 7 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 1.04GB |
| 8 | `database/sql.convertAssignRows` | 1.02GB |
| 9 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 883.83MB |
| 10 | `reflect.MakeSlice` | 701.52MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 139.79MB | 133.17MB | 141.74MB | 0B |
| `evaluation.mergeMetadata` | 74.02MB | 69.02MB | 71.91MB | 0B |
| `local.(*Client).EvaluateV2` | 210.61MB | 201.41MB | 204.89MB | 0B |
| `local.topologicalSort` | 30.32MB | 29.30MB | 29.65MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 204.48MB | 194.78MB | 191.47MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 22.98MB | 22.48MB | 29.28MB | 0B |
| `localEvaluation.getMapOfValue` | 204.48MB | 194.78MB | 191.47MB | 0B |
| `utils.ParseFeatureFlag` | 204.98MB | 195.28MB | 191.66MB | 0B |

**Total FF alloc (current snapshot):** 1.07GB  |  **24h avg:** 1.03GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 76.66MB | 28/1294 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 75.25MB | 44/1294 | `██████████████░ 98%` |
| 3 | `database/sql.convertAssignRows` | 37.16MB | 56/1294 | `███████░░░░░░░░ 48%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 945/1294 | `███████░░░░░░░░ 47%` |
| 5 | `runtime.mallocgc` | 18.58MB | 945/1294 | `███░░░░░░░░░░░░ 24%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1294 | `███░░░░░░░░░░░░ 23%` |
| 7 | `bytes.growSlice` | 14.65MB | 721/1294 | `██░░░░░░░░░░░░░ 19%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1294 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1294 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1294 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1294 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1294 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1294 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1294 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1294 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 35.62GB | 917/1294 | `████░░░░░░░░░░░ 28%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1294 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 15.88GB | 840/1294 | `█░░░░░░░░░░░░░░ 12%` |
| 9 | `fmt.Sprintf` | 10.05GB | 525/1294 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.77GB | 175/1294 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.7x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.3x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.7x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.4x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.8x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.7x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.3x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.4x avg)
- Goroutine spike to 25,220 at 2026-05-20T02:02 (2.2x avg)
