# Overview: prod
*Last updated: 2026-05-20 07:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T07:30 (224 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,352 | avg: 15,393 | max: 84,644 | trend: decreasing (-2.14/hr))
```
▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▂▃▄▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▄▁▁▁▁▁▁▁▁▁▂▁▁▂▁▃▁▁▁▁▁▁▂▁▁▁▁▇▁▁▁▁▁▂▁▁▁▁▁
```

**Heap InUse** (current: 143.1MB | avg: 228.7MB | max: 1896.6MB | trend: stable (+0.02MB/hr))
```
▂▂▃▂▄▂▂▃▂▂▃▄▃▂▁▃▄▃▂▂▃▃▄▃▆▂▃▂▂▂▂▂▂▂▂▂▄▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▆▂▁▂▁▄▁▁▂▂▁▁▁▃▄▃▁▁▂▂▃▁▂▁▁▁▁▃▁▂▁▁█▁▂▁▁▁▂▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,352 | 14,137 | +215 | 15,393 | 84,644 | decreasing (-2.14/hr) |
| Heap InUse | 143.1MB | 112.9MB | +30.2MB | 228.7MB | 1896.6MB | stable (+0.02MB/hr) |
| Heap Sys | 4313.8MB | 4314.5MB | -0.7MB | 4482.6MB | 6579.6MB | |
| Heap Objects | 631,206 | 334,273 | +296933 | 969,800 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 16 | 15,389 | 205.1MB | 786.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `dotlapse-event-service/workerpool.NewWorker` | 4.0MB |
| 6 | `internal/evaluation.mergeMetadata` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.03MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `compress/flate.NewWriter` | 1.76MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 75.24GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 45.02GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 45.01GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 42.72GB |
| 5 | `experiment/local.topologicalSort` | 29.99GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 23.65GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 19.66GB |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 14.24GB |
| 9 | `reflect.growslice` | 11.36GB |
| 10 | `jackskj/carta.getUniqueId` | 8.77GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/224 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/224 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 222/224 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 34.92MB | 13/224 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 24.87MB | 222/224 | `██████░░░░░░░░░ 40%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/224 | `████░░░░░░░░░░░ 29%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/224 | `███░░░░░░░░░░░░ 21%` |
| 8 | `bytes.growSlice` | 12.03MB | 138/224 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.5MB | 27/224 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 219/224 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 124.84GB | 213/224 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 73.74GB | 219/224 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 73.67GB | 219/224 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 64.51GB | 214/224 | `███████░░░░░░░░ 51%` |
| 5 | `experiment/local.topologicalSort` | 52.22GB | 201/224 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 47.78GB | 169/224 | `█████░░░░░░░░░░ 38%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 32.19GB | 146/224 | `███░░░░░░░░░░░░ 25%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 29.46GB | 203/224 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/224 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `fmt.Sprintf` | 22.97GB | 78/224 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
