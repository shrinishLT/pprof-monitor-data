# Overview: prod
*Last updated: 2026-05-20 04:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T04:00 (217 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,569 | avg: 15,402 | max: 84,644 | trend: decreasing (-1.80/hr))
```
▁▁▁▁▂▂▅▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▂▃▄▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▄▁▁▁▁▁▁▁▁▁▂▁▁▂▁▃▁▁▁▁▁▁▂▁▁▁▁▇▁▁▁▁
```

**Heap InUse** (current: 128.9MB | avg: 230.6MB | max: 1896.6MB | trend: stable (+0.13MB/hr))
```
▁▁▁▁▂▂▃▂▂▃▂▄▂▂▂▂▂▃▄▂▂▁▂▄▂▂▂▃▃▄▃▆▂▃▂▁▂▂▂▁▂▂▁▃▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▆▂▁▂▁▄▁▁▂▂▁▁▁▂▄▃▁▁▂▂▂▁▂▁▁▁▁▃▁▁▁▁█▁▂▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 1%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,569 | 14,160 | +409 | 15,402 | 84,644 | decreasing (-1.80/hr) |
| Heap InUse | 128.9MB | 132.6MB | -3.7MB | 230.6MB | 1896.6MB | stable (+0.13MB/hr) |
| Heap Sys | 621.5MB | 640.9MB | -19.4MB | 4495.3MB | 6579.6MB | |
| Heap Objects | 440,035 | 660,025 | -219990 | 982,207 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 9 | 15,610 | 233.5MB | 786.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `dotlapse-event-service/workerpool.NewWorker` | 4.0MB |
| 6 | `bufio.NewWriterSize` | 2.52MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.04MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 5.66GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 3.37GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 3.34GB |
| 4 | `experiment/local.topologicalSort` | 2.27GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 1.76GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 1.17GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 1.05GB |
| 8 | `segmentio/kafka-go.makePartitions` | 822.84MB |
| 9 | `fmt.Sprintf` | 661.21MB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 558.11MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/217 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/217 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 215/217 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 34.92MB | 13/217 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 25.29MB | 215/217 | `██████░░░░░░░░░ 40%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/217 | `████░░░░░░░░░░░ 29%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/217 | `███░░░░░░░░░░░░ 21%` |
| 8 | `bytes.growSlice` | 12.11MB | 134/217 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `internal/evaluation.mergeMetadata` | 12.02MB | 24/217 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 212/217 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 127.3GB | 206/217 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 75.13GB | 212/217 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 75.06GB | 212/217 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 65.9GB | 207/217 | `███████░░░░░░░░ 51%` |
| 5 | `experiment/local.topologicalSort` | 53.35GB | 194/217 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 49.13GB | 162/217 | `█████░░░░░░░░░░ 38%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 33.31GB | 139/217 | `███░░░░░░░░░░░░ 26%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 29.88GB | 198/217 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/217 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprintf` | 23.53GB | 76/217 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
