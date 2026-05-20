# Overview: prod
*Last updated: 2026-05-20 14:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T14:00 (237 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,790 | avg: 15,499 | max: 84,644 | trend: INCREASING (+3.23/hr))
```
▁▁▁▂▁▁▁▁▂▂▂▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▁▁▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▁▁▄▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▄█▁▁▁▁▁▁▁
```

**Heap InUse** (current: 191.9MB | avg: 231.0MB | max: 1896.6MB | trend: stable (+0.12MB/hr))
```
▂▁▂▃▂▂▂▃▃▃▂▅▂▂▂▁▂▂▂▁▂▂▁▃▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▂▂▁▁▁▂▃▂▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂█▂▂▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,790 | 14,787 | +3 | 15,499 | 84,644 | INCREASING (+3.23/hr) |
| Heap InUse | 191.9MB | 156.1MB | +35.8MB | 231.0MB | 1896.6MB | stable (+0.12MB/hr) |
| Heap Sys | 955.4MB | 820.7MB | +134.7MB | 4385.4MB | 6579.6MB | |
| Heap Objects | 984,238 | 670,222 | +314016 | 980,799 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 29 | 16,260 | 234.5MB | 958.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 5.56MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 4.5MB |
| 6 | `dotlapse-event-service/workerpool.NewWorker` | 3.5MB |
| 7 | `compress/flate.NewWriter` | 2.64MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 9.6GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 5.8GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 5.72GB |
| 4 | `experiment/local.topologicalSort` | 3.78GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 3.24GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 2.96GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 1.78GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 1.42GB |
| 9 | `segmentio/kafka-go.makePartitions` | 1.2GB |
| 10 | `fmt.Sprintf` | 1.06GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/237 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/237 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 235/237 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 34.92MB | 13/237 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 24.52MB | 235/237 | `█████░░░░░░░░░░ 39%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 16.18MB | 3/237 | `███░░░░░░░░░░░░ 26%` |
| 7 | `bytes.growSlice` | 12.77MB | 150/237 | `███░░░░░░░░░░░░ 20%` |
| 8 | `net/http.(*Transport).dialConn` | 12.62MB | 4/237 | `███░░░░░░░░░░░░ 20%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.05MB | 30/237 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 231/237 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 122.08GB | 226/237 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 72.18GB | 232/237 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 72.11GB | 232/237 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 63.1GB | 224/237 | `███████░░░░░░░░ 51%` |
| 5 | `experiment/local.topologicalSort` | 50.9GB | 214/237 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 46.09GB | 182/237 | `█████░░░░░░░░░░ 37%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 30.75GB | 159/237 | `███░░░░░░░░░░░░ 25%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 28.92GB | 212/237 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/237 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `fmt.Sprintf` | 21.5GB | 84/237 | `██░░░░░░░░░░░░░ 17%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.2x avg)
