# Overview: prod
*Last updated: 2026-05-21 20:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T20:00 (313 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 17,593 | avg: 15,767 | max: 84,644 | trend: INCREASING (+8.88/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁
```

**Heap InUse** (current: 368.8MB | avg: 241.2MB | max: 1896.6MB | trend: stable (+0.36MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▂▇▂▂▁▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▂▁▁▂▂▁▄▂▁▁▂▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▂▃▁▁▃▃▁▁▁▂▂▂▁▂▂▂▃▃▃
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 20%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 17,593 | 20,320 | -2727 | 15,767 | 84,644 | INCREASING (+8.88/hr) |
| Heap InUse | 368.8MB | 464.6MB | -95.8MB | 241.2MB | 1896.6MB | stable (+0.36MB/hr) |
| Heap Sys | 4877.1MB | 4876.2MB | +0.9MB | 4253.9MB | 6579.6MB | |
| Heap Objects | 1,377,413 | 2,062,232 | -684819 | 1,015,618 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 57 | 16,063 | 267.1MB | 501.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 35.36MB |
| 3 | `bytes.growSlice` | 29.45MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `bufio.NewWriterSize` | 7.54MB |
| 6 | `bufio.NewReaderSize` | 7.53MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 7.03MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 7.0MB |
| 9 | `crypto/tls.Client` | 4.0MB |
| 10 | `compress/flate.NewWriter` | 3.53MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 202.32GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 121.49GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 121.16GB |
| 4 | `experiment/local.topologicalSort` | 80.18GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 63.33GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 38.5GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 29.87GB |
| 8 | `fmt.Sprintf` | 21.08GB |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 13.71GB |
| 10 | `segmentio/kafka-go.makePartitions` | 13.14GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.01MB | 8/313 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.22MB | 14/313 | `███████████░░░░ 79%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 311/313 | `█████████░░░░░░ 63%` |
| 4 | `database/sql.convertAssignRows` | 32.63MB | 16/313 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 24.75MB | 311/313 | `██████░░░░░░░░░ 42%` |
| 6 | `bytes.growSlice` | 13.89MB | 222/313 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/313 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/313 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/313 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.66MB | 46/313 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 115.04GB | 302/313 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 68.32GB | 308/313 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 68.29GB | 308/313 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 53.34GB | 289/313 | `██████░░░░░░░░░ 46%` |
| 5 | `experiment/local.topologicalSort` | 47.39GB | 290/313 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 41.26GB | 258/313 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 26.73GB | 234/313 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 25.99GB | 254/313 | `███░░░░░░░░░░░░ 22%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/313 | `███░░░░░░░░░░░░ 20%` |
| 10 | `segmentio/kafka-go.makePartitions` | 17.34GB | 157/313 | `██░░░░░░░░░░░░░ 15%` |

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
