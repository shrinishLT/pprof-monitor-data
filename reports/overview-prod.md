# Overview: prod
*Last updated: 2026-06-05 05:30 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T05:30 (1309 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,224 | avg: 11,657 | max: 84,644 | trend: decreasing (-5.91/hr))
```
█▇▅▆▂▂▂▁▁▁▁▁▁▂▁▁▁▁▁▁▁▂▄▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▄▂▁▁▁▁▁▁▁▁▂▂▁▂▂▂▁▁▁▁▂▁▁▁▂▁▁▁▂▁▁▁▁▁▂▂▂▂▃▃▁▁▁▁▁▁▁▁▁▄▂▁▁▁▁▁▁▁
```

**Heap InUse** (current: 200.0MB | avg: 179.3MB | max: 3154.1MB | trend: stable (-0.04MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,224 | 14,956 | -732 | 11,657 | 84,644 | decreasing (-5.91/hr) |
| Heap InUse | 200.0MB | 203.9MB | -3.9MB | 179.3MB | 3154.1MB | stable (-0.04MB/hr) |
| Heap Sys | 4532.1MB | 4531.3MB | +0.8MB | 2688.6MB | 6883.9MB | |
| Heap Objects | 1,246,118 | 1,164,587 | +81531 | 796,111 | 17,165,538 | |

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
| 2026-06-05 | 67 | 14,932 | 272.9MB | 3154.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 7.51MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `reflect.unsafe_New` | 4.5MB |
| 6 | `bytes.growSlice` | 2.51MB |
| 7 | `jackskj/carta.getUniqueId` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 10 | `carta/value.(*Cell).Scan` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 20.62GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 8.16GB |
| 3 | `segmentio/kafka-go.makePartitions` | 4.16GB |
| 4 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.75GB |
| 5 | `database/sql.convertAssignRows` | 2.46GB |
| 6 | `reflect.unsafe_NewArray` | 2.15GB |
| 7 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 2.05GB |
| 8 | `fmt.Sprintf` | 1.88GB |
| 9 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 1.69GB |
| 10 | `reflect.MakeSlice` | 1.16GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 217.49MB | 213.43MB | 144.56MB | 0B |
| `evaluation.mergeMetadata` | 109.53MB | 108.03MB | 73.38MB | 0B |
| `local.(*Client).EvaluateV2` | 327.60MB | 320.93MB | 214.09MB | 0B |
| `local.topologicalSort` | 47.04MB | 45.51MB | 30.94MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 330.18MB | 320.97MB | 206.21MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 29.10MB | 29.10MB | 25.85MB | 0B |
| `localEvaluation.getMapOfValue` | 330.18MB | 320.97MB | 206.21MB | 0B |
| `utils.ParseFeatureFlag` | 331.18MB | 321.97MB | 206.72MB | 0B |

**Total FF alloc (current snapshot):** 1.68GB  |  **24h avg:** 1.08GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 99.07MB | 29/1309 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 81.93MB | 46/1309 | `████████████░░░ 82%` |
| 3 | `database/sql.convertAssignRows` | 41.93MB | 58/1309 | `██████░░░░░░░░░ 42%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 960/1309 | `█████░░░░░░░░░░ 36%` |
| 5 | `runtime.mallocgc` | 18.41MB | 960/1309 | `██░░░░░░░░░░░░░ 18%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1309 | `██░░░░░░░░░░░░░ 18%` |
| 7 | `bytes.growSlice` | 14.53MB | 732/1309 | `██░░░░░░░░░░░░░ 14%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1309 | `█░░░░░░░░░░░░░░ 12%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1309 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1309 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1309 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1309 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1309 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1309 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1309 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 35.3GB | 932/1309 | `████░░░░░░░░░░░ 28%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1309 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 15.71GB | 855/1309 | `█░░░░░░░░░░░░░░ 12%` |
| 9 | `fmt.Sprintf` | 9.82GB | 540/1309 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.77GB | 175/1309 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.6x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.3x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.7x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.4x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.7x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.7x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.7x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.3x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.4x avg)
- Goroutine spike to 25,220 at 2026-05-20T02:02 (2.2x avg)
