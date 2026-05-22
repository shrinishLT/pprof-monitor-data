# Overview: prod
*Last updated: 2026-05-23 02:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-23T02:00 (379 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,011 | avg: 15,838 | max: 84,644 | trend: INCREASING (+6.96/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▂▁▁▁▁
```

**Heap InUse** (current: 241.8MB | avg: 241.0MB | max: 1896.6MB | trend: stable (+0.19MB/hr))
```
▃▂▃▁▂▁▁▂▁▁▂▃▃▁▁▃▃▁▁▁▂▂▁▁▂▂▂▃▃▃▂▁▂▂▂▂▂▁▂▂▂▁▂▂▂▂▃▂▁▁▁▁▁▁▁▃▁▁▁▁▁▁▂▁█▁▁▁▁▁▁▁▁▂▁▂▁▂▁▁▂▁▁▁▁▁▁▂▂▁▂▂▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,011 | 15,530 | +481 | 15,838 | 84,644 | INCREASING (+6.96/hr) |
| Heap InUse | 241.8MB | 206.7MB | +35.1MB | 241.0MB | 1896.6MB | stable (+0.19MB/hr) |
| Heap Sys | 784.1MB | 818.8MB | -34.7MB | 4245.7MB | 6579.6MB | |
| Heap Objects | 1,071,242 | 651,331 | +419911 | 1,001,893 | 8,100,802 | |

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
| 2026-05-23 | 5 | 16,016 | 236.5MB | 349.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `internal/evaluation.mergeMetadata` | 24.51MB |
| 3 | `experiment/local.topologicalSort` | 14.19MB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 12.62MB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 10.14MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 9.5MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `bytes.growSlice` | 7.04MB |
| 9 | `runtime.mallocgc` | 7.01MB |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 6.67MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 15.02GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 8.96GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 8.95GB |
| 4 | `experiment/local.topologicalSort` | 6.0GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 4.69GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 2.8GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 1.93GB |
| 8 | `fmt.Sprintf` | 1.27GB |
| 9 | `reflect.growslice` | 1.19GB |
| 10 | `jackskj/carta.getUniqueId` | 1.11GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 57.13MB | 9/379 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 43.74MB | 15/379 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 377/379 | `█████████░░░░░░ 64%` |
| 4 | `database/sql.convertAssignRows` | 29.0MB | 19/379 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 24.66MB | 377/379 | `██████░░░░░░░░░ 43%` |
| 6 | `bytes.growSlice` | 14.19MB | 272/379 | `███░░░░░░░░░░░░ 24%` |
| 7 | `net/http.(*Transport).dialConn` | 12.08MB | 6/379 | `███░░░░░░░░░░░░ 21%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/379 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/379 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.41MB | 61/379 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 129.04GB | 368/379 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 76.68GB | 374/379 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 76.66GB | 374/379 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 52.81GB | 356/379 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 51.56GB | 355/379 | `█████░░░░░░░░░░ 39%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 45.15GB | 324/379 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.93GB | 300/379 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 24.99GB | 313/379 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/379 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprintf` | 18.66GB | 195/379 | `██░░░░░░░░░░░░░ 14%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.3x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
