# Overview: prod
*Last updated: 2026-05-17 19:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T19:31 (99 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,138 | avg: 15,391 | max: 84,644 | trend: decreasing (-47.91/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 122.0MB | avg: 218.8MB | max: 1896.6MB | trend: decreasing (-3.18MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,138 | 14,570 | -432 | 15,391 | 84,644 | decreasing (-47.91/hr) |
| Heap InUse | 122.0MB | 179.9MB | -57.9MB | 218.8MB | 1896.6MB | decreasing (-3.18MB/hr) |
| Heap Sys | 3576.8MB | 3575.6MB | +1.2MB | 4157.5MB | 5842.7MB | |
| Heap Objects | 482,074 | 931,352 | -449278 | 954,569 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 40 | 14,932 | 180.3MB | 391.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 8.58MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `encoding/json.typeFields` | 1.5MB |
| 8 | `reflect.mapassign_faststr0` | 1.5MB |
| 9 | `aws/endpoints.init` | 1.5MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 30.42GB |
| 2 | `internal/evaluation.mergeMetadata` | 29.14GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 17.56GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 17.45GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 13.77GB |
| 6 | `experiment/local.topologicalSort` | 11.67GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 8.51GB |
| 8 | `segmentio/kafka-go.makePartitions` | 6.96GB |
| 9 | `internal/evaluation.(*Engine).evaluateFlag` | 5.49GB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 4.82GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 97/99 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 36.12MB | 6/99 | `██████████████░ 98%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/99 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 23.53MB | 97/99 | `█████████░░░░░░ 64%` |
| 5 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/99 | `███████░░░░░░░░ 50%` |
| 6 | `database/sql.convertAssignRows` | 15.43MB | 7/99 | `██████░░░░░░░░░ 42%` |
| 7 | `bytes.growSlice` | 13.37MB | 50/99 | `█████░░░░░░░░░░ 36%` |
| 8 | `crypto/tls.Client` | 13.01MB | 3/99 | `█████░░░░░░░░░░ 35%` |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.03MB | 23/99 | `████░░░░░░░░░░░ 32%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 12.01MB | 7/99 | `████░░░░░░░░░░░ 32%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 51.93GB | 92/99 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 29.4GB | 88/99 | `████████░░░░░░░ 56%` |
| 3 | `fmt.(*buffer).writeString` | 24.13GB | 16/99 | `██████░░░░░░░░░ 46%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 21.05GB | 90/99 | `██████░░░░░░░░░ 40%` |
| 5 | `reflect.growslice` | 20.37GB | 36/99 | `█████░░░░░░░░░░ 39%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 17.71GB | 94/99 | `█████░░░░░░░░░░ 34%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 17.6GB | 94/99 | `█████░░░░░░░░░░ 33%` |
| 8 | `jackskj/carta.getUniqueId` | 17.48GB | 25/99 | `█████░░░░░░░░░░ 33%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 16.01GB | 5/99 | `████░░░░░░░░░░░ 30%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 13.03GB | 44/99 | `███░░░░░░░░░░░░ 25%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.7x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
