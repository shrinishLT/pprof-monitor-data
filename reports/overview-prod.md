# Overview: prod
*Last updated: 2026-05-19 04:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T04:30 (170 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,253 | avg: 15,365 | max: 84,644 | trend: decreasing (-7.38/hr))
```
▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▁▃▃▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 122.5MB | avg: 229.2MB | max: 1896.6MB | trend: stable (+0.13MB/hr))
```
▁▁▁▁▁▄▃▂▃▂▂▁▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▄▃▅▃▂▃▃▂▃▄▃▃▂▃▄▃▃▂▄▄▄▄█▂▃▃▂▃▃▃▂▃▂▂▄▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 1%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,253 | 14,526 | -273 | 15,365 | 84,644 | decreasing (-7.38/hr) |
| Heap InUse | 122.5MB | 140.0MB | -17.5MB | 229.2MB | 1896.6MB | stable (+0.13MB/hr) |
| Heap Sys | 2407.1MB | 2233.9MB | +173.2MB | 4587.0MB | 6579.6MB | |
| Heap Objects | 442,781 | 540,970 | -98189 | 977,530 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 10 | 14,585 | 210.3MB | 404.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 10.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.5MB |
| 5 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.03MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 8 | `bytes.growSlice` | 1.51MB |
| 9 | `bufio.NewWriterSize` | 1.51MB |
| 10 | `reflect.mapassign_faststr0` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 23.22GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 14.01GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 14.01GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 11.43GB |
| 5 | `experiment/local.topologicalSort` | 9.28GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 7.26GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 5.21GB |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 4.43GB |
| 9 | `segmentio/kafka-go.makePartitions` | 2.64GB |
| 10 | `fmt.Sprintf` | 2.55GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 78.57MB | 4/170 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 52.33MB | 8/170 | `█████████░░░░░░ 66%` |
| 3 | `database/sql.convertAssignRows` | 36.83MB | 9/170 | `███████░░░░░░░░ 46%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 168/170 | `██████░░░░░░░░░ 46%` |
| 5 | `runtime.mallocgc` | 27.47MB | 168/170 | `█████░░░░░░░░░░ 34%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/170 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/170 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `internal/evaluation.mergeMetadata` | 12.14MB | 11/170 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `bytes.growSlice` | 11.89MB | 100/170 | `██░░░░░░░░░░░░░ 15%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.86MB | 5/170 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 124.99GB | 159/170 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 73.44GB | 165/170 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 73.3GB | 165/170 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 72.05GB | 163/170 | `████████░░░░░░░ 57%` |
| 5 | `experiment/local.topologicalSort` | 53.2GB | 147/170 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 51.98GB | 115/170 | `██████░░░░░░░░░ 41%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 36.84GB | 93/170 | `████░░░░░░░░░░░ 29%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 31.54GB | 161/170 | `███░░░░░░░░░░░░ 25%` |
| 9 | `fmt.Sprintf` | 28.94GB | 43/170 | `███░░░░░░░░░░░░ 23%` |
| 10 | `fmt.(*buffer).writeString` | 24.13GB | 16/170 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
