# Overview: prod
*Last updated: 2026-05-21 19:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T19:31 (312 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 20,320 | avg: 15,761 | max: 84,644 | trend: INCREASING (+8.74/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂
```

**Heap InUse** (current: 464.6MB | avg: 240.8MB | max: 1896.6MB | trend: stable (+0.35MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▂▇▂▂▁▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▂▁▁▂▂▁▄▂▁▁▂▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▂▃▁▁▃▃▁▁▁▂▂▂▁▂▂▂▃▃
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 24%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 20,320 | 20,141 | +179 | 15,761 | 84,644 | INCREASING (+8.74/hr) |
| Heap InUse | 464.6MB | 469.0MB | -4.4MB | 240.8MB | 1896.6MB | stable (+0.35MB/hr) |
| Heap Sys | 4876.2MB | 4875.8MB | +0.4MB | 4251.9MB | 6579.6MB | |
| Heap Objects | 2,062,232 | 2,171,838 | -109606 | 1,014,458 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 56 | 16,036 | 265.2MB | 501.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 35.36MB |
| 3 | `bytes.growSlice` | 35.18MB |
| 4 | `bufio.NewWriterSize` | 18.08MB |
| 5 | `bufio.NewReaderSize` | 15.56MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 15.07MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `aes/gcm.NewGCMForTLS13` | 7.51MB |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 7.0MB |
| 10 | `net/http.(*http2Framer).startWriteDataPadded` | 5.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 186.27GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 111.81GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 111.67GB |
| 4 | `experiment/local.topologicalSort` | 73.78GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 58.46GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 35.46GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 29.84GB |
| 8 | `fmt.Sprintf` | 19.22GB |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 13.7GB |
| 10 | `segmentio/kafka-go.makePartitions` | 12.46GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.01MB | 8/312 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.22MB | 14/312 | `███████████░░░░ 79%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 310/312 | `█████████░░░░░░ 63%` |
| 4 | `database/sql.convertAssignRows` | 32.63MB | 16/312 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 24.71MB | 310/312 | `██████░░░░░░░░░ 42%` |
| 6 | `bytes.growSlice` | 13.82MB | 221/312 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/312 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/312 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/312 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.66MB | 46/312 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 114.75GB | 301/312 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 68.14GB | 307/312 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 68.12GB | 307/312 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 53.42GB | 288/312 | `██████░░░░░░░░░ 46%` |
| 5 | `experiment/local.topologicalSort` | 47.28GB | 289/312 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 41.18GB | 257/312 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 26.68GB | 233/312 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 26.04GB | 253/312 | `███░░░░░░░░░░░░ 22%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/312 | `███░░░░░░░░░░░░ 21%` |
| 10 | `segmentio/kafka-go.makePartitions` | 17.37GB | 156/312 | `██░░░░░░░░░░░░░ 15%` |

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
