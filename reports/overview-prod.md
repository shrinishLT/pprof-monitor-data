# Overview: prod
*Last updated: 2026-05-20 12:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T12:02 (233 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,377 | avg: 15,501 | max: 84,644 | trend: INCREASING (+3.50/hr))
```
▁▁▂▁▁▁▁▂▁▁▁▁▂▂▂▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▁▁▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▁▁▄▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▄█▁▁▁
```

**Heap InUse** (current: 226.9MB | avg: 231.7MB | max: 1896.6MB | trend: stable (+0.17MB/hr))
```
▂▂▃▂▂▁▂▃▂▂▂▃▃▃▂▅▂▂▂▁▂▂▂▁▂▂▁▃▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▂▂▁▁▁▂▃▂▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂█▂▂▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 19%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,377 | 15,204 | +1173 | 15,501 | 84,644 | INCREASING (+3.50/hr) |
| Heap InUse | 226.9MB | 265.3MB | -38.4MB | 231.7MB | 1896.6MB | stable (+0.17MB/hr) |
| Heap Sys | 805.2MB | 813.3MB | -8.1MB | 4445.3MB | 6579.6MB | |
| Heap Objects | 1,076,095 | 1,439,904 | -363809 | 984,500 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 25 | 16,398 | 241.9MB | 958.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 14.57MB |
| 3 | `runtime.mallocgc` | 12.01MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 8.04MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 7.0MB |
| 7 | `bufio.NewWriterSize` | 5.03MB |
| 8 | `bufio.NewReaderSize` | 3.51MB |
| 9 | `reflect.unsafe_NewArray` | 2.51MB |
| 10 | `aes/gcm.NewGCMForTLS13` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 29.84GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 18.07GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 17.96GB |
| 4 | `experiment/local.topologicalSort` | 11.93GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 9.34GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 5.69GB |
| 7 | `reflect.growslice` | 3.31GB |
| 8 | `jackskj/carta.getUniqueId` | 2.85GB |
| 9 | `reflect.unsafe_New` | 2.61GB |
| 10 | `fmt.Sprintf` | 2.55GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/233 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/233 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 231/233 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 34.92MB | 13/233 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 24.73MB | 231/233 | `█████░░░░░░░░░░ 39%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 16.18MB | 3/233 | `███░░░░░░░░░░░░ 26%` |
| 7 | `bytes.growSlice` | 12.87MB | 146/233 | `███░░░░░░░░░░░░ 20%` |
| 8 | `net/http.(*Transport).dialConn` | 12.62MB | 4/233 | `███░░░░░░░░░░░░ 20%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.05MB | 30/233 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 227/233 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 123.76GB | 222/233 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 73.15GB | 228/233 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 73.08GB | 228/233 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 63.64GB | 222/233 | `███████░░░░░░░░ 51%` |
| 5 | `experiment/local.topologicalSort` | 51.65GB | 210/233 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 46.93GB | 178/233 | `█████░░░░░░░░░░ 37%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 31.4GB | 155/233 | `███░░░░░░░░░░░░ 25%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 29.18GB | 210/233 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/233 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `fmt.Sprintf` | 22.44GB | 80/233 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.2x avg)
