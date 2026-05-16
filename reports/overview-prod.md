# Overview: prod
*Last updated: 2026-05-16 21:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T21:03 (54 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,093 | avg: 15,847 | max: 84,644 | trend: decreasing (-128.54/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 118.5MB | avg: 253.0MB | max: 1896.6MB | trend: decreasing (-6.08MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,093 | 14,071 | +22 | 15,847 | 84,644 | decreasing (-128.54/hr) |
| Heap InUse | 118.5MB | 102.7MB | +15.8MB | 253.0MB | 1896.6MB | decreasing (-6.08MB/hr) |
| Heap Sys | 3471.4MB | 3472.5MB | -1.1MB | 4750.7MB | 5842.7MB | |
| Heap Objects | 532,379 | 325,365 | +207014 | 1,037,779 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 44 | 16,196 | 256.0MB | 1896.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.01MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 1.5MB |
| 10 | `reflect.unsafe_NewArray` | 1.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 30.34GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 13.76GB |
| 3 | `internal/evaluation.mergeMetadata` | 11.61GB |
| 4 | `segmentio/kafka-go.makePartitions` | 9.31GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 7.23GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 7.14GB |
| 7 | `reflect.unsafe_NewArray` | 4.96GB |
| 8 | `experiment/local.topologicalSort` | 4.7GB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 4.67GB |
| 10 | `database/sql.convertAssignRows` | 4.16GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 52/54 | `███████████████ 100%` |
| 2 | `runtime.mallocgc` | 31.87MB | 52/54 | `█████████████░░ 87%` |
| 3 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/54 | `████████████░░░ 83%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 30.07MB | 3/54 | `████████████░░░ 82%` |
| 5 | `net/http.(*Transport).dialConn` | 30.0MB | 1/54 | `████████████░░░ 81%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 23.0MB | 9/54 | `█████████░░░░░░ 62%` |
| 7 | `bytes.growSlice` | 18.32MB | 25/54 | `███████░░░░░░░░ 50%` |
| 8 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/54 | `██████░░░░░░░░░ 45%` |
| 9 | `crypto/tls.Client` | 16.51MB | 2/54 | `██████░░░░░░░░░ 45%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB | 1/54 | `██████░░░░░░░░░ 44%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 54.36GB | 49/54 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 37.14GB | 43/54 | `██████████░░░░░ 68%` |
| 3 | `reflect.growslice` | 25.45GB | 23/54 | `███████░░░░░░░░ 46%` |
| 4 | `fmt.(*buffer).writeString` | 24.63GB | 15/54 | `██████░░░░░░░░░ 45%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 21.66GB | 49/54 | `█████░░░░░░░░░░ 39%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 21.51GB | 49/54 | `█████░░░░░░░░░░ 39%` |
| 7 | `jackskj/carta.getUniqueId` | 19.62GB | 17/54 | `█████░░░░░░░░░░ 36%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.46GB | 48/54 | `█████░░░░░░░░░░ 35%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.87GB | 28/54 | `████░░░░░░░░░░░ 31%` |
| 10 | `experiment/local.topologicalSort` | 15.5GB | 41/54 | `████░░░░░░░░░░░ 28%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.5x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.3x avg)
