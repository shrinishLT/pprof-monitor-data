# Overview: prod
*Last updated: 2026-05-21 10:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T10:02 (283 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 22,203 | avg: 15,698 | max: 84,644 | trend: INCREASING (+8.62/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂
```

**Heap InUse** (current: 286.4MB | avg: 235.3MB | max: 1896.6MB | trend: stable (+0.21MB/hr))
```
▁▂▂▁▁▁▂▃▂▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▇▂▂▁▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▂▁▁▂▂▁▄▂▁▁▂▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▂▂
```

## Current Status

Goroutines: `█████░░░░░░░░░░░░░░░ 26%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 22,203 | 20,983 | +1220 | 15,698 | 84,644 | INCREASING (+8.62/hr) |
| Heap InUse | 286.4MB | 351.6MB | -65.2MB | 235.3MB | 1896.6MB | stable (+0.21MB/hr) |
| Heap Sys | 3754.1MB | 3757.2MB | -3.1MB | 4219.0MB | 6579.6MB | |
| Heap Objects | 669,086 | 1,603,104 | -934018 | 994,308 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 27 | 15,670 | 233.3MB | 501.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 34.17MB |
| 3 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 20.09MB |
| 4 | `bufio.NewWriterSize` | 19.07MB |
| 5 | `runtime.mallocgc` | 14.01MB |
| 6 | `bufio.NewReaderSize` | 12.05MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `aes/gcm.NewGCMForTLS13` | 6.51MB |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 10 | `net/http.(*Transport).queueForIdleConn` | 5.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 156.99GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 94.73GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 94.38GB |
| 4 | `experiment/local.topologicalSort` | 62.96GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 49.81GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 38.53GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 30.09GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 17.96GB |
| 9 | `reflect.growslice` | 15.89GB |
| 10 | `jackskj/carta.getUniqueId` | 13.55GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.01MB | 8/283 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.22MB | 14/283 | `███████████░░░░ 79%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 281/283 | `█████████░░░░░░ 63%` |
| 4 | `database/sql.convertAssignRows` | 32.63MB | 16/283 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 23.61MB | 281/283 | `██████░░░░░░░░░ 40%` |
| 6 | `net/http.(*Transport).dialConn` | 13.7MB | 5/283 | `███░░░░░░░░░░░░ 23%` |
| 7 | `bytes.growSlice` | 13.69MB | 192/283 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 13.61MB | 5/283 | `███░░░░░░░░░░░░ 23%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.87MB | 42/283 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/283 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 116.25GB | 272/283 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 68.96GB | 278/283 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 68.93GB | 278/283 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 57.09GB | 261/283 | `███████░░░░░░░░ 49%` |
| 5 | `experiment/local.topologicalSort` | 48.1GB | 260/283 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 42.39GB | 228/283 | `█████░░░░░░░░░░ 36%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 27.74GB | 204/283 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 27.05GB | 237/283 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/283 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.Sprintf` | 17.98GB | 114/283 | `██░░░░░░░░░░░░░ 15%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.3x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
