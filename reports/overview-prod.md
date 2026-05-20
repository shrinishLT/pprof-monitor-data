# Overview: prod
*Last updated: 2026-05-20 15:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T15:02 (239 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,325 | avg: 15,495 | max: 84,644 | trend: INCREASING (+2.92/hr))
```
▁▂▁▁▁▁▂▂▂▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▁▁▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▁▁▄▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▄█▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 124.2MB | avg: 230.2MB | max: 1896.6MB | trend: stable (+0.08MB/hr))
```
▂▃▂▂▂▃▃▃▂▅▂▂▂▁▂▂▂▁▂▂▁▃▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▂▂▁▁▁▂▃▂▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂█▂▂▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 1%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,325 | 15,576 | -1251 | 15,495 | 84,644 | INCREASING (+2.92/hr) |
| Heap InUse | 124.2MB | 160.1MB | -35.9MB | 230.2MB | 1896.6MB | stable (+0.08MB/hr) |
| Heap Sys | 1366.2MB | 951.6MB | +414.6MB | 4358.4MB | 6579.6MB | |
| Heap Objects | 369,671 | 511,959 | -142288 | 976,280 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 31 | 16,175 | 228.5MB | 958.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 4.5MB |
| 5 | `dotlapse-event-service/workerpool.NewWorker` | 3.5MB |
| 6 | `bytes.growSlice` | 3.15MB |
| 7 | `compress/flate.NewWriter` | 2.64MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `bufio.NewReaderSize` | 1.51MB |
| 10 | `encoding/json.typeFields` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 23.53GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 14.34GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 14.22GB |
| 4 | `experiment/local.topologicalSort` | 9.33GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 8.18GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 7.42GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 4.41GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 3.71GB |
| 9 | `segmentio/kafka-go.makePartitions` | 2.58GB |
| 10 | `fmt.Sprintf` | 2.51GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/239 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/239 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 237/239 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 34.92MB | 13/239 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 24.42MB | 237/239 | `█████░░░░░░░░░░ 39%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 16.18MB | 3/239 | `███░░░░░░░░░░░░ 26%` |
| 7 | `bytes.growSlice` | 12.68MB | 152/239 | `███░░░░░░░░░░░░ 20%` |
| 8 | `net/http.(*Transport).dialConn` | 12.62MB | 4/239 | `███░░░░░░░░░░░░ 20%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.05MB | 30/239 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 233/239 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 121.19GB | 228/239 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.67GB | 234/239 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.61GB | 234/239 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 62.59GB | 226/239 | `███████░░░░░░░░ 51%` |
| 5 | `experiment/local.topologicalSort` | 50.51GB | 216/239 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 45.66GB | 184/239 | `█████░░░░░░░░░░ 37%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 30.41GB | 161/239 | `███░░░░░░░░░░░░ 25%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 28.67GB | 214/239 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/239 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `fmt.Sprintf` | 21.05GB | 86/239 | `██░░░░░░░░░░░░░ 17%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.2x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.2x avg)
