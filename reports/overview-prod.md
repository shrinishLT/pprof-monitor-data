# Overview: prod
*Last updated: 2026-05-19 07:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T07:00 (175 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,084 | avg: 15,346 | max: 84,644 | trend: decreasing (-8.06/hr))
```
█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▁▃▃▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 160.3MB | avg: 228.6MB | max: 1896.6MB | trend: stable (+0.07MB/hr))
```
▄▃▂▃▂▂▁▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▄▃▅▃▂▃▃▂▃▄▃▃▂▃▄▃▃▂▄▄▄▄█▂▃▃▂▃▃▃▂▃▂▂▄▁▁▁▁▁▁▂▄▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,084 | 14,967 | -883 | 15,346 | 84,644 | decreasing (-8.06/hr) |
| Heap InUse | 160.3MB | 165.0MB | -4.7MB | 228.6MB | 1896.6MB | stable (+0.07MB/hr) |
| Heap Sys | 2898.3MB | 2897.4MB | +0.9MB | 4535.9MB | 6579.6MB | |
| Heap Objects | 1,036,452 | 447,336 | +589116 | 974,667 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 15 | 14,619 | 209.4MB | 404.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 10.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.5MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `reflect.unsafe_NewArray` | 2.01MB |
| 8 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 9 | `segmentio/kafka-go.makePartitions` | 1.5MB |
| 10 | `aws/endpoints.init` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 72.95GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 47.03GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 44.23GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 43.81GB |
| 5 | `experiment/local.topologicalSort` | 29.11GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 22.79GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 21.53GB |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 13.83GB |
| 9 | `reflect.growslice` | 11.75GB |
| 10 | `jackskj/carta.getUniqueId` | 8.83GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 78.87MB | 5/175 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 47.37MB | 9/175 | `█████████░░░░░░ 60%` |
| 3 | `database/sql.convertAssignRows` | 38.7MB | 10/175 | `███████░░░░░░░░ 49%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 173/175 | `██████░░░░░░░░░ 46%` |
| 5 | `runtime.mallocgc` | 26.97MB | 173/175 | `█████░░░░░░░░░░ 34%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/175 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/175 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `internal/evaluation.mergeMetadata` | 12.09MB | 12/175 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `bytes.growSlice` | 11.74MB | 103/175 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.72MB | 6/175 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 122.95GB | 164/175 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 72.31GB | 170/175 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 72.18GB | 170/175 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 70.75GB | 168/175 | `████████░░░░░░░ 57%` |
| 5 | `experiment/local.topologicalSort` | 52.21GB | 152/175 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 50.57GB | 120/175 | `██████░░░░░░░░░ 41%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 35.52GB | 98/175 | `████░░░░░░░░░░░ 28%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 30.98GB | 166/175 | `███░░░░░░░░░░░░ 25%` |
| 9 | `fmt.Sprintf` | 28.34GB | 44/175 | `███░░░░░░░░░░░░ 23%` |
| 10 | `fmt.(*buffer).writeString` | 24.13GB | 16/175 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
