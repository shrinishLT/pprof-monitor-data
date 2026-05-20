# Overview: prod
*Last updated: 2026-05-21 02:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T02:00 (261 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,212 | avg: 15,688 | max: 84,644 | trend: INCREASING (+10.45/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 227.4MB | avg: 235.7MB | max: 1896.6MB | trend: stable (+0.30MB/hr))
```
▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▂▂▁▁▁▂▃▂▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▇▂▂▁▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▂▁▁▂▂▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,212 | 15,187 | +25 | 15,688 | 84,644 | INCREASING (+10.45/hr) |
| Heap InUse | 227.4MB | 271.6MB | -44.2MB | 235.7MB | 1896.6MB | stable (+0.30MB/hr) |
| Heap Sys | 4861.8MB | 4852.3MB | +9.5MB | 4313.8MB | 6579.6MB | |
| Heap Objects | 694,623 | 1,089,954 | -395331 | 992,723 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 5 | 15,029 | 247.0MB | 297.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 37.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `internal/evaluation.mergeMetadata` | 12.5MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 8.93MB |
| 7 | `bytes.growSlice` | 8.54MB |
| 8 | `experiment/local.topologicalSort` | 7.59MB |
| 9 | `internal/evaluation.(*Engine).Evaluate` | 4.66MB |
| 10 | `bufio.NewReaderSize` | 3.04MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 123.93GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 74.5GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 74.46GB |
| 4 | `experiment/local.topologicalSort` | 49.4GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 39.25GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 23.64GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 15.66GB |
| 8 | `fmt.Sprintf` | 11.88GB |
| 9 | `reflect.growslice` | 9.85GB |
| 10 | `jackskj/carta.getUniqueId` | 9.17GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/261 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/261 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 259/261 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 32.79MB | 14/261 | `███████░░░░░░░░ 52%` |
| 5 | `runtime.mallocgc` | 24.38MB | 259/261 | `█████░░░░░░░░░░ 39%` |
| 6 | `bytes.growSlice` | 13.81MB | 174/261 | `███░░░░░░░░░░░░ 22%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/261 | `███░░░░░░░░░░░░ 22%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 13.61MB | 5/261 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/261 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.63MB | 36/261 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 117.51GB | 250/261 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 69.62GB | 256/261 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 69.56GB | 256/261 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 59.57GB | 241/261 | `███████░░░░░░░░ 50%` |
| 5 | `experiment/local.topologicalSort` | 48.76GB | 238/261 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.45GB | 206/261 | `█████░░░░░░░░░░ 36%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.58GB | 183/261 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 27.85GB | 222/261 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/261 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.Sprintf` | 18.67GB | 106/261 | `██░░░░░░░░░░░░░ 15%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.3x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
