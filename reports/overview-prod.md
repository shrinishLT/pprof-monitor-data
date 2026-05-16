# Overview: prod
*Last updated: 2026-05-17 02:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T02:03 (64 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,513 | avg: 15,598 | max: 84,644 | trend: decreasing (-116.18/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 184.2MB | avg: 238.6MB | max: 1896.6MB | trend: decreasing (-5.91MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,513 | 14,097 | +1416 | 15,598 | 84,644 | decreasing (-116.18/hr) |
| Heap InUse | 184.2MB | 161.3MB | +22.9MB | 238.6MB | 1896.6MB | decreasing (-5.91MB/hr) |
| Heap Sys | 3467.8MB | 3472.2MB | -4.4MB | 4550.9MB | 5842.7MB | |
| Heap Objects | 651,752 | 953,200 | -301448 | 1,028,907 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 5 | 14,374 | 164.9MB | 184.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 8.04MB |
| 5 | `bufio.NewReaderSize` | 5.54MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 7 | `bufio.NewWriterSize` | 4.55MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.02MB |
| 9 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 47.46GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 21.61GB |
| 3 | `internal/evaluation.mergeMetadata` | 16.44GB |
| 4 | `segmentio/kafka-go.makePartitions` | 16.24GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 10.21GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 10.1GB |
| 7 | `reflect.unsafe_NewArray` | 8.45GB |
| 8 | `go-sql-driver/mysql.(*binaryRows).readRow` | 7.55GB |
| 9 | `experiment/local.topologicalSort` | 6.6GB |
| 10 | `database/sql.convertAssignRows` | 6.59GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 62/64 | `███████████████ 100%` |
| 2 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/64 | `████████████░░░ 83%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/64 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 28.51MB | 62/64 | `███████████░░░░ 77%` |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 23.43MB | 4/64 | `█████████░░░░░░ 63%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 21.1MB | 10/64 | `████████░░░░░░░ 57%` |
| 7 | `bytes.growSlice` | 17.92MB | 26/64 | `███████░░░░░░░░ 48%` |
| 8 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/64 | `██████░░░░░░░░░ 45%` |
| 9 | `crypto/tls.Client` | 16.51MB | 2/64 | `██████░░░░░░░░░ 45%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB | 1/64 | `██████░░░░░░░░░ 44%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 51.73GB | 59/64 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 32.72GB | 53/64 | `█████████░░░░░░ 63%` |
| 3 | `reflect.growslice` | 25.45GB | 23/64 | `███████░░░░░░░░ 49%` |
| 4 | `fmt.(*buffer).writeString` | 24.63GB | 15/64 | `███████░░░░░░░░ 47%` |
| 5 | `jackskj/carta.getUniqueId` | 19.62GB | 17/64 | `█████░░░░░░░░░░ 37%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 19.43GB | 59/64 | `█████░░░░░░░░░░ 37%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 19.29GB | 59/64 | `█████░░░░░░░░░░ 37%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.15GB | 58/64 | `█████░░░░░░░░░░ 37%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.87GB | 28/64 | `████░░░░░░░░░░░ 32%` |
| 10 | `experiment/local.topologicalSort` | 13.69GB | 50/64 | `███░░░░░░░░░░░░ 26%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
