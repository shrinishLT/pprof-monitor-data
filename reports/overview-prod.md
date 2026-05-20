# Overview: prod
*Last updated: 2026-05-20 15:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T15:30 (240 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,726 | avg: 15,491 | max: 84,644 | trend: INCREASING (+2.73/hr))
```
▂▁▁▁▁▂▂▂▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▁▁▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▁▁▄▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▄█▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 170.0MB | avg: 230.0MB | max: 1896.6MB | trend: stable (+0.07MB/hr))
```
▃▂▂▂▃▃▃▂▅▂▂▂▁▂▂▂▁▂▂▁▃▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▂▂▁▁▁▂▃▂▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂█▂▂▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,726 | 14,325 | +401 | 15,491 | 84,644 | INCREASING (+2.73/hr) |
| Heap InUse | 170.0MB | 124.2MB | +45.8MB | 230.0MB | 1896.6MB | stable (+0.07MB/hr) |
| Heap Sys | 1359.3MB | 1366.2MB | -6.9MB | 4345.9MB | 6579.6MB | |
| Heap Objects | 640,404 | 369,671 | +270733 | 974,880 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 32 | 16,130 | 226.7MB | 958.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 6.1MB |
| 5 | `database/sql.convertAssignRows` | 5.0MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 4.5MB |
| 7 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 4.28MB |
| 8 | `dotlapse-event-service/workerpool.NewWorker` | 3.5MB |
| 9 | `bufio.NewReaderSize` | 2.52MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 31.07GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 18.88GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 18.73GB |
| 4 | `experiment/local.topologicalSort` | 12.34GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 9.8GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 8.55GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 5.88GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 3.89GB |
| 9 | `fmt.Sprintf` | 3.44GB |
| 10 | `segmentio/kafka-go.makePartitions` | 3.2GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/240 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/240 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 238/240 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 32.79MB | 14/240 | `███████░░░░░░░░ 52%` |
| 5 | `runtime.mallocgc` | 24.37MB | 238/240 | `█████░░░░░░░░░░ 39%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 16.18MB | 3/240 | `███░░░░░░░░░░░░ 26%` |
| 7 | `bytes.growSlice` | 12.64MB | 153/240 | `███░░░░░░░░░░░░ 20%` |
| 8 | `net/http.(*Transport).dialConn` | 12.62MB | 4/240 | `███░░░░░░░░░░░░ 20%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.05MB | 30/240 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 234/240 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 120.8GB | 229/240 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.45GB | 235/240 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.38GB | 235/240 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 62.35GB | 227/240 | `███████░░░░░░░░ 51%` |
| 5 | `experiment/local.topologicalSort` | 50.33GB | 217/240 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 45.47GB | 185/240 | `█████░░░░░░░░░░ 37%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 30.26GB | 162/240 | `███░░░░░░░░░░░░ 25%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 28.56GB | 215/240 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/240 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `fmt.Sprintf` | 20.85GB | 87/240 | `██░░░░░░░░░░░░░ 17%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.2x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.2x avg)
