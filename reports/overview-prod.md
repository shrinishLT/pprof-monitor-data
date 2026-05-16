# Overview: prod
*Last updated: 2026-05-16 13:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T13:03 (38 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,208 | avg: 16,512 | max: 84,644 | trend: decreasing (-68.03/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 206.0MB | avg: 291.3MB | max: 1896.6MB | trend: INCREASING (+0.54MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,208 | 14,203 | +5 | 16,512 | 84,644 | decreasing (-68.03/hr) |
| Heap InUse | 206.0MB | 209.7MB | -3.7MB | 291.3MB | 1896.6MB | INCREASING (+0.54MB/hr) |
| Heap Sys | 5840.5MB | 5840.7MB | -0.2MB | 5191.2MB | 5842.7MB | |
| Heap Objects | 608,748 | 616,241 | -7493 | 1,137,510 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 28 | 17,298 | 309.8MB | 1896.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 60.12MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.55MB |
| 7 | `reflect.unsafe_NewArray` | 3.51MB |
| 8 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 1.6MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 79.65GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 75.6GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 48.44GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 48.18GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 34.39GB |
| 6 | `experiment/local.topologicalSort` | 31.81GB |
| 7 | `jackskj/carta.getUniqueId` | 27.71GB |
| 8 | `reflect.growslice` | 25.78GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 25.02GB |
| 10 | `fmt.(*buffer).writeString` | 21.91GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `runtime.mallocgc` | 38.67MB | 36/38 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 36/38 | `██████████████░ 94%` |
| 3 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/38 | `███████████░░░░ 78%` |
| 4 | `net/http.(*Transport).dialConn` | 30.0MB | 1/38 | `███████████░░░░ 77%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 28.78MB | 7/38 | `███████████░░░░ 74%` |
| 6 | `bytes.growSlice` | 20.92MB | 21/38 | `████████░░░░░░░ 54%` |
| 7 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/38 | `██████░░░░░░░░░ 42%` |
| 8 | `crypto/tls.Client` | 16.51MB | 2/38 | `██████░░░░░░░░░ 42%` |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 15.01MB | 1/38 | `█████░░░░░░░░░░ 38%` |
| 10 | `reflect.growslice` | 11.07MB | 2/38 | `████░░░░░░░░░░░ 28%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 67.75GB | 33/38 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 49.74GB | 27/38 | `███████████░░░░ 73%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 27.44GB | 33/38 | `██████░░░░░░░░░ 40%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 27.26GB | 33/38 | `██████░░░░░░░░░ 40%` |
| 5 | `reflect.growslice` | 25.41GB | 21/38 | `█████░░░░░░░░░░ 37%` |
| 6 | `fmt.(*buffer).writeString` | 25.04GB | 13/38 | `█████░░░░░░░░░░ 36%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 23.12GB | 32/38 | `█████░░░░░░░░░░ 34%` |
| 8 | `experiment/local.topologicalSort` | 19.88GB | 27/38 | `████░░░░░░░░░░░ 29%` |
| 9 | `jackskj/carta.getUniqueId` | 18.52GB | 15/38 | `████░░░░░░░░░░░ 27%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.21GB | 26/38 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (6.5x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.1x avg)
