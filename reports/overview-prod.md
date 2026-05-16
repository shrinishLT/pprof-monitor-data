# Overview: prod
*Last updated: 2026-05-16 11:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T11:31 (35 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,564 | avg: 16,709 | max: 84,644 | trend: decreasing (-13.67/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 309.9MB | avg: 295.7MB | max: 1896.6MB | trend: INCREASING (+2.39MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,564 | 14,307 | +257 | 16,709 | 84,644 | decreasing (-13.67/hr) |
| Heap InUse | 309.9MB | 206.5MB | +103.4MB | 295.7MB | 1896.6MB | INCREASING (+2.39MB/hr) |
| Heap Sys | 5840.3MB | 5840.6MB | -0.3MB | 5135.6MB | 5842.7MB | |
| Heap Objects | 1,369,947 | 544,674 | +825273 | 1,152,559 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 25 | 17,668 | 318.2MB | 1896.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 60.12MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `bytes.growSlice` | 5.53MB |
| 6 | `compress/flate.NewWriter` | 4.41MB |
| 7 | `bufio.NewReaderSize` | 2.54MB |
| 8 | `bufio.NewWriterSize` | 2.52MB |
| 9 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 76.23GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 68.19GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 46.36GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 46.05GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 30.98GB |
| 6 | `experiment/local.topologicalSort` | 30.38GB |
| 7 | `jackskj/carta.getUniqueId` | 25.29GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 23.91GB |
| 9 | `reflect.growslice` | 23.65GB |
| 10 | `fmt.(*buffer).writeString` | 20.12GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `runtime.mallocgc` | 36.72MB | 33/35 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 33/35 | `██████████████░ 99%` |
| 3 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/35 | `████████████░░░ 83%` |
| 4 | `net/http.(*Transport).dialConn` | 30.0MB | 1/35 | `████████████░░░ 81%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 28.78MB | 7/35 | `███████████░░░░ 78%` |
| 6 | `bytes.growSlice` | 21.89MB | 20/35 | `████████░░░░░░░ 59%` |
| 7 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/35 | `██████░░░░░░░░░ 44%` |
| 8 | `crypto/tls.Client` | 16.51MB | 2/35 | `██████░░░░░░░░░ 44%` |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 15.01MB | 1/35 | `██████░░░░░░░░░ 40%` |
| 10 | `reflect.growslice` | 11.07MB | 2/35 | `████░░░░░░░░░░░ 30%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 67.41GB | 30/35 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 46.17GB | 24/35 | `██████████░░░░░ 68%` |
| 3 | `fmt.(*buffer).writeString` | 26.02GB | 10/35 | `█████░░░░░░░░░░ 38%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 25.43GB | 30/35 | `█████░░░░░░░░░░ 37%` |
| 5 | `reflect.growslice` | 25.38GB | 18/35 | `█████░░░░░░░░░░ 37%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 25.25GB | 30/35 | `█████░░░░░░░░░░ 37%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 22.16GB | 29/35 | `████░░░░░░░░░░░ 32%` |
| 8 | `experiment/local.topologicalSort` | 18.46GB | 24/35 | `████░░░░░░░░░░░ 27%` |
| 9 | `jackskj/carta.getUniqueId` | 16.29GB | 12/35 | `███░░░░░░░░░░░░ 24%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 15.12GB | 23/35 | `███░░░░░░░░░░░░ 22%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (6.4x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.1x avg)
