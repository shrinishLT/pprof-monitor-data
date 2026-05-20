# Overview: prod
*Last updated: 2026-05-20 09:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T09:30 (228 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,070 | avg: 15,382 | max: 84,644 | trend: decreasing (-2.57/hr))
```
▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▂▃▄▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▄▁▁▁▁▁▁▁▁▁▂▁▁▂▁▃▁▁▁▁▁▁▂▁▁▁▁▇▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 181.8MB | avg: 227.8MB | max: 1896.6MB | trend: stable (-0.03MB/hr))
```
▄▂▂▃▂▂▃▄▃▂▁▃▄▃▂▂▃▃▄▃▆▂▃▂▂▂▂▂▂▂▂▂▄▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▆▂▁▂▁▄▁▁▂▂▁▁▁▃▄▃▁▁▂▂▃▁▂▁▁▁▁▃▁▂▁▁█▁▂▁▁▁▂▁▁▁▁▁▂▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,070 | 14,454 | +616 | 15,382 | 84,644 | decreasing (-2.57/hr) |
| Heap InUse | 181.8MB | 179.4MB | +2.4MB | 227.8MB | 1896.6MB | stable (-0.03MB/hr) |
| Heap Sys | 4315.9MB | 4314.0MB | +1.9MB | 4479.7MB | 6579.6MB | |
| Heap Objects | 684,609 | 865,007 | -180398 | 967,211 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 20 | 15,271 | 200.1MB | 786.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.01MB |
| 3 | `internal/evaluation.mergeMetadata` | 11.5MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 5.36MB |
| 7 | `experiment/local.(*Client).EvaluateV2` | 4.74MB |
| 8 | `bytes.growSlice` | 4.52MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.02MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 4.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 97.59GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 58.42GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 58.38GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 47.49GB |
| 5 | `experiment/local.topologicalSort` | 38.68GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 30.65GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 21.91GB |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 18.46GB |
| 9 | `reflect.growslice` | 12.99GB |
| 10 | `jackskj/carta.getUniqueId` | 10.45GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/228 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/228 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 226/228 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 34.92MB | 13/228 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 24.64MB | 226/228 | `█████░░░░░░░░░░ 39%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/228 | `████░░░░░░░░░░░ 29%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/228 | `███░░░░░░░░░░░░ 21%` |
| 8 | `bytes.growSlice` | 11.83MB | 142/228 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.5MB | 28/228 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 223/228 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 124.1GB | 217/228 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 73.32GB | 223/228 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 73.25GB | 223/228 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 64.15GB | 218/228 | `███████░░░░░░░░ 51%` |
| 5 | `experiment/local.topologicalSort` | 51.86GB | 205/228 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 47.29GB | 173/228 | `█████░░░░░░░░░░ 38%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 31.76GB | 150/228 | `███░░░░░░░░░░░░ 25%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 29.29GB | 207/228 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/228 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `fmt.Sprintf` | 22.97GB | 78/228 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.5x avg)
