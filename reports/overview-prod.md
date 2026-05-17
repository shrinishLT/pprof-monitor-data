# Overview: prod
*Last updated: 2026-05-17 18:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T18:03 (96 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,446 | avg: 15,425 | max: 84,644 | trend: decreasing (-48.04/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 174.1MB | avg: 221.1MB | max: 1896.6MB | trend: decreasing (-3.18MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,446 | 14,154 | +292 | 15,425 | 84,644 | decreasing (-48.04/hr) |
| Heap InUse | 174.1MB | 119.2MB | +54.9MB | 221.1MB | 1896.6MB | decreasing (-3.18MB/hr) |
| Heap Sys | 3576.1MB | 3576.4MB | -0.3MB | 4175.7MB | 5842.7MB | |
| Heap Objects | 917,442 | 489,395 | +428047 | 963,552 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 37 | 14,985 | 183.3MB | 391.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 8.58MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 2.53MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.01MB |
| 8 | `compress/flate.NewWriter` | 1.76MB |
| 9 | `bytes.growSlice` | 1.57MB |
| 10 | `encoding/json.typeFields` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 23.67GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 20.9GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 14.23GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 14.19GB |
| 5 | `experiment/local.topologicalSort` | 9.51GB |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 9.44GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 6.94GB |
| 8 | `segmentio/kafka-go.makePartitions` | 5.21GB |
| 9 | `internal/evaluation.(*Engine).evaluateFlag` | 4.47GB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 3.4GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 94/96 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 36.12MB | 6/96 | `██████████████░ 98%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/96 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 24.0MB | 94/96 | `█████████░░░░░░ 65%` |
| 5 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/96 | `███████░░░░░░░░ 50%` |
| 6 | `database/sql.convertAssignRows` | 15.43MB | 7/96 | `██████░░░░░░░░░ 42%` |
| 7 | `bytes.growSlice` | 13.61MB | 49/96 | `█████░░░░░░░░░░ 37%` |
| 8 | `crypto/tls.Client` | 13.01MB | 3/96 | `█████░░░░░░░░░░ 35%` |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.03MB | 23/96 | `████░░░░░░░░░░░ 32%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 12.01MB | 7/96 | `████░░░░░░░░░░░ 32%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 52.76GB | 89/96 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 29.49GB | 85/96 | `████████░░░░░░░ 55%` |
| 3 | `fmt.(*buffer).writeString` | 24.13GB | 16/96 | `██████░░░░░░░░░ 45%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 21.35GB | 87/96 | `██████░░░░░░░░░ 40%` |
| 5 | `reflect.growslice` | 20.37GB | 36/96 | `█████░░░░░░░░░░ 38%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 17.76GB | 91/96 | `█████░░░░░░░░░░ 33%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 17.65GB | 91/96 | `█████░░░░░░░░░░ 33%` |
| 8 | `jackskj/carta.getUniqueId` | 17.48GB | 25/96 | `████░░░░░░░░░░░ 33%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 16.01GB | 5/96 | `████░░░░░░░░░░░ 30%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 13.41GB | 41/96 | `███░░░░░░░░░░░░ 25%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.6x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
