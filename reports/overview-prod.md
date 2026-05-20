# Overview: prod
*Last updated: 2026-05-20 17:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T17:00 (243 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 19,980 | avg: 15,516 | max: 84,644 | trend: INCREASING (+3.83/hr))
```
▁▁▂▂▂▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▁▁▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▁▁▄▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▄█▁▁▁▁▁▁▁▁▁▁▂▁▃
```

**Heap InUse** (current: 438.9MB | avg: 231.2MB | max: 1896.6MB | trend: stable (+0.13MB/hr))
```
▂▃▃▃▂▅▂▂▂▁▂▂▂▁▂▂▁▃▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▂▂▁▁▁▂▃▂▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂█▂▂▁▁▁▁▁▁▁▁▂▁▃
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 23%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 19,980 | 14,942 | +5038 | 15,516 | 84,644 | INCREASING (+3.83/hr) |
| Heap InUse | 438.9MB | 213.8MB | +225.1MB | 231.2MB | 1896.6MB | stable (+0.13MB/hr) |
| Heap Sys | 4968.7MB | 1347.6MB | +3621.1MB | 4323.9MB | 6579.6MB | |
| Heap Objects | 2,281,833 | 1,081,099 | +1200734 | 983,441 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 35 | 16,246 | 235.8MB | 958.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 36.19MB |
| 3 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 21.6MB |
| 4 | `bufio.NewWriterSize` | 19.09MB |
| 5 | `bufio.NewReaderSize` | 16.07MB |
| 6 | `runtime.mallocgc` | 14.1MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `aes/gcm.NewGCMForTLS13` | 8.01MB |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 4.5MB |
| 10 | `net/http.(*Transport).tryPutIdleConn` | 3.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 72.12GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 43.61GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 43.35GB |
| 4 | `experiment/local.topologicalSort` | 28.74GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 22.81GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 15.12GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 13.81GB |
| 8 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 8.28GB |
| 9 | `fmt.Sprintf` | 7.93GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 6.79GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/243 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/243 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 241/243 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 32.79MB | 14/243 | `███████░░░░░░░░ 52%` |
| 5 | `runtime.mallocgc` | 24.24MB | 241/243 | `█████░░░░░░░░░░ 39%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 13.01MB | 4/243 | `███░░░░░░░░░░░░ 20%` |
| 7 | `bytes.growSlice` | 12.78MB | 156/243 | `███░░░░░░░░░░░░ 20%` |
| 8 | `net/http.(*Transport).dialConn` | 12.62MB | 4/243 | `███░░░░░░░░░░░░ 20%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.05MB | 30/243 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/243 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 119.97GB | 232/243 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 70.98GB | 238/243 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 70.92GB | 238/243 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 61.69GB | 230/243 | `███████░░░░░░░░ 51%` |
| 5 | `experiment/local.topologicalSort` | 49.95GB | 220/243 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 45.03GB | 188/243 | `█████░░░░░░░░░░ 37%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 29.91GB | 165/243 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 28.35GB | 217/243 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/243 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.Sprintf` | 20.36GB | 90/243 | `██░░░░░░░░░░░░░ 16%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.2x avg)
