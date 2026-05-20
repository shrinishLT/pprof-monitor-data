# Overview: prod
*Last updated: 2026-05-20 10:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T10:30 (230 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 33,655 | avg: 15,503 | max: 84,644 | trend: INCREASING (+3.77/hr))
```
▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▂▂▂▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▁▁▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▁▁▄▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▄█
```

**Heap InUse** (current: 958.1MB | avg: 231.5MB | max: 1896.6MB | trend: stable (+0.16MB/hr))
```
▂▂▂▂▂▃▂▂▁▂▃▂▂▂▃▃▃▂▅▂▂▂▁▂▂▂▁▂▂▁▃▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▂▂▁▁▁▂▃▂▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂█
```

## Current Status

Goroutines: `███████░░░░░░░░░░░░░ 39%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 14%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 33,655 | 24,938 | +8717 | 15,503 | 84,644 | INCREASING (+3.77/hr) |
| Heap InUse | 958.1MB | 343.3MB | +614.8MB | 231.5MB | 1896.6MB | stable (+0.16MB/hr) |
| Heap Sys | 4210.4MB | 4287.5MB | -77.1MB | 4477.7MB | 6579.6MB | |
| Heap Objects | 4,373,255 | 895,924 | +3477331 | 981,710 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 22 | 16,546 | 241.1MB | 958.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 114.56MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 53.75MB |
| 3 | `runtime.mallocgc` | 53.12MB |
| 4 | `bufio.NewReaderSize` | 46.17MB |
| 5 | `bufio.NewWriterSize` | 37.14MB |
| 6 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 16.51MB |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.51MB |
| 9 | `net/http.(*Transport).dialConn` | 11.0MB |
| 10 | `net/http.(*Transport).queueForIdleConn` | 10.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 182.33GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 109.21GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 109.19GB |
| 4 | `experiment/local.topologicalSort` | 72.26GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 57.19GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 47.52GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 34.62GB |
| 8 | `reflect.growslice` | 23.24GB |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 21.93GB |
| 10 | `jackskj/carta.getUniqueId` | 19.76GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/230 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/230 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 228/230 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 34.92MB | 13/230 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 24.72MB | 228/230 | `█████░░░░░░░░░░ 39%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 16.18MB | 3/230 | `███░░░░░░░░░░░░ 26%` |
| 7 | `bytes.growSlice` | 12.89MB | 144/230 | `███░░░░░░░░░░░░ 20%` |
| 8 | `net/http.(*Transport).dialConn` | 12.62MB | 4/230 | `███░░░░░░░░░░░░ 20%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.5MB | 28/230 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 224/230 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 124.4GB | 219/230 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 73.51GB | 225/230 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 73.44GB | 225/230 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 64.0GB | 220/230 | `███████░░░░░░░░ 51%` |
| 5 | `experiment/local.topologicalSort` | 51.96GB | 207/230 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 47.32GB | 175/230 | `█████░░░░░░░░░░ 38%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 31.73GB | 152/230 | `███░░░░░░░░░░░░ 25%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 29.22GB | 209/230 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/230 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `fmt.Sprintf` | 22.97GB | 78/230 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.2x avg)
