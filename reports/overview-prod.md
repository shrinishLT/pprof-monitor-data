# Overview: prod
*Last updated: 2026-05-18 10:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T10:31 (129 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,328 | avg: 15,235 | max: 84,644 | trend: decreasing (-30.66/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▁
```

**Heap InUse** (current: 285.1MB | avg: 208.1MB | max: 1896.6MB | trend: decreasing (-2.10MB/hr))
```
▃▅▅▃▃▄▄▁▂▁▂▁▂▄▁▂▃▂▁▁▁▁▂▂▂▁▂▂▂▂▂▁▁▁▂▂▃▂▃▃▂▁▂▂▁▂▇▆▄▆▃▃▁▂▃▄▁▂▁▁▂▁▂▁▂▁▂▂▁▁▁▂▂▂▁▁▁▁▂▂▁▁▁▁▁▅█▁▂▁▁▁▄▃▇▅
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,328 | 21,569 | -7241 | 15,235 | 84,644 | decreasing (-30.66/hr) |
| Heap InUse | 285.1MB | 373.5MB | -88.4MB | 208.1MB | 1896.6MB | decreasing (-2.10MB/hr) |
| Heap Sys | 4669.9MB | 4681.3MB | -11.4MB | 4202.5MB | 5842.7MB | |
| Heap Objects | 1,244,218 | 1,838,190 | -593972 | 929,342 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 22 | 14,938 | 182.1MB | 404.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 55.03MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.53MB |
| 6 | `bytes.growSlice` | 3.52MB |
| 7 | `compress/flate.NewWriter` | 2.64MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `reflect.unsafe_NewArray` | 2.01MB |
| 10 | `reflect.mapassign_faststr0` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 221.95GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 134.58GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 133.92GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 109.55GB |
| 5 | `experiment/local.topologicalSort` | 88.64GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 69.55GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 50.08GB |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 42.51GB |
| 9 | `segmentio/kafka-go.makePartitions` | 25.5GB |
| 10 | `reflect.growslice` | 25.07GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 36.75MB | 7/129 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 127/129 | `██████████████░ 99%` |
| 3 | `runtime.mallocgc` | 20.4MB | 127/129 | `████████░░░░░░░ 55%` |
| 4 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/129 | `███████░░░░░░░░ 50%` |
| 5 | `database/sql.convertAssignRows` | 17.44MB | 8/129 | `███████░░░░░░░░ 47%` |
| 6 | `net/http.(*Transport).dialConn` | 17.25MB | 2/129 | `███████░░░░░░░░ 46%` |
| 7 | `crypto/tls.Client` | 13.01MB | 3/129 | `█████░░░░░░░░░░ 35%` |
| 8 | `bytes.growSlice` | 12.6MB | 61/129 | `█████░░░░░░░░░░ 34%` |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 10.44MB | 31/129 | `████░░░░░░░░░░░ 28%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 10.4MB | 9/129 | `████░░░░░░░░░░░ 28%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 56.25GB | 122/129 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 41.94GB | 118/129 | `███████████░░░░ 74%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 24.9GB | 124/129 | `██████░░░░░░░░░ 44%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 24.86GB | 124/129 | `██████░░░░░░░░░ 44%` |
| 5 | `fmt.(*buffer).writeString` | 24.13GB | 16/129 | `██████░░░░░░░░░ 42%` |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 23.72GB | 120/129 | `██████░░░░░░░░░ 42%` |
| 7 | `reflect.growslice` | 20.49GB | 37/129 | `█████░░░░░░░░░░ 36%` |
| 8 | `experiment/local.topologicalSort` | 17.53GB | 106/129 | `████░░░░░░░░░░░ 31%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 17.51GB | 74/129 | `████░░░░░░░░░░░ 31%` |
| 10 | `jackskj/carta.getUniqueId` | 17.48GB | 25/129 | `████░░░░░░░░░░░ 31%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.6x avg)
