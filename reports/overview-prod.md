# Overview: prod
*Last updated: 2026-05-21 14:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T14:02 (293 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,731 | avg: 15,696 | max: 84,644 | trend: INCREASING (+7.67/hr))
```
▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 226.0MB | avg: 236.2MB | max: 1896.6MB | trend: stable (+0.22MB/hr))
```
▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▇▂▂▁▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▂▁▁▂▂▁▄▂▁▁▂▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,731 | 14,312 | +419 | 15,696 | 84,644 | INCREASING (+7.67/hr) |
| Heap InUse | 226.0MB | 185.0MB | +41.0MB | 236.2MB | 1896.6MB | stable (+0.22MB/hr) |
| Heap Sys | 4891.1MB | 4891.0MB | +0.1MB | 4211.2MB | 6579.6MB | |
| Heap Objects | 894,823 | 624,647 | +270176 | 995,933 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 37 | 15,663 | 241.3MB | 501.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 35.36MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 7.0MB |
| 5 | `bufio.NewReaderSize` | 4.02MB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 3.76MB |
| 7 | `bufio.NewWriterSize` | 3.53MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.52MB |
| 9 | `internal/evaluation.mergeMetadata` | 3.5MB |
| 10 | `bytes.growSlice` | 3.02MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 70.88GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 42.5GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 42.49GB |
| 4 | `experiment/local.topologicalSort` | 28.12GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 22.29GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 13.63GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 13.08GB |
| 8 | `reflect.growslice` | 6.87GB |
| 9 | `jackskj/carta.getUniqueId` | 6.65GB |
| 10 | `fmt.Sprintf` | 6.64GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.01MB | 8/293 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.22MB | 14/293 | `███████████░░░░ 79%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 291/293 | `█████████░░░░░░ 63%` |
| 4 | `database/sql.convertAssignRows` | 32.63MB | 16/293 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 24.02MB | 291/293 | `██████░░░░░░░░░ 41%` |
| 6 | `net/http.(*Transport).dialConn` | 13.7MB | 5/293 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).tryPutIdleConn` | 13.61MB | 5/293 | `███░░░░░░░░░░░░ 23%` |
| 8 | `bytes.growSlice` | 13.59MB | 202/293 | `███░░░░░░░░░░░░ 23%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.82MB | 44/293 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/293 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 113.7GB | 282/293 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 67.49GB | 288/293 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 67.47GB | 288/293 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 55.6GB | 269/293 | `███████░░░░░░░░ 48%` |
| 5 | `experiment/local.topologicalSort` | 46.97GB | 270/293 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 41.2GB | 238/293 | `█████░░░░░░░░░░ 36%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 27.05GB | 237/293 | `███░░░░░░░░░░░░ 23%` |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 26.84GB | 214/293 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/293 | `███░░░░░░░░░░░░ 21%` |
| 10 | `segmentio/kafka-go.makePartitions` | 17.89GB | 145/293 | `██░░░░░░░░░░░░░ 15%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.3x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
