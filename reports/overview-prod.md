# Overview: prod
*Last updated: 2026-05-21 18:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T18:02 (306 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,977 | avg: 15,721 | max: 84,644 | trend: INCREASING (+7.64/hr))
```
▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁
```

**Heap InUse** (current: 242.2MB | avg: 238.6MB | max: 1896.6MB | trend: stable (+0.28MB/hr))
```
▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▇▂▂▁▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▂▁▁▂▂▁▄▂▁▁▂▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▂▃▁▁▃▃▁▁▁▂▂▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,977 | 14,874 | +103 | 15,721 | 84,644 | INCREASING (+7.64/hr) |
| Heap InUse | 242.2MB | 251.0MB | -8.8MB | 238.6MB | 1896.6MB | stable (+0.28MB/hr) |
| Heap Sys | 4880.2MB | 4880.0MB | +0.2MB | 4239.7MB | 6579.6MB | |
| Heap Objects | 983,019 | 1,125,095 | -142076 | 1,004,521 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 50 | 15,823 | 254.4MB | 501.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 35.36MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 7.0MB |
| 5 | `bytes.growSlice` | 5.03MB |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 3.17MB |
| 7 | `internal/evaluation.mergeMetadata` | 3.0MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.01MB |
| 10 | `bufio.NewReaderSize` | 2.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 152.38GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 91.45GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 91.39GB |
| 4 | `experiment/local.topologicalSort` | 60.34GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 47.83GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 28.91GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 24.88GB |
| 8 | `fmt.Sprintf` | 15.55GB |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 11.45GB |
| 10 | `segmentio/kafka-go.makePartitions` | 10.46GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.01MB | 8/306 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.22MB | 14/306 | `███████████░░░░ 79%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 304/306 | `█████████░░░░░░ 63%` |
| 4 | `database/sql.convertAssignRows` | 32.63MB | 16/306 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 24.5MB | 304/306 | `██████░░░░░░░░░ 42%` |
| 6 | `net/http.(*Transport).dialConn` | 13.7MB | 5/306 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).tryPutIdleConn` | 13.61MB | 5/306 | `███░░░░░░░░░░░░ 23%` |
| 8 | `bytes.growSlice` | 13.52MB | 215/306 | `███░░░░░░░░░░░░ 23%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/306 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.65MB | 45/306 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 113.61GB | 295/306 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 67.46GB | 301/306 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 67.44GB | 301/306 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 53.96GB | 282/306 | `███████░░░░░░░░ 47%` |
| 5 | `experiment/local.topologicalSort` | 46.85GB | 283/306 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 40.88GB | 251/306 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 26.52GB | 227/306 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 26.36GB | 247/306 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/306 | `███░░░░░░░░░░░░ 21%` |
| 10 | `segmentio/kafka-go.makePartitions` | 17.59GB | 150/306 | `██░░░░░░░░░░░░░ 15%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
