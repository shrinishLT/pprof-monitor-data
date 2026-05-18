# Overview: prod
*Last updated: 2026-05-18 07:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T07:01 (122 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,573 | avg: 15,189 | max: 84,644 | trend: decreasing (-41.31/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 156.6MB | avg: 207.7MB | max: 1896.6MB | trend: decreasing (-2.54MB/hr))
```
▃▄▄▃▄▆▃▃▅▅▃▃▄▄▁▂▁▂▁▂▄▁▂▃▂▁▁▁▁▂▂▂▁▂▂▂▂▂▁▁▁▂▂▃▂▃▃▂▁▂▂▁▂▇▆▄▆▃▃▁▂▃▄▁▂▁▁▂▁▂▁▂▁▂▂▁▁▁▂▂▂▁▁▁▁▂▂▁▁▁▁▁▅█▁▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,573 | 14,596 | -23 | 15,189 | 84,644 | decreasing (-41.31/hr) |
| Heap InUse | 156.6MB | 139.1MB | +17.5MB | 207.7MB | 1896.6MB | decreasing (-2.54MB/hr) |
| Heap Sys | 4699.4MB | 4699.4MB | +0.0MB | 4174.4MB | 5842.7MB | |
| Heap Objects | 737,374 | 504,075 | +233299 | 929,789 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 15 | 14,420 | 166.5MB | 404.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 8.58MB |
| 4 | `bytes.growSlice` | 8.57MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 6 | `bufio.NewReaderSize` | 4.52MB |
| 7 | `compress/flate.NewWriter` | 3.53MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.54MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.51MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 119.27GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 106.63GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 72.25GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 72.03GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 48.71GB |
| 6 | `experiment/local.topologicalSort` | 47.63GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.84GB |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 22.83GB |
| 9 | `segmentio/kafka-go.makePartitions` | 20.71GB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.01GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 36.75MB | 7/122 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 120/122 | `██████████████░ 99%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/122 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 20.66MB | 120/122 | `████████░░░░░░░ 56%` |
| 5 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/122 | `███████░░░░░░░░ 50%` |
| 6 | `database/sql.convertAssignRows` | 17.44MB | 8/122 | `███████░░░░░░░░ 47%` |
| 7 | `crypto/tls.Client` | 13.01MB | 3/122 | `█████░░░░░░░░░░ 35%` |
| 8 | `bytes.growSlice` | 12.37MB | 56/122 | `█████░░░░░░░░░░ 33%` |
| 9 | `aes/gcm.NewGCMForTLS13` | 12.01MB | 7/122 | `████░░░░░░░░░░░ 32%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 10.68MB | 27/122 | `████░░░░░░░░░░░ 29%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 53.08GB | 115/122 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 35.06GB | 111/122 | `█████████░░░░░░ 66%` |
| 3 | `fmt.(*buffer).writeString` | 24.13GB | 16/122 | `██████░░░░░░░░░ 45%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 22.12GB | 113/122 | `██████░░░░░░░░░ 41%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 20.94GB | 117/122 | `█████░░░░░░░░░░ 39%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 20.87GB | 117/122 | `█████░░░░░░░░░░ 39%` |
| 7 | `reflect.growslice` | 20.37GB | 36/122 | `█████░░░░░░░░░░ 38%` |
| 8 | `jackskj/carta.getUniqueId` | 17.48GB | 25/122 | `████░░░░░░░░░░░ 32%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 16.01GB | 5/122 | `████░░░░░░░░░░░ 30%` |
| 10 | `experiment/local.topologicalSort` | 14.5GB | 99/122 | `████░░░░░░░░░░░ 27%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.6x avg)
