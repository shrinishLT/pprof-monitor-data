# Overview: prod
*Last updated: 2026-05-18 00:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T00:31 (109 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,095 | avg: 15,275 | max: 84,644 | trend: decreasing (-47.46/hr))
```
▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 122.6MB | avg: 212.0MB | max: 1896.6MB | trend: decreasing (-3.06MB/hr))
```
▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,095 | 14,146 | -51 | 15,275 | 84,644 | decreasing (-47.46/hr) |
| Heap InUse | 122.6MB | 143.4MB | -20.8MB | 212.0MB | 1896.6MB | decreasing (-3.06MB/hr) |
| Heap Sys | 4165.8MB | 3885.6MB | +280.2MB | 4126.6MB | 5842.7MB | |
| Heap Objects | 610,724 | 709,341 | -98617 | 940,647 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 2 | 14,120 | 133.0MB | 143.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 8.58MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 8 | `encoding/json.typeFields` | 1.5MB |
| 9 | `reflect.mapassign_faststr0` | 1.5MB |
| 10 | `aws/endpoints.init` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 50.88GB |
| 2 | `internal/evaluation.mergeMetadata` | 35.37GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 23.22GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 21.26GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 21.18GB |
| 6 | `experiment/local.topologicalSort` | 14.18GB |
| 7 | `segmentio/kafka-go.makePartitions` | 12.82GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 10.38GB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 8.01GB |
| 10 | `database/sql.convertAssignRows` | 7.36GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 107/109 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 36.12MB | 6/109 | `██████████████░ 98%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/109 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 22.13MB | 107/109 | `█████████░░░░░░ 60%` |
| 5 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/109 | `███████░░░░░░░░ 50%` |
| 6 | `database/sql.convertAssignRows` | 15.43MB | 7/109 | `██████░░░░░░░░░ 42%` |
| 7 | `bytes.growSlice` | 13.14MB | 51/109 | `█████░░░░░░░░░░ 35%` |
| 8 | `crypto/tls.Client` | 13.01MB | 3/109 | `█████░░░░░░░░░░ 35%` |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.03MB | 23/109 | `████░░░░░░░░░░░ 32%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 12.01MB | 7/109 | `████░░░░░░░░░░░ 32%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 50.83GB | 102/109 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 29.75GB | 98/109 | `████████░░░░░░░ 58%` |
| 3 | `fmt.(*buffer).writeString` | 24.13GB | 16/109 | `███████░░░░░░░░ 47%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 20.79GB | 100/109 | `██████░░░░░░░░░ 40%` |
| 5 | `reflect.growslice` | 20.37GB | 36/109 | `██████░░░░░░░░░ 40%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 17.9GB | 104/109 | `█████░░░░░░░░░░ 35%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 17.81GB | 104/109 | `█████░░░░░░░░░░ 35%` |
| 8 | `jackskj/carta.getUniqueId` | 17.48GB | 25/109 | `█████░░░░░░░░░░ 34%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 16.01GB | 5/109 | `████░░░░░░░░░░░ 31%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 12.4GB | 54/109 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
