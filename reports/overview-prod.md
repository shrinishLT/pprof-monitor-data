# Overview: prod
*Last updated: 2026-05-16 15:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T15:02 (42 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,682 | avg: 16,318 | max: 84,644 | trend: decreasing (-100.52/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 159.8MB | avg: 282.6MB | max: 1896.6MB | trend: decreasing (-1.90MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,682 | 14,401 | +281 | 16,318 | 84,644 | decreasing (-100.52/hr) |
| Heap InUse | 159.8MB | 132.3MB | +27.5MB | 282.6MB | 1896.6MB | decreasing (-1.90MB/hr) |
| Heap Sys | 3301.4MB | 3310.2MB | -8.8MB | 5132.4MB | 5842.7MB | |
| Heap Objects | 806,777 | 500,968 | +305809 | 1,113,613 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 32 | 16,945 | 296.1MB | 1896.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 10.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 6.53MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.02MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `internal/evaluation.(*Engine).Evaluate` | 2.03MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 8.44GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 3.79GB |
| 3 | `internal/evaluation.mergeMetadata` | 2.75GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 1.73GB |
| 5 | `experiment/local.(*Client).EvaluateV2` | 1.65GB |
| 6 | `segmentio/kafka-go.makePartitions` | 1.34GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 1.33GB |
| 8 | `database/sql.convertAssignRows` | 1.12GB |
| 9 | `experiment/local.topologicalSort` | 1.11GB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 939.06MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `runtime.mallocgc` | 38.31MB | 40/42 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 40/42 | `██████████████░ 95%` |
| 3 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/42 | `███████████░░░░ 79%` |
| 4 | `net/http.(*Transport).dialConn` | 30.0MB | 1/42 | `███████████░░░░ 78%` |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 27.04MB | 2/42 | `██████████░░░░░ 70%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 25.43MB | 8/42 | `█████████░░░░░░ 66%` |
| 7 | `bytes.growSlice` | 18.91MB | 24/42 | `███████░░░░░░░░ 49%` |
| 8 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/42 | `██████░░░░░░░░░ 43%` |
| 9 | `crypto/tls.Client` | 16.51MB | 2/42 | `██████░░░░░░░░░ 43%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB | 1/42 | `██████░░░░░░░░░ 42%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 65.12GB | 37/42 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 48.67GB | 31/42 | `███████████░░░░ 74%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 27.21GB | 37/42 | `██████░░░░░░░░░ 41%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 27.03GB | 37/42 | `██████░░░░░░░░░ 41%` |
| 5 | `reflect.growslice` | 25.45GB | 23/42 | `█████░░░░░░░░░░ 39%` |
| 6 | `fmt.(*buffer).writeString` | 24.63GB | 15/42 | `█████░░░░░░░░░░ 37%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 22.74GB | 36/42 | `█████░░░░░░░░░░ 34%` |
| 8 | `experiment/local.topologicalSort` | 20.08GB | 30/42 | `████░░░░░░░░░░░ 30%` |
| 9 | `jackskj/carta.getUniqueId` | 19.62GB | 17/42 | `████░░░░░░░░░░░ 30%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.87GB | 28/42 | `███░░░░░░░░░░░░ 25%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (6.7x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.2x avg)
