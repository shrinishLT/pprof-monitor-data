# Overview: prod
*Last updated: 2026-05-20 18:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T18:02 (245 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,220 | avg: 15,509 | max: 84,644 | trend: INCREASING (+3.38/hr))
```
▂▂▂▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▁▁▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▁▁▄▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▄█▁▁▁▁▁▁▁▁▁▁▂▁▃▁▁
```

**Heap InUse** (current: 128.9MB | avg: 230.8MB | max: 1896.6MB | trend: stable (+0.10MB/hr))
```
▃▃▂▅▂▂▂▁▂▂▂▁▂▂▁▃▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▂▂▁▁▁▂▃▂▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂█▂▂▁▁▁▁▁▁▁▁▂▁▃▂▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 1%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,220 | 15,028 | -808 | 15,509 | 84,644 | INCREASING (+3.38/hr) |
| Heap InUse | 128.9MB | 234.5MB | -105.6MB | 230.8MB | 1896.6MB | stable (+0.10MB/hr) |
| Heap Sys | 4972.8MB | 4972.4MB | +0.4MB | 4329.2MB | 6579.6MB | |
| Heap Objects | 363,767 | 1,035,264 | -671497 | 981,123 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 37 | 16,158 | 232.9MB | 958.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 15.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 4.5MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `dotlapse-event-service/workerpool.NewWorker` | 3.5MB |
| 7 | `bytes.growSlice` | 3.15MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `reflect.growslice` | 2.0MB |
| 10 | `reflect.unsafe_NewArray` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 89.71GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 54.18GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 53.91GB |
| 4 | `experiment/local.topologicalSort` | 35.8GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 28.19GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 17.1GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 15.16GB |
| 8 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 10.59GB |
| 9 | `fmt.Sprintf` | 10.07GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 6.81GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/245 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/245 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 243/245 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 32.79MB | 14/245 | `███████░░░░░░░░ 52%` |
| 5 | `runtime.mallocgc` | 24.17MB | 243/245 | `█████░░░░░░░░░░ 38%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 13.01MB | 4/245 | `███░░░░░░░░░░░░ 20%` |
| 7 | `bytes.growSlice` | 12.68MB | 158/245 | `███░░░░░░░░░░░░ 20%` |
| 8 | `net/http.(*Transport).dialConn` | 12.62MB | 4/245 | `███░░░░░░░░░░░░ 20%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.03MB | 31/245 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/245 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 119.67GB | 234/245 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 70.82GB | 240/245 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 70.75GB | 240/245 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 61.29GB | 232/245 | `███████░░░░░░░░ 51%` |
| 5 | `experiment/local.topologicalSort` | 49.81GB | 222/245 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 44.84GB | 190/245 | `█████░░░░░░░░░░ 37%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 29.75GB | 167/245 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 28.15GB | 219/245 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/245 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.Sprintf` | 20.13GB | 92/245 | `██░░░░░░░░░░░░░ 16%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.2x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.2x avg)
