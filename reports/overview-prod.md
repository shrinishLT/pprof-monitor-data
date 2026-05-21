# Overview: prod
*Last updated: 2026-05-21 19:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T19:02 (310 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 17,973 | avg: 15,733 | max: 84,644 | trend: INCREASING (+7.78/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 339.8MB | avg: 239.4MB | max: 1896.6MB | trend: stable (+0.30MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▇▂▂▁▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▂▁▁▂▂▁▄▂▁▁▂▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▂▃▁▁▃▃▁▁▁▂▂▂▁▂▂▂
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 21%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 17,973 | 17,432 | +541 | 15,733 | 84,644 | INCREASING (+7.78/hr) |
| Heap InUse | 339.8MB | 344.8MB | -5.0MB | 239.4MB | 1896.6MB | stable (+0.30MB/hr) |
| Heap Sys | 4880.2MB | 4880.9MB | -0.7MB | 4247.9MB | 6579.6MB | |
| Heap Objects | 1,332,384 | 1,450,526 | -118142 | 1,007,345 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 54 | 15,881 | 257.8MB | 501.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 35.36MB |
| 3 | `bytes.growSlice` | 24.18MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.56MB |
| 5 | `bufio.NewReaderSize` | 11.54MB |
| 6 | `bufio.NewWriterSize` | 11.05MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `aes/gcm.NewGCMForTLS13` | 7.51MB |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 7.0MB |
| 10 | `net/http.(*Transport).tryPutIdleConn` | 3.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 168.33GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 100.89GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 100.87GB |
| 4 | `experiment/local.topologicalSort` | 66.55GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 52.73GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 32.0GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 29.83GB |
| 8 | `fmt.Sprintf` | 17.14GB |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 13.69GB |
| 10 | `segmentio/kafka-go.makePartitions` | 11.81GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.01MB | 8/310 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.22MB | 14/310 | `███████████░░░░ 79%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 308/310 | `█████████░░░░░░ 63%` |
| 4 | `database/sql.convertAssignRows` | 32.63MB | 16/310 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 24.64MB | 308/310 | `██████░░░░░░░░░ 42%` |
| 6 | `net/http.(*Transport).dialConn` | 13.7MB | 5/310 | `███░░░░░░░░░░░░ 23%` |
| 7 | `bytes.growSlice` | 13.62MB | 219/310 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/310 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/310 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.66MB | 46/310 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 114.27GB | 299/310 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 67.86GB | 305/310 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 67.83GB | 305/310 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 53.59GB | 286/310 | `███████░░░░░░░░ 46%` |
| 5 | `experiment/local.topologicalSort` | 47.09GB | 287/310 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 41.04GB | 255/310 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 26.6GB | 231/310 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 26.14GB | 251/310 | `███░░░░░░░░░░░░ 22%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/310 | `███░░░░░░░░░░░░ 21%` |
| 10 | `segmentio/kafka-go.makePartitions` | 17.43GB | 154/310 | `██░░░░░░░░░░░░░ 15%` |

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
