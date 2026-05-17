# Overview: prod
*Last updated: 2026-05-17 21:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T21:03 (102 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,279 | avg: 15,355 | max: 84,644 | trend: decreasing (-47.86/hr))
```
▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 132.2MB | avg: 216.8MB | max: 1896.6MB | trend: decreasing (-3.14MB/hr))
```
▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,279 | 14,102 | +177 | 15,355 | 84,644 | decreasing (-47.86/hr) |
| Heap InUse | 132.2MB | 166.4MB | -34.2MB | 216.8MB | 1896.6MB | decreasing (-3.14MB/hr) |
| Heap Sys | 3577.0MB | 3577.2MB | -0.2MB | 4140.4MB | 5842.7MB | |
| Heap Objects | 582,447 | 1,042,020 | -459573 | 949,896 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 43 | 14,879 | 178.2MB | 391.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 8.58MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 7 | `encoding/json.typeFields` | 1.5MB |
| 8 | `reflect.mapassign_faststr0` | 1.5MB |
| 9 | `aws/endpoints.init` | 1.5MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 34.66GB |
| 2 | `internal/evaluation.mergeMetadata` | 31.58GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 19.0GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 18.91GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 15.72GB |
| 6 | `experiment/local.topologicalSort` | 12.68GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 9.21GB |
| 8 | `segmentio/kafka-go.makePartitions` | 8.79GB |
| 9 | `internal/evaluation.(*Engine).evaluateFlag` | 5.95GB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 5.56GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 100/102 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 36.12MB | 6/102 | `██████████████░ 98%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/102 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 23.08MB | 100/102 | `█████████░░░░░░ 63%` |
| 5 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/102 | `███████░░░░░░░░ 50%` |
| 6 | `database/sql.convertAssignRows` | 15.43MB | 7/102 | `██████░░░░░░░░░ 42%` |
| 7 | `bytes.growSlice` | 13.37MB | 50/102 | `█████░░░░░░░░░░ 36%` |
| 8 | `crypto/tls.Client` | 13.01MB | 3/102 | `█████░░░░░░░░░░ 35%` |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.03MB | 23/102 | `████░░░░░░░░░░░ 32%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 12.01MB | 7/102 | `████░░░░░░░░░░░ 32%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 51.34GB | 95/102 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 29.45GB | 91/102 | `████████░░░░░░░ 57%` |
| 3 | `fmt.(*buffer).writeString` | 24.13GB | 16/102 | `███████░░░░░░░░ 47%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 20.85GB | 93/102 | `██████░░░░░░░░░ 40%` |
| 5 | `reflect.growslice` | 20.37GB | 36/102 | `█████░░░░░░░░░░ 39%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 17.73GB | 97/102 | `█████░░░░░░░░░░ 34%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 17.63GB | 97/102 | `█████░░░░░░░░░░ 34%` |
| 8 | `jackskj/carta.getUniqueId` | 17.48GB | 25/102 | `█████░░░░░░░░░░ 34%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 16.01GB | 5/102 | `████░░░░░░░░░░░ 31%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 12.77GB | 47/102 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
