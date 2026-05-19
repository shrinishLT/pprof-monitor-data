# Overview: prod
*Last updated: 2026-05-19 19:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T19:30 (200 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,383 | avg: 15,381 | max: 84,644 | trend: decreasing (-3.61/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▅▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▂▃▄▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▄▁▁▁▁▁▁▁▁▁▂▁▁▂▁
```

**Heap InUse** (current: 254.7MB | avg: 230.6MB | max: 1896.6MB | trend: stable (+0.16MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▃▃▅▃▂▃▂▂▃▄▃▃▂▃▄▃▃▂▄▄▄▃█▂▃▃▂▃▃▃▂▃▂▂▄▁▁▁▁▁▁▁▄▁▁▁▁▁▁▂▇▂▁▂▁▅▁▁▂▂▂▁▂▃▅▃▂▁▂▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,383 | 15,991 | -608 | 15,381 | 84,644 | decreasing (-3.61/hr) |
| Heap InUse | 254.7MB | 230.6MB | +24.1MB | 230.6MB | 1896.6MB | stable (+0.16MB/hr) |
| Heap Sys | 4942.2MB | 4940.2MB | +2.0MB | 4501.0MB | 6579.6MB | |
| Heap Objects | 1,205,076 | 712,520 | +492556 | 986,487 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 40 | 15,251 | 231.5MB | 661.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 20.22MB |
| 3 | `bytes.growSlice` | 15.14MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 6 | `bufio.NewReaderSize` | 5.02MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.02MB |
| 8 | `reflect.unsafe_NewArray` | 2.51MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 2.5MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 178.58GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 107.16GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 107.14GB |
| 4 | `experiment/local.topologicalSort` | 71.08GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 57.69GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 55.44GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 33.85GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 26.47GB |
| 9 | `fmt.Sprintf` | 17.89GB |
| 10 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 16.77GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 69.11MB | 6/200 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.54MB | 11/200 | `█████████░░░░░░ 65%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 198/200 | `███████░░░░░░░░ 53%` |
| 4 | `database/sql.convertAssignRows` | 35.58MB | 12/200 | `███████░░░░░░░░ 51%` |
| 5 | `runtime.mallocgc` | 25.83MB | 198/200 | `█████░░░░░░░░░░ 37%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/200 | `████░░░░░░░░░░░ 26%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/200 | `██░░░░░░░░░░░░░ 19%` |
| 8 | `bytes.growSlice` | 11.94MB | 123/200 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.76MB | 19/200 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 196/200 | `██░░░░░░░░░░░░░ 13%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 119.35GB | 189/200 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 70.4GB | 195/200 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 70.3GB | 195/200 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 66.38GB | 190/200 | `████████░░░░░░░ 55%` |
| 5 | `experiment/local.topologicalSort` | 50.22GB | 177/200 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 47.02GB | 145/200 | `█████░░░░░░░░░░ 39%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 31.98GB | 123/200 | `████░░░░░░░░░░░ 26%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 30.07GB | 181/200 | `███░░░░░░░░░░░░ 25%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/200 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.Sprintf` | 23.58GB | 60/200 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
