# Overview: prod
*Last updated: 2026-05-22 23:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-22T23:02 (373 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,352 | avg: 15,816 | max: 84,644 | trend: INCREASING (+6.61/hr))
```
▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁
```

**Heap InUse** (current: 168.1MB | avg: 240.9MB | max: 1896.6MB | trend: stable (+0.20MB/hr))
```
▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▃▃▁▁▃▃▁▁▁▂▂▁▁▂▂▂▃▃▃▂▁▂▂▂▂▂▁▂▂▂▁▂▂▂▂▃▂▁▁▁▁▁▁▁▃▁▁▁▁▁▁▂▁█▁▁▁▁▁▁▁▁▂▁▂▁▂▁▁▂▁▁▁▁▁▁▂▂▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,352 | 19,044 | -3692 | 15,816 | 84,644 | INCREASING (+6.61/hr) |
| Heap InUse | 168.1MB | 311.3MB | -143.2MB | 240.9MB | 1896.6MB | stable (+0.20MB/hr) |
| Heap Sys | 2876.7MB | 2870.5MB | +6.2MB | 4272.1MB | 6579.6MB | |
| Heap Objects | 430,642 | 673,505 | -242863 | 1,003,697 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 68 | 16,073 | 267.1MB | 501.2MB |
| 2026-05-22 | 49 | 16,060 | 233.0MB | 962.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `internal/evaluation.mergeMetadata` | 9.0MB |
| 5 | `bytes.growSlice` | 8.55MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 7 | `internal/evaluation.(*Engine).Evaluate` | 6.36MB |
| 8 | `experiment/local.topologicalSort` | 5.05MB |
| 9 | `experiment/local.(*Client).EvaluateV2` | 4.17MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.02MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 45.71GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 27.56GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 27.47GB |
| 4 | `experiment/local.topologicalSort` | 18.16GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 17.97GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 14.28GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 8.83GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 6.86GB |
| 9 | `segmentio/kafka-go.makePartitions` | 5.79GB |
| 10 | `fmt.Sprintf` | 5.33GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 57.13MB | 9/373 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 43.74MB | 15/373 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 371/373 | `█████████░░░░░░ 64%` |
| 4 | `database/sql.convertAssignRows` | 29.0MB | 19/373 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 24.83MB | 371/373 | `██████░░░░░░░░░ 43%` |
| 6 | `bytes.growSlice` | 14.06MB | 268/373 | `███░░░░░░░░░░░░ 24%` |
| 7 | `net/http.(*Transport).dialConn` | 12.08MB | 6/373 | `███░░░░░░░░░░░░ 21%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/373 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/373 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.23MB | 59/373 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 130.43GB | 362/373 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 77.49GB | 368/373 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 77.47GB | 368/373 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 53.41GB | 350/373 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 52.15GB | 349/373 | `█████░░░░░░░░░░ 39%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 45.74GB | 318/373 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 29.35GB | 294/373 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 25.27GB | 308/373 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/373 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprintf` | 18.99GB | 190/373 | `██░░░░░░░░░░░░░ 14%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
