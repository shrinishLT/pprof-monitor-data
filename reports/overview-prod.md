# Overview: prod
*Last updated: 2026-05-16 06:35 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T06:35 (26 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,441 | avg: 17,487 | max: 84,644 | trend: INCREASING (+447.73/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 320.3MB | avg: 313.3MB | max: 1896.6MB | trend: INCREASING (+16.34MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,441 | 15,043 | -602 | 17,487 | 84,644 | INCREASING (+447.73/hr) |
| Heap InUse | 320.3MB | 478.7MB | -158.4MB | 313.3MB | 1896.6MB | INCREASING (+16.34MB/hr) |
| Heap Sys | 5832.7MB | 5831.9MB | +0.8MB | 4892.6MB | 5832.7MB | |
| Heap Objects | 1,788,140 | 1,602,599 | +185541 | 1,232,820 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 16 | 19,472 | 359.5MB | 1896.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 60.12MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.01MB |
| 6 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `bytes.growSlice` | 2.01MB |
| 9 | `compress/flate.NewWriter` | 1.76MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 1.6MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 58.72GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 51.64GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 35.8GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 35.5GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 23.45GB |
| 6 | `experiment/local.topologicalSort` | 23.43GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 18.43GB |
| 8 | `reflect.growslice` | 13.54GB |
| 9 | `jackskj/carta.getUniqueId` | 13.23GB |
| 10 | `internal/evaluation.(*Engine).evaluateFlag` | 11.17GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 38.68MB | 5/26 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 24/26 | `██████████████░ 94%` |
| 3 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/26 | `███████████░░░░ 78%` |
| 4 | `net/http.(*Transport).dialConn` | 30.0MB | 1/26 | `███████████░░░░ 77%` |
| 5 | `bytes.growSlice` | 27.99MB | 15/26 | `██████████░░░░░ 72%` |
| 6 | `runtime.mallocgc` | 27.94MB | 24/26 | `██████████░░░░░ 72%` |
| 7 | `reflect.growslice` | 19.28MB | 1/26 | `███████░░░░░░░░ 49%` |
| 8 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/26 | `██████░░░░░░░░░ 42%` |
| 9 | `crypto/tls.Client` | 16.51MB | 2/26 | `██████░░░░░░░░░ 42%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 15.01MB | 1/26 | `█████░░░░░░░░░░ 38%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 68.95GB | 21/26 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 34.04GB | 15/26 | `███████░░░░░░░░ 49%` |
| 3 | `reflect.growslice` | 33.61GB | 9/26 | `███████░░░░░░░░ 48%` |
| 4 | `fmt.(*buffer).writeString` | 31.53GB | 6/26 | `██████░░░░░░░░░ 45%` |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 19.09GB | 20/26 | `████░░░░░░░░░░░ 27%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 18.97GB | 21/26 | `████░░░░░░░░░░░ 27%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 18.87GB | 21/26 | `████░░░░░░░░░░░ 27%` |
| 8 | `experiment/local.topologicalSort` | 13.64GB | 15/26 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `jackskj/carta.getUniqueId` | 12.35GB | 3/26 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 11.45GB | 14/26 | `██░░░░░░░░░░░░░ 16%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (6.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (4.8x avg)
