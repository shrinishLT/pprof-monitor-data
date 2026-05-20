# Overview: prod
*Last updated: 2026-05-20 11:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T11:30 (232 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,204 | avg: 15,497 | max: 84,644 | trend: INCREASING (+3.35/hr))
```
▁▁▁▂▁▁▁▁▂▁▁▁▁▂▂▂▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▁▁▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▁▁▄▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▄█▁▁
```

**Heap InUse** (current: 265.3MB | avg: 231.7MB | max: 1896.6MB | trend: stable (+0.17MB/hr))
```
▂▂▂▃▂▂▁▂▃▂▂▂▃▃▃▂▅▂▂▂▁▂▂▂▁▂▂▁▃▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▂▂▁▁▁▂▃▂▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂█▂▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,204 | 14,354 | +850 | 15,497 | 84,644 | INCREASING (+3.35/hr) |
| Heap InUse | 265.3MB | 251.6MB | +13.7MB | 231.7MB | 1896.6MB | stable (+0.17MB/hr) |
| Heap Sys | 813.3MB | 4276.5MB | -3463.2MB | 4461.0MB | 6579.6MB | |
| Heap Objects | 1,439,904 | 1,079,348 | +360556 | 984,105 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 24 | 16,399 | 242.5MB | 958.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 7.54MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 7.5MB |
| 6 | `internal/evaluation.mergeMetadata` | 6.0MB |
| 7 | `internal/evaluation.(*Engine).Evaluate` | 5.19MB |
| 8 | `experiment/local.(*Client).EvaluateV2` | 4.74MB |
| 9 | `experiment/local.topologicalSort` | 4.57MB |
| 10 | `bufio.NewWriterSize` | 4.53MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 14.32GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 8.62GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 8.61GB |
| 4 | `experiment/local.topologicalSort` | 5.64GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 4.46GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 2.76GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 1.69GB |
| 8 | `fmt.Sprintf` | 1.22GB |
| 9 | `reflect.growslice` | 995.77MB |
| 10 | `internal/evaluation.coerceString` | 956.01MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/232 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/232 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 230/232 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 34.92MB | 13/232 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 24.79MB | 230/232 | `█████░░░░░░░░░░ 39%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 16.18MB | 3/232 | `███░░░░░░░░░░░░ 26%` |
| 7 | `bytes.growSlice` | 12.86MB | 145/232 | `███░░░░░░░░░░░░ 20%` |
| 8 | `net/http.(*Transport).dialConn` | 12.62MB | 4/232 | `███░░░░░░░░░░░░ 20%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.05MB | 30/232 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 226/232 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 124.19GB | 221/232 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 73.39GB | 227/232 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 73.32GB | 227/232 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 63.64GB | 222/232 | `███████░░░░░░░░ 51%` |
| 5 | `experiment/local.topologicalSort` | 51.85GB | 209/232 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 47.14GB | 177/232 | `█████░░░░░░░░░░ 37%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 31.57GB | 154/232 | `███░░░░░░░░░░░░ 25%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 29.18GB | 210/232 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/232 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `fmt.Sprintf` | 22.69GB | 79/232 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.2x avg)
