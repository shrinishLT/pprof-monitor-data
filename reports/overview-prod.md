# Overview: prod
*Last updated: 2026-05-21 21:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T21:03 (316 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,783 | avg: 15,762 | max: 84,644 | trend: INCREASING (+8.42/hr))
```
▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁
```

**Heap InUse** (current: 260.3MB | avg: 241.4MB | max: 1896.6MB | trend: stable (+0.36MB/hr))
```
▁▁▁▁▁▁▁▁▂▇▂▂▁▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▂▁▁▂▂▁▄▂▁▁▂▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▂▃▁▁▃▃▁▁▁▂▂▂▁▂▂▂▃▃▃▂▁▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,783 | 14,963 | -180 | 15,762 | 84,644 | INCREASING (+8.42/hr) |
| Heap InUse | 260.3MB | 228.5MB | +31.8MB | 241.4MB | 1896.6MB | stable (+0.36MB/hr) |
| Heap Sys | 4879.2MB | 4878.8MB | +0.4MB | 4259.9MB | 6579.6MB | |
| Heap Objects | 1,329,793 | 845,959 | +483834 | 1,016,363 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 60 | 16,020 | 266.7MB | 501.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 35.36MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 7.0MB |
| 5 | `bytes.growSlice` | 6.53MB |
| 6 | `bufio.NewReaderSize` | 4.03MB |
| 7 | `bufio.NewWriterSize` | 3.03MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.56MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 219.54GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 131.7GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 131.4GB |
| 4 | `experiment/local.topologicalSort` | 86.98GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 68.58GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 41.72GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 34.77GB |
| 8 | `fmt.Sprintf` | 22.95GB |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 15.98GB |
| 10 | `segmentio/kafka-go.makePartitions` | 14.57GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.01MB | 8/316 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.22MB | 14/316 | `███████████░░░░ 79%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 314/316 | `█████████░░░░░░ 63%` |
| 4 | `database/sql.convertAssignRows` | 32.63MB | 16/316 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 24.85MB | 314/316 | `██████░░░░░░░░░ 42%` |
| 6 | `bytes.growSlice` | 13.82MB | 225/316 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/316 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/316 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/316 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.66MB | 46/316 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 116.0GB | 305/316 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 68.89GB | 311/316 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 68.87GB | 311/316 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 53.12GB | 292/316 | `██████░░░░░░░░░ 45%` |
| 5 | `experiment/local.topologicalSort` | 47.77GB | 293/316 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 41.55GB | 261/316 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 26.9GB | 237/316 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 25.9GB | 256/316 | `███░░░░░░░░░░░░ 22%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/316 | `███░░░░░░░░░░░░ 20%` |
| 10 | `segmentio/kafka-go.makePartitions` | 17.3GB | 159/316 | `██░░░░░░░░░░░░░ 14%` |

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
