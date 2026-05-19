# Overview: prod
*Last updated: 2026-05-19 23:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T23:30 (208 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 17,638 | avg: 15,393 | max: 84,644 | trend: decreasing (-2.58/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▅▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▂▃▄▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▄▁▁▁▁▁▁▁▁▁▂▁▁▂▁▃▁▁▁▁▁▁▂
```

**Heap InUse** (current: 341.6MB | avg: 230.5MB | max: 1896.6MB | trend: stable (+0.14MB/hr))
```
▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▃▃▅▃▂▃▂▂▃▄▃▃▂▃▄▃▃▂▄▄▄▃█▂▃▃▂▃▃▃▂▃▂▂▄▁▁▁▁▁▁▁▄▁▁▁▁▁▁▂▇▂▁▂▁▅▁▁▂▂▂▁▂▃▅▃▂▁▂▂▃▂▃▁▁▁▁▃
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 20%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 17,638 | 14,249 | +3389 | 15,393 | 84,644 | decreasing (-2.58/hr) |
| Heap InUse | 341.6MB | 152.3MB | +189.3MB | 230.5MB | 1896.6MB | stable (+0.14MB/hr) |
| Heap Sys | 4944.0MB | 4943.7MB | +0.3MB | 4518.0MB | 6579.6MB | |
| Heap Objects | 1,652,582 | 472,386 | +1180196 | 983,445 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 23.12MB |
| 3 | `runtime.mallocgc` | 20.22MB |
| 4 | `bufio.NewReaderSize` | 11.57MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `bufio.NewWriterSize` | 9.05MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 8 | `aes/gcm.NewGCMForTLS13` | 5.5MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.52MB |
| 10 | `net/http.(*Transport).queueForIdleConn` | 3.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 236.22GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 142.04GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 141.78GB |
| 4 | `experiment/local.topologicalSort` | 94.22GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 73.49GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 65.39GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 44.9GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 30.06GB |
| 9 | `fmt.Sprintf` | 24.24GB |
| 10 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 22.31GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 69.11MB | 6/208 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.54MB | 11/208 | `█████████░░░░░░ 65%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 206/208 | `███████░░░░░░░░ 53%` |
| 4 | `database/sql.convertAssignRows` | 35.58MB | 12/208 | `███████░░░░░░░░ 51%` |
| 5 | `runtime.mallocgc` | 25.61MB | 206/208 | `█████░░░░░░░░░░ 37%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/208 | `████░░░░░░░░░░░ 26%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/208 | `██░░░░░░░░░░░░░ 19%` |
| 8 | `bytes.growSlice` | 11.94MB | 130/208 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.05MB | 21/208 | `██░░░░░░░░░░░░░ 15%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 204/208 | `██░░░░░░░░░░░░░ 13%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 123.31GB | 197/208 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 72.75GB | 203/208 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 72.66GB | 203/208 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 66.19GB | 198/208 | `████████░░░░░░░ 53%` |
| 5 | `experiment/local.topologicalSort` | 51.78GB | 185/208 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 48.09GB | 153/208 | `█████░░░░░░░░░░ 38%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 32.54GB | 131/208 | `███░░░░░░░░░░░░ 26%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 30.0GB | 189/208 | `███░░░░░░░░░░░░ 24%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/208 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `fmt.Sprintf` | 23.41GB | 68/208 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
