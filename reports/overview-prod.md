# Overview: prod
*Last updated: 2026-05-19 01:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T01:30 (164 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,557 | avg: 15,392 | max: 84,644 | trend: decreasing (-6.19/hr))
```
▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▁▃▃▃▅▁▁▂▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 217.4MB | avg: 230.7MB | max: 1896.6MB | trend: stable (+0.26MB/hr))
```
▁▂▁▂▂▂▁▁▁▁▁▄▃▂▃▂▂▁▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▄▃▅▃▂▃▃▂▃▄▃▃▂▃▄▃▃▂▄▄▄▄█▂▃▃▂▃▃▃▂▃▂▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,557 | 14,517 | +40 | 15,392 | 84,644 | decreasing (-6.19/hr) |
| Heap InUse | 217.4MB | 256.7MB | -39.3MB | 230.7MB | 1896.6MB | stable (+0.26MB/hr) |
| Heap Sys | 6572.2MB | 6571.3MB | +0.9MB | 4645.3MB | 6579.6MB | |
| Heap Objects | 606,214 | 1,101,915 | -495701 | 983,795 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 4 | 14,501 | 244.1MB | 287.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 55.03MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 5.03MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 6 | `bufio.NewWriterSize` | 3.05MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.01MB |
| 9 | `reflect.unsafe_NewArray` | 2.0MB |
| 10 | `compress/flate.NewWriter` | 1.76MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 547.61GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 331.32GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 330.17GB |
| 4 | `experiment/local.topologicalSort` | 218.6GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 171.83GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 158.57GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 104.26GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 72.58GB |
| 9 | `fmt.Sprintf` | 54.85GB |
| 10 | `segmentio/kafka-go.makePartitions` | 45.7GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 78.57MB | 4/164 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 52.33MB | 8/164 | `█████████░░░░░░ 66%` |
| 3 | `database/sql.convertAssignRows` | 36.83MB | 9/164 | `███████░░░░░░░░ 46%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 162/164 | `██████░░░░░░░░░ 46%` |
| 5 | `runtime.mallocgc` | 27.88MB | 162/164 | `█████░░░░░░░░░░ 35%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/164 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/164 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `bytes.growSlice` | 12.37MB | 94/164 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.55MB | 10/164 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.86MB | 5/164 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.74GB | 153/164 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 73.8GB | 159/164 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 73.66GB | 159/164 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 73.58GB | 157/164 | `████████░░░░░░░ 58%` |
| 5 | `experiment/local.topologicalSort` | 53.66GB | 141/164 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 53.01GB | 109/164 | `██████░░░░░░░░░ 42%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 37.56GB | 88/164 | `████░░░░░░░░░░░ 29%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 32.2GB | 155/164 | `███░░░░░░░░░░░░ 25%` |
| 9 | `fmt.Sprintf` | 31.07GB | 38/164 | `███░░░░░░░░░░░░ 24%` |
| 10 | `fmt.(*buffer).writeString` | 24.13GB | 16/164 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
