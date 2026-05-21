# Overview: prod
*Last updated: 2026-05-21 21:32 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T21:32 (318 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 18,897 | avg: 15,779 | max: 84,644 | trend: INCREASING (+8.91/hr))
```
▁▁▁▁▁▁▃▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁
```

**Heap InUse** (current: 297.8MB | avg: 241.8MB | max: 1896.6MB | trend: stable (+0.37MB/hr))
```
▁▁▁▁▁▁▂▇▂▂▁▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▂▁▁▂▂▁▄▂▁▁▂▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▂▃▁▁▃▃▁▁▁▂▂▂▁▂▂▂▃▃▃▂▁▂▂▂
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 22%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 18,897 | 18,091 | +806 | 15,779 | 84,644 | INCREASING (+8.91/hr) |
| Heap InUse | 297.8MB | 304.2MB | -6.4MB | 241.8MB | 1896.6MB | stable (+0.37MB/hr) |
| Heap Sys | 4881.1MB | 4879.5MB | +1.6MB | 4263.8MB | 6579.6MB | |
| Heap Objects | 792,081 | 997,247 | -205166 | 1,015,597 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 62 | 16,100 | 267.8MB | 501.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 35.36MB |
| 3 | `bytes.growSlice` | 29.15MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 13.56MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `bufio.NewReaderSize` | 9.05MB |
| 7 | `bufio.NewWriterSize` | 8.53MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 7.0MB |
| 9 | `net/http.(*Transport).queueForIdleConn` | 6.01MB |
| 10 | `segmentio/kafka-go.makePartitions` | 3.54MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 232.04GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 139.2GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 138.84GB |
| 4 | `experiment/local.topologicalSort` | 91.97GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 72.46GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 44.13GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 34.8GB |
| 8 | `fmt.Sprintf` | 24.21GB |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 16.0GB |
| 10 | `segmentio/kafka-go.makePartitions` | 15.26GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.01MB | 8/318 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.22MB | 14/318 | `███████████░░░░ 79%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 316/318 | `█████████░░░░░░ 63%` |
| 4 | `database/sql.convertAssignRows` | 32.63MB | 16/318 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 24.92MB | 316/318 | `██████░░░░░░░░░ 42%` |
| 6 | `bytes.growSlice` | 13.92MB | 227/318 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/318 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/318 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/318 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.66MB | 46/318 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 116.75GB | 307/318 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 69.33GB | 313/318 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 69.31GB | 313/318 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 52.99GB | 294/318 | `██████░░░░░░░░░ 45%` |
| 5 | `experiment/local.topologicalSort` | 48.07GB | 295/318 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 41.79GB | 263/318 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 27.04GB | 239/318 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 25.83GB | 258/318 | `███░░░░░░░░░░░░ 22%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/318 | `███░░░░░░░░░░░░ 20%` |
| 10 | `segmentio/kafka-go.makePartitions` | 17.28GB | 161/318 | `██░░░░░░░░░░░░░ 14%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
