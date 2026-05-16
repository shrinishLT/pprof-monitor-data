# Overview: prod
*Last updated: 2026-05-16 11:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T11:01 (34 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,307 | avg: 16,772 | max: 84,644 | trend: INCREASING (+8.03/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 206.5MB | avg: 295.3MB | max: 1896.6MB | trend: INCREASING (+2.45MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,307 | 14,211 | +96 | 16,772 | 84,644 | INCREASING (+8.03/hr) |
| Heap InUse | 206.5MB | 211.4MB | -4.9MB | 295.3MB | 1896.6MB | INCREASING (+2.45MB/hr) |
| Heap Sys | 5840.6MB | 5842.7MB | -2.1MB | 5114.9MB | 5842.7MB | |
| Heap Objects | 544,674 | 657,402 | -112728 | 1,146,166 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 24 | 17,798 | 318.5MB | 1896.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 60.12MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `reflect.unsafe_NewArray` | 3.03MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `bytes.growSlice` | 2.01MB |
| 10 | `reflect.mapassign_faststr0` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 74.64GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 68.16GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 45.45GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 45.12GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 30.96GB |
| 6 | `experiment/local.topologicalSort` | 29.77GB |
| 7 | `jackskj/carta.getUniqueId` | 23.99GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 23.42GB |
| 9 | `reflect.growslice` | 22.83GB |
| 10 | `fmt.(*buffer).writeString` | 19.2GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 32/34 | `███████████████ 100%` |
| 2 | `runtime.mallocgc` | 35.98MB | 32/34 | `██████████████░ 98%` |
| 3 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/34 | `████████████░░░ 83%` |
| 4 | `net/http.(*Transport).dialConn` | 30.0MB | 1/34 | `████████████░░░ 81%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 28.78MB | 7/34 | `███████████░░░░ 78%` |
| 6 | `bytes.growSlice` | 22.76MB | 19/34 | `█████████░░░░░░ 62%` |
| 7 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/34 | `██████░░░░░░░░░ 45%` |
| 8 | `crypto/tls.Client` | 16.51MB | 2/34 | `██████░░░░░░░░░ 45%` |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 15.01MB | 1/34 | `██████░░░░░░░░░ 40%` |
| 10 | `reflect.growslice` | 11.07MB | 2/34 | `████░░░░░░░░░░░ 30%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 67.38GB | 29/34 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 44.87GB | 23/34 | `█████████░░░░░░ 66%` |
| 3 | `fmt.(*buffer).writeString` | 26.68GB | 9/34 | `█████░░░░░░░░░░ 39%` |
| 4 | `reflect.growslice` | 25.49GB | 17/34 | `█████░░░░░░░░░░ 37%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 24.71GB | 29/34 | `█████░░░░░░░░░░ 36%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 24.54GB | 29/34 | `█████░░░░░░░░░░ 36%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 21.85GB | 28/34 | `████░░░░░░░░░░░ 32%` |
| 8 | `experiment/local.topologicalSort` | 17.94GB | 23/34 | `███░░░░░░░░░░░░ 26%` |
| 9 | `jackskj/carta.getUniqueId` | 15.48GB | 11/34 | `███░░░░░░░░░░░░ 22%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 14.72GB | 22/34 | `███░░░░░░░░░░░░ 21%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (6.4x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.0x avg)
