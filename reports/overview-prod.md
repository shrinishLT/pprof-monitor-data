# Overview: prod
*Last updated: 2026-05-17 21:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T21:31 (103 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,087 | avg: 15,343 | max: 84,644 | trend: decreasing (-47.90/hr))
```
▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 107.3MB | avg: 215.7MB | max: 1896.6MB | trend: decreasing (-3.17MB/hr))
```
▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 1%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,087 | 14,279 | -192 | 15,343 | 84,644 | decreasing (-47.90/hr) |
| Heap InUse | 107.3MB | 132.2MB | -24.9MB | 215.7MB | 1896.6MB | decreasing (-3.17MB/hr) |
| Heap Sys | 3885.4MB | 3577.0MB | +308.4MB | 4137.9MB | 5842.7MB | |
| Heap Objects | 396,958 | 582,447 | -185489 | 944,528 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 44 | 14,861 | 176.6MB | 391.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 8.58MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 8 | `encoding/json.typeFields` | 1.5MB |
| 9 | `aws/endpoints.init` | 1.5MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 39.58GB |
| 2 | `internal/evaluation.mergeMetadata` | 32.3GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 19.44GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 19.36GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 17.97GB |
| 6 | `experiment/local.topologicalSort` | 12.96GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 9.45GB |
| 8 | `segmentio/kafka-go.makePartitions` | 9.34GB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 6.31GB |
| 10 | `internal/evaluation.(*Engine).evaluateFlag` | 6.1GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 101/103 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 36.12MB | 6/103 | `██████████████░ 98%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/103 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 22.93MB | 101/103 | `█████████░░░░░░ 62%` |
| 5 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/103 | `███████░░░░░░░░ 50%` |
| 6 | `database/sql.convertAssignRows` | 15.43MB | 7/103 | `██████░░░░░░░░░ 42%` |
| 7 | `bytes.growSlice` | 13.37MB | 50/103 | `█████░░░░░░░░░░ 36%` |
| 8 | `crypto/tls.Client` | 13.01MB | 3/103 | `█████░░░░░░░░░░ 35%` |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.03MB | 23/103 | `████░░░░░░░░░░░ 32%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 12.01MB | 7/103 | `████░░░░░░░░░░░ 32%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 51.22GB | 96/103 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 29.48GB | 92/103 | `████████░░░░░░░ 57%` |
| 3 | `fmt.(*buffer).writeString` | 24.13GB | 16/103 | `███████░░░░░░░░ 47%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 20.82GB | 94/103 | `██████░░░░░░░░░ 40%` |
| 5 | `reflect.growslice` | 20.37GB | 36/103 | `█████░░░░░░░░░░ 39%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 17.75GB | 98/103 | `█████░░░░░░░░░░ 34%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 17.65GB | 98/103 | `█████░░░░░░░░░░ 34%` |
| 8 | `jackskj/carta.getUniqueId` | 17.48GB | 25/103 | `█████░░░░░░░░░░ 34%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 16.01GB | 5/103 | `████░░░░░░░░░░░ 31%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 12.7GB | 48/103 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
