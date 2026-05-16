# Overview: prod
*Last updated: 2026-05-16 22:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T22:01 (56 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,140 | avg: 15,788 | max: 84,644 | trend: decreasing (-127.49/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 172.5MB | avg: 249.4MB | max: 1896.6MB | trend: decreasing (-6.19MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,140 | 14,241 | -101 | 15,788 | 84,644 | decreasing (-127.49/hr) |
| Heap InUse | 172.5MB | 132.3MB | +40.2MB | 249.4MB | 1896.6MB | decreasing (-6.19MB/hr) |
| Heap Sys | 3471.5MB | 3471.6MB | -0.1MB | 4705.1MB | 5842.7MB | |
| Heap Objects | 1,027,822 | 635,198 | +392624 | 1,030,413 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 46 | 16,109 | 251.5MB | 1896.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `compress/flate.NewWriter` | 1.76MB |
| 8 | `aws/endpoints.init` | 1.5MB |
| 9 | `segmentio/kafka-go.makePartitions` | 1.0MB |
| 10 | `jasonlvhit/gocron.NewScheduler` | 553.04kB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 33.04GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.02GB |
| 3 | `internal/evaluation.mergeMetadata` | 12.26GB |
| 4 | `segmentio/kafka-go.makePartitions` | 10.65GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 7.62GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 7.55GB |
| 7 | `reflect.unsafe_NewArray` | 5.64GB |
| 8 | `go-sql-driver/mysql.(*binaryRows).readRow` | 5.1GB |
| 9 | `experiment/local.topologicalSort` | 4.97GB |
| 10 | `database/sql.convertAssignRows` | 4.53GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 54/56 | `███████████████ 100%` |
| 2 | `runtime.mallocgc` | 31.1MB | 54/56 | `████████████░░░ 84%` |
| 3 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/56 | `████████████░░░ 83%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 30.07MB | 3/56 | `████████████░░░ 82%` |
| 5 | `net/http.(*Transport).dialConn` | 30.0MB | 1/56 | `████████████░░░ 81%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 23.0MB | 9/56 | `█████████░░░░░░ 62%` |
| 7 | `bytes.growSlice` | 18.32MB | 25/56 | `███████░░░░░░░░ 50%` |
| 8 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/56 | `██████░░░░░░░░░ 45%` |
| 9 | `crypto/tls.Client` | 16.51MB | 2/56 | `██████░░░░░░░░░ 45%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB | 1/56 | `██████░░░░░░░░░ 44%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 53.53GB | 51/56 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 36.03GB | 45/56 | `██████████░░░░░ 67%` |
| 3 | `reflect.growslice` | 25.45GB | 23/56 | `███████░░░░░░░░ 47%` |
| 4 | `fmt.(*buffer).writeString` | 24.63GB | 15/56 | `██████░░░░░░░░░ 46%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 21.11GB | 51/56 | `█████░░░░░░░░░░ 39%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 20.96GB | 51/56 | `█████░░░░░░░░░░ 39%` |
| 7 | `jackskj/carta.getUniqueId` | 19.62GB | 17/56 | `█████░░░░░░░░░░ 36%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.28GB | 50/56 | `█████░░░░░░░░░░ 36%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.87GB | 28/56 | `████░░░░░░░░░░░ 31%` |
| 10 | `experiment/local.topologicalSort` | 15.01GB | 43/56 | `████░░░░░░░░░░░ 28%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.6x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
