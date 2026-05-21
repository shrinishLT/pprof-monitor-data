# Overview: prod
*Last updated: 2026-05-22 01:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-22T01:30 (329 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,043 | avg: 15,783 | max: 84,644 | trend: INCREASING (+8.20/hr))
```
▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 257.5MB | avg: 242.4MB | max: 1896.6MB | trend: stable (+0.35MB/hr))
```
▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▁▁▁▂▂▁▄▂▁▁▂▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▂▃▁▁▃▃▁▁▁▂▂▁▁▂▂▂▃▃▂▂▁▂▂▂▂▂▁▂▂▂▁▂▂▂▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,043 | 18,366 | -3323 | 15,783 | 84,644 | INCREASING (+8.20/hr) |
| Heap InUse | 257.5MB | 312.9MB | -55.4MB | 242.4MB | 1896.6MB | stable (+0.35MB/hr) |
| Heap Sys | 4876.2MB | 4875.4MB | +0.8MB | 4284.5MB | 6579.6MB | |
| Heap Objects | 1,240,165 | 702,415 | +537750 | 1,012,980 | 8,100,802 | |

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
| 2026-05-22 | 5 | 16,049 | 261.1MB | 312.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 35.36MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 7.0MB |
| 5 | `bytes.growSlice` | 6.03MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 5.02MB |
| 7 | `reflect.unsafe_NewArray` | 4.02MB |
| 8 | `segmentio/kafka-go.makePartitions` | 3.54MB |
| 9 | `bufio.NewReaderSize` | 3.53MB |
| 10 | `compress/flate.NewWriter` | 3.53MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 278.58GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 166.95GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 166.61GB |
| 4 | `experiment/local.topologicalSort` | 110.41GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 87.03GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 52.92GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 52.86GB |
| 8 | `fmt.Sprintf` | 29.51GB |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 24.42GB |
| 10 | `segmentio/kafka-go.makePartitions` | 20.46GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.01MB | 8/329 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.22MB | 14/329 | `███████████░░░░ 79%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 327/329 | `█████████░░░░░░ 63%` |
| 4 | `database/sql.convertAssignRows` | 32.63MB | 16/329 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 25.27MB | 327/329 | `██████░░░░░░░░░ 43%` |
| 6 | `bytes.growSlice` | 13.89MB | 236/329 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/329 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/329 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/329 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.53MB | 47/329 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 121.71GB | 318/329 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 72.26GB | 324/329 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 72.26GB | 324/329 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 52.64GB | 305/329 | `██████░░░░░░░░░ 43%` |
| 5 | `experiment/local.topologicalSort` | 50.04GB | 306/329 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.37GB | 274/329 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.03GB | 250/329 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 25.62GB | 268/329 | `███░░░░░░░░░░░░ 21%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/329 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `fmt.Sprintf` | 18.0GB | 153/329 | `██░░░░░░░░░░░░░ 14%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.2x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
