# Overview: prod
*Last updated: 2026-05-17 09:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T09:01 (78 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,586 | avg: 15,389 | max: 84,644 | trend: decreasing (-90.37/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 140.2MB | avg: 224.7MB | max: 1896.6MB | trend: decreasing (-4.99MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,586 | 14,151 | +435 | 15,389 | 84,644 | decreasing (-90.37/hr) |
| Heap InUse | 140.2MB | 175.4MB | -35.2MB | 224.7MB | 1896.6MB | decreasing (-4.99MB/hr) |
| Heap Sys | 4131.2MB | 4131.0MB | +0.2MB | 4435.2MB | 5842.7MB | |
| Heap Objects | 466,462 | 1,096,927 | -630465 | 992,636 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 19 | 14,419 | 162.2MB | 211.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.01MB |
| 6 | `bytes.growSlice` | 3.01MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 2.0MB |
| 10 | `compress/flate.NewWriter` | 1.76MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 97.48GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 44.44GB |
| 3 | `internal/evaluation.mergeMetadata` | 29.68GB |
| 4 | `segmentio/kafka-go.makePartitions` | 25.68GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 18.13GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 18.03GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 16.52GB |
| 8 | `database/sql.convertAssignRows` | 13.43GB |
| 9 | `reflect.unsafe_NewArray` | 13.29GB |
| 10 | `experiment/local.topologicalSort` | 11.92GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 76/78 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 35.48MB | 5/78 | `██████████████░ 96%` |
| 3 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/78 | `████████████░░░ 83%` |
| 4 | `net/http.(*Transport).dialConn` | 30.0MB | 1/78 | `████████████░░░ 81%` |
| 5 | `runtime.mallocgc` | 25.28MB | 76/78 | `██████████░░░░░ 69%` |
| 6 | `crypto/tls.Client` | 16.51MB | 2/78 | `██████░░░░░░░░░ 45%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB | 1/78 | `██████░░░░░░░░░ 44%` |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 15.93MB | 14/78 | `██████░░░░░░░░░ 43%` |
| 9 | `bytes.growSlice` | 14.99MB | 33/78 | `██████░░░░░░░░░ 40%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 13.61MB | 5/78 | `█████░░░░░░░░░░ 37%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 55.72GB | 73/78 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 30.73GB | 67/78 | `████████░░░░░░░ 55%` |
| 3 | `fmt.(*buffer).writeString` | 24.63GB | 15/78 | `██████░░░░░░░░░ 44%` |
| 4 | `reflect.growslice` | 22.46GB | 29/78 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 21.85GB | 72/78 | `█████░░░░░░░░░░ 39%` |
| 6 | `jackskj/carta.getUniqueId` | 18.63GB | 19/78 | `█████░░░░░░░░░░ 33%` |
| 7 | `internal/evaluation.(*Engine).Evaluate` | 18.44GB | 73/78 | `████░░░░░░░░░░░ 33%` |
| 8 | `experiment/local.(*Client).EvaluateV2` | 18.3GB | 73/78 | `████░░░░░░░░░░░ 32%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.87GB | 28/78 | `████░░░░░░░░░░░ 30%` |
| 10 | `segmentio/kafka-go.makePartitions` | 13.12GB | 38/78 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.4x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
