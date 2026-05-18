# Overview: prod
*Last updated: 2026-05-18 11:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T11:02 (130 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,525 | avg: 15,230 | max: 84,644 | trend: decreasing (-30.46/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▁▁
```

**Heap InUse** (current: 266.6MB | avg: 208.5MB | max: 1896.6MB | trend: decreasing (-2.01MB/hr))
```
▅▅▃▃▄▄▁▂▁▂▁▂▄▁▂▃▂▁▁▁▁▂▂▂▁▂▂▂▂▂▁▁▁▂▂▃▂▃▃▂▁▂▂▁▂▇▆▄▆▃▃▁▂▃▄▁▂▁▁▂▁▂▁▂▁▂▂▁▁▁▂▂▂▁▁▁▁▂▂▁▁▁▁▁▅█▁▂▁▁▁▄▃▇▅▄
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,525 | 14,328 | +197 | 15,230 | 84,644 | decreasing (-30.46/hr) |
| Heap InUse | 266.6MB | 285.1MB | -18.5MB | 208.5MB | 1896.6MB | decreasing (-2.01MB/hr) |
| Heap Sys | 4672.9MB | 4669.9MB | +3.0MB | 4206.1MB | 5842.7MB | |
| Heap Objects | 1,080,249 | 1,244,218 | -163969 | 930,503 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 23 | 14,920 | 185.8MB | 404.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 55.03MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `jackskj/carta.getUniqueId` | 4.5MB |
| 6 | `reflect.growslice` | 3.42MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `bytes.growSlice` | 2.28MB |
| 9 | `reflect.unsafe_New` | 2.0MB |
| 10 | `reflect.mapassign_faststr0` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 225.77GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 136.85GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 136.19GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 109.55GB |
| 5 | `experiment/local.topologicalSort` | 90.12GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 70.73GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 50.08GB |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 43.25GB |
| 9 | `reflect.growslice` | 26.52GB |
| 10 | `segmentio/kafka-go.makePartitions` | 26.24GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 36.75MB | 7/130 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 128/130 | `██████████████░ 99%` |
| 3 | `runtime.mallocgc` | 20.67MB | 128/130 | `████████░░░░░░░ 56%` |
| 4 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/130 | `███████░░░░░░░░ 50%` |
| 5 | `database/sql.convertAssignRows` | 17.44MB | 8/130 | `███████░░░░░░░░ 47%` |
| 6 | `net/http.(*Transport).dialConn` | 17.25MB | 2/130 | `███████░░░░░░░░ 46%` |
| 7 | `crypto/tls.Client` | 13.01MB | 3/130 | `█████░░░░░░░░░░ 35%` |
| 8 | `bytes.growSlice` | 12.43MB | 62/130 | `█████░░░░░░░░░░ 33%` |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 10.44MB | 31/130 | `████░░░░░░░░░░░ 28%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 10.4MB | 9/130 | `████░░░░░░░░░░░ 28%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 56.68GB | 123/130 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 43.48GB | 119/130 | `███████████░░░░ 76%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 25.79GB | 125/130 | `██████░░░░░░░░░ 45%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 25.75GB | 125/130 | `██████░░░░░░░░░ 45%` |
| 5 | `fmt.(*buffer).writeString` | 24.13GB | 16/130 | `██████░░░░░░░░░ 42%` |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 23.93GB | 121/130 | `██████░░░░░░░░░ 42%` |
| 7 | `reflect.growslice` | 20.65GB | 38/130 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 18.22GB | 75/130 | `████░░░░░░░░░░░ 32%` |
| 9 | `experiment/local.topologicalSort` | 18.21GB | 107/130 | `████░░░░░░░░░░░ 32%` |
| 10 | `jackskj/carta.getUniqueId` | 17.48GB | 25/130 | `████░░░░░░░░░░░ 30%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.6x avg)
