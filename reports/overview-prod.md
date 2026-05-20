# Overview: prod
*Last updated: 2026-05-20 09:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T09:02 (227 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,454 | avg: 15,384 | max: 84,644 | trend: decreasing (-2.53/hr))
```
▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▂▃▄▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▄▁▁▁▁▁▁▁▁▁▂▁▁▂▁▃▁▁▁▁▁▁▂▁▁▁▁▇▁▁▁▁▁▂▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 179.4MB | avg: 228.0MB | max: 1896.6MB | trend: stable (-0.02MB/hr))
```
▂▄▂▂▃▂▂▃▄▃▂▁▃▄▃▂▂▃▃▄▃▆▂▃▂▂▂▂▂▂▂▂▂▄▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▆▂▁▂▁▄▁▁▂▂▁▁▁▃▄▃▁▁▂▂▃▁▂▁▁▁▁▃▁▂▁▁█▁▂▁▁▁▂▁▁▁▁▁▂▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,454 | 14,458 | -4 | 15,384 | 84,644 | decreasing (-2.53/hr) |
| Heap InUse | 179.4MB | 140.5MB | +38.9MB | 228.0MB | 1896.6MB | stable (-0.02MB/hr) |
| Heap Sys | 4314.0MB | 4314.1MB | -0.1MB | 4480.4MB | 6579.6MB | |
| Heap Objects | 865,007 | 632,200 | +232807 | 968,456 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 19 | 15,281 | 201.1MB | 786.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `dotlapse-event-service/workerpool.NewWorker` | 4.0MB |
| 6 | `bytes.growSlice` | 3.09MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `bufio.NewWriterSize` | 2.01MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 83.37GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 49.82GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 49.8GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 47.49GB |
| 5 | `experiment/local.topologicalSort` | 33.11GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 26.19GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 21.91GB |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 15.77GB |
| 9 | `reflect.growslice` | 11.88GB |
| 10 | `jackskj/carta.getUniqueId` | 9.36GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/227 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/227 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 225/227 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 34.92MB | 13/227 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 24.7MB | 225/227 | `█████░░░░░░░░░░ 39%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/227 | `████░░░░░░░░░░░ 29%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/227 | `███░░░░░░░░░░░░ 21%` |
| 8 | `bytes.growSlice` | 11.88MB | 141/227 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.5MB | 27/227 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 222/227 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 124.22GB | 216/227 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 73.39GB | 222/227 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 73.32GB | 222/227 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 64.23GB | 217/227 | `███████░░░░░░░░ 51%` |
| 5 | `experiment/local.topologicalSort` | 51.93GB | 204/227 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 47.39GB | 172/227 | `█████░░░░░░░░░░ 38%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 31.85GB | 149/227 | `███░░░░░░░░░░░░ 25%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 29.32GB | 206/227 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/227 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `fmt.Sprintf` | 22.97GB | 78/227 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.5x avg)
