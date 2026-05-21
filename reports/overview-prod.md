# Overview: prod
*Last updated: 2026-05-21 19:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T19:30 (311 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 20,141 | avg: 15,747 | max: 84,644 | trend: INCREASING (+8.25/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂
```

**Heap InUse** (current: 469.0MB | avg: 240.1MB | max: 1896.6MB | trend: stable (+0.33MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▂▇▂▂▁▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▂▁▁▂▂▁▄▂▁▁▂▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▂▃▁▁▃▃▁▁▁▂▂▂▁▂▂▂▃
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 23%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 20,141 | 17,973 | +2168 | 15,747 | 84,644 | INCREASING (+8.25/hr) |
| Heap InUse | 469.0MB | 339.8MB | +129.2MB | 240.1MB | 1896.6MB | stable (+0.33MB/hr) |
| Heap Sys | 4875.8MB | 4880.2MB | -4.4MB | 4249.9MB | 6579.6MB | |
| Heap Objects | 2,171,838 | 1,332,384 | +839454 | 1,011,089 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 55 | 15,958 | 261.6MB | 501.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 36.25MB |
| 3 | `runtime.mallocgc` | 35.36MB |
| 4 | `bufio.NewReaderSize` | 20.08MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 17.08MB |
| 6 | `bufio.NewWriterSize` | 15.57MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `aes/gcm.NewGCMForTLS13` | 8.01MB |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 7.0MB |
| 10 | `crypto/tls.Client` | 4.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 185.48GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 111.34GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 111.22GB |
| 4 | `experiment/local.topologicalSort` | 73.46GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 58.22GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 35.33GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 29.84GB |
| 8 | `fmt.Sprintf` | 19.11GB |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 13.7GB |
| 10 | `segmentio/kafka-go.makePartitions` | 12.44GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.01MB | 8/311 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.22MB | 14/311 | `███████████░░░░ 79%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 309/311 | `█████████░░░░░░ 63%` |
| 4 | `database/sql.convertAssignRows` | 32.63MB | 16/311 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 24.68MB | 309/311 | `██████░░░░░░░░░ 42%` |
| 6 | `bytes.growSlice` | 13.72MB | 220/311 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/311 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/311 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/311 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.66MB | 46/311 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 114.51GB | 300/311 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 68.0GB | 306/311 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 67.98GB | 306/311 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 53.5GB | 287/311 | `███████░░░░░░░░ 46%` |
| 5 | `experiment/local.topologicalSort` | 47.18GB | 288/311 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 41.11GB | 256/311 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 26.64GB | 232/311 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 26.09GB | 252/311 | `███░░░░░░░░░░░░ 22%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/311 | `███░░░░░░░░░░░░ 21%` |
| 10 | `segmentio/kafka-go.makePartitions` | 17.4GB | 155/311 | `██░░░░░░░░░░░░░ 15%` |

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
