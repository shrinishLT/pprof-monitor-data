# Overview: prod
*Last updated: 2026-05-20 03:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T03:02 (215 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,336 | avg: 15,412 | max: 84,644 | trend: decreasing (-1.31/hr))
```
▁▁▁▁▁▁▂▂▅▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▂▃▄▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▄▁▁▁▁▁▁▁▁▁▂▁▁▂▁▃▁▁▁▁▁▁▂▁▁▁▁▇▁▁
```

**Heap InUse** (current: 230.8MB | avg: 231.5MB | max: 1896.6MB | trend: stable (+0.18MB/hr))
```
▃▁▁▁▁▁▂▂▃▂▂▃▂▄▂▂▂▂▂▃▄▂▂▁▂▄▂▂▂▃▃▄▃▆▂▃▂▁▂▂▂▁▂▂▁▃▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▆▂▁▂▁▄▁▁▂▂▁▁▁▂▄▃▁▁▂▂▂▁▂▁▁▁▁▃▁▁▁▁█▁▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,336 | 14,355 | -19 | 15,412 | 84,644 | decreasing (-1.31/hr) |
| Heap InUse | 230.8MB | 144.0MB | +86.8MB | 231.5MB | 1896.6MB | stable (+0.18MB/hr) |
| Heap Sys | 4898.9MB | 4898.4MB | +0.5MB | 4531.2MB | 6579.6MB | |
| Heap Objects | 1,208,848 | 277,624 | +931224 | 986,227 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 7 | 15,966 | 262.8MB | 786.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 20.22MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `internal/evaluation.mergeMetadata` | 4.5MB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 3.75MB |
| 7 | `segmentio/kafka-go.makePartitions` | 3.04MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 2.02MB |
| 10 | `bufio.NewReaderSize` | 2.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 309.17GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 186.04GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 185.8GB |
| 4 | `experiment/local.topologicalSort` | 123.32GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 96.42GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 82.51GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 58.82GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 37.99GB |
| 9 | `fmt.Sprintf` | 31.35GB |
| 10 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 23.74GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/215 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/215 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 213/215 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 34.92MB | 13/215 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 25.44MB | 213/215 | `██████░░░░░░░░░ 40%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/215 | `████░░░░░░░░░░░ 29%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/215 | `███░░░░░░░░░░░░ 21%` |
| 8 | `bytes.growSlice` | 12.11MB | 134/215 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `internal/evaluation.mergeMetadata` | 12.02MB | 24/215 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 210/215 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 128.51GB | 204/215 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 75.83GB | 210/215 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 75.75GB | 210/215 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 66.53GB | 205/215 | `███████░░░░░░░░ 51%` |
| 5 | `experiment/local.topologicalSort` | 53.89GB | 192/215 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 49.73GB | 160/215 | `█████░░░░░░░░░░ 38%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 33.54GB | 138/215 | `███░░░░░░░░░░░░ 26%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 30.18GB | 196/215 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/215 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprintf` | 23.83GB | 75/215 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
