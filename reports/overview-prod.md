# Overview: prod
*Last updated: 2026-06-04 08:40 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T08:40 (1059 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,297 | avg: 10,470 | max: 84,644 | trend: decreasing (-27.14/hr))
```
▁▁▁▁▁▁▁▁█▃▁▁▁▁▁▁▁▃▁▃▂▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▁▁▁▁▁▃▂▃▅▁▁▁▁▃▁▁▁▁▃▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 128.1MB | avg: 155.9MB | max: 2823.8MB | trend: stable (-0.39MB/hr))
```
▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 1%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,297 | 14,192 | +105 | 10,470 | 84,644 | decreasing (-27.14/hr) |
| Heap InUse | 128.1MB | 161.5MB | -33.4MB | 155.9MB | 2823.8MB | stable (-0.39MB/hr) |
| Heap Sys | 4135.6MB | 4135.3MB | +0.3MB | 2577.2MB | 6883.9MB | |
| Heap Objects | 504,722 | 1,023,728 | -519006 | 671,623 | 14,090,816 | |

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
| 2026-06-04 | 105 | 15,210 | 239.4MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.6MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.01MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 1.74MB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 1.74MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 42.47GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 16.77GB |
| 3 | `reflect.growslice` | 6.64GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 6.07GB |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 6.06GB |
| 6 | `jackskj/carta.getUniqueId` | 5.44GB |
| 7 | `database/sql.convertAssignRows` | 4.97GB |
| 8 | `reflect.unsafe_New` | 4.94GB |
| 9 | `segmentio/kafka-go.makePartitions` | 4.29GB |
| 10 | `fmt.(*buffer).writeString` | 3.85GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 182.59MB | 179.01MB | 88.32MB | 0B |
| `evaluation.mergeMetadata` | 96.02MB | 94.52MB | 48.00MB | 0B |
| `local.(*Client).EvaluateV2` | 272.67MB | 268.04MB | 130.64MB | 0B |
| `local.topologicalSort` | 35.93MB | 35.42MB | 17.45MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 274.65MB | 270.01MB | 131.08MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 24.61MB | 23.61MB | 13.41MB | 0B |
| `localEvaluation.getMapOfValue` | 274.65MB | 270.01MB | 131.08MB | 0B |
| `utils.ParseFeatureFlag` | 275.15MB | 270.51MB | 131.31MB | 0B |

**Total FF alloc (current snapshot):** 1.40GB  |  **24h avg:** 691.29MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 62.96MB | 36/1059 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 56.78MB | 21/1059 | `█████████████░░ 90%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 710/1059 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 32.09MB | 44/1059 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 20.81MB | 710/1059 | `████░░░░░░░░░░░ 33%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1059 | `████░░░░░░░░░░░ 28%` |
| 7 | `bytes.growSlice` | 13.03MB | 501/1059 | `███░░░░░░░░░░░░ 20%` |
| 8 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1059 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `net/http.(*Transport).dialConn` | 10.5MB | 9/1059 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.58MB | 23/1059 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1059 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1059 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1059 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1059 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1059 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 42.77GB | 683/1059 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1059 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.51GB | 614/1059 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `fmt.Sprintf` | 13.22GB | 347/1059 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `segmentio/kafka-go.makePartitions` | 12.32GB | 449/1059 | `█░░░░░░░░░░░░░░ 9%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (12.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (8.1x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.8x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (3.1x avg)
- Heap spike to 391.4MB at 2026-05-17T10:03 (2.5x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.7x avg)
- Heap spike to 404.6MB at 2026-05-18T06:03 (2.6x avg)
- Goroutine spike to 21,569 at 2026-05-18T10:01 (2.1x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (3.2x avg)
- Heap spike to 408.3MB at 2026-05-18T16:02 (2.6x avg)
