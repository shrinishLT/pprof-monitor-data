# Overview: prod
*Last updated: 2026-05-20 14:32 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T14:32 (238 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,576 | avg: 15,499 | max: 84,644 | trend: INCREASING (+3.21/hr))
```
▁▁▂▁▁▁▁▂▂▂▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▁▁▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▁▁▄▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▄█▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 160.1MB | avg: 230.7MB | max: 1896.6MB | trend: stable (+0.10MB/hr))
```
▁▂▃▂▂▂▃▃▃▂▅▂▂▂▁▂▂▂▁▂▂▁▃▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▂▂▁▁▁▂▃▂▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂█▂▂▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,576 | 14,790 | +786 | 15,499 | 84,644 | INCREASING (+3.21/hr) |
| Heap InUse | 160.1MB | 191.9MB | -31.8MB | 230.7MB | 1896.6MB | stable (+0.10MB/hr) |
| Heap Sys | 951.6MB | 955.4MB | -3.8MB | 4371.0MB | 6579.6MB | |
| Heap Objects | 511,959 | 984,238 | -472279 | 978,829 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 30 | 16,237 | 232.0MB | 958.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 8.54MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 4.5MB |
| 6 | `dotlapse-event-service/workerpool.NewWorker` | 3.5MB |
| 7 | `bufio.NewWriterSize` | 3.01MB |
| 8 | `segmentio/kafka-go.makePartitions` | 3.01MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.51MB |
| 10 | `bufio.NewReaderSize` | 2.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 18.77GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 11.36GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 11.28GB |
| 4 | `experiment/local.topologicalSort` | 7.39GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 5.89GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 3.48GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 3.24GB |
| 8 | `fmt.Sprintf` | 2.04GB |
| 9 | `segmentio/kafka-go.makePartitions` | 1.88GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 1.42GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/238 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/238 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 236/238 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 34.92MB | 13/238 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 24.47MB | 236/238 | `█████░░░░░░░░░░ 39%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 16.18MB | 3/238 | `███░░░░░░░░░░░░ 26%` |
| 7 | `bytes.growSlice` | 12.74MB | 151/238 | `███░░░░░░░░░░░░ 20%` |
| 8 | `net/http.(*Transport).dialConn` | 12.62MB | 4/238 | `███░░░░░░░░░░░░ 20%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.05MB | 30/238 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 232/238 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 121.62GB | 227/238 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.92GB | 233/238 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.85GB | 233/238 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 62.83GB | 225/238 | `███████░░░░░░░░ 51%` |
| 5 | `experiment/local.topologicalSort` | 50.7GB | 215/238 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 45.87GB | 183/238 | `█████░░░░░░░░░░ 37%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 30.58GB | 160/238 | `███░░░░░░░░░░░░ 25%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 28.79GB | 213/238 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/238 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `fmt.Sprintf` | 21.27GB | 85/238 | `██░░░░░░░░░░░░░ 17%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.2x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.2x avg)
