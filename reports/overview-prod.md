# Overview: prod
*Last updated: 2026-05-21 03:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T03:00 (263 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 17,806 | avg: 15,705 | max: 84,644 | trend: INCREASING (+10.98/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 344.5MB | avg: 237.1MB | max: 1896.6MB | trend: stable (+0.35MB/hr))
```
▁▁▁▁▁▂▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▂▂▁▁▁▂▃▂▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▇▂▂▁▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▂▁▁▂▂▁▄▂
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 21%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 17,806 | 17,977 | -171 | 15,705 | 84,644 | INCREASING (+10.98/hr) |
| Heap InUse | 344.5MB | 501.2MB | -156.7MB | 237.1MB | 1896.6MB | stable (+0.35MB/hr) |
| Heap Sys | 5106.0MB | 5103.4MB | +2.6MB | 4319.8MB | 6579.6MB | |
| Heap Objects | 1,407,822 | 1,718,114 | -310292 | 997,060 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 7 | 15,847 | 297.2MB | 501.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 37.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 27.14MB |
| 4 | `bufio.NewReaderSize` | 9.55MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 7 | `bufio.NewWriterSize` | 8.53MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 6.53MB |
| 9 | `net/http.(*Transport).queueForIdleConn` | 4.5MB |
| 10 | `segmentio/kafka-go.makePartitions` | 3.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 153.68GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 92.27GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 92.21GB |
| 4 | `experiment/local.topologicalSort` | 61.31GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 48.65GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 29.31GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 20.63GB |
| 8 | `fmt.Sprintf` | 14.78GB |
| 9 | `reflect.growslice` | 11.03GB |
| 10 | `jackskj/carta.getUniqueId` | 10.3GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/263 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 43.44MB | 13/263 | `██████████░░░░░ 69%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 261/263 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 31.87MB | 15/263 | `███████░░░░░░░░ 51%` |
| 5 | `runtime.mallocgc` | 24.48MB | 261/263 | `█████░░░░░░░░░░ 39%` |
| 6 | `bytes.growSlice` | 13.99MB | 176/263 | `███░░░░░░░░░░░░ 22%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/263 | `███░░░░░░░░░░░░ 22%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 13.61MB | 5/263 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/263 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.63MB | 36/263 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 117.76GB | 252/263 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 69.77GB | 258/263 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 69.71GB | 258/263 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 59.25GB | 243/263 | `███████░░░░░░░░ 50%` |
| 5 | `experiment/local.topologicalSort` | 48.85GB | 240/263 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.49GB | 208/263 | `█████░░░░░░░░░░ 36%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.57GB | 185/263 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 27.85GB | 222/263 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/263 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.Sprintf` | 18.59GB | 108/263 | `██░░░░░░░░░░░░░ 15%` |

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
