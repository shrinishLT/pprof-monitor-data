# Overview: prod
*Last updated: 2026-05-19 08:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T08:30 (178 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,211 | avg: 15,327 | max: 84,644 | trend: decreasing (-8.92/hr))
```
▂▁▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▂▃▆▁▁▁▂▆▁▁▁▂▁▁▄▃▁▁▂▄▁▁▂▂▄▅▄█▁▁▂▁▂▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 145.6MB | avg: 227.3MB | max: 1896.6MB | trend: stable (-0.01MB/hr))
```
▃▂▂▁▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▄▃▅▃▂▃▃▂▃▄▃▃▂▃▄▃▃▂▄▄▄▄█▂▃▃▂▃▃▃▂▃▂▂▄▁▁▁▁▁▁▂▄▁▁▁▂▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,211 | 14,198 | +13 | 15,327 | 84,644 | decreasing (-8.92/hr) |
| Heap InUse | 145.6MB | 192.8MB | -47.2MB | 227.3MB | 1896.6MB | stable (-0.01MB/hr) |
| Heap Sys | 2898.3MB | 2898.1MB | +0.2MB | 4508.3MB | 6579.6MB | |
| Heap Objects | 685,350 | 1,111,121 | -425771 | 970,688 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 18 | 14,552 | 200.4MB | 404.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 10.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.5MB |
| 5 | `experiment/local.(*Client).EvaluateV2` | 4.76MB |
| 6 | `internal/evaluation.mergeMetadata` | 3.5MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.51MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 1.53MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 78.73GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 47.68GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 47.3GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 47.06GB |
| 5 | `experiment/local.topologicalSort` | 31.4GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 24.63GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 21.55GB |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 14.91GB |
| 9 | `reflect.growslice` | 12.26GB |
| 10 | `jackskj/carta.getUniqueId` | 9.46GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 78.87MB | 5/178 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 47.37MB | 9/178 | `█████████░░░░░░ 60%` |
| 3 | `database/sql.convertAssignRows` | 38.7MB | 10/178 | `███████░░░░░░░░ 49%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 176/178 | `██████░░░░░░░░░ 46%` |
| 5 | `runtime.mallocgc` | 26.69MB | 176/178 | `█████░░░░░░░░░░ 33%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/178 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/178 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `bytes.growSlice` | 11.74MB | 103/178 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.42MB | 13/178 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.72MB | 6/178 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 122.12GB | 167/178 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.85GB | 173/178 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.73GB | 173/178 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 70.33GB | 171/178 | `████████░░░░░░░ 57%` |
| 5 | `experiment/local.topologicalSort` | 51.79GB | 155/178 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 49.92GB | 123/178 | `██████░░░░░░░░░ 40%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 34.9GB | 101/178 | `████░░░░░░░░░░░ 28%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 30.81GB | 169/178 | `███░░░░░░░░░░░░ 25%` |
| 9 | `fmt.Sprintf` | 28.34GB | 44/178 | `███░░░░░░░░░░░░ 23%` |
| 10 | `fmt.(*buffer).writeString` | 24.13GB | 16/178 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.0x avg)
