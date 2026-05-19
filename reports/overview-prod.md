# Overview: prod
*Last updated: 2026-05-19 08:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T08:01 (177 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,198 | avg: 15,333 | max: 84,644 | trend: decreasing (-8.64/hr))
```
▁▂▁▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▂▃▆▁▁▁▂▆▁▁▁▂▁▁▄▃▁▁▂▄▁▁▂▂▄▅▄█▁▁▂▁▂▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 192.8MB | avg: 227.8MB | max: 1896.6MB | trend: stable (+0.02MB/hr))
```
▂▃▂▂▁▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▄▃▅▃▂▃▃▂▃▄▃▃▂▃▄▃▃▂▄▄▄▄█▂▃▃▂▃▃▃▂▃▂▂▄▁▁▁▁▁▁▂▄▁▁▁▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,198 | 14,236 | -38 | 15,333 | 84,644 | decreasing (-8.64/hr) |
| Heap InUse | 192.8MB | 127.2MB | +65.6MB | 227.8MB | 1896.6MB | stable (+0.02MB/hr) |
| Heap Sys | 2898.1MB | 2898.1MB | +0.0MB | 4517.4MB | 6579.6MB | |
| Heap Objects | 1,111,121 | 419,180 | +691941 | 972,300 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 17 | 14,572 | 203.6MB | 404.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 10.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.5MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.01MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `reflect.unsafe_NewArray` | 2.51MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `reflect.mapassign_faststr0` | 2.0MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 76.72GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 47.06GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 46.46GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 46.07GB |
| 5 | `experiment/local.topologicalSort` | 30.62GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 23.99GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 21.55GB |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 14.55GB |
| 9 | `reflect.growslice` | 12.11GB |
| 10 | `jackskj/carta.getUniqueId` | 9.3GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 78.87MB | 5/177 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 47.37MB | 9/177 | `█████████░░░░░░ 60%` |
| 3 | `database/sql.convertAssignRows` | 38.7MB | 10/177 | `███████░░░░░░░░ 49%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 175/177 | `██████░░░░░░░░░ 46%` |
| 5 | `runtime.mallocgc` | 26.78MB | 175/177 | `█████░░░░░░░░░░ 33%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/177 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/177 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `internal/evaluation.mergeMetadata` | 12.09MB | 12/177 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `bytes.growSlice` | 11.74MB | 103/177 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.72MB | 6/177 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 122.38GB | 166/177 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 72.0GB | 172/177 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.87GB | 172/177 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 70.47GB | 170/177 | `████████░░░░░░░ 57%` |
| 5 | `experiment/local.topologicalSort` | 51.92GB | 154/177 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 50.13GB | 122/177 | `██████░░░░░░░░░ 40%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 35.1GB | 100/177 | `████░░░░░░░░░░░ 28%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 30.87GB | 168/177 | `███░░░░░░░░░░░░ 25%` |
| 9 | `fmt.Sprintf` | 28.34GB | 44/177 | `███░░░░░░░░░░░░ 23%` |
| 10 | `fmt.(*buffer).writeString` | 24.13GB | 16/177 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
