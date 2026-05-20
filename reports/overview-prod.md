# Overview: prod
*Last updated: 2026-05-20 05:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T05:30 (220 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,441 | avg: 15,408 | max: 84,644 | trend: decreasing (-1.42/hr))
```
▁▂▂▅▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▂▃▄▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▄▁▁▁▁▁▁▁▁▁▂▁▁▂▁▃▁▁▁▁▁▁▂▁▁▁▁▇▁▁▁▁▁▂▁
```

**Heap InUse** (current: 180.1MB | avg: 230.2MB | max: 1896.6MB | trend: stable (+0.10MB/hr))
```
▁▂▂▃▂▂▃▂▄▂▂▂▂▂▃▄▂▂▁▂▄▂▂▂▃▃▄▃▆▂▃▂▁▂▂▂▁▂▂▁▃▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▆▂▁▂▁▄▁▁▂▂▁▁▁▂▄▃▁▁▂▂▂▁▂▁▁▁▁▃▁▁▁▁█▁▂▁▁▁▂▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,441 | 17,268 | -1827 | 15,408 | 84,644 | decreasing (-1.42/hr) |
| Heap InUse | 180.1MB | 222.1MB | -42.0MB | 230.2MB | 1896.6MB | stable (+0.10MB/hr) |
| Heap Sys | 4311.8MB | 3530.3MB | +781.5MB | 4485.7MB | 6579.6MB | |
| Heap Objects | 622,641 | 526,671 | +95970 | 978,630 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 12 | 15,662 | 225.2MB | 786.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `internal/evaluation.mergeMetadata` | 13.5MB |
| 3 | `runtime.mallocgc` | 12.01MB |
| 4 | `experiment/local.topologicalSort` | 10.67MB |
| 5 | `experiment/local.(*Client).EvaluateV2` | 10.43MB |
| 6 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 8 | `internal/evaluation.(*Engine).Evaluate` | 8.93MB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 5.61MB |
| 10 | `bufio.NewReaderSize` | 5.02MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 52.66GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 31.5GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 31.44GB |
| 4 | `experiment/local.topologicalSort` | 21.0GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.71GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 11.09GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 9.97GB |
| 8 | `reflect.growslice` | 9.51GB |
| 9 | `jackskj/carta.getUniqueId` | 7.24GB |
| 10 | `reflect.unsafe_New` | 6.6GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/220 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/220 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 218/220 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 34.92MB | 13/220 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 25.11MB | 218/220 | `██████░░░░░░░░░ 40%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/220 | `████░░░░░░░░░░░ 29%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/220 | `███░░░░░░░░░░░░ 21%` |
| 8 | `bytes.growSlice` | 12.13MB | 136/220 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `internal/evaluation.mergeMetadata` | 12.08MB | 25/220 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 215/220 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.86GB | 209/220 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 74.31GB | 215/220 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 74.24GB | 215/220 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 65.07GB | 210/220 | `███████░░░░░░░░ 51%` |
| 5 | `experiment/local.topologicalSort` | 52.7GB | 197/220 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 48.4GB | 165/220 | `█████░░░░░░░░░░ 38%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 32.72GB | 142/220 | `███░░░░░░░░░░░░ 25%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 29.61GB | 200/220 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/220 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `fmt.Sprintf` | 22.97GB | 78/220 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
