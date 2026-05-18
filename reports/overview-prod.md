# Overview: prod
*Last updated: 2026-05-19 05:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T05:00 (171 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,338 | avg: 15,359 | max: 84,644 | trend: decreasing (-7.67/hr))
```
▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▁▃▃▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 158.8MB | avg: 228.8MB | max: 1896.6MB | trend: stable (+0.09MB/hr))
```
▁▁▁▁▄▃▂▃▂▂▁▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▄▃▅▃▂▃▃▂▃▄▃▃▂▃▄▃▃▂▄▄▄▄█▂▃▃▂▃▃▃▂▃▂▂▄▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,338 | 14,253 | +85 | 15,359 | 84,644 | decreasing (-7.67/hr) |
| Heap InUse | 158.8MB | 122.5MB | +36.3MB | 228.8MB | 1896.6MB | stable (+0.09MB/hr) |
| Heap Sys | 2407.9MB | 2407.1MB | +0.8MB | 4574.3MB | 6579.6MB | |
| Heap Objects | 808,133 | 442,781 | +365352 | 976,539 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 11 | 14,563 | 205.6MB | 404.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.5MB |
| 5 | `reflect.growslice` | 5.59MB |
| 6 | `experiment/local.topologicalSort` | 3.06MB |
| 7 | `fmt.(*buffer).writeByte` | 2.64MB |
| 8 | `bufio.NewWriterSize` | 2.51MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `reflect.mapassign_faststr0` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 25.05GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 15.14GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 15.1GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 11.47GB |
| 5 | `experiment/local.topologicalSort` | 9.99GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 7.82GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 5.23GB |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 4.78GB |
| 9 | `segmentio/kafka-go.makePartitions` | 3.27GB |
| 10 | `fmt.Sprintf` | 2.74GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 78.57MB | 4/171 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 52.33MB | 8/171 | `█████████░░░░░░ 66%` |
| 3 | `database/sql.convertAssignRows` | 36.83MB | 9/171 | `███████░░░░░░░░ 46%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 169/171 | `██████░░░░░░░░░ 46%` |
| 5 | `runtime.mallocgc` | 27.38MB | 169/171 | `█████░░░░░░░░░░ 34%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/171 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/171 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `internal/evaluation.mergeMetadata` | 12.14MB | 11/171 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `bytes.growSlice` | 11.89MB | 100/171 | `██░░░░░░░░░░░░░ 15%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.86MB | 5/171 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 124.37GB | 160/171 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 73.09GB | 166/171 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 72.95GB | 166/171 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 71.68GB | 164/171 | `████████░░░░░░░ 57%` |
| 5 | `experiment/local.topologicalSort` | 52.91GB | 148/171 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 51.6GB | 116/171 | `██████░░░░░░░░░ 41%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 36.5GB | 94/171 | `████░░░░░░░░░░░ 29%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 31.38GB | 162/171 | `███░░░░░░░░░░░░ 25%` |
| 9 | `fmt.Sprintf` | 28.34GB | 44/171 | `███░░░░░░░░░░░░ 22%` |
| 10 | `fmt.(*buffer).writeString` | 24.13GB | 16/171 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
