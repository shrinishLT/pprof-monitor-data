# Overview: prod
*Last updated: 2026-05-20 13:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T13:31 (236 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,787 | avg: 15,502 | max: 84,644 | trend: INCREASING (+3.43/hr))
```
▁▁▁▁▂▁▁▁▁▂▂▂▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▁▁▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▁▁▄▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▄█▁▁▁▁▁▁
```

**Heap InUse** (current: 156.1MB | avg: 231.1MB | max: 1896.6MB | trend: stable (+0.13MB/hr))
```
▂▂▁▂▃▂▂▂▃▃▃▂▅▂▂▂▁▂▂▂▁▂▂▁▃▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▂▂▁▁▁▂▃▂▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂█▂▂▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,787 | 15,292 | -505 | 15,502 | 84,644 | INCREASING (+3.43/hr) |
| Heap InUse | 156.1MB | 211.8MB | -55.7MB | 231.1MB | 1896.6MB | stable (+0.13MB/hr) |
| Heap Sys | 820.7MB | 1016.3MB | -195.6MB | 4400.0MB | 6579.6MB | |
| Heap Objects | 670,222 | 1,020,776 | -350554 | 980,784 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 28 | 16,312 | 236.0MB | 958.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 6.03MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 6 | `segmentio/kafka-go.makePartitions` | 4.54MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 3.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.01MB |
| 10 | `bufio.NewReaderSize` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 5.15GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 3.07GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 3.02GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 2.29GB |
| 5 | `experiment/local.topologicalSort` | 1.99GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 1.6GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 1.06GB |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 959.56MB |
| 9 | `segmentio/kafka-go.makePartitions` | 576.37MB |
| 10 | `fmt.Sprintf` | 567.64MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/236 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/236 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 234/236 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 34.92MB | 13/236 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 24.58MB | 234/236 | `█████░░░░░░░░░░ 39%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 16.18MB | 3/236 | `███░░░░░░░░░░░░ 26%` |
| 7 | `bytes.growSlice` | 12.82MB | 149/236 | `███░░░░░░░░░░░░ 20%` |
| 8 | `net/http.(*Transport).dialConn` | 12.62MB | 4/236 | `███░░░░░░░░░░░░ 20%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.05MB | 30/236 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 230/236 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 122.58GB | 225/236 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 72.47GB | 231/236 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 72.4GB | 231/236 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 63.37GB | 223/236 | `███████░░░░░░░░ 51%` |
| 5 | `experiment/local.topologicalSort` | 51.12GB | 213/236 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 46.33GB | 181/236 | `█████░░░░░░░░░░ 37%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 30.93GB | 158/236 | `███░░░░░░░░░░░░ 25%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 29.05GB | 211/236 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/236 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `fmt.Sprintf` | 21.74GB | 83/236 | `██░░░░░░░░░░░░░ 17%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.2x avg)
