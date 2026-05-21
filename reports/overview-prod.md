# Overview: prod
*Last updated: 2026-05-21 12:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T12:02 (288 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,715 | avg: 15,709 | max: 84,644 | trend: INCREASING (+8.59/hr))
```
▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁
```

**Heap InUse** (current: 284.5MB | avg: 236.6MB | max: 1896.6MB | trend: stable (+0.25MB/hr))
```
▁▂▃▂▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▇▂▂▁▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▂▁▁▂▂▁▄▂▁▁▂▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▃▁▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,715 | 15,336 | -621 | 15,709 | 84,644 | INCREASING (+8.59/hr) |
| Heap InUse | 284.5MB | 234.4MB | +50.1MB | 236.6MB | 1896.6MB | stable (+0.25MB/hr) |
| Heap Sys | 4086.2MB | 4086.1MB | +0.1MB | 4207.8MB | 6579.6MB | |
| Heap Objects | 1,435,213 | 914,479 | +520734 | 1,000,157 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 32 | 15,767 | 245.4MB | 501.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 35.36MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `reflect.unsafe_New` | 7.0MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 7.0MB |
| 6 | `bufio.NewWriterSize` | 4.03MB |
| 7 | `jackskj/carta.getUniqueId` | 3.5MB |
| 8 | `carta/value.NewCell` | 3.5MB |
| 9 | `bytes.growSlice` | 3.02MB |
| 10 | `bufio.NewReaderSize` | 2.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 47.3GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 28.45GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 28.33GB |
| 4 | `experiment/local.topologicalSort` | 18.82GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 15.09GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 9.13GB |
| 7 | `reflect.growslice` | 5.65GB |
| 8 | `jackskj/carta.getUniqueId` | 5.36GB |
| 9 | `dotlapse-event-service/project.ApplyPagination` | 4.93GB |
| 10 | `reflect.unsafe_New` | 4.61GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.01MB | 8/288 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.22MB | 14/288 | `███████████░░░░ 79%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 286/288 | `█████████░░░░░░ 63%` |
| 4 | `database/sql.convertAssignRows` | 32.63MB | 16/288 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 23.82MB | 286/288 | `██████░░░░░░░░░ 41%` |
| 6 | `bytes.growSlice` | 13.81MB | 197/288 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/288 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 13.61MB | 5/288 | `███░░░░░░░░░░░░ 23%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.99MB | 43/288 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/288 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 114.67GB | 277/288 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 68.04GB | 283/288 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 68.02GB | 283/288 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 56.5GB | 264/288 | `███████░░░░░░░░ 49%` |
| 5 | `experiment/local.topologicalSort` | 47.41GB | 265/288 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 41.67GB | 233/288 | `█████░░░░░░░░░░ 36%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 27.21GB | 209/288 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 27.05GB | 237/288 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/288 | `███░░░░░░░░░░░░ 21%` |
| 10 | `fmt.Sprintf` | 17.98GB | 114/288 | `██░░░░░░░░░░░░░ 15%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
