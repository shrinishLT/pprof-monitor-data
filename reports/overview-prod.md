# Overview: prod
*Last updated: 2026-05-16 20:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T20:31 (53 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,071 | avg: 15,880 | max: 84,644 | trend: decreasing (-128.32/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 102.7MB | avg: 255.5MB | max: 1896.6MB | trend: decreasing (-5.84MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 1%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,071 | 14,109 | -38 | 15,880 | 84,644 | decreasing (-128.32/hr) |
| Heap InUse | 102.7MB | 111.4MB | -8.7MB | 255.5MB | 1896.6MB | decreasing (-5.84MB/hr) |
| Heap Sys | 3472.5MB | 3471.2MB | +1.3MB | 4774.9MB | 5842.7MB | |
| Heap Objects | 325,365 | 388,750 | -63385 | 1,047,315 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 43 | 16,245 | 259.2MB | 1896.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.01MB |
| 9 | `reflect.unsafe_NewArray` | 1.5MB |
| 10 | `aws/endpoints.init` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 30.3GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 13.74GB |
| 3 | `internal/evaluation.mergeMetadata` | 11.55GB |
| 4 | `segmentio/kafka-go.makePartitions` | 8.61GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 7.2GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 7.11GB |
| 7 | `experiment/local.topologicalSort` | 4.68GB |
| 8 | `go-sql-driver/mysql.(*binaryRows).readRow` | 4.66GB |
| 9 | `reflect.unsafe_NewArray` | 4.6GB |
| 10 | `database/sql.convertAssignRows` | 4.15GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 51/53 | `███████████████ 100%` |
| 2 | `runtime.mallocgc` | 32.28MB | 51/53 | `█████████████░░ 88%` |
| 3 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/53 | `████████████░░░ 83%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 30.07MB | 3/53 | `████████████░░░ 82%` |
| 5 | `net/http.(*Transport).dialConn` | 30.0MB | 1/53 | `████████████░░░ 81%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 23.0MB | 9/53 | `█████████░░░░░░ 62%` |
| 7 | `bytes.growSlice` | 18.32MB | 25/53 | `███████░░░░░░░░ 50%` |
| 8 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/53 | `██████░░░░░░░░░ 45%` |
| 9 | `crypto/tls.Client` | 16.51MB | 2/53 | `██████░░░░░░░░░ 45%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB | 1/53 | `██████░░░░░░░░░ 44%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 54.86GB | 48/53 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 37.75GB | 42/53 | `██████████░░░░░ 68%` |
| 3 | `reflect.growslice` | 25.45GB | 23/53 | `██████░░░░░░░░░ 46%` |
| 4 | `fmt.(*buffer).writeString` | 24.63GB | 15/53 | `██████░░░░░░░░░ 44%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 21.96GB | 48/53 | `██████░░░░░░░░░ 40%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 21.81GB | 48/53 | `█████░░░░░░░░░░ 39%` |
| 7 | `jackskj/carta.getUniqueId` | 19.62GB | 17/53 | `█████░░░░░░░░░░ 35%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.58GB | 47/53 | `█████░░░░░░░░░░ 35%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.87GB | 28/53 | `████░░░░░░░░░░░ 30%` |
| 10 | `experiment/local.topologicalSort` | 15.77GB | 40/53 | `████░░░░░░░░░░░ 28%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.4x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.3x avg)
