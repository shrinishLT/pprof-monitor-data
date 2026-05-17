# Overview: prod
*Last updated: 2026-05-17 17:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T17:02 (94 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,451 | avg: 15,449 | max: 84,644 | trend: decreasing (-48.06/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 152.7MB | avg: 222.7MB | max: 1896.6MB | trend: decreasing (-3.18MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,451 | 14,423 | +28 | 15,449 | 84,644 | decreasing (-48.06/hr) |
| Heap InUse | 152.7MB | 121.2MB | +31.5MB | 222.7MB | 1896.6MB | decreasing (-3.18MB/hr) |
| Heap Sys | 3112.0MB | 3112.1MB | -0.1MB | 4188.4MB | 5842.7MB | |
| Heap Objects | 679,904 | 395,781 | +284123 | 969,087 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 35 | 15,024 | 185.4MB | 391.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 8.58MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.01MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `internal/evaluation.mergeMetadata` | 2.0MB |
| 8 | `compress/flate.NewWriter` | 1.76MB |
| 9 | `encoding/json.typeFields` | 1.5MB |
| 10 | `reflect.mapassign_faststr0` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 21.72GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 17.26GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 13.06GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 13.04GB |
| 5 | `experiment/local.topologicalSort` | 8.71GB |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 7.79GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 6.4GB |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 4.11GB |
| 9 | `segmentio/kafka-go.makePartitions` | 4.06GB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.75GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 92/94 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 36.12MB | 6/94 | `██████████████░ 98%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/94 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 24.34MB | 92/94 | `█████████░░░░░░ 66%` |
| 5 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/94 | `███████░░░░░░░░ 50%` |
| 6 | `database/sql.convertAssignRows` | 15.43MB | 7/94 | `██████░░░░░░░░░ 42%` |
| 7 | `bytes.growSlice` | 14.11MB | 47/94 | `█████░░░░░░░░░░ 38%` |
| 8 | `crypto/tls.Client` | 13.01MB | 3/94 | `█████░░░░░░░░░░ 35%` |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.49MB | 22/94 | `█████░░░░░░░░░░ 34%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 12.01MB | 7/94 | `████░░░░░░░░░░░ 32%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 53.5GB | 87/94 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 29.64GB | 83/94 | `████████░░░░░░░ 55%` |
| 3 | `fmt.(*buffer).writeString` | 24.13GB | 16/94 | `██████░░░░░░░░░ 45%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 21.63GB | 85/94 | `██████░░░░░░░░░ 40%` |
| 5 | `reflect.growslice` | 20.37GB | 36/94 | `█████░░░░░░░░░░ 38%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 17.85GB | 89/94 | `█████░░░░░░░░░░ 33%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 17.73GB | 89/94 | `████░░░░░░░░░░░ 33%` |
| 8 | `jackskj/carta.getUniqueId` | 17.48GB | 25/94 | `████░░░░░░░░░░░ 32%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 16.01GB | 5/94 | `████░░░░░░░░░░░ 29%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 13.74GB | 39/94 | `███░░░░░░░░░░░░ 25%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.5x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
