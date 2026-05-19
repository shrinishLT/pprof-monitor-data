# Overview: prod
*Last updated: 2026-05-19 06:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T06:00 (173 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,729 | avg: 15,355 | max: 84,644 | trend: decreasing (-7.67/hr))
```
▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▁▃▃▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 366.0MB | avg: 229.3MB | max: 1896.6MB | trend: stable (+0.13MB/hr))
```
▁▁▄▃▂▃▂▂▁▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▄▃▅▃▂▃▃▂▃▄▃▃▂▃▄▃▃▂▄▄▄▄█▂▃▃▂▃▃▃▂▃▂▂▄▁▁▁▁▁▁▂▄
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,729 | 15,314 | -585 | 15,355 | 84,644 | decreasing (-7.67/hr) |
| Heap InUse | 366.0MB | 187.8MB | +178.2MB | 229.3MB | 1896.6MB | stable (+0.13MB/hr) |
| Heap Sys | 2897.3MB | 2895.9MB | +1.4MB | 4554.9MB | 6579.6MB | |
| Heap Objects | 1,423,581 | 671,193 | +752388 | 977,358 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 13 | 14,633 | 216.6MB | 404.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 80.05MB |
| 2 | `database/sql.convertAssignRows` | 55.5MB |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 4 | `runtime.mallocgc` | 10.01MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.01MB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 7.66MB |
| 8 | `bytes.growSlice` | 6.53MB |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 6.5MB |
| 10 | `internal/strconv.FormatInt` | 3.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 68.24GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 41.34GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 40.98GB |
| 4 | `experiment/local.topologicalSort` | 27.22GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 22.64GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 21.45GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 12.95GB |
| 8 | `reflect.growslice` | 11.71GB |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 10.4GB |
| 10 | `jackskj/carta.getUniqueId` | 8.8GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 78.87MB | 5/173 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 47.37MB | 9/173 | `█████████░░░░░░ 60%` |
| 3 | `database/sql.convertAssignRows` | 38.7MB | 10/173 | `███████░░░░░░░░ 49%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 171/173 | `██████░░░░░░░░░ 46%` |
| 5 | `runtime.mallocgc` | 27.17MB | 171/173 | `█████░░░░░░░░░░ 34%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/173 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/173 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `internal/evaluation.mergeMetadata` | 12.09MB | 12/173 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `bytes.growSlice` | 11.79MB | 102/173 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.72MB | 6/173 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 123.57GB | 162/173 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 72.65GB | 168/173 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 72.52GB | 168/173 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 71.05GB | 166/173 | `████████░░░░░░░ 57%` |
| 5 | `experiment/local.topologicalSort` | 52.52GB | 150/173 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 51.05GB | 118/173 | `██████░░░░░░░░░ 41%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 35.97GB | 96/173 | `████░░░░░░░░░░░ 29%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 31.1GB | 164/173 | `███░░░░░░░░░░░░ 25%` |
| 9 | `fmt.Sprintf` | 28.34GB | 44/173 | `███░░░░░░░░░░░░ 22%` |
| 10 | `fmt.(*buffer).writeString` | 24.13GB | 16/173 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
