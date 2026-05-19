# Overview: prod
*Last updated: 2026-05-20 05:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T05:00 (219 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 17,268 | avg: 15,408 | max: 84,644 | trend: decreasing (-1.45/hr))
```
▁▁▂▂▅▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▂▃▄▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▄▁▁▁▁▁▁▁▁▁▂▁▁▂▁▃▁▁▁▁▁▁▂▁▁▁▁▇▁▁▁▁▁▂
```

**Heap InUse** (current: 222.1MB | avg: 230.4MB | max: 1896.6MB | trend: stable (+0.11MB/hr))
```
▁▁▂▂▃▂▂▃▂▄▂▂▂▂▂▃▄▂▂▁▂▄▂▂▂▃▃▄▃▆▂▃▂▁▂▂▂▁▂▂▁▃▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▆▂▁▂▁▄▁▁▂▂▁▁▁▂▄▃▁▁▂▂▂▁▂▁▁▁▁▃▁▁▁▁█▁▂▁▁▁▂
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 20%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 17,268 | 14,742 | +2526 | 15,408 | 84,644 | decreasing (-1.45/hr) |
| Heap InUse | 222.1MB | 198.9MB | +23.2MB | 230.4MB | 1896.6MB | stable (+0.11MB/hr) |
| Heap Sys | 3530.3MB | 3536.3MB | -6.0MB | 4486.5MB | 6579.6MB | |
| Heap Objects | 526,671 | 1,010,506 | -483835 | 980,256 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 11 | 15,682 | 229.3MB | 786.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 19.09MB |
| 3 | `runtime.mallocgc` | 12.01MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 8.04MB |
| 7 | `bufio.NewWriterSize` | 7.04MB |
| 8 | `reflect.growslice` | 5.09MB |
| 9 | `bufio.NewReaderSize` | 5.02MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 4.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 20.96GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 12.62GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 12.62GB |
| 4 | `experiment/local.topologicalSort` | 8.4GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 6.66GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 6.15GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 3.93GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 2.83GB |
| 9 | `fmt.Sprintf` | 2.17GB |
| 10 | `segmentio/kafka-go.makePartitions` | 2.01GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/219 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/219 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 217/219 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 34.92MB | 13/219 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 25.17MB | 217/219 | `██████░░░░░░░░░ 40%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/219 | `████░░░░░░░░░░░ 29%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/219 | `███░░░░░░░░░░░░ 21%` |
| 8 | `bytes.growSlice` | 12.13MB | 136/219 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `internal/evaluation.mergeMetadata` | 12.02MB | 24/219 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 214/219 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 126.22GB | 208/219 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 74.51GB | 214/219 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 74.44GB | 214/219 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 65.33GB | 209/219 | `███████░░░░░░░░ 51%` |
| 5 | `experiment/local.topologicalSort` | 52.87GB | 196/219 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 48.59GB | 164/219 | `█████░░░░░░░░░░ 38%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 32.88GB | 141/219 | `███░░░░░░░░░░░░ 26%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 29.61GB | 200/219 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/219 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `fmt.Sprintf` | 22.97GB | 78/219 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
