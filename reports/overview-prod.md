# Overview: prod
*Last updated: 2026-05-20 16:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T16:31 (242 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,942 | avg: 15,497 | max: 84,644 | trend: INCREASING (+2.96/hr))
```
▁▁▁▂▂▂▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▁▁▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▁▁▄▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▄█▁▁▁▁▁▁▁▁▁▁▂▁
```

**Heap InUse** (current: 213.8MB | avg: 230.4MB | max: 1896.6MB | trend: stable (+0.09MB/hr))
```
▂▂▃▃▃▂▅▂▂▂▁▂▂▂▁▂▂▁▃▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▂▂▁▁▁▂▃▂▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂█▂▂▁▁▁▁▁▁▁▁▂▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,942 | 17,522 | -2580 | 15,497 | 84,644 | INCREASING (+2.96/hr) |
| Heap InUse | 213.8MB | 345.2MB | -131.4MB | 230.4MB | 1896.6MB | stable (+0.09MB/hr) |
| Heap Sys | 1347.6MB | 1360.0MB | -12.4MB | 4321.2MB | 6579.6MB | |
| Heap Objects | 1,081,099 | 1,641,990 | -560891 | 978,076 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 34 | 16,136 | 229.8MB | 958.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 5.52MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 4.5MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.02MB |
| 7 | `bufio.NewReaderSize` | 3.53MB |
| 8 | `dotlapse-event-service/workerpool.NewWorker` | 3.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `bufio.NewWriterSize` | 2.02MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 55.73GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 33.74GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 33.61GB |
| 4 | `experiment/local.topologicalSort` | 22.11GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 17.56GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 10.67GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 9.65GB |
| 8 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 6.65GB |
| 9 | `fmt.Sprintf` | 6.13GB |
| 10 | `segmentio/kafka-go.makePartitions` | 4.59GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/242 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/242 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 240/242 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 32.79MB | 14/242 | `███████░░░░░░░░ 52%` |
| 5 | `runtime.mallocgc` | 24.28MB | 240/242 | `█████░░░░░░░░░░ 39%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 16.18MB | 3/242 | `███░░░░░░░░░░░░ 26%` |
| 7 | `bytes.growSlice` | 12.63MB | 155/242 | `███░░░░░░░░░░░░ 20%` |
| 8 | `net/http.(*Transport).dialConn` | 12.62MB | 4/242 | `███░░░░░░░░░░░░ 20%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.05MB | 30/242 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/242 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 120.18GB | 231/242 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.1GB | 237/242 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.03GB | 237/242 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 61.89GB | 229/242 | `███████░░░░░░░░ 51%` |
| 5 | `experiment/local.topologicalSort` | 50.05GB | 219/242 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 45.15GB | 187/242 | `█████░░░░░░░░░░ 37%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 30.01GB | 164/242 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 28.45GB | 216/242 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/242 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.Sprintf` | 20.5GB | 89/242 | `██░░░░░░░░░░░░░ 17%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.2x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.2x avg)
