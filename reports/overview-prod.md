# Overview: prod
*Last updated: 2026-05-17 03:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T03:31 (67 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,201 | avg: 15,534 | max: 84,644 | trend: decreasing (-112.17/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 137.3MB | avg: 233.5MB | max: 1896.6MB | trend: decreasing (-6.02MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,201 | 14,101 | +100 | 15,534 | 84,644 | decreasing (-112.17/hr) |
| Heap InUse | 137.3MB | 119.9MB | +17.4MB | 233.5MB | 1896.6MB | decreasing (-6.02MB/hr) |
| Heap Sys | 3589.1MB | 3469.1MB | +120.0MB | 4504.2MB | 5842.7MB | |
| Heap Objects | 582,485 | 529,924 | +52561 | 1,005,741 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 8 | 14,299 | 150.0MB | 184.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `bytes.growSlice` | 2.01MB |
| 9 | `reflect.unsafe_NewArray` | 2.0MB |
| 10 | `bufio.NewWriterSize` | 1.53MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 52.64GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 23.92GB |
| 3 | `internal/evaluation.mergeMetadata` | 18.34GB |
| 4 | `segmentio/kafka-go.makePartitions` | 18.27GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 11.3GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 11.22GB |
| 7 | `reflect.unsafe_NewArray` | 9.49GB |
| 8 | `go-sql-driver/mysql.(*binaryRows).readRow` | 8.49GB |
| 9 | `database/sql.convertAssignRows` | 7.35GB |
| 10 | `experiment/local.topologicalSort` | 7.32GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 65/67 | `███████████████ 100%` |
| 2 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/67 | `████████████░░░ 83%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/67 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 27.7MB | 65/67 | `███████████░░░░ 75%` |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 23.43MB | 4/67 | `█████████░░░░░░ 63%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 21.1MB | 10/67 | `████████░░░░░░░ 57%` |
| 7 | `bytes.growSlice` | 17.33MB | 27/67 | `███████░░░░░░░░ 47%` |
| 8 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/67 | `██████░░░░░░░░░ 45%` |
| 9 | `crypto/tls.Client` | 16.51MB | 2/67 | `██████░░░░░░░░░ 45%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB | 1/67 | `██████░░░░░░░░░ 44%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 51.62GB | 62/67 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 31.92GB | 56/67 | `█████████░░░░░░ 61%` |
| 3 | `reflect.growslice` | 25.45GB | 23/67 | `███████░░░░░░░░ 49%` |
| 4 | `fmt.(*buffer).writeString` | 24.63GB | 15/67 | `███████░░░░░░░░ 47%` |
| 5 | `jackskj/carta.getUniqueId` | 19.62GB | 17/67 | `█████░░░░░░░░░░ 38%` |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 19.32GB | 61/67 | `█████░░░░░░░░░░ 37%` |
| 7 | `internal/evaluation.(*Engine).Evaluate` | 19.02GB | 62/67 | `█████░░░░░░░░░░ 36%` |
| 8 | `experiment/local.(*Client).EvaluateV2` | 18.88GB | 62/67 | `█████░░░░░░░░░░ 36%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.87GB | 28/67 | `████░░░░░░░░░░░ 32%` |
| 10 | `experiment/local.topologicalSort` | 13.32GB | 53/67 | `███░░░░░░░░░░░░ 25%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
