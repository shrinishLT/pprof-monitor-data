# Overview: prod
*Last updated: 2026-05-17 16:32 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T16:31 (93 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,423 | avg: 15,460 | max: 84,644 | trend: decreasing (-48.23/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 121.2MB | avg: 223.5MB | max: 1896.6MB | trend: decreasing (-3.19MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,423 | 14,899 | -476 | 15,460 | 84,644 | decreasing (-48.23/hr) |
| Heap InUse | 121.2MB | 138.7MB | -17.5MB | 223.5MB | 1896.6MB | decreasing (-3.19MB/hr) |
| Heap Sys | 3112.1MB | 2922.9MB | +189.2MB | 4200.0MB | 5842.7MB | |
| Heap Objects | 395,781 | 492,093 | -96312 | 972,196 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 34 | 15,041 | 186.4MB | 391.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 8.58MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `bytes.growSlice` | 2.51MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.03MB |
| 8 | `encoding/json.typeFields` | 1.5MB |
| 9 | `aws/endpoints.init` | 1.5MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 20.25GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 17.22GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 12.18GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 12.16GB |
| 5 | `experiment/local.topologicalSort` | 8.11GB |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 7.77GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 5.99GB |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 3.82GB |
| 9 | `segmentio/kafka-go.makePartitions` | 3.46GB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.72GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 91/93 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 36.12MB | 6/93 | `██████████████░ 98%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/93 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 24.51MB | 91/93 | `██████████░░░░░ 66%` |
| 5 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/93 | `███████░░░░░░░░ 50%` |
| 6 | `database/sql.convertAssignRows` | 15.43MB | 7/93 | `██████░░░░░░░░░ 42%` |
| 7 | `bytes.growSlice` | 14.11MB | 47/93 | `█████░░░░░░░░░░ 38%` |
| 8 | `crypto/tls.Client` | 13.01MB | 3/93 | `█████░░░░░░░░░░ 35%` |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.49MB | 22/93 | `█████░░░░░░░░░░ 34%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 12.01MB | 7/93 | `████░░░░░░░░░░░ 32%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 53.92GB | 86/93 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 29.73GB | 82/93 | `████████░░░░░░░ 55%` |
| 3 | `fmt.(*buffer).writeString` | 24.13GB | 16/93 | `██████░░░░░░░░░ 44%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 21.79GB | 84/93 | `██████░░░░░░░░░ 40%` |
| 5 | `reflect.growslice` | 20.37GB | 36/93 | `█████░░░░░░░░░░ 37%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 17.9GB | 88/93 | `████░░░░░░░░░░░ 33%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 17.78GB | 88/93 | `████░░░░░░░░░░░ 32%` |
| 8 | `jackskj/carta.getUniqueId` | 17.48GB | 25/93 | `████░░░░░░░░░░░ 32%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 16.01GB | 5/93 | `████░░░░░░░░░░░ 29%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 13.93GB | 38/93 | `███░░░░░░░░░░░░ 25%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.5x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
