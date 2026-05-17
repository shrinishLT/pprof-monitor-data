# Overview: prod
*Last updated: 2026-05-18 01:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T01:01 (110 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,143 | avg: 15,265 | max: 84,644 | trend: decreasing (-47.29/hr))
```
▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 124.9MB | avg: 211.2MB | max: 1896.6MB | trend: decreasing (-3.06MB/hr))
```
▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,143 | 14,095 | +48 | 15,265 | 84,644 | decreasing (-47.29/hr) |
| Heap InUse | 124.9MB | 122.6MB | +2.3MB | 211.2MB | 1896.6MB | decreasing (-3.06MB/hr) |
| Heap Sys | 4165.8MB | 4165.8MB | +0.0MB | 4127.0MB | 5842.7MB | |
| Heap Objects | 577,420 | 610,724 | -33304 | 937,345 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 3 | 14,128 | 130.3MB | 143.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 8.58MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `encoding/json.typeFields` | 1.5MB |
| 8 | `reflect.mapassign_faststr0` | 1.5MB |
| 9 | `aws/endpoints.init` | 1.5MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 50.92GB |
| 2 | `internal/evaluation.mergeMetadata` | 35.7GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 23.24GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 21.46GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 21.39GB |
| 6 | `experiment/local.topologicalSort` | 14.31GB |
| 7 | `segmentio/kafka-go.makePartitions` | 13.39GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 10.49GB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 8.02GB |
| 10 | `database/sql.convertAssignRows` | 7.37GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 108/110 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 36.12MB | 6/110 | `██████████████░ 98%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/110 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 22.0MB | 108/110 | `█████████░░░░░░ 60%` |
| 5 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/110 | `███████░░░░░░░░ 50%` |
| 6 | `database/sql.convertAssignRows` | 15.43MB | 7/110 | `██████░░░░░░░░░ 42%` |
| 7 | `bytes.growSlice` | 13.14MB | 51/110 | `█████░░░░░░░░░░ 35%` |
| 8 | `crypto/tls.Client` | 13.01MB | 3/110 | `█████░░░░░░░░░░ 35%` |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.03MB | 23/110 | `████░░░░░░░░░░░ 32%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 12.01MB | 7/110 | `████░░░░░░░░░░░ 32%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 50.83GB | 103/110 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 29.81GB | 99/110 | `████████░░░░░░░ 58%` |
| 3 | `fmt.(*buffer).writeString` | 24.13GB | 16/110 | `███████░░░░░░░░ 47%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 20.82GB | 101/110 | `██████░░░░░░░░░ 40%` |
| 5 | `reflect.growslice` | 20.37GB | 36/110 | `██████░░░░░░░░░ 40%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 17.93GB | 105/110 | `█████░░░░░░░░░░ 35%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 17.85GB | 105/110 | `█████░░░░░░░░░░ 35%` |
| 8 | `jackskj/carta.getUniqueId` | 17.48GB | 25/110 | `█████░░░░░░░░░░ 34%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 16.01GB | 5/110 | `████░░░░░░░░░░░ 31%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 12.36GB | 55/110 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
