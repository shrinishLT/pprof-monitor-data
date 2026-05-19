# Overview: prod
*Last updated: 2026-05-19 07:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T07:30 (176 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,236 | avg: 15,339 | max: 84,644 | trend: decreasing (-8.35/hr))
```
▁▁▂▁▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▂▃▆▁▁▁▂▆▁▁▁▂▁▁▄▃▁▁▂▄▁▁▂▂▄▅▄█▁▁▂▁▂▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 127.2MB | avg: 228.0MB | max: 1896.6MB | trend: stable (+0.03MB/hr))
```
▃▂▃▂▂▁▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▄▃▅▃▂▃▃▂▃▄▃▃▂▃▄▃▃▂▄▄▄▄█▂▃▃▂▃▃▃▂▃▂▂▄▁▁▁▁▁▁▂▄▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 1%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,236 | 14,084 | +152 | 15,339 | 84,644 | decreasing (-8.35/hr) |
| Heap InUse | 127.2MB | 160.3MB | -33.1MB | 228.0MB | 1896.6MB | stable (+0.03MB/hr) |
| Heap Sys | 2898.1MB | 2898.3MB | -0.2MB | 4526.6MB | 6579.6MB | |
| Heap Objects | 419,180 | 1,036,452 | -617272 | 971,511 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 16 | 14,595 | 204.3MB | 404.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 10.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.5MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 8 | `segmentio/kafka-go.makePartitions` | 1.5MB |
| 9 | `aws/endpoints.init` | 1.5MB |
| 10 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 74.86GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 47.03GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 45.39GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 44.99GB |
| 5 | `experiment/local.topologicalSort` | 29.89GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 23.41GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 21.53GB |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 14.22GB |
| 9 | `reflect.growslice` | 11.92GB |
| 10 | `jackskj/carta.getUniqueId` | 9.04GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 78.87MB | 5/176 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 47.37MB | 9/176 | `█████████░░░░░░ 60%` |
| 3 | `database/sql.convertAssignRows` | 38.7MB | 10/176 | `███████░░░░░░░░ 49%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 174/176 | `██████░░░░░░░░░ 46%` |
| 5 | `runtime.mallocgc` | 26.88MB | 174/176 | `█████░░░░░░░░░░ 34%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/176 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/176 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `internal/evaluation.mergeMetadata` | 12.09MB | 12/176 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `bytes.growSlice` | 11.74MB | 103/176 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.72MB | 6/176 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 122.66GB | 165/176 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 72.15GB | 171/176 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 72.02GB | 171/176 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 70.61GB | 169/176 | `████████░░░░░░░ 57%` |
| 5 | `experiment/local.topologicalSort` | 52.06GB | 153/176 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 50.35GB | 121/176 | `██████░░░░░░░░░ 41%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 35.3GB | 99/176 | `████░░░░░░░░░░░ 28%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 30.92GB | 167/176 | `███░░░░░░░░░░░░ 25%` |
| 9 | `fmt.Sprintf` | 28.34GB | 44/176 | `███░░░░░░░░░░░░ 23%` |
| 10 | `fmt.(*buffer).writeString` | 24.13GB | 16/176 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
