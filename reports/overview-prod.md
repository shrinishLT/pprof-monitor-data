# Overview: prod
*Last updated: 2026-05-17 04:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T04:02 (68 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,306 | avg: 15,516 | max: 84,644 | trend: decreasing (-110.44/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 175.1MB | avg: 232.7MB | max: 1896.6MB | trend: decreasing (-5.90MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,306 | 14,201 | +105 | 15,516 | 84,644 | decreasing (-110.44/hr) |
| Heap InUse | 175.1MB | 137.3MB | +37.8MB | 232.7MB | 1896.6MB | decreasing (-5.90MB/hr) |
| Heap Sys | 3589.3MB | 3589.1MB | +0.2MB | 4490.8MB | 5842.7MB | |
| Heap Objects | 1,073,042 | 582,485 | +490557 | 1,006,731 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 9 | 14,300 | 152.8MB | 184.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `bytes.growSlice` | 2.01MB |
| 9 | `aws/endpoints.init` | 1.5MB |
| 10 | `reflect.mapassign_faststr0` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 52.7GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 23.95GB |
| 3 | `internal/evaluation.mergeMetadata` | 19.28GB |
| 4 | `segmentio/kafka-go.makePartitions` | 18.95GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 11.87GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 11.78GB |
| 7 | `reflect.unsafe_NewArray` | 9.83GB |
| 8 | `go-sql-driver/mysql.(*binaryRows).readRow` | 8.51GB |
| 9 | `experiment/local.topologicalSort` | 7.7GB |
| 10 | `database/sql.convertAssignRows` | 7.37GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 66/68 | `███████████████ 100%` |
| 2 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/68 | `████████████░░░ 83%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/68 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 27.45MB | 66/68 | `███████████░░░░ 74%` |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 23.43MB | 4/68 | `█████████░░░░░░ 63%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 21.1MB | 10/68 | `████████░░░░░░░ 57%` |
| 7 | `bytes.growSlice` | 16.79MB | 28/68 | `██████░░░░░░░░░ 45%` |
| 8 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/68 | `██████░░░░░░░░░ 45%` |
| 9 | `crypto/tls.Client` | 16.51MB | 2/68 | `██████░░░░░░░░░ 45%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB | 1/68 | `██████░░░░░░░░░ 44%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 51.63GB | 63/68 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 31.7GB | 57/68 | `█████████░░░░░░ 61%` |
| 3 | `reflect.growslice` | 25.45GB | 23/68 | `███████░░░░░░░░ 49%` |
| 4 | `fmt.(*buffer).writeString` | 24.63GB | 15/68 | `███████░░░░░░░░ 47%` |
| 5 | `jackskj/carta.getUniqueId` | 19.62GB | 17/68 | `█████░░░░░░░░░░ 38%` |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 19.39GB | 62/68 | `█████░░░░░░░░░░ 37%` |
| 7 | `internal/evaluation.(*Engine).Evaluate` | 18.91GB | 63/68 | `█████░░░░░░░░░░ 36%` |
| 8 | `experiment/local.(*Client).EvaluateV2` | 18.77GB | 63/68 | `█████░░░░░░░░░░ 36%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.87GB | 28/68 | `████░░░░░░░░░░░ 32%` |
| 10 | `experiment/local.topologicalSort` | 13.22GB | 54/68 | `███░░░░░░░░░░░░ 25%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
