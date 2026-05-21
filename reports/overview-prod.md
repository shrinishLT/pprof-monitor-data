# Overview: prod
*Last updated: 2026-05-22 02:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-22T02:30 (331 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,552 | avg: 15,792 | max: 84,644 | trend: INCREASING (+8.38/hr))
```
▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁
```

**Heap InUse** (current: 252.6MB | avg: 243.0MB | max: 1896.6MB | trend: stable (+0.37MB/hr))
```
▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▁▁▁▂▂▁▄▂▁▁▂▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▂▃▁▁▃▃▁▁▁▂▂▁▁▂▂▂▃▃▂▂▁▂▂▂▂▂▁▂▂▂▁▂▂▂▂▃▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,552 | 20,018 | -5466 | 15,792 | 84,644 | INCREASING (+8.38/hr) |
| Heap InUse | 252.6MB | 432.8MB | -180.2MB | 243.0MB | 1896.6MB | stable (+0.37MB/hr) |
| Heap Sys | 4873.7MB | 4875.3MB | -1.6MB | 4288.1MB | 6579.6MB | |
| Heap Objects | 1,207,358 | 1,663,407 | -456049 | 1,015,532 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 68 | 16,073 | 267.1MB | 501.2MB |
| 2026-05-22 | 7 | 16,402 | 284.4MB | 432.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 35.36MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 7.0MB |
| 5 | `bufio.NewWriterSize` | 4.04MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `reflect.unsafe_NewArray` | 2.0MB |
| 8 | `http2/hpack.(*headerFieldTable).addEntry` | 2.0MB |
| 9 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 10 | `segmentio/kafka-go.makePartitions` | 1.53MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 311.86GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 186.89GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 186.58GB |
| 4 | `experiment/local.topologicalSort` | 123.67GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 97.48GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 59.26GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 55.91GB |
| 8 | `fmt.Sprintf` | 32.46GB |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 25.81GB |
| 10 | `segmentio/kafka-go.makePartitions` | 21.81GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.01MB | 8/331 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.22MB | 14/331 | `███████████░░░░ 79%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 329/331 | `█████████░░░░░░ 63%` |
| 4 | `database/sql.convertAssignRows` | 32.63MB | 16/331 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 25.33MB | 329/331 | `██████░░░░░░░░░ 43%` |
| 6 | `bytes.growSlice` | 14.02MB | 237/331 | `███░░░░░░░░░░░░ 24%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/331 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/331 | `███░░░░░░░░░░░░ 20%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.93MB | 48/331 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/331 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 122.84GB | 320/331 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 72.93GB | 326/331 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 72.92GB | 326/331 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 52.65GB | 307/331 | `██████░░░░░░░░░ 42%` |
| 5 | `experiment/local.topologicalSort` | 50.5GB | 308/331 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.74GB | 276/331 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.26GB | 252/331 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 25.62GB | 270/331 | `███░░░░░░░░░░░░ 20%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/331 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `fmt.Sprintf` | 18.18GB | 155/331 | `██░░░░░░░░░░░░░ 14%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.2x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (3.9x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
