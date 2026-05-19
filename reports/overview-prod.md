# Overview: prod
*Last updated: 2026-05-20 00:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T00:00 (209 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,487 | avg: 15,389 | max: 84,644 | trend: decreasing (-2.80/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▂▂▅▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▂▃▄▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▄▁▁▁▁▁▁▁▁▁▂▁▁▂▁▃▁▁▁▁▁▁▂▁
```

**Heap InUse** (current: 151.8MB | avg: 230.1MB | max: 1896.6MB | trend: stable (+0.12MB/hr))
```
▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▃▃▅▃▂▃▂▂▃▄▃▃▂▃▄▃▃▂▄▄▄▃█▂▃▃▂▃▃▃▂▃▂▂▄▁▁▁▁▁▁▁▄▁▁▁▁▁▁▂▇▂▁▂▁▅▁▁▂▂▂▁▂▃▅▃▂▁▂▂▃▂▃▁▁▁▁▃▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,487 | 17,638 | -3151 | 15,389 | 84,644 | decreasing (-2.80/hr) |
| Heap InUse | 151.8MB | 341.6MB | -189.8MB | 230.1MB | 1896.6MB | stable (+0.12MB/hr) |
| Heap Sys | 4944.5MB | 4944.0MB | +0.5MB | 4520.1MB | 6579.6MB | |
| Heap Objects | 468,744 | 1,652,582 | -1183838 | 980,982 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 1 | 14,487 | 151.8MB | 151.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 20.22MB |
| 3 | `internal/evaluation.mergeMetadata` | 15.5MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `experiment/local.topologicalSort` | 9.08MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 7 | `experiment/local.(*Client).EvaluateV2` | 8.45MB |
| 8 | `internal/evaluation.(*Engine).Evaluate` | 6.35MB |
| 9 | `internal/evaluation.(*Engine).evaluateFlag` | 4.5MB |
| 10 | `segmentio/kafka-go.makePartitions` | 3.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 240.66GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 144.79GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 144.46GB |
| 4 | `experiment/local.topologicalSort` | 95.95GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 74.8GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 68.06GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 45.74GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 31.28GB |
| 9 | `fmt.Sprintf` | 24.69GB |
| 10 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 22.46GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 69.11MB | 6/209 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.54MB | 11/209 | `█████████░░░░░░ 65%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 207/209 | `███████░░░░░░░░ 53%` |
| 4 | `database/sql.convertAssignRows` | 35.58MB | 12/209 | `███████░░░░░░░░ 51%` |
| 5 | `runtime.mallocgc` | 25.59MB | 207/209 | `█████░░░░░░░░░░ 37%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/209 | `████░░░░░░░░░░░ 26%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/209 | `██░░░░░░░░░░░░░ 19%` |
| 8 | `bytes.growSlice` | 11.94MB | 130/209 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.25MB | 22/209 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 205/209 | `██░░░░░░░░░░░░░ 13%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 123.91GB | 198/209 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 73.1GB | 204/209 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 73.02GB | 204/209 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 66.2GB | 199/209 | `████████░░░░░░░ 53%` |
| 5 | `experiment/local.topologicalSort` | 52.02GB | 186/209 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 48.27GB | 154/209 | `█████░░░░░░░░░░ 38%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 32.64GB | 132/209 | `███░░░░░░░░░░░░ 26%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 30.01GB | 190/209 | `███░░░░░░░░░░░░ 24%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/209 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `fmt.Sprintf` | 23.43GB | 69/209 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
