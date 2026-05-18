# Overview: prod
*Last updated: 2026-05-18 06:33 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T06:33 (121 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,596 | avg: 15,194 | max: 84,644 | trend: decreasing (-41.83/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 139.1MB | avg: 208.1MB | max: 1896.6MB | trend: decreasing (-2.56MB/hr))
```
▆▃▄▄▃▄▆▃▃▅▅▃▃▄▄▁▂▁▂▁▂▄▁▂▃▂▁▁▁▁▂▂▂▁▂▂▂▂▂▁▁▁▂▂▃▂▃▃▂▁▂▂▁▂▇▆▄▆▃▃▁▂▃▄▁▂▁▁▂▁▂▁▂▁▂▂▁▁▁▂▂▂▁▁▁▁▂▂▁▁▁▁▁▅█▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,596 | 14,692 | -96 | 15,194 | 84,644 | decreasing (-41.83/hr) |
| Heap InUse | 139.1MB | 404.6MB | -265.5MB | 208.1MB | 1896.6MB | decreasing (-2.56MB/hr) |
| Heap Sys | 4699.4MB | 4699.2MB | +0.2MB | 4170.1MB | 5842.7MB | |
| Heap Objects | 504,075 | 2,396,996 | -1892921 | 931,379 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 14 | 14,409 | 167.2MB | 404.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 8.58MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `bytes.growSlice` | 2.51MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 1.51MB |
| 9 | `encoding/json.typeFields` | 1.5MB |
| 10 | `net/http.(*Transport).queueForIdleConn` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 117.2GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 102.08GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 71.02GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 70.76GB |
| 5 | `experiment/local.topologicalSort` | 46.76GB |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 46.64GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.18GB |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 22.44GB |
| 9 | `segmentio/kafka-go.makePartitions` | 20.09GB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 17.28GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 36.75MB | 7/121 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 119/121 | `██████████████░ 99%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/121 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 20.76MB | 119/121 | `████████░░░░░░░ 56%` |
| 5 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/121 | `███████░░░░░░░░ 50%` |
| 6 | `database/sql.convertAssignRows` | 17.44MB | 8/121 | `███████░░░░░░░░ 47%` |
| 7 | `crypto/tls.Client` | 13.01MB | 3/121 | `█████░░░░░░░░░░ 35%` |
| 8 | `bytes.growSlice` | 12.44MB | 55/121 | `█████░░░░░░░░░░ 33%` |
| 9 | `aes/gcm.NewGCMForTLS13` | 12.01MB | 7/121 | `████░░░░░░░░░░░ 32%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 10.99MB | 26/121 | `████░░░░░░░░░░░ 29%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 52.61GB | 114/121 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 34.29GB | 110/121 | `█████████░░░░░░ 65%` |
| 3 | `fmt.(*buffer).writeString` | 24.13GB | 16/121 | `██████░░░░░░░░░ 45%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 21.88GB | 112/121 | `██████░░░░░░░░░ 41%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 20.49GB | 116/121 | `█████░░░░░░░░░░ 38%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 20.42GB | 116/121 | `█████░░░░░░░░░░ 38%` |
| 7 | `reflect.growslice` | 20.37GB | 36/121 | `█████░░░░░░░░░░ 38%` |
| 8 | `jackskj/carta.getUniqueId` | 17.48GB | 25/121 | `████░░░░░░░░░░░ 33%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 16.01GB | 5/121 | `████░░░░░░░░░░░ 30%` |
| 10 | `experiment/local.topologicalSort` | 14.17GB | 98/121 | `████░░░░░░░░░░░ 26%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.6x avg)
