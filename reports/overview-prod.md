# Overview: prod
*Last updated: 2026-05-17 22:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T22:01 (104 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,076 | avg: 15,330 | max: 84,644 | trend: decreasing (-47.92/hr))
```
▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 105.0MB | avg: 214.6MB | max: 1896.6MB | trend: decreasing (-3.20MB/hr))
```
▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 1%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,076 | 14,087 | -11 | 15,330 | 84,644 | decreasing (-47.92/hr) |
| Heap InUse | 105.0MB | 107.3MB | -2.3MB | 214.6MB | 1896.6MB | decreasing (-3.20MB/hr) |
| Heap Sys | 3885.4MB | 3885.4MB | +0.0MB | 4135.5MB | 5842.7MB | |
| Heap Objects | 400,413 | 396,958 | +3455 | 939,296 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 45 | 14,844 | 175.0MB | 391.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 8.58MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.51MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.mapassign_faststr0` | 2.0MB |
| 9 | `encoding/json.typeFields` | 1.5MB |
| 10 | `aws/endpoints.init` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 39.62GB |
| 2 | `internal/evaluation.mergeMetadata` | 32.38GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 19.49GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 19.41GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 17.99GB |
| 6 | `experiment/local.topologicalSort` | 13.0GB |
| 7 | `segmentio/kafka-go.makePartitions` | 9.92GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 9.48GB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 6.31GB |
| 10 | `internal/evaluation.(*Engine).evaluateFlag` | 6.11GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 102/104 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 36.12MB | 6/104 | `██████████████░ 98%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/104 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 22.79MB | 102/104 | `█████████░░░░░░ 62%` |
| 5 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/104 | `███████░░░░░░░░ 50%` |
| 6 | `database/sql.convertAssignRows` | 15.43MB | 7/104 | `██████░░░░░░░░░ 42%` |
| 7 | `bytes.growSlice` | 13.37MB | 50/104 | `█████░░░░░░░░░░ 36%` |
| 8 | `crypto/tls.Client` | 13.01MB | 3/104 | `█████░░░░░░░░░░ 35%` |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.03MB | 23/104 | `████░░░░░░░░░░░ 32%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 12.01MB | 7/104 | `████░░░░░░░░░░░ 32%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 51.1GB | 97/104 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 29.51GB | 93/104 | `████████░░░░░░░ 57%` |
| 3 | `fmt.(*buffer).writeString` | 24.13GB | 16/104 | `███████░░░░░░░░ 47%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 20.79GB | 95/104 | `██████░░░░░░░░░ 40%` |
| 5 | `reflect.growslice` | 20.37GB | 36/104 | `█████░░░░░░░░░░ 39%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 17.77GB | 99/104 | `█████░░░░░░░░░░ 34%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 17.67GB | 99/104 | `█████░░░░░░░░░░ 34%` |
| 8 | `jackskj/carta.getUniqueId` | 17.48GB | 25/104 | `█████░░░░░░░░░░ 34%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 16.01GB | 5/104 | `████░░░░░░░░░░░ 31%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 12.64GB | 49/104 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
