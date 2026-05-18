# Overview: prod
*Last updated: 2026-05-19 03:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T03:01 (167 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,390 | avg: 15,380 | max: 84,644 | trend: decreasing (-6.70/hr))
```
▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▁▃▃▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 135.7MB | avg: 230.7MB | max: 1896.6MB | trend: stable (+0.24MB/hr))
```
▂▂▂▁▁▁▁▁▄▃▂▃▂▂▁▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▄▃▅▃▂▃▃▂▃▄▃▃▂▃▄▃▃▂▄▄▄▄█▂▃▃▂▃▃▃▂▃▂▂▄▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,390 | 14,456 | -66 | 15,380 | 84,644 | decreasing (-6.70/hr) |
| Heap InUse | 135.7MB | 154.3MB | -18.6MB | 230.7MB | 1896.6MB | stable (+0.24MB/hr) |
| Heap Sys | 2246.5MB | 2261.8MB | -15.3MB | 4628.2MB | 6579.6MB | |
| Heap Objects | 489,313 | 695,140 | -205827 | 984,870 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 7 | 14,602 | 238.7MB | 404.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 8.01MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.5MB |
| 5 | `bytes.growSlice` | 2.58MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `reflect.unsafe_NewArray` | 2.01MB |
| 8 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.0MB |
| 9 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 10 | `compress/flate.NewWriter` | 1.76MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 9.02GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 5.45GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 5.37GB |
| 4 | `experiment/local.topologicalSort` | 3.62GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 3.42GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 2.83GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 1.7GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 1.57GB |
| 9 | `fmt.Sprintf` | 993.3MB |
| 10 | `segmentio/kafka-go.makePartitions` | 888.9MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 78.57MB | 4/167 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 52.33MB | 8/167 | `█████████░░░░░░ 66%` |
| 3 | `database/sql.convertAssignRows` | 36.83MB | 9/167 | `███████░░░░░░░░ 46%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 165/167 | `██████░░░░░░░░░ 46%` |
| 5 | `runtime.mallocgc` | 27.8MB | 165/167 | `█████░░░░░░░░░░ 35%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/167 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/167 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `bytes.growSlice` | 12.17MB | 97/167 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `internal/evaluation.mergeMetadata` | 12.14MB | 11/167 | `██░░░░░░░░░░░░░ 15%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.86MB | 5/167 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 127.03GB | 156/167 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 74.59GB | 162/167 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 74.45GB | 162/167 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 73.24GB | 160/167 | `████████░░░░░░░ 57%` |
| 5 | `experiment/local.topologicalSort` | 54.15GB | 144/167 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 53.21GB | 112/167 | `██████░░░░░░░░░ 41%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 37.94GB | 90/167 | `████░░░░░░░░░░░ 29%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 32.06GB | 158/167 | `███░░░░░░░░░░░░ 25%` |
| 9 | `fmt.Sprintf` | 30.95GB | 40/167 | `███░░░░░░░░░░░░ 24%` |
| 10 | `fmt.(*buffer).writeString` | 24.13GB | 16/167 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
