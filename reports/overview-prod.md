# Overview: prod
*Last updated: 2026-05-20 06:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T06:31 (222 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,098 | avg: 15,403 | max: 84,644 | trend: decreasing (-1.63/hr))
```
▂▅▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▂▃▄▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▄▁▁▁▁▁▁▁▁▁▂▁▁▂▁▃▁▁▁▁▁▁▂▁▁▁▁▇▁▁▁▁▁▂▁▁▁
```

**Heap InUse** (current: 157.3MB | avg: 229.6MB | max: 1896.6MB | trend: stable (+0.06MB/hr))
```
▂▃▂▂▃▂▄▂▂▂▂▂▃▄▂▂▁▂▄▂▂▂▃▃▄▃▆▂▃▂▁▂▂▂▁▂▂▁▃▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▆▂▁▂▁▄▁▁▂▂▁▁▁▂▄▃▁▁▂▂▂▁▂▁▁▁▁▃▁▁▁▁█▁▂▁▁▁▂▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,098 | 14,696 | +402 | 15,403 | 84,644 | decreasing (-1.63/hr) |
| Heap InUse | 157.3MB | 166.2MB | -8.9MB | 229.6MB | 1896.6MB | stable (+0.06MB/hr) |
| Heap Sys | 4313.8MB | 4312.9MB | +0.9MB | 4484.1MB | 6579.6MB | |
| Heap Objects | 376,014 | 595,109 | -219095 | 974,188 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 14 | 15,552 | 216.1MB | 786.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `internal/evaluation.mergeMetadata` | 6.0MB |
| 6 | `bytes.growSlice` | 4.02MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 4.0MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.53MB |
| 9 | `bufio.NewWriterSize` | 2.52MB |
| 10 | `reflect.unsafe_NewArray` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 70.73GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 42.35GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 42.35GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 37.98GB |
| 5 | `experiment/local.topologicalSort` | 28.23GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 22.27GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 17.48GB |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 13.41GB |
| 9 | `reflect.growslice` | 11.13GB |
| 10 | `jackskj/carta.getUniqueId` | 8.5GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/222 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/222 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 220/222 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 34.92MB | 13/222 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 24.99MB | 220/222 | `██████░░░░░░░░░ 40%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/222 | `████░░░░░░░░░░░ 29%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/222 | `███░░░░░░░░░░░░ 21%` |
| 8 | `bytes.growSlice` | 12.03MB | 138/222 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.85MB | 26/222 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 217/222 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.32GB | 211/222 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 74.01GB | 217/222 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 73.93GB | 217/222 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 64.71GB | 212/222 | `███████░░░░░░░░ 51%` |
| 5 | `experiment/local.topologicalSort` | 52.45GB | 199/222 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 48.08GB | 167/222 | `█████░░░░░░░░░░ 38%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 32.44GB | 144/222 | `███░░░░░░░░░░░░ 25%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 29.55GB | 201/222 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/222 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `fmt.Sprintf` | 22.97GB | 78/222 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
