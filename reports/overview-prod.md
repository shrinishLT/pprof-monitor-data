# Overview: prod
*Last updated: 2026-05-21 15:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T15:30 (299 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 19,768 | avg: 15,719 | max: 84,644 | trend: INCREASING (+8.10/hr))
```
▁▁▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂
```

**Heap InUse** (current: 417.1MB | avg: 237.9MB | max: 1896.6MB | trend: stable (+0.28MB/hr))
```
▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▇▂▂▁▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▂▁▁▂▂▁▄▂▁▁▂▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▂▃▁▁▃
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 23%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 19,768 | 14,698 | +5070 | 15,719 | 84,644 | INCREASING (+8.10/hr) |
| Heap InUse | 417.1MB | 207.8MB | +209.3MB | 237.9MB | 1896.6MB | stable (+0.28MB/hr) |
| Heap Sys | 4878.1MB | 4881.4MB | -3.3MB | 4224.7MB | 6579.6MB | |
| Heap Objects | 1,746,317 | 676,932 | +1069385 | 1,002,529 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 43 | 15,824 | 252.2MB | 501.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 35.36MB |
| 3 | `bytes.growSlice` | 31.96MB |
| 4 | `bufio.NewWriterSize` | 18.57MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.56MB |
| 6 | `bufio.NewReaderSize` | 12.05MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 7.0MB |
| 9 | `net/http.(*Transport).queueForIdleConn` | 5.0MB |
| 10 | `net/http.(*http2Framer).startWriteDataPadded` | 3.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 109.77GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 65.83GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 65.69GB |
| 4 | `experiment/local.topologicalSort` | 43.58GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.45GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 20.9GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 19.93GB |
| 8 | `fmt.Sprintf` | 10.94GB |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 9.2GB |
| 10 | `reflect.growslice` | 7.41GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.01MB | 8/299 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.22MB | 14/299 | `███████████░░░░ 79%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 297/299 | `█████████░░░░░░ 63%` |
| 4 | `database/sql.convertAssignRows` | 32.63MB | 16/299 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 24.25MB | 297/299 | `██████░░░░░░░░░ 41%` |
| 6 | `net/http.(*Transport).dialConn` | 13.7MB | 5/299 | `███░░░░░░░░░░░░ 23%` |
| 7 | `bytes.growSlice` | 13.63MB | 208/299 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 13.61MB | 5/299 | `███░░░░░░░░░░░░ 23%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.82MB | 44/299 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/299 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 113.29GB | 288/299 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 67.26GB | 294/299 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 67.24GB | 294/299 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 54.76GB | 275/299 | `███████░░░░░░░░ 48%` |
| 5 | `experiment/local.topologicalSort` | 46.76GB | 276/299 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 40.91GB | 244/299 | `█████░░░░░░░░░░ 36%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 26.83GB | 240/299 | `███░░░░░░░░░░░░ 23%` |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 26.6GB | 220/299 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/299 | `███░░░░░░░░░░░░ 21%` |
| 10 | `segmentio/kafka-go.makePartitions` | 17.89GB | 145/299 | `██░░░░░░░░░░░░░ 15%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
