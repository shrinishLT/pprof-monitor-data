# Overview: prod
*Last updated: 2026-05-16 19:32 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T19:32 (51 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,146 | avg: 15,951 | max: 84,644 | trend: decreasing (-126.84/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 173.2MB | avg: 261.3MB | max: 1896.6MB | trend: decreasing (-5.13MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,146 | 15,051 | -905 | 15,951 | 84,644 | decreasing (-126.84/hr) |
| Heap InUse | 173.2MB | 193.5MB | -20.3MB | 261.3MB | 1896.6MB | decreasing (-5.13MB/hr) |
| Heap Sys | 3470.8MB | 3474.2MB | -3.4MB | 4826.0MB | 5842.7MB | |
| Heap Objects | 1,170,766 | 1,044,732 | +126034 | 1,074,384 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 41 | 16,351 | 266.7MB | 1896.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `reflect.unsafe_NewArray` | 3.02MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 1.5MB |
| 10 | `kafka-go/protocol.newPage` | 1.06MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 26.48GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 12.01GB |
| 3 | `internal/evaluation.mergeMetadata` | 9.8GB |
| 4 | `segmentio/kafka-go.makePartitions` | 7.25GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 6.11GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 6.02GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 4.08GB |
| 8 | `experiment/local.topologicalSort` | 3.97GB |
| 9 | `reflect.unsafe_NewArray` | 3.93GB |
| 10 | `database/sql.convertAssignRows` | 3.62GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 49/51 | `███████████████ 100%` |
| 2 | `runtime.mallocgc` | 33.15MB | 49/51 | `█████████████░░ 90%` |
| 3 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/51 | `████████████░░░ 83%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 30.07MB | 3/51 | `████████████░░░ 82%` |
| 5 | `net/http.(*Transport).dialConn` | 30.0MB | 1/51 | `████████████░░░ 81%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 23.0MB | 9/51 | `█████████░░░░░░ 62%` |
| 7 | `bytes.growSlice` | 18.32MB | 25/51 | `███████░░░░░░░░ 50%` |
| 8 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/51 | `██████░░░░░░░░░ 45%` |
| 9 | `crypto/tls.Client` | 16.51MB | 2/51 | `██████░░░░░░░░░ 45%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB | 1/51 | `██████░░░░░░░░░ 44%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 56.01GB | 46/51 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 39.07GB | 40/51 | `██████████░░░░░ 69%` |
| 3 | `reflect.growslice` | 25.45GB | 23/51 | `██████░░░░░░░░░ 45%` |
| 4 | `fmt.(*buffer).writeString` | 24.63GB | 15/51 | `██████░░░░░░░░░ 43%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 22.62GB | 46/51 | `██████░░░░░░░░░ 40%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 22.45GB | 46/51 | `██████░░░░░░░░░ 40%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 19.88GB | 45/51 | `█████░░░░░░░░░░ 35%` |
| 8 | `jackskj/carta.getUniqueId` | 19.62GB | 17/51 | `█████░░░░░░░░░░ 35%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.87GB | 28/51 | `████░░░░░░░░░░░ 30%` |
| 10 | `experiment/local.topologicalSort` | 16.36GB | 38/51 | `████░░░░░░░░░░░ 29%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.3x avg)
