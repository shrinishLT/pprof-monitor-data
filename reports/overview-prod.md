# Overview: prod
*Last updated: 2026-05-17 07:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T07:31 (75 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,158 | avg: 15,432 | max: 84,644 | trend: decreasing (-94.49/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 122.4MB | avg: 227.4MB | max: 1896.6MB | trend: decreasing (-5.18MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,158 | 14,109 | +49 | 15,432 | 84,644 | decreasing (-94.49/hr) |
| Heap InUse | 122.4MB | 187.1MB | -64.7MB | 227.4MB | 1896.6MB | decreasing (-5.18MB/hr) |
| Heap Sys | 4130.6MB | 4130.8MB | -0.2MB | 4447.4MB | 5842.7MB | |
| Heap Objects | 490,485 | 1,251,989 | -761504 | 999,743 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 16 | 14,439 | 162.8MB | 211.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.03MB |
| 9 | `reflect.mapassign_faststr0` | 2.0MB |
| 10 | `aws/endpoints.init` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 93.86GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 42.76GB |
| 3 | `internal/evaluation.mergeMetadata` | 27.22GB |
| 4 | `segmentio/kafka-go.makePartitions` | 23.7GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 16.64GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 16.57GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 15.84GB |
| 8 | `database/sql.convertAssignRows` | 12.89GB |
| 9 | `reflect.unsafe_NewArray` | 12.25GB |
| 10 | `reflect.growslice` | 11.21GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 73/75 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 35.48MB | 5/75 | `██████████████░ 96%` |
| 3 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/75 | `████████████░░░ 83%` |
| 4 | `net/http.(*Transport).dialConn` | 30.0MB | 1/75 | `████████████░░░ 81%` |
| 5 | `runtime.mallocgc` | 25.87MB | 73/75 | `██████████░░░░░ 70%` |
| 6 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/75 | `██████░░░░░░░░░ 45%` |
| 7 | `crypto/tls.Client` | 16.51MB | 2/75 | `██████░░░░░░░░░ 45%` |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB | 1/75 | `██████░░░░░░░░░ 44%` |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 15.93MB | 14/75 | `██████░░░░░░░░░ 43%` |
| 10 | `bytes.growSlice` | 15.36MB | 32/75 | `██████░░░░░░░░░ 41%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 54.03GB | 70/75 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 30.83GB | 64/75 | `████████░░░░░░░ 57%` |
| 3 | `fmt.(*buffer).writeString` | 24.63GB | 15/75 | `██████░░░░░░░░░ 45%` |
| 4 | `reflect.growslice` | 22.85GB | 28/75 | `██████░░░░░░░░░ 42%` |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 20.92GB | 69/75 | `█████░░░░░░░░░░ 38%` |
| 6 | `jackskj/carta.getUniqueId` | 18.63GB | 19/75 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).Evaluate` | 18.47GB | 70/75 | `█████░░░░░░░░░░ 34%` |
| 8 | `experiment/local.(*Client).EvaluateV2` | 18.34GB | 70/75 | `█████░░░░░░░░░░ 33%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.87GB | 28/75 | `████░░░░░░░░░░░ 31%` |
| 10 | `experiment/local.topologicalSort` | 13.03GB | 56/75 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
