# Overview: prod
*Last updated: 2026-05-18 04:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T04:02 (116 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,263 | avg: 15,216 | max: 84,644 | trend: decreasing (-45.13/hr))
```
▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 125.9MB | avg: 207.5MB | max: 1896.6MB | trend: decreasing (-2.97MB/hr))
```
▂▃▄▅█▅▂▃▃▃▃▅▃▂▄▄▂▂▃▃▁▂▁▂▁▂▃▁▂▂▂▁▁▁▁▂▂▂▁▁▂▂▂▂▁▁▁▂▂▂▂▂▃▂▁▂▂▁▂▆▅▃▅▂▃▁▂▂▄▁▂▁▁▁▁▂▁▂▁▁▂▁▁▁▂▂▂▁▁▁▁▁▂▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,263 | 14,155 | +108 | 15,216 | 84,644 | decreasing (-45.13/hr) |
| Heap InUse | 125.9MB | 135.5MB | -9.6MB | 207.5MB | 1896.6MB | decreasing (-2.97MB/hr) |
| Heap Sys | 4699.2MB | 4698.9MB | +0.3MB | 4147.3MB | 5842.7MB | |
| Heap Objects | 454,718 | 651,674 | -196956 | 922,236 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 9 | 14,256 | 137.5MB | 156.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 8.58MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.53MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `encoding/json.typeFields` | 1.5MB |
| 9 | `aws/endpoints.init` | 1.5MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 65.98GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 64.52GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 39.75GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 39.72GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 29.52GB |
| 6 | `experiment/local.topologicalSort` | 26.31GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 20.05GB |
| 8 | `segmentio/kafka-go.makePartitions` | 17.0GB |
| 9 | `internal/evaluation.(*Engine).evaluateFlag` | 12.57GB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 10.42GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 114/116 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 36.12MB | 6/116 | `██████████████░ 98%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/116 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 21.3MB | 114/116 | `████████░░░░░░░ 58%` |
| 5 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/116 | `███████░░░░░░░░ 50%` |
| 6 | `database/sql.convertAssignRows` | 15.43MB | 7/116 | `██████░░░░░░░░░ 42%` |
| 7 | `crypto/tls.Client` | 13.01MB | 3/116 | `█████░░░░░░░░░░ 35%` |
| 8 | `bytes.growSlice` | 13.0MB | 52/116 | `█████░░░░░░░░░░ 35%` |
| 9 | `aes/gcm.NewGCMForTLS13` | 12.01MB | 7/116 | `████░░░░░░░░░░░ 32%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.7MB | 24/116 | `████░░░░░░░░░░░ 31%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 51.34GB | 109/116 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 31.43GB | 105/116 | `█████████░░░░░░ 61%` |
| 3 | `fmt.(*buffer).writeString` | 24.13GB | 16/116 | `███████░░░░░░░░ 47%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 21.19GB | 107/116 | `██████░░░░░░░░░ 41%` |
| 5 | `reflect.growslice` | 20.37GB | 36/116 | `█████░░░░░░░░░░ 39%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 18.85GB | 111/116 | `█████░░░░░░░░░░ 36%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 18.77GB | 111/116 | `█████░░░░░░░░░░ 36%` |
| 8 | `jackskj/carta.getUniqueId` | 17.48GB | 25/116 | `█████░░░░░░░░░░ 34%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 16.01GB | 5/116 | `████░░░░░░░░░░░ 31%` |
| 10 | `experiment/local.topologicalSort` | 12.9GB | 93/116 | `███░░░░░░░░░░░░ 25%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.6x avg)
