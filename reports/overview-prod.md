# Overview: prod
*Last updated: 2026-05-16 18:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T18:03 (48 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,100 | avg: 16,046 | max: 84,644 | trend: decreasing (-126.88/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 107.3MB | avg: 266.7MB | max: 1896.6MB | trend: decreasing (-4.73MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 1%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,100 | 14,143 | -43 | 16,046 | 84,644 | decreasing (-126.88/hr) |
| Heap InUse | 107.3MB | 243.6MB | -136.3MB | 266.7MB | 1896.6MB | decreasing (-4.73MB/hr) |
| Heap Sys | 3474.4MB | 3474.3MB | +0.1MB | 4910.5MB | 5842.7MB | |
| Heap Objects | 392,723 | 1,182,039 | -789316 | 1,072,214 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 38 | 16,502 | 273.9MB | 1896.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 10.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 1.5MB |
| 10 | `reflect.mapassign_faststr0` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 20.52GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 9.31GB |
| 3 | `internal/evaluation.mergeMetadata` | 6.15GB |
| 4 | `segmentio/kafka-go.makePartitions` | 5.31GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 3.82GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 3.72GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 3.13GB |
| 8 | `reflect.unsafe_NewArray` | 2.83GB |
| 9 | `database/sql.convertAssignRows` | 2.75GB |
| 10 | `experiment/local.topologicalSort` | 2.49GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 46/48 | `███████████████ 100%` |
| 2 | `runtime.mallocgc` | 34.61MB | 46/48 | `██████████████░ 94%` |
| 3 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/48 | `████████████░░░ 83%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 30.07MB | 3/48 | `████████████░░░ 82%` |
| 5 | `net/http.(*Transport).dialConn` | 30.0MB | 1/48 | `████████████░░░ 81%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 25.43MB | 8/48 | `██████████░░░░░ 69%` |
| 7 | `bytes.growSlice` | 18.91MB | 24/48 | `███████░░░░░░░░ 51%` |
| 8 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/48 | `██████░░░░░░░░░ 45%` |
| 9 | `crypto/tls.Client` | 16.51MB | 2/48 | `██████░░░░░░░░░ 45%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB | 1/48 | `██████░░░░░░░░░ 44%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.2GB | 43/48 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 41.58GB | 37/48 | `██████████░░░░░ 71%` |
| 3 | `reflect.growslice` | 25.45GB | 23/48 | `██████░░░░░░░░░ 43%` |
| 4 | `fmt.(*buffer).writeString` | 24.63GB | 15/48 | `██████░░░░░░░░░ 42%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 23.84GB | 43/48 | `██████░░░░░░░░░ 40%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 23.67GB | 43/48 | `██████░░░░░░░░░ 40%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 20.5GB | 42/48 | `█████░░░░░░░░░░ 35%` |
| 8 | `jackskj/carta.getUniqueId` | 19.62GB | 17/48 | `█████░░░░░░░░░░ 33%` |
| 9 | `experiment/local.topologicalSort` | 17.07GB | 36/48 | `████░░░░░░░░░░░ 29%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.87GB | 28/48 | `████░░░░░░░░░░░ 28%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.3x avg)
