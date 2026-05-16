# Overview: prod
*Last updated: 2026-05-16 15:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T15:31 (43 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,097 | avg: 16,266 | max: 84,644 | trend: decreasing (-107.75/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 109.5MB | avg: 278.6MB | max: 1896.6MB | trend: decreasing (-2.87MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 1%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,097 | 14,682 | -585 | 16,266 | 84,644 | decreasing (-107.75/hr) |
| Heap InUse | 109.5MB | 159.8MB | -50.3MB | 278.6MB | 1896.6MB | decreasing (-2.87MB/hr) |
| Heap Sys | 3301.2MB | 3301.4MB | -0.2MB | 5089.8MB | 5842.7MB | |
| Heap Objects | 439,560 | 806,777 | -367217 | 1,097,937 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 33 | 16,858 | 290.5MB | 1896.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 10.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.01MB |
| 6 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 1.5MB |
| 9 | `reflect.mapassign_faststr0` | 1.5MB |
| 10 | `reflect.growslice` | 1.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 11.11GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 5.02GB |
| 3 | `internal/evaluation.mergeMetadata` | 3.37GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 2.13GB |
| 5 | `experiment/local.(*Client).EvaluateV2` | 2.05GB |
| 6 | `segmentio/kafka-go.makePartitions` | 1.93GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 1.75GB |
| 8 | `database/sql.convertAssignRows` | 1.51GB |
| 9 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 1.45GB |
| 10 | `experiment/local.topologicalSort` | 1.4GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `runtime.mallocgc` | 37.62MB | 41/43 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 41/43 | `██████████████░ 97%` |
| 3 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/43 | `████████████░░░ 81%` |
| 4 | `net/http.(*Transport).dialConn` | 30.0MB | 1/43 | `███████████░░░░ 79%` |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 27.04MB | 2/43 | `██████████░░░░░ 71%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 25.43MB | 8/43 | `██████████░░░░░ 67%` |
| 7 | `bytes.growSlice` | 18.91MB | 24/43 | `███████░░░░░░░░ 50%` |
| 8 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/43 | `██████░░░░░░░░░ 43%` |
| 9 | `crypto/tls.Client` | 16.51MB | 2/43 | `██████░░░░░░░░░ 43%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB | 1/43 | `██████░░░░░░░░░ 43%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 63.7GB | 38/43 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 47.26GB | 32/43 | `███████████░░░░ 74%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 26.55GB | 38/43 | `██████░░░░░░░░░ 41%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 26.37GB | 38/43 | `██████░░░░░░░░░ 41%` |
| 5 | `reflect.growslice` | 25.45GB | 23/43 | `█████░░░░░░░░░░ 39%` |
| 6 | `fmt.(*buffer).writeString` | 24.63GB | 15/43 | `█████░░░░░░░░░░ 38%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 22.26GB | 37/43 | `█████░░░░░░░░░░ 34%` |
| 8 | `jackskj/carta.getUniqueId` | 19.62GB | 17/43 | `████░░░░░░░░░░░ 30%` |
| 9 | `experiment/local.topologicalSort` | 19.48GB | 31/43 | `████░░░░░░░░░░░ 30%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.87GB | 28/43 | `███░░░░░░░░░░░░ 26%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (6.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.2x avg)
