# Overview: prod
*Last updated: 2026-05-20 08:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T08:00 (225 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,211 | avg: 15,392 | max: 84,644 | trend: decreasing (-2.15/hr))
```
▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▂▃▄▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▄▁▁▁▁▁▁▁▁▁▂▁▁▂▁▃▁▁▁▁▁▁▂▁▁▁▁▇▁▁▁▁▁▂▁▁▁▁▁▁
```

**Heap InUse** (current: 218.4MB | avg: 228.6MB | max: 1896.6MB | trend: stable (+0.01MB/hr))
```
▂▃▂▄▂▂▃▂▂▃▄▃▂▁▃▄▃▂▂▃▃▄▃▆▂▃▂▂▂▂▂▂▂▂▂▄▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▆▂▁▂▁▄▁▁▂▂▁▁▁▃▄▃▁▁▂▂▃▁▂▁▁▁▁▃▁▂▁▁█▁▂▁▁▁▂▁▁▁▁▁▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,211 | 14,352 | +859 | 15,392 | 84,644 | decreasing (-2.15/hr) |
| Heap InUse | 218.4MB | 143.1MB | +75.3MB | 228.6MB | 1896.6MB | stable (+0.01MB/hr) |
| Heap Sys | 4313.5MB | 4313.8MB | -0.3MB | 4481.9MB | 6579.6MB | |
| Heap Objects | 1,106,961 | 631,206 | +475755 | 970,410 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 17 | 15,378 | 205.9MB | 786.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 9.05MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 6 | `bufio.NewWriterSize` | 4.52MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 4.0MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.52MB |
| 9 | `reflect.mapassign_faststr0` | 2.5MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 77.83GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 46.58GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 46.53GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 42.75GB |
| 5 | `experiment/local.topologicalSort` | 30.98GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 24.47GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 19.68GB |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 14.73GB |
| 9 | `reflect.growslice` | 11.52GB |
| 10 | `jackskj/carta.getUniqueId` | 8.98GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/225 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/225 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 223/225 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 34.92MB | 13/225 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 24.81MB | 223/225 | `█████░░░░░░░░░░ 39%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/225 | `████░░░░░░░░░░░ 29%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/225 | `███░░░░░░░░░░░░ 21%` |
| 8 | `bytes.growSlice` | 12.01MB | 139/225 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.5MB | 27/225 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 220/225 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 124.62GB | 214/225 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 73.61GB | 220/225 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 73.54GB | 220/225 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 64.4GB | 215/225 | `███████░░░░░░░░ 51%` |
| 5 | `experiment/local.topologicalSort` | 52.12GB | 202/225 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 47.65GB | 170/225 | `█████░░░░░░░░░░ 38%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 32.07GB | 147/225 | `███░░░░░░░░░░░░ 25%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 29.41GB | 204/225 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/225 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `fmt.Sprintf` | 22.97GB | 78/225 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
