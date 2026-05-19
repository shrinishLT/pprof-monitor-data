# Overview: prod
*Last updated: 2026-05-20 03:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T03:30 (216 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,160 | avg: 15,406 | max: 84,644 | trend: decreasing (-1.61/hr))
```
▁▁▁▁▁▂▂▅▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▂▃▄▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▄▁▁▁▁▁▁▁▁▁▂▁▁▂▁▃▁▁▁▁▁▁▂▁▁▁▁▇▁▁▁
```

**Heap InUse** (current: 132.6MB | avg: 231.1MB | max: 1896.6MB | trend: stable (+0.16MB/hr))
```
▁▁▁▁▁▂▂▃▂▂▃▂▄▂▂▂▂▂▃▄▂▂▁▂▄▂▂▂▃▃▄▃▆▂▃▂▁▂▂▂▁▂▂▁▃▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▆▂▁▂▁▄▁▁▂▂▁▁▁▂▄▃▁▁▂▂▂▁▂▁▁▁▁▃▁▁▁▁█▁▂▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,160 | 14,336 | -176 | 15,406 | 84,644 | decreasing (-1.61/hr) |
| Heap InUse | 132.6MB | 230.8MB | -98.2MB | 231.1MB | 1896.6MB | stable (+0.16MB/hr) |
| Heap Sys | 640.9MB | 4898.9MB | -4258.0MB | 4513.2MB | 6579.6MB | |
| Heap Objects | 660,025 | 1,208,848 | -548823 | 984,717 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 8 | 15,740 | 246.5MB | 786.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 9.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `dotlapse-event-service/workerpool.NewWorker` | 4.0MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `aws/endpoints.init` | 2.0MB |
| 8 | `reflect.mapassign_faststr0` | 2.0MB |
| 9 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.0MB |
| 10 | `segmentio/kafka-go.makePartitions` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 1.17GB |
| 2 | `internal/evaluation.mergeMetadata` | 764.68MB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 558.11MB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 457.19MB |
| 5 | `experiment/local.(*Client).EvaluateV2` | 440.44MB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 400.66MB |
| 7 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 325.54MB |
| 8 | `experiment/local.topologicalSort` | 310.22MB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 225.76MB |
| 10 | `segmentio/kafka-go.makePartitions` | 222.64MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/216 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/216 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 214/216 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 34.92MB | 13/216 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 25.36MB | 214/216 | `██████░░░░░░░░░ 40%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/216 | `████░░░░░░░░░░░ 29%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/216 | `███░░░░░░░░░░░░ 21%` |
| 8 | `bytes.growSlice` | 12.11MB | 134/216 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `internal/evaluation.mergeMetadata` | 12.02MB | 24/216 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 211/216 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 127.89GB | 205/216 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 75.47GB | 211/216 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 75.4GB | 211/216 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 66.22GB | 206/216 | `███████░░░░░░░░ 51%` |
| 5 | `experiment/local.topologicalSort` | 53.61GB | 193/216 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 49.42GB | 161/216 | `█████░░░░░░░░░░ 38%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 33.54GB | 138/216 | `███░░░░░░░░░░░░ 26%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 30.03GB | 197/216 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/216 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprintf` | 23.83GB | 75/216 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
