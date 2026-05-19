# Overview: prod
*Last updated: 2026-05-19 23:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T23:00 (207 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,249 | avg: 15,382 | max: 84,644 | trend: decreasing (-3.25/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▅▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▂▃▄▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▄▁▁▁▁▁▁▁▁▁▂▁▁▂▁▃▁▁▁▁▁▁
```

**Heap InUse** (current: 152.3MB | avg: 229.9MB | max: 1896.6MB | trend: stable (+0.11MB/hr))
```
▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▃▃▅▃▂▃▂▂▃▄▃▃▂▃▄▃▃▂▄▄▄▃█▂▃▃▂▃▃▃▂▃▂▂▄▁▁▁▁▁▁▁▄▁▁▁▁▁▁▂▇▂▁▂▁▅▁▁▂▂▂▁▂▃▅▃▂▁▂▂▃▂▃▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,249 | 14,231 | +18 | 15,382 | 84,644 | decreasing (-3.25/hr) |
| Heap InUse | 152.3MB | 171.0MB | -18.7MB | 229.9MB | 1896.6MB | stable (+0.11MB/hr) |
| Heap Sys | 4943.7MB | 4943.7MB | +0.0MB | 4516.0MB | 6579.6MB | |
| Heap Objects | 472,386 | 802,164 | -329778 | 980,212 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 47 | 15,275 | 228.5MB | 661.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 20.22MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.54MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `internal/evaluation.(*Engine).Evaluate` | 1.6MB |
| 9 | `bufio.NewReaderSize` | 1.53MB |
| 10 | `bufio.NewWriterSize` | 1.52MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 230.88GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 138.77GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 138.57GB |
| 4 | `experiment/local.topologicalSort` | 92.06GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 71.81GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 65.35GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 43.82GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 30.04GB |
| 9 | `fmt.Sprintf` | 23.61GB |
| 10 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 22.26GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 69.11MB | 6/207 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.54MB | 11/207 | `█████████░░░░░░ 65%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 205/207 | `███████░░░░░░░░ 53%` |
| 4 | `database/sql.convertAssignRows` | 35.58MB | 12/207 | `███████░░░░░░░░ 51%` |
| 5 | `runtime.mallocgc` | 25.64MB | 205/207 | `█████░░░░░░░░░░ 37%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/207 | `████░░░░░░░░░░░ 26%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/207 | `██░░░░░░░░░░░░░ 19%` |
| 8 | `bytes.growSlice` | 11.85MB | 129/207 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.05MB | 21/207 | `██░░░░░░░░░░░░░ 15%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 203/207 | `██░░░░░░░░░░░░░ 13%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 122.74GB | 196/207 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 72.41GB | 202/207 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 72.32GB | 202/207 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 66.2GB | 197/207 | `████████░░░░░░░ 53%` |
| 5 | `experiment/local.topologicalSort` | 51.55GB | 184/207 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 47.93GB | 152/207 | `█████░░░░░░░░░░ 39%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 32.45GB | 130/207 | `███░░░░░░░░░░░░ 26%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 30.0GB | 188/207 | `███░░░░░░░░░░░░ 24%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/207 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `fmt.Sprintf` | 23.4GB | 67/207 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
