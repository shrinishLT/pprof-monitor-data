# Overview: prod
*Last updated: 2026-05-19 04:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T04:01 (169 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,526 | avg: 15,372 | max: 84,644 | trend: decreasing (-7.04/hr))
```
▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▁▃▃▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 140.0MB | avg: 229.8MB | max: 1896.6MB | trend: stable (+0.17MB/hr))
```
▂▁▁▁▁▁▄▃▂▃▂▂▁▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▄▃▅▃▂▃▃▂▃▄▃▃▂▃▄▃▃▂▄▄▄▄█▂▃▃▂▃▃▃▂▃▂▂▄▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,526 | 14,855 | -329 | 15,372 | 84,644 | decreasing (-7.04/hr) |
| Heap InUse | 140.0MB | 170.1MB | -30.1MB | 229.8MB | 1896.6MB | stable (+0.17MB/hr) |
| Heap Sys | 2233.9MB | 2245.0MB | -11.1MB | 4599.9MB | 6579.6MB | |
| Heap Objects | 540,970 | 723,128 | -182158 | 980,694 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 9 | 14,622 | 220.1MB | 404.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 10.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.5MB |
| 5 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 6 | `bufio.NewReaderSize` | 2.02MB |
| 7 | `bytes.growSlice` | 2.01MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.01MB |
| 9 | `bufio.NewWriterSize` | 2.01MB |
| 10 | `segmentio/kafka-go.makePartitions` | 2.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 21.57GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 13.05GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 13.0GB |
| 4 | `experiment/local.topologicalSort` | 8.61GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 7.06GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 6.76GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 4.07GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 3.22GB |
| 9 | `fmt.Sprintf` | 2.38GB |
| 10 | `segmentio/kafka-go.makePartitions` | 2.09GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 78.57MB | 4/169 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 52.33MB | 8/169 | `█████████░░░░░░ 66%` |
| 3 | `database/sql.convertAssignRows` | 36.83MB | 9/169 | `███████░░░░░░░░ 46%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 167/169 | `██████░░░░░░░░░ 46%` |
| 5 | `runtime.mallocgc` | 27.58MB | 167/169 | `█████░░░░░░░░░░ 35%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/169 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/169 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `internal/evaluation.mergeMetadata` | 12.14MB | 11/169 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `bytes.growSlice` | 12.0MB | 99/169 | `██░░░░░░░░░░░░░ 15%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.86MB | 5/169 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.63GB | 158/169 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 73.81GB | 164/169 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 73.66GB | 164/169 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 72.42GB | 162/169 | `████████░░░░░░░ 57%` |
| 5 | `experiment/local.topologicalSort` | 53.5GB | 146/169 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 52.37GB | 114/169 | `██████░░░░░░░░░ 41%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 37.19GB | 92/169 | `████░░░░░░░░░░░ 29%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 31.7GB | 160/169 | `███░░░░░░░░░░░░ 25%` |
| 9 | `fmt.Sprintf` | 29.57GB | 42/169 | `███░░░░░░░░░░░░ 23%` |
| 10 | `fmt.(*buffer).writeString` | 24.13GB | 16/169 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
