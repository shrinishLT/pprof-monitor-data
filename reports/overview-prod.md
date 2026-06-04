# Overview: prod
*Last updated: 2026-06-04 07:50 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T07:50 (1049 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,236 | avg: 10,434 | max: 84,644 | trend: decreasing (-28.33/hr))
```
▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁█▃▁▁▁▁▁▁▁▃▁▃▂▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▁▁▁▁▁▃▂▃▅▁▁▁▁▃▁▁▁▁▃▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 150.2MB | avg: 155.9MB | max: 2823.8MB | trend: stable (-0.41MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,236 | 14,240 | -4 | 10,434 | 84,644 | decreasing (-28.33/hr) |
| Heap InUse | 150.2MB | 145.2MB | +5.0MB | 155.9MB | 2823.8MB | stable (-0.41MB/hr) |
| Heap Sys | 4135.3MB | 4135.3MB | +0.0MB | 2562.3MB | 6883.9MB | |
| Heap Objects | 800,624 | 634,230 | +166394 | 670,036 | 14,090,816 | |

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
| 2026-06-04 | 95 | 15,315 | 248.3MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.6MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `compress/flate.NewWriter` | 5.29MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.54MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 7 | `bytes.growSlice` | 3.04MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `reflect.mapassign_faststr0` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 42.44GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 16.75GB |
| 3 | `reflect.growslice` | 6.47GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 6.06GB |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 6.01GB |
| 6 | `jackskj/carta.getUniqueId` | 5.25GB |
| 7 | `database/sql.convertAssignRows` | 4.91GB |
| 8 | `reflect.unsafe_New` | 4.79GB |
| 9 | `fmt.(*buffer).writeString` | 3.78GB |
| 10 | `carta/value.NewCell` | 3.36GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 150.68MB | 142.56MB | 77.66MB | 0B |
| `evaluation.mergeMetadata` | 81.02MB | 75.52MB | 42.44MB | 0B |
| `local.(*Client).EvaluateV2` | 221.55MB | 210.86MB | 115.73MB | 0B |
| `local.topologicalSort` | 28.33MB | 27.32MB | 15.89MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 219.92MB | 208.69MB | 114.99MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 23.61MB | 22.61MB | 11.61MB | 0B |
| `localEvaluation.getMapOfValue` | 219.92MB | 208.69MB | 114.99MB | 0B |
| `utils.ParseFeatureFlag` | 220.42MB | 209.19MB | 115.12MB | 0B |

**Total FF alloc (current snapshot):** 1.14GB  |  **24h avg:** 608.44MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 64.64MB | 35/1049 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 59.47MB | 20/1049 | `█████████████░░ 92%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 700/1049 | `████████░░░░░░░ 56%` |
| 4 | `database/sql.convertAssignRows` | 32.78MB | 43/1049 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 20.93MB | 700/1049 | `████░░░░░░░░░░░ 32%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1049 | `████░░░░░░░░░░░ 27%` |
| 7 | `bytes.growSlice` | 13.07MB | 499/1049 | `███░░░░░░░░░░░░ 20%` |
| 8 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1049 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `net/http.(*Transport).dialConn` | 10.5MB | 9/1049 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.58MB | 23/1049 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1049 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1049 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1049 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1049 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1049 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 42.78GB | 673/1049 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1049 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.56GB | 604/1049 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `fmt.Sprintf` | 13.22GB | 347/1049 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `segmentio/kafka-go.makePartitions` | 12.47GB | 441/1049 | `█░░░░░░░░░░░░░░ 9%` |

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
