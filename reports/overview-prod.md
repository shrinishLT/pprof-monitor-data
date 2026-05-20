# Overview: prod
*Last updated: 2026-05-20 19:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T19:30 (248 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,678 | avg: 15,509 | max: 84,644 | trend: INCREASING (+3.30/hr))
```
▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▁▁▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▁▁▄▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▄█▁▁▁▁▁▁▁▁▁▁▂▁▃▁▁▁▁▁
```

**Heap InUse** (current: 223.6MB | avg: 230.7MB | max: 1896.6MB | trend: stable (+0.10MB/hr))
```
▅▂▂▂▁▂▂▂▁▂▂▁▃▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▂▂▁▁▁▂▃▂▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂█▂▂▁▁▁▁▁▁▁▁▂▁▃▂▁▁▂▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,678 | 15,998 | -320 | 15,509 | 84,644 | INCREASING (+3.30/hr) |
| Heap InUse | 223.6MB | 256.1MB | -32.5MB | 230.7MB | 1896.6MB | stable (+0.10MB/hr) |
| Heap Sys | 4976.3MB | 4974.1MB | +2.2MB | 4337.0MB | 6579.6MB | |
| Heap Objects | 1,052,432 | 1,324,641 | -272209 | 982,377 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 40 | 16,114 | 232.1MB | 958.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 15.63MB |
| 3 | `bytes.growSlice` | 10.56MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `bufio.NewReaderSize` | 6.04MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 4.5MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.02MB |
| 8 | `dotlapse-event-service/workerpool.NewWorker` | 3.5MB |
| 9 | `compress/flate.NewWriter` | 2.64MB |
| 10 | `aes/gcm.NewGCMForTLS13` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 110.45GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 66.77GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 66.32GB |
| 4 | `experiment/local.topologicalSort` | 44.12GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.62GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 20.96GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 19.75GB |
| 8 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 12.34GB |
| 9 | `fmt.Sprintf` | 12.27GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 8.97GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/248 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/248 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 246/248 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 32.79MB | 14/248 | `███████░░░░░░░░ 52%` |
| 5 | `runtime.mallocgc` | 24.06MB | 246/248 | `█████░░░░░░░░░░ 38%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 13.01MB | 4/248 | `███░░░░░░░░░░░░ 20%` |
| 7 | `bytes.growSlice` | 12.64MB | 161/248 | `███░░░░░░░░░░░░ 20%` |
| 8 | `net/http.(*Transport).dialConn` | 12.62MB | 4/248 | `███░░░░░░░░░░░░ 20%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.03MB | 31/248 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/248 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 119.46GB | 237/248 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 70.7GB | 243/248 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 70.65GB | 243/248 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 60.74GB | 235/248 | `███████░░░░░░░░ 50%` |
| 5 | `experiment/local.topologicalSort` | 49.69GB | 225/248 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 44.64GB | 193/248 | `█████░░░░░░░░░░ 37%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 29.57GB | 170/248 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 27.98GB | 221/248 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/248 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.Sprintf` | 19.85GB | 95/248 | `██░░░░░░░░░░░░░ 16%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.2x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.2x avg)
