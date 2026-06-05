# Overview: prod
*Last updated: 2026-06-05 05:35 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T05:35 (1310 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,308 | avg: 11,659 | max: 84,644 | trend: decreasing (-5.88/hr))
```
█▅▇▂▂▂▂▁▂▁▁▁▃▁▁▁▁▁▁▁▂▅▃▁▁▁▁▂▁▁▁▁▁▁▁▁▁▄▂▁▁▁▁▁▁▁▁▂▂▁▂▂▂▁▁▁▁▃▁▁▁▂▁▁▁▂▁▁▁▁▁▂▃▂▃▄▄▁▁▁▁▁▁▁▁▁▄▂▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 162.4MB | avg: 179.3MB | max: 3154.1MB | trend: stable (-0.04MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,308 | 14,224 | +84 | 11,659 | 84,644 | decreasing (-5.88/hr) |
| Heap InUse | 162.4MB | 200.0MB | -37.6MB | 179.3MB | 3154.1MB | stable (-0.04MB/hr) |
| Heap Sys | 4532.4MB | 4532.1MB | +0.3MB | 2690.0MB | 6883.9MB | |
| Heap Objects | 750,774 | 1,246,118 | -495344 | 796,076 | 17,165,538 | |

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
| 2026-06-05 | 68 | 14,923 | 271.3MB | 3154.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `reflect.unsafe_New` | 8.51MB |
| 4 | `reflect.growslice` | 8.16MB |
| 5 | `runtime.mallocgc` | 7.51MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 7 | `segmentio/kafka-go.makePartitions` | 5.01MB |
| 8 | `carta/value.(*Cell).Scan` | 2.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `bytes.growSlice` | 2.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 20.62GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 8.16GB |
| 3 | `segmentio/kafka-go.makePartitions` | 4.29GB |
| 4 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.79GB |
| 5 | `database/sql.convertAssignRows` | 2.46GB |
| 6 | `reflect.unsafe_NewArray` | 2.22GB |
| 7 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 2.05GB |
| 8 | `fmt.Sprintf` | 1.91GB |
| 9 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 1.69GB |
| 10 | `reflect.MakeSlice` | 1.19GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 221.04MB | 217.49MB | 144.50MB | 0B |
| `evaluation.mergeMetadata` | 111.53MB | 109.53MB | 73.39MB | 0B |
| `local.(*Client).EvaluateV2` | 331.65MB | 327.60MB | 214.23MB | 0B |
| `local.topologicalSort` | 47.54MB | 47.04MB | 30.91MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 335.27MB | 330.18MB | 206.85MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 29.10MB | 29.10MB | 25.53MB | 0B |
| `localEvaluation.getMapOfValue` | 335.27MB | 330.18MB | 206.85MB | 0B |
| `utils.ParseFeatureFlag` | 336.27MB | 331.18MB | 207.39MB | 0B |

**Total FF alloc (current snapshot):** 1.71GB  |  **24h avg:** 1.08GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 99.07MB | 29/1310 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 81.93MB | 46/1310 | `████████████░░░ 82%` |
| 3 | `database/sql.convertAssignRows` | 41.93MB | 58/1310 | `██████░░░░░░░░░ 42%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 961/1310 | `█████░░░░░░░░░░ 36%` |
| 5 | `runtime.mallocgc` | 18.4MB | 961/1310 | `██░░░░░░░░░░░░░ 18%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1310 | `██░░░░░░░░░░░░░ 18%` |
| 7 | `bytes.growSlice` | 14.51MB | 733/1310 | `██░░░░░░░░░░░░░ 14%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1310 | `█░░░░░░░░░░░░░░ 12%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1310 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1310 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1310 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1310 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1310 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1310 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1310 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 35.29GB | 933/1310 | `████░░░░░░░░░░░ 28%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1310 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 15.7GB | 856/1310 | `█░░░░░░░░░░░░░░ 12%` |
| 9 | `fmt.Sprintf` | 9.8GB | 541/1310 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.77GB | 175/1310 | `█░░░░░░░░░░░░░░ 7%` |

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
