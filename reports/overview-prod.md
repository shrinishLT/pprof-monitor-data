# Overview: prod
*Last updated: 2026-05-20 11:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T11:01 (231 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,354 | avg: 15,498 | max: 84,644 | trend: INCREASING (+3.46/hr))
```
▁▁▁▁▂▁▁▁▁▂▁▁▁▁▂▂▂▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▁▁▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▁▁▄▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▄█▁
```

**Heap InUse** (current: 251.6MB | avg: 231.6MB | max: 1896.6MB | trend: stable (+0.16MB/hr))
```
▂▂▂▂▃▂▂▁▂▃▂▂▂▃▃▃▂▅▂▂▂▁▂▂▂▁▂▂▁▃▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▂▂▁▁▁▂▃▂▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂█▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,354 | 33,655 | -19301 | 15,498 | 84,644 | INCREASING (+3.46/hr) |
| Heap InUse | 251.6MB | 958.1MB | -706.5MB | 231.6MB | 1896.6MB | stable (+0.16MB/hr) |
| Heap Sys | 4276.5MB | 4210.4MB | +66.1MB | 4476.8MB | 6579.6MB | |
| Heap Objects | 1,079,348 | 4,373,255 | -3293907 | 982,132 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 23 | 16,451 | 241.5MB | 958.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 53.12MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `dotlapse-event-service/workerpool.NewWorker` | 4.0MB |
| 6 | `compress/flate.NewWriter` | 3.53MB |
| 7 | `internal/evaluation.mergeMetadata` | 3.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `experiment/local.topologicalSort` | 2.02MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 186.96GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 112.1GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 112.01GB |
| 4 | `experiment/local.topologicalSort` | 74.13GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 58.68GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 47.52GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 35.51GB |
| 8 | `reflect.growslice` | 24.81GB |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 21.93GB |
| 10 | `jackskj/carta.getUniqueId` | 21.28GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/231 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/231 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 229/231 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 34.92MB | 13/231 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 24.84MB | 229/231 | `█████░░░░░░░░░░ 39%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 16.18MB | 3/231 | `███░░░░░░░░░░░░ 26%` |
| 7 | `bytes.growSlice` | 12.89MB | 144/231 | `███░░░░░░░░░░░░ 20%` |
| 8 | `net/http.(*Transport).dialConn` | 12.62MB | 4/231 | `███░░░░░░░░░░░░ 20%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.23MB | 29/231 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 225/231 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 124.69GB | 220/231 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 73.68GB | 226/231 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 73.61GB | 226/231 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 63.92GB | 221/231 | `███████░░░░░░░░ 51%` |
| 5 | `experiment/local.topologicalSort` | 52.07GB | 208/231 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 47.38GB | 176/231 | `█████░░░░░░░░░░ 37%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 31.76GB | 153/231 | `███░░░░░░░░░░░░ 25%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 29.18GB | 210/231 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/231 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `fmt.Sprintf` | 22.97GB | 78/231 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.2x avg)
