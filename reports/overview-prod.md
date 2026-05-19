# Overview: prod
*Last updated: 2026-05-19 05:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T05:30 (172 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,314 | avg: 15,359 | max: 84,644 | trend: decreasing (-7.55/hr))
```
▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▁▃▃▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 187.8MB | avg: 228.5MB | max: 1896.6MB | trend: stable (+0.08MB/hr))
```
▁▁▁▄▃▂▃▂▂▁▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▄▃▅▃▂▃▃▂▃▄▃▃▂▃▄▃▃▂▄▄▄▄█▂▃▃▂▃▃▃▂▃▂▂▄▁▁▁▁▁▁▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,314 | 14,338 | +976 | 15,359 | 84,644 | decreasing (-7.55/hr) |
| Heap InUse | 187.8MB | 158.8MB | +29.0MB | 228.5MB | 1896.6MB | stable (+0.08MB/hr) |
| Heap Sys | 2895.9MB | 2407.9MB | +488.0MB | 4564.5MB | 6579.6MB | |
| Heap Objects | 671,193 | 808,133 | -136940 | 974,764 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 12 | 14,625 | 204.2MB | 404.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `internal/evaluation.mergeMetadata` | 11.5MB |
| 3 | `runtime.mallocgc` | 10.01MB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 9.45MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `bytes.growSlice` | 7.04MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 6.5MB |
| 8 | `experiment/local.(*Client).EvaluateV2` | 6.39MB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 4.61MB |
| 10 | `experiment/local.topologicalSort` | 4.56MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 51.94GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 31.45GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 31.24GB |
| 4 | `experiment/local.topologicalSort` | 20.71GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 16.39GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.28GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 9.87GB |
| 8 | `reflect.growslice` | 9.49GB |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 7.5GB |
| 10 | `jackskj/carta.getUniqueId` | 7.1GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 78.57MB | 4/172 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 52.33MB | 8/172 | `█████████░░░░░░ 66%` |
| 3 | `database/sql.convertAssignRows` | 36.83MB | 9/172 | `███████░░░░░░░░ 46%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 170/172 | `██████░░░░░░░░░ 46%` |
| 5 | `runtime.mallocgc` | 27.27MB | 170/172 | `█████░░░░░░░░░░ 34%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/172 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/172 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `internal/evaluation.mergeMetadata` | 12.09MB | 12/172 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `bytes.growSlice` | 11.85MB | 101/172 | `██░░░░░░░░░░░░░ 15%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.86MB | 5/172 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 123.92GB | 161/172 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 72.84GB | 167/172 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 72.7GB | 167/172 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 71.34GB | 165/172 | `████████░░░░░░░ 57%` |
| 5 | `experiment/local.topologicalSort` | 52.69GB | 149/172 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 51.3GB | 117/172 | `██████░░░░░░░░░ 41%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 36.22GB | 95/172 | `████░░░░░░░░░░░ 29%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 31.23GB | 163/172 | `███░░░░░░░░░░░░ 25%` |
| 9 | `fmt.Sprintf` | 28.34GB | 44/172 | `███░░░░░░░░░░░░ 22%` |
| 10 | `fmt.(*buffer).writeString` | 24.13GB | 16/172 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
