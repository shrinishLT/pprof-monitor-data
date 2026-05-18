# Overview: prod
*Last updated: 2026-05-18 23:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T23:30 (160 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,719 | avg: 15,414 | max: 84,644 | trend: decreasing (-4.96/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▁▃▃▃▅▁▁▂▁▁▁▁
```

**Heap InUse** (current: 286.9MB | avg: 230.4MB | max: 1896.6MB | trend: stable (+0.25MB/hr))
```
▁▁▁▁▁▂▁▂▂▂▁▁▁▁▁▄▃▂▃▂▂▁▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▄▃▅▃▂▃▃▂▃▄▃▃▂▃▄▃▃▂▄▄▄▄█▂▃▃▂▃▃▃
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,719 | 14,904 | -185 | 15,414 | 84,644 | decreasing (-4.96/hr) |
| Heap InUse | 286.9MB | 287.2MB | -0.3MB | 230.4MB | 1896.6MB | stable (+0.25MB/hr) |
| Heap Sys | 6572.6MB | 6579.6MB | -7.0MB | 4597.1MB | 6579.6MB | |
| Heap Objects | 800,785 | 1,044,062 | -243277 | 985,691 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 285.97MB |
| 2 | `database/sql.convertAssignRows` | 192.01MB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 161.42MB |
| 4 | `runtime.mallocgc` | 55.03MB |
| 5 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 6 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 27.63MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `dotlapse-event-service/project.FilterProjectsByTags` | 8.14MB |
| 9 | `internal/strconv.FormatInt` | 7.5MB |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 521.53GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 315.46GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 314.57GB |
| 4 | `experiment/local.topologicalSort` | 208.4GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 163.61GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 148.31GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 99.28GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 67.8GB |
| 9 | `fmt.Sprintf` | 52.1GB |
| 10 | `segmentio/kafka-go.makePartitions` | 42.95GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 78.57MB | 4/160 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 52.33MB | 8/160 | `█████████░░░░░░ 66%` |
| 3 | `database/sql.convertAssignRows` | 36.83MB | 9/160 | `███████░░░░░░░░ 46%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 158/160 | `██████░░░░░░░░░ 46%` |
| 5 | `runtime.mallocgc` | 27.19MB | 158/160 | `█████░░░░░░░░░░ 34%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/160 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/160 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `bytes.growSlice` | 12.75MB | 90/160 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.55MB | 10/160 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.86MB | 5/160 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 114.7GB | 149/160 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 71.5GB | 153/160 | `█████████░░░░░░ 62%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 67.32GB | 155/160 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 67.2GB | 155/160 | `████████░░░░░░░ 58%` |
| 5 | `experiment/local.topologicalSort` | 48.97GB | 137/160 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 48.61GB | 105/160 | `██████░░░░░░░░░ 42%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 34.48GB | 84/160 | `████░░░░░░░░░░░ 30%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 31.19GB | 151/160 | `████░░░░░░░░░░░ 27%` |
| 9 | `fmt.Sprintf` | 28.41GB | 34/160 | `███░░░░░░░░░░░░ 24%` |
| 10 | `fmt.(*buffer).writeString` | 24.13GB | 16/160 | `███░░░░░░░░░░░░ 21%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
