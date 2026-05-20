# Overview: prod
*Last updated: 2026-05-20 19:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T19:02 (247 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,998 | avg: 15,509 | max: 84,644 | trend: INCREASING (+3.30/hr))
```
▂▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▁▁▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▁▁▄▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▄█▁▁▁▁▁▁▁▁▁▁▂▁▃▁▁▁▁
```

**Heap InUse** (current: 256.1MB | avg: 230.8MB | max: 1896.6MB | trend: stable (+0.10MB/hr))
```
▂▅▂▂▂▁▂▂▂▁▂▂▁▃▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▂▂▁▁▁▂▃▂▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂█▂▂▁▁▁▁▁▁▁▁▂▁▃▂▁▁▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,998 | 15,021 | +977 | 15,509 | 84,644 | INCREASING (+3.30/hr) |
| Heap InUse | 256.1MB | 188.4MB | +67.7MB | 230.8MB | 1896.6MB | stable (+0.10MB/hr) |
| Heap Sys | 4974.1MB | 4973.1MB | +1.0MB | 4334.4MB | 6579.6MB | |
| Heap Objects | 1,324,641 | 877,136 | +447505 | 982,093 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 39 | 16,125 | 232.3MB | 958.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 15.63MB |
| 3 | `bytes.growSlice` | 14.57MB |
| 4 | `bufio.NewWriterSize` | 10.55MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `bufio.NewReaderSize` | 9.05MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 7.03MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 4.5MB |
| 9 | `dotlapse-event-service/workerpool.NewWorker` | 3.5MB |
| 10 | `aes/gcm.NewGCMForTLS13` | 3.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 103.46GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 62.52GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 62.12GB |
| 4 | `experiment/local.topologicalSort` | 41.3GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 32.39GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 19.71GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 19.65GB |
| 8 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 11.6GB |
| 9 | `fmt.Sprintf` | 11.45GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 8.95GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/247 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/247 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 245/247 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 32.79MB | 14/247 | `███████░░░░░░░░ 52%` |
| 5 | `runtime.mallocgc` | 24.1MB | 245/247 | `█████░░░░░░░░░░ 38%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 13.01MB | 4/247 | `███░░░░░░░░░░░░ 20%` |
| 7 | `bytes.growSlice` | 12.65MB | 160/247 | `███░░░░░░░░░░░░ 20%` |
| 8 | `net/http.(*Transport).dialConn` | 12.62MB | 4/247 | `███░░░░░░░░░░░░ 20%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.03MB | 31/247 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/247 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 119.5GB | 236/247 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 70.72GB | 242/247 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 70.66GB | 242/247 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 60.91GB | 234/247 | `███████░░░░░░░░ 50%` |
| 5 | `experiment/local.topologicalSort` | 49.72GB | 224/247 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 44.69GB | 192/247 | `█████░░░░░░░░░░ 37%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 29.62GB | 169/247 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 28.06GB | 220/247 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/247 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.Sprintf` | 19.93GB | 94/247 | `██░░░░░░░░░░░░░ 16%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.2x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.2x avg)
