# Overview: prod
*Last updated: 2026-05-19 02:32 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T02:32 (166 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,456 | avg: 15,386 | max: 84,644 | trend: decreasing (-6.39/hr))
```
▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▁▃▃▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 154.3MB | avg: 231.3MB | max: 1896.6MB | trend: stable (+0.29MB/hr))
```
▁▂▂▂▁▁▁▁▁▄▃▂▃▂▂▁▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▄▃▅▃▂▃▃▂▃▄▃▃▂▃▄▃▃▂▄▄▄▄█▂▃▃▂▃▃▃▂▃▂▂▄▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,456 | 15,368 | -912 | 15,386 | 84,644 | decreasing (-6.39/hr) |
| Heap InUse | 154.3MB | 404.4MB | -250.1MB | 231.3MB | 1896.6MB | stable (+0.29MB/hr) |
| Heap Sys | 2261.8MB | 6573.2MB | -4311.4MB | 4642.5MB | 6579.6MB | |
| Heap Objects | 695,140 | 1,946,449 | -1251309 | 987,855 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 6 | 14,638 | 255.8MB | 404.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 8.01MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.5MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.51MB |
| 6 | `compress/flate.NewWriter` | 3.53MB |
| 7 | `bytes.growSlice` | 2.51MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.0MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 3.39GB |
| 2 | `internal/evaluation.mergeMetadata` | 2.6GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 1.59GB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 1.55GB |
| 5 | `experiment/local.(*Client).EvaluateV2` | 1.52GB |
| 6 | `experiment/local.topologicalSort` | 1.01GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 828.35MB |
| 8 | `reflect.growslice` | 670.26MB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 643.01MB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 616.89MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 78.57MB | 4/166 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 52.33MB | 8/166 | `█████████░░░░░░ 66%` |
| 3 | `database/sql.convertAssignRows` | 36.83MB | 9/166 | `███████░░░░░░░░ 46%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 164/166 | `██████░░░░░░░░░ 46%` |
| 5 | `runtime.mallocgc` | 27.92MB | 164/166 | `█████░░░░░░░░░░ 35%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/166 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/166 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `bytes.growSlice` | 12.27MB | 96/166 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `internal/evaluation.mergeMetadata` | 12.14MB | 11/166 | `██░░░░░░░░░░░░░ 15%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.86MB | 5/166 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 127.79GB | 155/166 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 75.02GB | 161/166 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 74.87GB | 161/166 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 73.68GB | 159/166 | `████████░░░░░░░ 57%` |
| 5 | `experiment/local.topologicalSort` | 54.5GB | 143/166 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 53.67GB | 111/166 | `██████░░░░░░░░░ 41%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 38.35GB | 89/166 | `████░░░░░░░░░░░ 30%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 32.26GB | 157/166 | `███░░░░░░░░░░░░ 25%` |
| 9 | `fmt.Sprintf` | 31.72GB | 39/166 | `███░░░░░░░░░░░░ 24%` |
| 10 | `fmt.(*buffer).writeString` | 24.13GB | 16/166 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
