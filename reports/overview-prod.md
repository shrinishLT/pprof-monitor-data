# Overview: prod
*Last updated: 2026-05-16 19:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T19:01 (50 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,051 | avg: 15,987 | max: 84,644 | trend: decreasing (-125.76/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 193.5MB | avg: 263.1MB | max: 1896.6MB | trend: decreasing (-5.02MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,051 | 14,090 | +961 | 15,987 | 84,644 | decreasing (-125.76/hr) |
| Heap InUse | 193.5MB | 159.0MB | +34.5MB | 263.1MB | 1896.6MB | decreasing (-5.02MB/hr) |
| Heap Sys | 3474.2MB | 3474.7MB | -0.5MB | 4853.1MB | 5842.7MB | |
| Heap Objects | 1,044,732 | 1,111,800 | -67068 | 1,072,457 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 40 | 16,406 | 269.0MB | 1896.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 10.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `bytes.growSlice` | 4.02MB |
| 6 | `bufio.NewWriterSize` | 3.53MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.52MB |
| 8 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `segmentio/kafka-go.makePartitions` | 2.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 23.8GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 10.8GB |
| 3 | `internal/evaluation.mergeMetadata` | 7.64GB |
| 4 | `segmentio/kafka-go.makePartitions` | 6.62GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 4.77GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 4.66GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 3.66GB |
| 8 | `reflect.unsafe_NewArray` | 3.54GB |
| 9 | `database/sql.convertAssignRows` | 3.24GB |
| 10 | `experiment/local.topologicalSort` | 3.1GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 48/50 | `███████████████ 100%` |
| 2 | `runtime.mallocgc` | 33.61MB | 48/50 | `█████████████░░ 91%` |
| 3 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/50 | `████████████░░░ 83%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 30.07MB | 3/50 | `████████████░░░ 82%` |
| 5 | `net/http.(*Transport).dialConn` | 30.0MB | 1/50 | `████████████░░░ 81%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 23.0MB | 9/50 | `█████████░░░░░░ 62%` |
| 7 | `bytes.growSlice` | 18.32MB | 25/50 | `███████░░░░░░░░ 50%` |
| 8 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/50 | `██████░░░░░░░░░ 45%` |
| 9 | `crypto/tls.Client` | 16.51MB | 2/50 | `██████░░░░░░░░░ 45%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB | 1/50 | `██████░░░░░░░░░ 44%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 56.67GB | 45/50 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 39.82GB | 39/50 | `██████████░░░░░ 70%` |
| 3 | `reflect.growslice` | 25.45GB | 23/50 | `██████░░░░░░░░░ 44%` |
| 4 | `fmt.(*buffer).writeString` | 24.63GB | 15/50 | `██████░░░░░░░░░ 43%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 22.98GB | 45/50 | `██████░░░░░░░░░ 40%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 22.82GB | 45/50 | `██████░░░░░░░░░ 40%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 20.06GB | 44/50 | `█████░░░░░░░░░░ 35%` |
| 8 | `jackskj/carta.getUniqueId` | 19.62GB | 17/50 | `█████░░░░░░░░░░ 34%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.87GB | 28/50 | `████░░░░░░░░░░░ 29%` |
| 10 | `experiment/local.topologicalSort` | 16.69GB | 37/50 | `████░░░░░░░░░░░ 29%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.3x avg)
