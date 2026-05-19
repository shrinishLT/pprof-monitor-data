# Overview: prod
*Last updated: 2026-05-19 09:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T09:31 (180 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,508 | avg: 15,324 | max: 84,644 | trend: decreasing (-8.77/hr))
```
▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▂▃▆▁▁▁▂▆▁▁▁▂▁▁▄▃▁▁▂▄▁▁▂▂▄▅▄█▁▁▂▁▂▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂
```

**Heap InUse** (current: 199.9MB | avg: 226.9MB | max: 1896.6MB | trend: stable (-0.04MB/hr))
```
▂▁▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▄▃▅▃▂▃▃▂▃▄▃▃▂▃▄▃▃▂▄▄▄▄█▂▃▃▂▃▃▃▂▃▂▂▄▁▁▁▁▁▁▂▄▁▁▁▂▁▁▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,508 | 14,744 | +764 | 15,324 | 84,644 | decreasing (-8.77/hr) |
| Heap InUse | 199.9MB | 177.9MB | +22.0MB | 226.9MB | 1896.6MB | stable (-0.04MB/hr) |
| Heap Sys | 3151.6MB | 3150.4MB | +1.2MB | 4493.2MB | 6579.6MB | |
| Heap Objects | 775,090 | 728,446 | +46644 | 968,256 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 20 | 14,609 | 199.2MB | 404.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 10.01MB |
| 3 | `internal/evaluation.mergeMetadata` | 9.5MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `bytes.growSlice` | 8.55MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 7.53MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 6.5MB |
| 8 | `experiment/local.(*Client).EvaluateV2` | 6.29MB |
| 9 | `bufio.NewReaderSize` | 6.04MB |
| 10 | `bufio.NewWriterSize` | 4.02MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 96.1GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 58.13GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 57.68GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 51.62GB |
| 5 | `experiment/local.topologicalSort` | 38.3GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 30.11GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 23.65GB |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 18.15GB |
| 9 | `reflect.growslice` | 13.54GB |
| 10 | `jackskj/carta.getUniqueId` | 10.76GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 78.87MB | 5/180 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 47.37MB | 9/180 | `█████████░░░░░░ 60%` |
| 3 | `database/sql.convertAssignRows` | 38.7MB | 10/180 | `███████░░░░░░░░ 49%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 178/180 | `██████░░░░░░░░░ 46%` |
| 5 | `runtime.mallocgc` | 26.5MB | 178/180 | `█████░░░░░░░░░░ 33%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/180 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/180 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `bytes.growSlice` | 11.63MB | 105/180 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.29MB | 14/180 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.72MB | 6/180 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 121.72GB | 169/180 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.64GB | 175/180 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.53GB | 175/180 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 70.11GB | 173/180 | `████████░░░░░░░ 57%` |
| 5 | `experiment/local.topologicalSort` | 51.58GB | 157/180 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 49.57GB | 125/180 | `██████░░░░░░░░░ 40%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 34.54GB | 103/180 | `████░░░░░░░░░░░ 28%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 30.73GB | 171/180 | `███░░░░░░░░░░░░ 25%` |
| 9 | `fmt.Sprintf` | 28.34GB | 44/180 | `███░░░░░░░░░░░░ 23%` |
| 10 | `fmt.(*buffer).writeString` | 24.13GB | 16/180 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.4x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.0x avg)
