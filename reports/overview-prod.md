# Overview: prod
*Last updated: 2026-06-04 00:35 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T00:35 (962 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,107 | avg: 9,989 | max: 84,644 | trend: decreasing (-42.77/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▆▁█▇▆▇▇▆▆▆▆▇▆▆▆▆
```

**Heap InUse** (current: 116.5MB | avg: 147.0MB | max: 1896.6MB | trend: decreasing (-0.65MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▇▆▅▅▆▄▄▆▄█▆▃▃▃
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 1%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,107 | 14,342 | -235 | 9,989 | 84,644 | decreasing (-42.77/hr) |
| Heap InUse | 116.5MB | 134.2MB | -17.7MB | 147.0MB | 1896.6MB | decreasing (-0.65MB/hr) |
| Heap Sys | 2428.3MB | 2428.6MB | -0.3MB | 2579.7MB | 6883.9MB | |
| Heap Objects | 356,577 | 532,207 | -175630 | 628,762 | 8,100,802 | |

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
| 2026-06-04 | 8 | 14,861 | 183.7MB | 318.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 2.24MB |
| 8 | `segmentio/kafka-go.makePartitions` | 1.5MB |
| 9 | `aws/endpoints.init` | 1.5MB |
| 10 | `v3/newrelic.newAnalyticsEvents` | 1.06MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 3.56GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 1.39GB |
| 3 | `segmentio/kafka-go.makePartitions` | 1.31GB |
| 4 | `fmt.Sprintf` | 1.04GB |
| 5 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 974.99MB |
| 6 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 823.1MB |
| 7 | `reflect.unsafe_NewArray` | 689.89MB |
| 8 | `go-sql-driver/mysql.(*binaryRows).readRow` | 631.01MB |
| 9 | `database/sql.convertAssignRows` | 533.53MB |
| 10 | `strconv.appendQuotedWith` | 499.08MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 78.05MB | 72.94MB | 80.31MB | 0B |
| `evaluation.mergeMetadata` | 41.51MB | 39.01MB | 41.21MB | 0B |
| `local.(*Client).EvaluateV2` | 112.03MB | 105.90MB | 120.70MB | 0B |
| `local.topologicalSort` | 19.28MB | 18.77MB | 20.05MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 101.36MB | 95.77MB | 103.03MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 19.37MB | 18.32MB | 26.81MB | 0B |
| `localEvaluation.getMapOfValue` | 101.36MB | 95.77MB | 103.03MB | 0B |
| `utils.ParseFeatureFlag` | 101.86MB | 96.27MB | 103.40MB | 0B |

**Total FF alloc (current snapshot):** 574.83MB  |  **24h avg:** 598.54MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 49.06MB | 26/962 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 43.74MB | 16/962 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 613/962 | `███████████░░░░ 74%` |
| 4 | `database/sql.convertAssignRows` | 26.65MB | 33/962 | `████████░░░░░░░ 54%` |
| 5 | `runtime.mallocgc` | 22.05MB | 613/962 | `██████░░░░░░░░░ 44%` |
| 6 | `bytes.growSlice` | 13.36MB | 423/962 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*Transport).dialConn` | 11.31MB | 8/962 | `███░░░░░░░░░░░░ 23%` |
| 8 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/962 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 9.68MB | 3/962 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.2MB | 606/962 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/962 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/962 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/962 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/962 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 47.12GB | 590/962 | `█████░░░░░░░░░░ 37%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/962 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/962 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 21.07GB | 543/962 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `fmt.Sprintf` | 15.81GB | 280/962 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `segmentio/kafka-go.makePartitions` | 13.68GB | 396/962 | `█░░░░░░░░░░░░░░ 10%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (12.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (8.5x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (3.0x avg)
- Goroutine spike to 20,552 at 2026-05-16T03:31 (2.1x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (3.3x avg)
- Heap spike to 391.4MB at 2026-05-17T10:03 (2.7x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.8x avg)
- Heap spike to 404.6MB at 2026-05-18T06:03 (2.8x avg)
- Heap spike to 373.5MB at 2026-05-18T10:01 (2.5x avg)
- Goroutine spike to 21,569 at 2026-05-18T10:01 (2.2x avg)
