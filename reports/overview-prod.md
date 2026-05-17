# Overview: prod
*Last updated: 2026-05-17 17:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T17:31 (95 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,154 | avg: 15,436 | max: 84,644 | trend: decreasing (-48.26/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 119.2MB | avg: 221.6MB | max: 1896.6MB | trend: decreasing (-3.22MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,154 | 14,451 | -297 | 15,436 | 84,644 | decreasing (-48.26/hr) |
| Heap InUse | 119.2MB | 152.7MB | -33.5MB | 221.6MB | 1896.6MB | decreasing (-3.22MB/hr) |
| Heap Sys | 3576.4MB | 3112.0MB | +464.4MB | 4182.0MB | 5842.7MB | |
| Heap Objects | 489,395 | 679,904 | -190509 | 964,037 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 36 | 15,000 | 183.6MB | 391.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 8.58MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.51MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `bytes.growSlice` | 1.84MB |
| 9 | `encoding/json.typeFields` | 1.5MB |
| 10 | `aws/endpoints.init` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 22.96GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 20.87GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 13.81GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 13.77GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 9.42GB |
| 6 | `experiment/local.topologicalSort` | 9.22GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 6.76GB |
| 8 | `segmentio/kafka-go.makePartitions` | 4.6GB |
| 9 | `internal/evaluation.(*Engine).evaluateFlag` | 4.34GB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 3.38GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 93/95 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 36.12MB | 6/95 | `██████████████░ 98%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/95 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 24.17MB | 93/95 | `█████████░░░░░░ 65%` |
| 5 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/95 | `███████░░░░░░░░ 50%` |
| 6 | `database/sql.convertAssignRows` | 15.43MB | 7/95 | `██████░░░░░░░░░ 42%` |
| 7 | `bytes.growSlice` | 13.86MB | 48/95 | `█████░░░░░░░░░░ 37%` |
| 8 | `crypto/tls.Client` | 13.01MB | 3/95 | `█████░░░░░░░░░░ 35%` |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.49MB | 22/95 | `█████░░░░░░░░░░ 34%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 12.01MB | 7/95 | `████░░░░░░░░░░░ 32%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 53.13GB | 88/95 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 29.56GB | 84/95 | `████████░░░░░░░ 55%` |
| 3 | `fmt.(*buffer).writeString` | 24.13GB | 16/95 | `██████░░░░░░░░░ 45%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 21.48GB | 86/95 | `██████░░░░░░░░░ 40%` |
| 5 | `reflect.growslice` | 20.37GB | 36/95 | `█████░░░░░░░░░░ 38%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 17.8GB | 90/95 | `█████░░░░░░░░░░ 33%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 17.69GB | 90/95 | `████░░░░░░░░░░░ 33%` |
| 8 | `jackskj/carta.getUniqueId` | 17.48GB | 25/95 | `████░░░░░░░░░░░ 32%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 16.01GB | 5/95 | `████░░░░░░░░░░░ 30%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 13.57GB | 40/95 | `███░░░░░░░░░░░░ 25%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.6x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
