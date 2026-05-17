# Overview: prod
*Last updated: 2026-05-17 20:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T20:31 (101 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,102 | avg: 15,366 | max: 84,644 | trend: decreasing (-48.02/hr))
```
▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 166.4MB | avg: 217.6MB | max: 1896.6MB | trend: decreasing (-3.13MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,102 | 14,164 | -62 | 15,366 | 84,644 | decreasing (-48.02/hr) |
| Heap InUse | 166.4MB | 150.1MB | +16.3MB | 217.6MB | 1896.6MB | decreasing (-3.13MB/hr) |
| Heap Sys | 3577.2MB | 3576.3MB | +0.9MB | 4146.0MB | 5842.7MB | |
| Heap Objects | 1,042,020 | 762,611 | +279409 | 953,535 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 42 | 14,894 | 179.3MB | 391.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 8.58MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.03MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `encoding/json.typeFields` | 1.5MB |
| 9 | `aws/endpoints.init` | 1.5MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 34.63GB |
| 2 | `internal/evaluation.mergeMetadata` | 31.45GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 18.92GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 18.82GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 15.71GB |
| 6 | `experiment/local.topologicalSort` | 12.63GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 9.17GB |
| 8 | `segmentio/kafka-go.makePartitions` | 8.15GB |
| 9 | `internal/evaluation.(*Engine).evaluateFlag` | 5.92GB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 5.55GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 99/101 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 36.12MB | 6/101 | `██████████████░ 98%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/101 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 23.22MB | 99/101 | `█████████░░░░░░ 63%` |
| 5 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/101 | `███████░░░░░░░░ 50%` |
| 6 | `database/sql.convertAssignRows` | 15.43MB | 7/101 | `██████░░░░░░░░░ 42%` |
| 7 | `bytes.growSlice` | 13.37MB | 50/101 | `█████░░░░░░░░░░ 36%` |
| 8 | `crypto/tls.Client` | 13.01MB | 3/101 | `█████░░░░░░░░░░ 35%` |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.03MB | 23/101 | `████░░░░░░░░░░░ 32%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 12.01MB | 7/101 | `████░░░░░░░░░░░ 32%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 51.52GB | 94/101 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 29.43GB | 90/101 | `████████░░░░░░░ 57%` |
| 3 | `fmt.(*buffer).writeString` | 24.13GB | 16/101 | `███████░░░░░░░░ 46%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 20.91GB | 92/101 | `██████░░░░░░░░░ 40%` |
| 5 | `reflect.growslice` | 20.37GB | 36/101 | `█████░░░░░░░░░░ 39%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 17.72GB | 96/101 | `█████░░░░░░░░░░ 34%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 17.62GB | 96/101 | `█████░░░░░░░░░░ 34%` |
| 8 | `jackskj/carta.getUniqueId` | 17.48GB | 25/101 | `█████░░░░░░░░░░ 33%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 16.01GB | 5/101 | `████░░░░░░░░░░░ 31%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 12.85GB | 46/101 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.7x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
