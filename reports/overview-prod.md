# Overview: prod
*Last updated: 2026-05-21 05:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T05:00 (267 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,584 | avg: 15,703 | max: 84,644 | trend: INCREASING (+10.39/hr))
```
▁▁▁▁▁▁▁▁▁▃▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 194.3MB | avg: 237.2MB | max: 1896.6MB | trend: stable (+0.34MB/hr))
```
▁▂▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▂▂▁▁▁▂▃▂▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▇▂▂▁▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▂▁▁▂▂▁▄▂▁▁▂▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,584 | 16,086 | -1502 | 15,703 | 84,644 | INCREASING (+10.39/hr) |
| Heap InUse | 194.3MB | 342.1MB | -147.8MB | 237.2MB | 1896.6MB | stable (+0.34MB/hr) |
| Heap Sys | 3992.3MB | 3978.7MB | +13.6MB | 4290.5MB | 6579.6MB | |
| Heap Objects | 773,754 | 1,977,990 | -1204236 | 999,618 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 11 | 15,741 | 277.5MB | 501.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 15.11MB |
| 3 | `internal/evaluation.mergeMetadata` | 13.0MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 8.41MB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 5.82MB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 4.14MB |
| 8 | `experiment/local.topologicalSort` | 4.06MB |
| 9 | `bytes.growSlice` | 4.02MB |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 3.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 137.35GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 82.78GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 82.62GB |
| 4 | `experiment/local.topologicalSort` | 54.73GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.69GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 26.09GB |
| 7 | `fmt.Sprintf` | 11.32GB |
| 8 | `internal/evaluation.coerceString` | 8.92GB |
| 9 | `internal/evaluation.(*Engine).bucket` | 6.75GB |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 6.5GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/267 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 43.44MB | 13/267 | `██████████░░░░░ 69%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 265/267 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 31.87MB | 15/267 | `███████░░░░░░░░ 51%` |
| 5 | `runtime.mallocgc` | 24.33MB | 265/267 | `█████░░░░░░░░░░ 39%` |
| 6 | `bytes.growSlice` | 13.9MB | 180/267 | `███░░░░░░░░░░░░ 22%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/267 | `███░░░░░░░░░░░░ 22%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 13.61MB | 5/267 | `███░░░░░░░░░░░░ 21%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.86MB | 39/267 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/267 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 116.77GB | 256/267 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 69.2GB | 262/267 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 69.15GB | 262/267 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 58.36GB | 247/267 | `███████░░░░░░░░ 49%` |
| 5 | `experiment/local.topologicalSort` | 48.41GB | 244/267 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 42.99GB | 212/267 | `█████░░░░░░░░░░ 36%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.34GB | 188/267 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 27.73GB | 223/267 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/267 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.Sprintf` | 18.25GB | 111/267 | `██░░░░░░░░░░░░░ 15%` |

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
