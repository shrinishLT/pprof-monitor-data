# Overview: prod
*Last updated: 2026-05-21 14:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T14:02 (294 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,721 | avg: 15,693 | max: 84,644 | trend: INCREASING (+7.45/hr))
```
▁▁▂▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 263.7MB | avg: 236.3MB | max: 1896.6MB | trend: stable (+0.22MB/hr))
```
▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▇▂▂▁▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▂▁▁▂▂▁▄▂▁▁▂▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,721 | 14,731 | -10 | 15,693 | 84,644 | INCREASING (+7.45/hr) |
| Heap InUse | 263.7MB | 226.0MB | +37.7MB | 236.3MB | 1896.6MB | stable (+0.22MB/hr) |
| Heap Sys | 4891.4MB | 4891.1MB | +0.3MB | 4213.5MB | 6579.6MB | |
| Heap Objects | 1,195,981 | 894,823 | +301158 | 996,613 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 38 | 15,638 | 241.9MB | 501.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 35.36MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 7.0MB |
| 5 | `bufio.NewReaderSize` | 4.52MB |
| 6 | `bufio.NewWriterSize` | 3.53MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.52MB |
| 8 | `bytes.growSlice` | 3.02MB |
| 9 | `segmentio/kafka-go.makePartitions` | 2.52MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 70.94GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 42.53GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 42.52GB |
| 4 | `experiment/local.topologicalSort` | 28.13GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 22.3GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 13.64GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 13.08GB |
| 8 | `reflect.growslice` | 6.87GB |
| 9 | `jackskj/carta.getUniqueId` | 6.65GB |
| 10 | `fmt.Sprintf` | 6.65GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.01MB | 8/294 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.22MB | 14/294 | `███████████░░░░ 79%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 292/294 | `█████████░░░░░░ 63%` |
| 4 | `database/sql.convertAssignRows` | 32.63MB | 16/294 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 24.06MB | 292/294 | `██████░░░░░░░░░ 41%` |
| 6 | `net/http.(*Transport).dialConn` | 13.7MB | 5/294 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).tryPutIdleConn` | 13.61MB | 5/294 | `███░░░░░░░░░░░░ 23%` |
| 8 | `bytes.growSlice` | 13.54MB | 203/294 | `███░░░░░░░░░░░░ 23%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.82MB | 44/294 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/294 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 113.55GB | 283/294 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 67.4GB | 289/294 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 67.38GB | 289/294 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 55.45GB | 270/294 | `███████░░░░░░░░ 48%` |
| 5 | `experiment/local.topologicalSort` | 46.9GB | 271/294 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 41.12GB | 239/294 | `█████░░░░░░░░░░ 36%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 27.05GB | 237/294 | `███░░░░░░░░░░░░ 23%` |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 26.78GB | 215/294 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/294 | `███░░░░░░░░░░░░ 21%` |
| 10 | `segmentio/kafka-go.makePartitions` | 17.89GB | 145/294 | `██░░░░░░░░░░░░░ 15%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
