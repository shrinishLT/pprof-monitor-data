# Overview: prod
*Last updated: 2026-05-16 22:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T22:31 (57 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,074 | avg: 15,758 | max: 84,644 | trend: decreasing (-127.12/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 174.4MB | avg: 248.1MB | max: 1896.6MB | trend: decreasing (-6.14MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,074 | 14,140 | -66 | 15,758 | 84,644 | decreasing (-127.12/hr) |
| Heap InUse | 174.4MB | 172.5MB | +1.9MB | 248.1MB | 1896.6MB | decreasing (-6.14MB/hr) |
| Heap Sys | 3471.8MB | 3471.5MB | +0.3MB | 4683.4MB | 5842.7MB | |
| Heap Objects | 1,275,799 | 1,027,822 | +247977 | 1,034,718 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 47 | 16,066 | 249.9MB | 1896.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `reflect.mapassign_faststr0` | 3.0MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.54MB |
| 8 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `reflect.unsafe_NewArray` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 35.7GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 16.25GB |
| 3 | `internal/evaluation.mergeMetadata` | 12.9GB |
| 4 | `segmentio/kafka-go.makePartitions` | 11.34GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 8.0GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 7.93GB |
| 7 | `reflect.unsafe_NewArray` | 5.99GB |
| 8 | `go-sql-driver/mysql.(*binaryRows).readRow` | 5.51GB |
| 9 | `experiment/local.topologicalSort` | 5.2GB |
| 10 | `database/sql.convertAssignRows` | 4.91GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 55/57 | `███████████████ 100%` |
| 2 | `runtime.mallocgc` | 30.73MB | 55/57 | `████████████░░░ 83%` |
| 3 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/57 | `████████████░░░ 83%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 30.07MB | 3/57 | `████████████░░░ 82%` |
| 5 | `net/http.(*Transport).dialConn` | 30.0MB | 1/57 | `████████████░░░ 81%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 23.0MB | 9/57 | `█████████░░░░░░ 62%` |
| 7 | `bytes.growSlice` | 18.32MB | 25/57 | `███████░░░░░░░░ 50%` |
| 8 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/57 | `██████░░░░░░░░░ 45%` |
| 9 | `crypto/tls.Client` | 16.51MB | 2/57 | `██████░░░░░░░░░ 45%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB | 1/57 | `██████░░░░░░░░░ 44%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 53.18GB | 52/57 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 35.53GB | 46/57 | `██████████░░░░░ 66%` |
| 3 | `reflect.growslice` | 25.45GB | 23/57 | `███████░░░░░░░░ 47%` |
| 4 | `fmt.(*buffer).writeString` | 24.63GB | 15/57 | `██████░░░░░░░░░ 46%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 20.86GB | 52/57 | `█████░░░░░░░░░░ 39%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 20.71GB | 52/57 | `█████░░░░░░░░░░ 38%` |
| 7 | `jackskj/carta.getUniqueId` | 19.62GB | 17/57 | `█████░░░░░░░░░░ 36%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.22GB | 51/57 | `█████░░░░░░░░░░ 36%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.87GB | 28/57 | `████░░░░░░░░░░░ 31%` |
| 10 | `experiment/local.topologicalSort` | 14.78GB | 44/57 | `████░░░░░░░░░░░ 27%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.6x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
