# Overview: prod
*Last updated: 2026-05-17 07:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T07:02 (74 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,109 | avg: 15,450 | max: 84,644 | trend: decreasing (-95.54/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 187.1MB | avg: 228.8MB | max: 1896.6MB | trend: decreasing (-5.16MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,109 | 15,380 | -1271 | 15,450 | 84,644 | decreasing (-95.54/hr) |
| Heap InUse | 187.1MB | 211.2MB | -24.1MB | 228.8MB | 1896.6MB | decreasing (-5.16MB/hr) |
| Heap Sys | 4130.8MB | 4129.9MB | +0.9MB | 4451.7MB | 5842.7MB | |
| Heap Objects | 1,251,989 | 1,066,063 | +185926 | 1,006,625 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 15 | 14,458 | 165.5MB | 211.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 1.5MB |
| 10 | `bufio.NewWriterSize` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 93.86GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 42.76GB |
| 3 | `internal/evaluation.mergeMetadata` | 26.82GB |
| 4 | `segmentio/kafka-go.makePartitions` | 23.03GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 16.41GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 16.36GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 15.82GB |
| 8 | `database/sql.convertAssignRows` | 12.89GB |
| 9 | `reflect.unsafe_NewArray` | 11.91GB |
| 10 | `reflect.growslice` | 11.08GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 72/74 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 35.48MB | 5/74 | `██████████████░ 96%` |
| 3 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/74 | `████████████░░░ 83%` |
| 4 | `net/http.(*Transport).dialConn` | 30.0MB | 1/74 | `████████████░░░ 81%` |
| 5 | `runtime.mallocgc` | 26.08MB | 72/74 | `██████████░░░░░ 71%` |
| 6 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/74 | `██████░░░░░░░░░ 45%` |
| 7 | `crypto/tls.Client` | 16.51MB | 2/74 | `██████░░░░░░░░░ 45%` |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB | 1/74 | `██████░░░░░░░░░ 44%` |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 15.93MB | 14/74 | `██████░░░░░░░░░ 43%` |
| 10 | `bytes.growSlice` | 15.36MB | 32/74 | `██████░░░░░░░░░ 41%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 53.45GB | 69/74 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 30.88GB | 63/74 | `████████░░░░░░░ 57%` |
| 3 | `fmt.(*buffer).writeString` | 24.63GB | 15/74 | `██████░░░░░░░░░ 46%` |
| 4 | `reflect.growslice` | 23.29GB | 27/74 | `██████░░░░░░░░░ 43%` |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 20.59GB | 68/74 | `█████░░░░░░░░░░ 38%` |
| 6 | `jackskj/carta.getUniqueId` | 18.63GB | 19/74 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).Evaluate` | 18.5GB | 69/74 | `█████░░░░░░░░░░ 34%` |
| 8 | `experiment/local.(*Client).EvaluateV2` | 18.36GB | 69/74 | `█████░░░░░░░░░░ 34%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.87GB | 28/74 | `████░░░░░░░░░░░ 31%` |
| 10 | `experiment/local.topologicalSort` | 13.03GB | 56/74 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
