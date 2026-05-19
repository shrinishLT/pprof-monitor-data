# Overview: prod
*Last updated: 2026-05-20 04:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T04:30 (218 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,742 | avg: 15,399 | max: 84,644 | trend: decreasing (-1.94/hr))
```
▁▁▁▂▂▅▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▂▃▄▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▄▁▁▁▁▁▁▁▁▁▂▁▁▂▁▃▁▁▁▁▁▁▂▁▁▁▁▇▁▁▁▁▁
```

**Heap InUse** (current: 198.9MB | avg: 230.5MB | max: 1896.6MB | trend: stable (+0.12MB/hr))
```
▁▁▁▂▂▃▂▂▃▂▄▂▂▂▂▂▃▄▂▂▁▂▄▂▂▂▃▃▄▃▆▂▃▂▁▂▂▂▁▂▂▁▃▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▆▂▁▂▁▄▁▁▂▂▁▁▁▂▄▃▁▁▂▂▂▁▂▁▁▁▁▃▁▁▁▁█▁▂▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,742 | 14,569 | +173 | 15,399 | 84,644 | decreasing (-1.94/hr) |
| Heap InUse | 198.9MB | 128.9MB | +70.0MB | 230.5MB | 1896.6MB | stable (+0.12MB/hr) |
| Heap Sys | 3536.3MB | 621.5MB | +2914.8MB | 4490.9MB | 6579.6MB | |
| Heap Objects | 1,010,506 | 440,035 | +570471 | 982,336 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 10 | 15,523 | 230.0MB | 786.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `bytes.growSlice` | 7.04MB |
| 6 | `segmentio/kafka-go.makePartitions` | 4.52MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 4.0MB |
| 8 | `compress/flate.NewWriter` | 3.53MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.51MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 8.99GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 6.11GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 5.43GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 5.38GB |
| 5 | `experiment/local.topologicalSort` | 3.63GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 2.86GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 2.81GB |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 1.69GB |
| 9 | `segmentio/kafka-go.makePartitions` | 1.4GB |
| 10 | `fmt.Sprintf` | 1022.39MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/218 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/218 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 216/218 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 34.92MB | 13/218 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 25.23MB | 216/218 | `██████░░░░░░░░░ 40%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/218 | `████░░░░░░░░░░░ 29%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/218 | `███░░░░░░░░░░░░ 21%` |
| 8 | `bytes.growSlice` | 12.08MB | 135/218 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `internal/evaluation.mergeMetadata` | 12.02MB | 24/218 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 213/218 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 126.72GB | 207/218 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 74.8GB | 213/218 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 74.73GB | 213/218 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 65.61GB | 208/218 | `███████░░░░░░░░ 51%` |
| 5 | `experiment/local.topologicalSort` | 53.09GB | 195/218 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 48.85GB | 163/218 | `█████░░░░░░░░░░ 38%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 33.08GB | 140/218 | `███░░░░░░░░░░░░ 26%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 29.75GB | 199/218 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/218 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `fmt.Sprintf` | 23.24GB | 77/218 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
