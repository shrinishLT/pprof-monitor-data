# Overview: prod
*Last updated: 2026-05-17 20:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T20:03 (100 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,164 | avg: 15,378 | max: 84,644 | trend: decreasing (-47.94/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 150.1MB | avg: 218.1MB | max: 1896.6MB | trend: decreasing (-3.16MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,164 | 14,138 | +26 | 15,378 | 84,644 | decreasing (-47.94/hr) |
| Heap InUse | 150.1MB | 122.0MB | +28.1MB | 218.1MB | 1896.6MB | decreasing (-3.16MB/hr) |
| Heap Sys | 3576.3MB | 3576.8MB | -0.5MB | 4151.7MB | 5842.7MB | |
| Heap Objects | 762,611 | 482,074 | +280537 | 952,650 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 41 | 14,913 | 179.6MB | 391.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 8.58MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.52MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.growslice` | 1.51MB |
| 9 | `encoding/json.typeFields` | 1.5MB |
| 10 | `aws/endpoints.init` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 30.45GB |
| 2 | `internal/evaluation.mergeMetadata` | 29.64GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 17.86GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 17.75GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 13.79GB |
| 6 | `experiment/local.topologicalSort` | 11.89GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 8.66GB |
| 8 | `segmentio/kafka-go.makePartitions` | 7.6GB |
| 9 | `internal/evaluation.(*Engine).evaluateFlag` | 5.59GB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 4.86GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 98/100 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 36.12MB | 6/100 | `██████████████░ 98%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/100 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 23.37MB | 98/100 | `█████████░░░░░░ 63%` |
| 5 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/100 | `███████░░░░░░░░ 50%` |
| 6 | `database/sql.convertAssignRows` | 15.43MB | 7/100 | `██████░░░░░░░░░ 42%` |
| 7 | `bytes.growSlice` | 13.37MB | 50/100 | `█████░░░░░░░░░░ 36%` |
| 8 | `crypto/tls.Client` | 13.01MB | 3/100 | `█████░░░░░░░░░░ 35%` |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.03MB | 23/100 | `████░░░░░░░░░░░ 32%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 12.01MB | 7/100 | `████░░░░░░░░░░░ 32%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 51.7GB | 93/100 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 29.4GB | 89/100 | `████████░░░░░░░ 56%` |
| 3 | `fmt.(*buffer).writeString` | 24.13GB | 16/100 | `███████░░░░░░░░ 46%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 20.97GB | 91/100 | `██████░░░░░░░░░ 40%` |
| 5 | `reflect.growslice` | 20.37GB | 36/100 | `█████░░░░░░░░░░ 39%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 17.71GB | 95/100 | `█████░░░░░░░░░░ 34%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 17.6GB | 95/100 | `█████░░░░░░░░░░ 34%` |
| 8 | `jackskj/carta.getUniqueId` | 17.48GB | 25/100 | `█████░░░░░░░░░░ 33%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 16.01GB | 5/100 | `████░░░░░░░░░░░ 30%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 12.93GB | 45/100 | `███░░░░░░░░░░░░ 25%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.7x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
