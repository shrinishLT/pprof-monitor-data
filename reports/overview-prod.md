# Overview: prod
*Last updated: 2026-05-21 22:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T22:31 (320 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,140 | avg: 15,787 | max: 84,644 | trend: INCREASING (+9.06/hr))
```
▁▁▁▁▃▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 301.7MB | avg: 242.1MB | max: 1896.6MB | trend: stable (+0.37MB/hr))
```
▁▁▁▁▂▇▂▂▁▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▁▁▁▂▂▁▄▂▁▁▂▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▂▃▁▁▃▃▁▁▁▂▂▁▁▂▂▂▃▃▂▂▁▂▂▂▂▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 19%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,140 | 18,115 | -1975 | 15,787 | 84,644 | INCREASING (+9.06/hr) |
| Heap InUse | 301.7MB | 275.3MB | +26.4MB | 242.1MB | 1896.6MB | stable (+0.37MB/hr) |
| Heap Sys | 4884.9MB | 4881.6MB | +3.3MB | 4267.6MB | 6579.6MB | |
| Heap Objects | 1,262,813 | 718,530 | +544283 | 1,015,442 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 64 | 16,132 | 268.5MB | 501.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 35.36MB |
| 3 | `bytes.growSlice` | 14.13MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 8.54MB |
| 6 | `bufio.NewReaderSize` | 7.04MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 7.0MB |
| 8 | `bufio.NewWriterSize` | 5.02MB |
| 9 | `segmentio/kafka-go.makePartitions` | 3.03MB |
| 10 | `net/http.(*http2Framer).startWriteDataPadded` | 3.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 250.56GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 150.35GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 149.91GB |
| 4 | `experiment/local.topologicalSort` | 99.3GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 78.36GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 47.64GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 34.83GB |
| 8 | `fmt.Sprintf` | 26.23GB |
| 9 | `segmentio/kafka-go.makePartitions` | 16.6GB |
| 10 | `internal/evaluation.coerceString` | 16.25GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.01MB | 8/320 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.22MB | 14/320 | `███████████░░░░ 79%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 318/320 | `█████████░░░░░░ 63%` |
| 4 | `database/sql.convertAssignRows` | 32.63MB | 16/320 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 24.98MB | 318/320 | `██████░░░░░░░░░ 43%` |
| 6 | `bytes.growSlice` | 13.98MB | 229/320 | `███░░░░░░░░░░░░ 24%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/320 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/320 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/320 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.66MB | 46/320 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 117.59GB | 309/320 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 69.83GB | 315/320 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 69.81GB | 315/320 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 52.87GB | 296/320 | `██████░░░░░░░░░ 44%` |
| 5 | `experiment/local.topologicalSort` | 48.4GB | 297/320 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 42.05GB | 265/320 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 27.21GB | 241/320 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 25.79GB | 259/320 | `███░░░░░░░░░░░░ 21%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/320 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.Sprintf` | 17.39GB | 144/320 | `██░░░░░░░░░░░░░ 14%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
