# Overview: prod
*Last updated: 2026-05-16 17:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T17:01 (46 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,098 | avg: 16,129 | max: 84,644 | trend: decreasing (-121.38/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 162.5MB | avg: 270.7MB | max: 1896.6MB | trend: decreasing (-4.28MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,098 | 14,162 | -64 | 16,129 | 84,644 | decreasing (-121.38/hr) |
| Heap InUse | 162.5MB | 139.5MB | +23.0MB | 270.7MB | 1896.6MB | decreasing (-4.28MB/hr) |
| Heap Sys | 3298.2MB | 3298.0MB | +0.2MB | 4973.0MB | 5842.7MB | |
| Heap Objects | 1,025,043 | 685,271 | +339772 | 1,084,599 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 36 | 16,634 | 279.4MB | 1896.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 10.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.02MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `reflect.unsafe_NewArray` | 1.51MB |
| 10 | `aws/endpoints.init` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 14.99GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 6.81GB |
| 3 | `internal/evaluation.mergeMetadata` | 5.23GB |
| 4 | `segmentio/kafka-go.makePartitions` | 3.95GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 3.24GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 3.16GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.34GB |
| 8 | `experiment/local.topologicalSort` | 2.12GB |
| 9 | `reflect.unsafe_NewArray` | 2.09GB |
| 10 | `database/sql.convertAssignRows` | 2.04GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 44/46 | `███████████████ 100%` |
| 2 | `runtime.mallocgc` | 35.73MB | 44/46 | `██████████████░ 97%` |
| 3 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/46 | `████████████░░░ 83%` |
| 4 | `net/http.(*Transport).dialConn` | 30.0MB | 1/46 | `████████████░░░ 81%` |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 27.04MB | 2/46 | `███████████░░░░ 73%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 25.43MB | 8/46 | `██████████░░░░░ 69%` |
| 7 | `bytes.growSlice` | 18.91MB | 24/46 | `███████░░░░░░░░ 51%` |
| 8 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/46 | `██████░░░░░░░░░ 45%` |
| 9 | `crypto/tls.Client` | 16.51MB | 2/46 | `██████░░░░░░░░░ 45%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB | 1/46 | `██████░░░░░░░░░ 44%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 60.04GB | 41/46 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 43.61GB | 35/46 | `██████████░░░░░ 72%` |
| 3 | `reflect.growslice` | 25.45GB | 23/46 | `██████░░░░░░░░░ 42%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 24.82GB | 41/46 | `██████░░░░░░░░░ 41%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 24.65GB | 41/46 | `██████░░░░░░░░░ 41%` |
| 6 | `fmt.(*buffer).writeString` | 24.63GB | 15/46 | `██████░░░░░░░░░ 41%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 21.06GB | 40/46 | `█████░░░░░░░░░░ 35%` |
| 8 | `jackskj/carta.getUniqueId` | 19.62GB | 17/46 | `████░░░░░░░░░░░ 32%` |
| 9 | `experiment/local.topologicalSort` | 17.93GB | 34/46 | `████░░░░░░░░░░░ 29%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.87GB | 28/46 | `████░░░░░░░░░░░ 28%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.2x avg)
