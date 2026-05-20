# Overview: prod
*Last updated: 2026-05-20 07:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T07:00 (223 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,137 | avg: 15,397 | max: 84,644 | trend: decreasing (-1.91/hr))
```
▅▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▂▃▄▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▄▁▁▁▁▁▁▁▁▁▂▁▁▂▁▃▁▁▁▁▁▁▂▁▁▁▁▇▁▁▁▁▁▂▁▁▁▁
```

**Heap InUse** (current: 112.9MB | avg: 229.0MB | max: 1896.6MB | trend: stable (+0.04MB/hr))
```
▃▂▂▃▂▄▂▂▃▂▂▃▄▃▂▁▃▄▃▂▂▃▃▄▃▆▂▃▂▂▂▂▂▂▂▂▂▄▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▆▂▁▂▁▄▁▁▂▂▁▁▁▃▄▃▁▁▂▂▃▁▂▁▁▁▁▃▁▂▁▁█▁▂▁▁▁▂▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 1%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,137 | 15,098 | -961 | 15,397 | 84,644 | decreasing (-1.91/hr) |
| Heap InUse | 112.9MB | 157.3MB | -44.4MB | 229.0MB | 1896.6MB | stable (+0.04MB/hr) |
| Heap Sys | 4314.5MB | 4313.8MB | +0.7MB | 4483.4MB | 6579.6MB | |
| Heap Objects | 334,273 | 376,014 | -41741 | 971,319 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 15 | 15,458 | 209.2MB | 786.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `dotlapse-event-service/workerpool.NewWorker` | 4.0MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `reflect.unsafe_NewArray` | 1.5MB |
| 10 | `reflect.mapassign_faststr0` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 73.64GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 44.1GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 44.09GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 42.72GB |
| 5 | `experiment/local.topologicalSort` | 29.39GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 23.18GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 19.66GB |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 13.95GB |
| 9 | `reflect.growslice` | 11.19GB |
| 10 | `jackskj/carta.getUniqueId` | 8.56GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/223 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/223 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 221/223 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 34.92MB | 13/223 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 24.93MB | 221/223 | `██████░░░░░░░░░ 40%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/223 | `████░░░░░░░░░░░ 29%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/223 | `███░░░░░░░░░░░░ 21%` |
| 8 | `bytes.growSlice` | 12.03MB | 138/223 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.85MB | 26/223 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 218/223 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.08GB | 212/223 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 73.87GB | 218/223 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 73.8GB | 218/223 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 64.61GB | 213/223 | `███████░░░░░░░░ 51%` |
| 5 | `experiment/local.topologicalSort` | 52.33GB | 200/223 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 47.93GB | 168/223 | `█████░░░░░░░░░░ 38%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 32.32GB | 145/223 | `███░░░░░░░░░░░░ 25%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 29.5GB | 202/223 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/223 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `fmt.Sprintf` | 22.97GB | 78/223 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
