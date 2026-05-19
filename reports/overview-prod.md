# Overview: prod
*Last updated: 2026-05-20 01:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T01:00 (211 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,223 | avg: 15,381 | max: 84,644 | trend: decreasing (-3.18/hr))
```
▁▁▁▁▁▁▁▁▁▁▂▂▅▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▂▃▄▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▄▁▁▁▁▁▁▁▁▁▂▁▁▂▁▃▁▁▁▁▁▁▂▁▁▁
```

**Heap InUse** (current: 158.4MB | avg: 229.7MB | max: 1896.6MB | trend: stable (+0.09MB/hr))
```
▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▃▃▅▃▂▃▂▂▃▄▃▃▂▃▄▃▃▂▄▄▄▃█▂▃▃▂▃▃▃▂▃▂▂▄▁▁▁▁▁▁▁▄▁▁▁▁▁▁▂▇▂▁▂▁▅▁▁▂▂▂▁▂▃▅▃▂▁▂▂▃▂▃▁▁▁▁▃▁▂▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,223 | 14,819 | -596 | 15,381 | 84,644 | decreasing (-3.18/hr) |
| Heap InUse | 158.4MB | 213.4MB | -55.0MB | 229.7MB | 1896.6MB | stable (+0.09MB/hr) |
| Heap Sys | 4945.5MB | 4945.2MB | +0.3MB | 4524.1MB | 6579.6MB | |
| Heap Objects | 694,187 | 1,050,216 | -356029 | 979,951 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 3 | 14,510 | 174.5MB | 213.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 20.22MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.01MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 1.5MB |
| 9 | `reflect.mapassign_faststr0` | 1.5MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 257.23GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 154.85GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 154.52GB |
| 4 | `experiment/local.topologicalSort` | 102.53GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 80.01GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 72.8GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 48.93GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 33.48GB |
| 9 | `fmt.Sprintf` | 26.18GB |
| 10 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 22.99GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/211 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/211 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 209/211 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 34.92MB | 13/211 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 25.54MB | 209/211 | `██████░░░░░░░░░ 41%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/211 | `████░░░░░░░░░░░ 29%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/211 | `███░░░░░░░░░░░░ 21%` |
| 8 | `bytes.growSlice` | 11.91MB | 131/211 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.25MB | 22/211 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 207/211 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.23GB | 200/211 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 73.88GB | 206/211 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 73.8GB | 206/211 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 66.27GB | 201/211 | `███████░░░░░░░░ 52%` |
| 5 | `experiment/local.topologicalSort` | 52.55GB | 188/211 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 48.67GB | 156/211 | `█████░░░░░░░░░░ 38%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 32.88GB | 134/211 | `███░░░░░░░░░░░░ 26%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 30.05GB | 192/211 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/211 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `fmt.Sprintf` | 23.5GB | 71/211 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
