# Overview: prod
*Last updated: 2026-05-17 15:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T15:31 (91 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,162 | avg: 15,478 | max: 84,644 | trend: decreasing (-49.10/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 172.3MB | avg: 225.5MB | max: 1896.6MB | trend: decreasing (-3.12MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,162 | 14,373 | +789 | 15,478 | 84,644 | decreasing (-49.10/hr) |
| Heap InUse | 172.3MB | 130.4MB | +41.9MB | 225.5MB | 1896.6MB | decreasing (-3.12MB/hr) |
| Heap Sys | 2922.6MB | 2762.8MB | +159.8MB | 4226.0MB | 5842.7MB | |
| Heap Objects | 705,949 | 513,244 | +192705 | 983,806 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 32 | 15,065 | 189.9MB | 391.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 8.58MB |
| 4 | `bytes.growSlice` | 6.53MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.52MB |
| 7 | `bufio.NewWriterSize` | 3.03MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `reflect.unsafe_NewArray` | 2.02MB |
| 10 | `reflect.mapassign_faststr0` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 15.52GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 12.1GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 9.37GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 9.34GB |
| 5 | `experiment/local.topologicalSort` | 6.25GB |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 5.45GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 4.64GB |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 2.92GB |
| 9 | `segmentio/kafka-go.makePartitions` | 2.25GB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 1.94GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 89/91 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 36.12MB | 6/91 | `██████████████░ 98%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/91 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 24.87MB | 89/91 | `██████████░░░░░ 67%` |
| 5 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/91 | `███████░░░░░░░░ 50%` |
| 6 | `database/sql.convertAssignRows` | 15.43MB | 7/91 | `██████░░░░░░░░░ 42%` |
| 7 | `bytes.growSlice` | 14.51MB | 45/91 | `█████░░░░░░░░░░ 39%` |
| 8 | `crypto/tls.Client` | 13.01MB | 3/91 | `█████░░░░░░░░░░ 35%` |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.92MB | 21/91 | `█████░░░░░░░░░░ 35%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 12.01MB | 7/91 | `████░░░░░░░░░░░ 32%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 54.85GB | 84/91 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 29.99GB | 80/91 | `████████░░░░░░░ 54%` |
| 3 | `fmt.(*buffer).writeString` | 24.13GB | 16/91 | `██████░░░░░░░░░ 43%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 22.16GB | 82/91 | `██████░░░░░░░░░ 40%` |
| 5 | `reflect.growslice` | 20.37GB | 36/91 | `█████░░░░░░░░░░ 37%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 18.05GB | 86/91 | `████░░░░░░░░░░░ 32%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 17.92GB | 86/91 | `████░░░░░░░░░░░ 32%` |
| 8 | `jackskj/carta.getUniqueId` | 17.48GB | 25/91 | `████░░░░░░░░░░░ 31%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 16.01GB | 5/91 | `████░░░░░░░░░░░ 29%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 14.39GB | 36/91 | `███░░░░░░░░░░░░ 26%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.4x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
