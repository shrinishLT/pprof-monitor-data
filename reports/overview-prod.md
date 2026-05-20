# Overview: prod
*Last updated: 2026-05-20 18:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T18:31 (246 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,021 | avg: 15,507 | max: 84,644 | trend: INCREASING (+3.25/hr))
```
▂▂▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▁▁▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▁▁▄▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▄█▁▁▁▁▁▁▁▁▁▁▂▁▃▁▁▁
```

**Heap InUse** (current: 188.4MB | avg: 230.7MB | max: 1896.6MB | trend: stable (+0.09MB/hr))
```
▃▂▅▂▂▂▁▂▂▂▁▂▂▁▃▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▂▂▁▁▁▂▃▂▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂█▂▂▁▁▁▁▁▁▁▁▂▁▃▂▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,021 | 14,220 | +801 | 15,507 | 84,644 | INCREASING (+3.25/hr) |
| Heap InUse | 188.4MB | 128.9MB | +59.5MB | 230.7MB | 1896.6MB | stable (+0.09MB/hr) |
| Heap Sys | 4973.1MB | 4972.8MB | +0.3MB | 4331.8MB | 6579.6MB | |
| Heap Objects | 877,136 | 363,767 | +513369 | 980,701 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 38 | 16,128 | 231.7MB | 958.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 15.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 6.53MB |
| 5 | `bufio.NewReaderSize` | 4.53MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 4.5MB |
| 7 | `segmentio/kafka-go.makePartitions` | 3.52MB |
| 8 | `dotlapse-event-service/workerpool.NewWorker` | 3.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 94.12GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 56.81GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 56.56GB |
| 4 | `experiment/local.topologicalSort` | 37.54GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 29.53GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 17.92GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 15.19GB |
| 8 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 10.84GB |
| 9 | `fmt.Sprintf` | 10.61GB |
| 10 | `segmentio/kafka-go.makePartitions` | 7.32GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/246 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/246 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 244/246 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 32.79MB | 14/246 | `███████░░░░░░░░ 52%` |
| 5 | `runtime.mallocgc` | 24.13MB | 244/246 | `█████░░░░░░░░░░ 38%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 13.01MB | 4/246 | `███░░░░░░░░░░░░ 20%` |
| 7 | `bytes.growSlice` | 12.64MB | 159/246 | `███░░░░░░░░░░░░ 20%` |
| 8 | `net/http.(*Transport).dialConn` | 12.62MB | 4/246 | `███░░░░░░░░░░░░ 20%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.03MB | 31/246 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/246 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 119.56GB | 235/246 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 70.76GB | 241/246 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 70.7GB | 241/246 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 61.09GB | 233/246 | `███████░░░░░░░░ 51%` |
| 5 | `experiment/local.topologicalSort` | 49.75GB | 223/246 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 44.76GB | 191/246 | `█████░░░░░░░░░░ 37%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 29.68GB | 168/246 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 28.15GB | 219/246 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/246 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.Sprintf` | 20.02GB | 93/246 | `██░░░░░░░░░░░░░ 16%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.2x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.2x avg)
