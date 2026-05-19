# Overview: prod
*Last updated: 2026-05-20 01:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T01:30 (212 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,320 | avg: 15,376 | max: 84,644 | trend: decreasing (-3.42/hr))
```
▁▁▁▁▁▁▁▁▁▂▂▅▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▂▃▄▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▄▁▁▁▁▁▁▁▁▁▂▁▁▂▁▃▁▁▁▁▁▁▂▁▁▁▁
```

**Heap InUse** (current: 154.3MB | avg: 229.3MB | max: 1896.6MB | trend: stable (+0.07MB/hr))
```
▁▁▃▄▁▁▁▁▁▂▂▄▃▂▃▃▅▃▂▃▂▂▃▄▃▃▂▃▄▃▃▂▄▄▄▃█▂▃▃▂▃▃▃▂▃▂▂▄▁▁▁▁▁▁▁▄▁▁▁▁▁▁▂▇▂▁▂▁▅▁▁▂▂▂▁▂▃▅▃▂▁▂▂▃▂▃▁▁▁▁▃▁▂▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,320 | 14,223 | +97 | 15,376 | 84,644 | decreasing (-3.42/hr) |
| Heap InUse | 154.3MB | 158.4MB | -4.1MB | 229.3MB | 1896.6MB | stable (+0.07MB/hr) |
| Heap Sys | 4945.7MB | 4945.5MB | +0.2MB | 4526.1MB | 6579.6MB | |
| Heap Objects | 535,096 | 694,187 | -159091 | 977,853 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 4 | 14,462 | 169.5MB | 213.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 20.22MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.53MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `bufio.NewReaderSize` | 2.01MB |
| 9 | `internal/evaluation.(*Engine).Evaluate` | 1.57MB |
| 10 | `bytes.growSlice` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 258.85GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 155.85GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 155.5GB |
| 4 | `experiment/local.topologicalSort` | 103.15GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 80.49GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 77.32GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 49.22GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 35.54GB |
| 9 | `fmt.Sprintf` | 26.37GB |
| 10 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 23.02GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/212 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/212 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 210/212 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 34.92MB | 13/212 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 25.51MB | 210/212 | `██████░░░░░░░░░ 41%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/212 | `████░░░░░░░░░░░ 29%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/212 | `███░░░░░░░░░░░░ 21%` |
| 8 | `bytes.growSlice` | 11.83MB | 132/212 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.25MB | 22/212 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 208/212 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.89GB | 201/212 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 74.28GB | 207/212 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 74.2GB | 207/212 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 66.32GB | 202/212 | `███████░░░░░░░░ 52%` |
| 5 | `experiment/local.topologicalSort` | 52.82GB | 189/212 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 48.87GB | 157/212 | `█████░░░░░░░░░░ 38%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 33.0GB | 135/212 | `███░░░░░░░░░░░░ 26%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 30.07GB | 193/212 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/212 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `fmt.Sprintf` | 23.54GB | 72/212 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
