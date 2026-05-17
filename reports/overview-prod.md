# Overview: prod
*Last updated: 2026-05-18 02:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T02:31 (113 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,119 | avg: 15,243 | max: 84,644 | trend: decreasing (-45.90/hr))
```
▁▁▄▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 156.5MB | avg: 209.5MB | max: 1896.6MB | trend: decreasing (-3.00MB/hr))
```
▃▄▇▂▃▄▅█▅▂▃▃▃▃▅▃▂▄▄▂▂▃▃▁▂▁▂▁▂▃▁▂▂▂▁▁▁▁▂▂▂▁▁▂▂▂▂▁▁▁▂▂▂▂▂▃▂▁▂▂▁▂▆▅▃▅▂▃▁▂▂▄▁▂▁▁▁▁▂▁▂▁▁▂▁▁▁▂▂▂▁▁▁▁▁▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,119 | 15,118 | -999 | 15,243 | 84,644 | decreasing (-45.90/hr) |
| Heap InUse | 156.5MB | 149.1MB | +7.4MB | 209.5MB | 1896.6MB | decreasing (-3.00MB/hr) |
| Heap Sys | 4698.5MB | 4163.1MB | +535.4MB | 4132.7MB | 5842.7MB | |
| Heap Objects | 911,999 | 293,307 | +618692 | 930,575 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 6 | 14,281 | 139.0MB | 156.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 8.58MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `reflect.unsafe_NewArray` | 2.01MB |
| 8 | `reflect.mapassign_faststr0` | 2.0MB |
| 9 | `encoding/json.typeFields` | 1.5MB |
| 10 | `aws/endpoints.init` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 62.22GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 60.27GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 37.47GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 37.43GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 27.56GB |
| 6 | `experiment/local.topologicalSort` | 24.8GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 18.86GB |
| 8 | `segmentio/kafka-go.makePartitions` | 15.15GB |
| 9 | `internal/evaluation.(*Engine).evaluateFlag` | 11.82GB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 9.76GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 111/113 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 36.12MB | 6/113 | `██████████████░ 98%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/113 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 21.64MB | 111/113 | `████████░░░░░░░ 59%` |
| 5 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/113 | `███████░░░░░░░░ 50%` |
| 6 | `database/sql.convertAssignRows` | 15.43MB | 7/113 | `██████░░░░░░░░░ 42%` |
| 7 | `crypto/tls.Client` | 13.01MB | 3/113 | `█████░░░░░░░░░░ 35%` |
| 8 | `bytes.growSlice` | 13.0MB | 52/113 | `█████░░░░░░░░░░ 35%` |
| 9 | `aes/gcm.NewGCMForTLS13` | 12.01MB | 7/113 | `████░░░░░░░░░░░ 32%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.7MB | 24/113 | `████░░░░░░░░░░░ 31%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 51.01GB | 106/113 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 30.47GB | 102/113 | `████████░░░░░░░ 59%` |
| 3 | `fmt.(*buffer).writeString` | 24.13GB | 16/113 | `███████░░░░░░░░ 47%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 20.97GB | 104/113 | `██████░░░░░░░░░ 41%` |
| 5 | `reflect.growslice` | 20.37GB | 36/113 | `█████░░░░░░░░░░ 39%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 18.3GB | 108/113 | `█████░░░░░░░░░░ 35%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 18.22GB | 108/113 | `█████░░░░░░░░░░ 35%` |
| 8 | `jackskj/carta.getUniqueId` | 17.48GB | 25/113 | `█████░░░░░░░░░░ 34%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 16.01GB | 5/113 | `████░░░░░░░░░░░ 31%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 12.53GB | 58/113 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.6x avg)
