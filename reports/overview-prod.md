# Overview: prod
*Last updated: 2026-05-17 09:32 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T09:31 (79 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,670 | avg: 15,380 | max: 84,644 | trend: decreasing (-88.35/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 183.4MB | avg: 224.2MB | max: 1896.6MB | trend: decreasing (-4.88MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,670 | 14,586 | +84 | 15,380 | 84,644 | decreasing (-88.35/hr) |
| Heap InUse | 183.4MB | 140.2MB | +43.2MB | 224.2MB | 1896.6MB | decreasing (-4.88MB/hr) |
| Heap Sys | 4131.0MB | 4131.2MB | -0.2MB | 4431.4MB | 5842.7MB | |
| Heap Objects | 959,581 | 466,462 | +493119 | 992,217 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 20 | 14,431 | 163.3MB | 211.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 5.53MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.51MB |
| 7 | `bufio.NewWriterSize` | 2.51MB |
| 8 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `bufio.NewReaderSize` | 2.02MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 97.51GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 44.46GB |
| 3 | `internal/evaluation.mergeMetadata` | 31.47GB |
| 4 | `segmentio/kafka-go.makePartitions` | 26.38GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 19.21GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 19.09GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 16.69GB |
| 8 | `reflect.unsafe_NewArray` | 13.66GB |
| 9 | `database/sql.convertAssignRows` | 13.47GB |
| 10 | `experiment/local.topologicalSort` | 12.66GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 77/79 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 35.48MB | 5/79 | `██████████████░ 96%` |
| 3 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/79 | `████████████░░░ 83%` |
| 4 | `net/http.(*Transport).dialConn` | 30.0MB | 1/79 | `████████████░░░ 81%` |
| 5 | `runtime.mallocgc` | 25.1MB | 77/79 | `██████████░░░░░ 68%` |
| 6 | `crypto/tls.Client` | 16.51MB | 2/79 | `██████░░░░░░░░░ 45%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB | 1/79 | `██████░░░░░░░░░ 44%` |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 15.93MB | 14/79 | `██████░░░░░░░░░ 43%` |
| 9 | `bytes.growSlice` | 14.71MB | 34/79 | `██████░░░░░░░░░ 40%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 13.61MB | 5/79 | `█████░░░░░░░░░░ 37%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 56.28GB | 74/79 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 30.74GB | 68/79 | `████████░░░░░░░ 54%` |
| 3 | `fmt.(*buffer).writeString` | 24.63GB | 15/79 | `██████░░░░░░░░░ 43%` |
| 4 | `reflect.growslice` | 22.46GB | 29/79 | `█████░░░░░░░░░░ 39%` |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 22.16GB | 73/79 | `█████░░░░░░░░░░ 39%` |
| 6 | `jackskj/carta.getUniqueId` | 18.63GB | 19/79 | `████░░░░░░░░░░░ 33%` |
| 7 | `internal/evaluation.(*Engine).Evaluate` | 18.45GB | 74/79 | `████░░░░░░░░░░░ 32%` |
| 8 | `experiment/local.(*Client).EvaluateV2` | 18.31GB | 74/79 | `████░░░░░░░░░░░ 32%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.87GB | 28/79 | `████░░░░░░░░░░░ 29%` |
| 10 | `segmentio/kafka-go.makePartitions` | 13.46GB | 39/79 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.5x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
