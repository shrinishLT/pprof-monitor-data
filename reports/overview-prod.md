# Overview: prod
*Last updated: 2026-05-17 08:32 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T08:32 (77 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,151 | avg: 15,400 | max: 84,644 | trend: decreasing (-92.29/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 175.4MB | avg: 225.8MB | max: 1896.6MB | trend: decreasing (-5.02MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,151 | 14,188 | -37 | 15,400 | 84,644 | decreasing (-92.29/hr) |
| Heap InUse | 175.4MB | 161.6MB | +13.8MB | 225.8MB | 1896.6MB | decreasing (-5.02MB/hr) |
| Heap Sys | 4131.0MB | 4130.9MB | +0.1MB | 4439.2MB | 5842.7MB | |
| Heap Objects | 1,096,927 | 881,436 | +215491 | 999,469 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 18 | 14,409 | 163.4MB | 211.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `reflect.unsafe_NewArray` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `segmentio/kafka-go.makePartitions` | 2.01MB |
| 10 | `aws/endpoints.init` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 93.89GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 42.78GB |
| 3 | `internal/evaluation.mergeMetadata` | 28.66GB |
| 4 | `segmentio/kafka-go.makePartitions` | 25.04GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 17.53GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 17.45GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 15.91GB |
| 8 | `reflect.unsafe_NewArray` | 12.96GB |
| 9 | `database/sql.convertAssignRows` | 12.93GB |
| 10 | `experiment/local.topologicalSort` | 11.5GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 75/77 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 35.48MB | 5/77 | `██████████████░ 96%` |
| 3 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/77 | `████████████░░░ 83%` |
| 4 | `net/http.(*Transport).dialConn` | 30.0MB | 1/77 | `████████████░░░ 81%` |
| 5 | `runtime.mallocgc` | 25.47MB | 75/77 | `██████████░░░░░ 69%` |
| 6 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/77 | `██████░░░░░░░░░ 45%` |
| 7 | `crypto/tls.Client` | 16.51MB | 2/77 | `██████░░░░░░░░░ 45%` |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB | 1/77 | `██████░░░░░░░░░ 44%` |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 15.93MB | 14/77 | `██████░░░░░░░░░ 43%` |
| 10 | `bytes.growSlice` | 15.36MB | 32/77 | `██████░░░░░░░░░ 41%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 55.14GB | 72/77 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 30.75GB | 66/77 | `████████░░░░░░░ 55%` |
| 3 | `fmt.(*buffer).writeString` | 24.63GB | 15/77 | `██████░░░░░░░░░ 44%` |
| 4 | `reflect.growslice` | 22.46GB | 29/77 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 21.53GB | 71/77 | `█████░░░░░░░░░░ 39%` |
| 6 | `jackskj/carta.getUniqueId` | 18.63GB | 19/77 | `█████░░░░░░░░░░ 33%` |
| 7 | `internal/evaluation.(*Engine).Evaluate` | 18.44GB | 72/77 | `█████░░░░░░░░░░ 33%` |
| 8 | `experiment/local.(*Client).EvaluateV2` | 18.31GB | 72/77 | `████░░░░░░░░░░░ 33%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.87GB | 28/77 | `████░░░░░░░░░░░ 30%` |
| 10 | `experiment/local.topologicalSort` | 13.0GB | 57/77 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.4x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
