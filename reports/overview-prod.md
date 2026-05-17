# Overview: prod
*Last updated: 2026-05-18 03:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T03:31 (115 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,155 | avg: 15,224 | max: 84,644 | trend: decreasing (-45.45/hr))
```
▄▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 135.5MB | avg: 208.3MB | max: 1896.6MB | trend: decreasing (-2.97MB/hr))
```
▇▂▃▄▅█▅▂▃▃▃▃▅▃▂▄▄▂▂▃▃▁▂▁▂▁▂▃▁▂▂▂▁▁▁▁▂▂▂▁▁▂▂▂▂▁▁▁▂▂▂▂▂▃▂▁▂▂▁▂▆▅▃▅▂▃▁▂▂▄▁▂▁▁▁▁▂▁▂▁▁▂▁▁▁▂▂▂▁▁▁▁▁▂▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,155 | 14,196 | -41 | 15,224 | 84,644 | decreasing (-45.45/hr) |
| Heap InUse | 135.5MB | 141.8MB | -6.3MB | 208.3MB | 1896.6MB | decreasing (-2.97MB/hr) |
| Heap Sys | 4698.9MB | 4698.8MB | +0.1MB | 4142.5MB | 5842.7MB | |
| Heap Objects | 651,674 | 718,086 | -66412 | 926,302 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 8 | 14,255 | 138.9MB | 156.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 8.58MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `reflect.unsafe_NewArray` | 3.02MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.growslice` | 2.01MB |
| 9 | `segmentio/kafka-go.makePartitions` | 1.5MB |
| 10 | `encoding/json.typeFields` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 64.49GB |
| 2 | `internal/evaluation.mergeMetadata` | 63.58GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 38.3GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 38.25GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 29.51GB |
| 6 | `experiment/local.topologicalSort` | 25.34GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 19.27GB |
| 8 | `segmentio/kafka-go.makePartitions` | 16.36GB |
| 9 | `internal/evaluation.(*Engine).evaluateFlag` | 12.09GB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 10.4GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 113/115 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 36.12MB | 6/115 | `██████████████░ 98%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/115 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 21.41MB | 113/115 | `████████░░░░░░░ 58%` |
| 5 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/115 | `███████░░░░░░░░ 50%` |
| 6 | `database/sql.convertAssignRows` | 15.43MB | 7/115 | `██████░░░░░░░░░ 42%` |
| 7 | `crypto/tls.Client` | 13.01MB | 3/115 | `█████░░░░░░░░░░ 35%` |
| 8 | `bytes.growSlice` | 13.0MB | 52/115 | `█████░░░░░░░░░░ 35%` |
| 9 | `aes/gcm.NewGCMForTLS13` | 12.01MB | 7/115 | `████░░░░░░░░░░░ 32%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.7MB | 24/115 | `████░░░░░░░░░░░ 31%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 51.22GB | 108/115 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 31.1GB | 104/115 | `█████████░░░░░░ 60%` |
| 3 | `fmt.(*buffer).writeString` | 24.13GB | 16/115 | `███████░░░░░░░░ 47%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 21.11GB | 106/115 | `██████░░░░░░░░░ 41%` |
| 5 | `reflect.growslice` | 20.37GB | 36/115 | `█████░░░░░░░░░░ 39%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 18.66GB | 110/115 | `█████░░░░░░░░░░ 36%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 18.58GB | 110/115 | `█████░░░░░░░░░░ 36%` |
| 8 | `jackskj/carta.getUniqueId` | 17.48GB | 25/115 | `█████░░░░░░░░░░ 34%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 16.01GB | 5/115 | `████░░░░░░░░░░░ 31%` |
| 10 | `experiment/local.topologicalSort` | 12.75GB | 92/115 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.6x avg)
