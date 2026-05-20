# Overview: prod
*Last updated: 2026-05-20 10:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T10:02 (229 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 24,938 | avg: 15,424 | max: 84,644 | trend: stable (-0.36/hr))
```
▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▂▃▄▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▄▁▁▁▁▁▁▁▁▁▂▁▁▂▁▃▁▁▁▁▁▁▂▁▁▁▁▇▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▆
```

**Heap InUse** (current: 343.3MB | avg: 228.3MB | max: 1896.6MB | trend: stable (-0.00MB/hr))
```
▂▂▃▂▂▃▄▃▂▁▃▄▃▂▂▃▃▄▃▆▂▃▂▂▂▂▂▂▂▂▂▄▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▆▂▁▂▁▄▁▁▂▂▁▁▁▃▄▃▁▁▂▂▃▁▂▁▁▁▁▃▁▂▁▁█▁▂▁▁▁▂▁▁▁▁▁▂▁▁▁▃
```

## Current Status

Goroutines: `█████░░░░░░░░░░░░░░░ 29%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 24,938 | 15,070 | +9868 | 15,424 | 84,644 | stable (-0.36/hr) |
| Heap InUse | 343.3MB | 181.8MB | +161.5MB | 228.3MB | 1896.6MB | stable (-0.00MB/hr) |
| Heap Sys | 4287.5MB | 4315.9MB | -28.4MB | 4478.8MB | 6579.6MB | |
| Heap Objects | 895,924 | 684,609 | +211315 | 966,899 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 21 | 15,731 | 206.9MB | 786.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 62.31MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bufio.NewWriterSize` | 23.09MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 22.6MB |
| 5 | `bufio.NewReaderSize` | 20.58MB |
| 6 | `runtime.mallocgc` | 13.51MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 9.5MB |
| 8 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 9 | `net/http.(*Transport).queueForIdleConn` | 8.51MB |
| 10 | `aes/gcm.NewGCMForTLS13` | 7.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 131.6GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 78.94GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 78.91GB |
| 4 | `experiment/local.topologicalSort` | 52.16GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 47.49GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 41.27GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 24.82GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 21.91GB |
| 9 | `reflect.growslice` | 16.41GB |
| 10 | `jackskj/carta.getUniqueId` | 13.74GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/229 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/229 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 227/229 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 34.92MB | 13/229 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 24.59MB | 227/229 | `█████░░░░░░░░░░ 39%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/229 | `████░░░░░░░░░░░ 29%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/229 | `███░░░░░░░░░░░░ 21%` |
| 8 | `bytes.growSlice` | 12.18MB | 143/229 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.5MB | 28/229 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 224/229 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 124.14GB | 218/229 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 73.35GB | 224/229 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 73.28GB | 224/229 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 64.07GB | 219/229 | `███████░░░░░░░░ 51%` |
| 5 | `experiment/local.topologicalSort` | 51.86GB | 206/229 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 47.26GB | 174/229 | `█████░░░░░░░░░░ 38%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 31.71GB | 151/229 | `███░░░░░░░░░░░░ 25%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 29.25GB | 208/229 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/229 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `fmt.Sprintf` | 22.97GB | 78/229 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
