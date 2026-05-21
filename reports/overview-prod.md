# Overview: prod
*Last updated: 2026-05-21 20:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T20:02 (314 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,861 | avg: 15,768 | max: 84,644 | trend: INCREASING (+8.80/hr))
```
▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁
```

**Heap InUse** (current: 292.9MB | avg: 241.4MB | max: 1896.6MB | trend: stable (+0.37MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▂▇▂▂▁▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▂▁▁▂▂▁▄▂▁▁▂▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▂▃▁▁▃▃▁▁▁▂▂▂▁▂▂▂▃▃▃▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,861 | 17,593 | -1732 | 15,768 | 84,644 | INCREASING (+8.80/hr) |
| Heap InUse | 292.9MB | 368.8MB | -75.9MB | 241.4MB | 1896.6MB | stable (+0.37MB/hr) |
| Heap Sys | 4876.6MB | 4877.1MB | -0.5MB | 4255.9MB | 6579.6MB | |
| Heap Objects | 1,106,416 | 1,377,413 | -270997 | 1,015,907 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 58 | 16,060 | 267.5MB | 501.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 35.36MB |
| 3 | `bytes.growSlice` | 13.07MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 7.0MB |
| 6 | `segmentio/kafka-go.makePartitions` | 4.01MB |
| 7 | `bufio.NewWriterSize` | 3.03MB |
| 8 | `bufio.NewReaderSize` | 3.01MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 204.43GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 122.73GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 122.38GB |
| 4 | `experiment/local.topologicalSort` | 80.99GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 63.97GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 38.92GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 29.87GB |
| 8 | `fmt.Sprintf` | 21.26GB |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 13.71GB |
| 10 | `internal/evaluation.coerceString` | 13.27GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.01MB | 8/314 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.22MB | 14/314 | `███████████░░░░ 79%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 312/314 | `█████████░░░░░░ 63%` |
| 4 | `database/sql.convertAssignRows` | 32.63MB | 16/314 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 24.78MB | 312/314 | `██████░░░░░░░░░ 42%` |
| 6 | `bytes.growSlice` | 13.89MB | 223/314 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/314 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/314 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/314 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.66MB | 46/314 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 115.33GB | 303/314 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 68.49GB | 309/314 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 68.47GB | 309/314 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 53.26GB | 290/314 | `██████░░░░░░░░░ 46%` |
| 5 | `experiment/local.topologicalSort` | 47.51GB | 291/314 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 41.35GB | 259/314 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 26.78GB | 235/314 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 25.94GB | 255/314 | `███░░░░░░░░░░░░ 22%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/314 | `███░░░░░░░░░░░░ 20%` |
| 10 | `segmentio/kafka-go.makePartitions` | 17.34GB | 157/314 | `██░░░░░░░░░░░░░ 15%` |

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
