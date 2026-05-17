# Overview: prod
*Last updated: 2026-05-18 00:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T00:01 (108 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,146 | avg: 15,286 | max: 84,644 | trend: decreasing (-47.56/hr))
```
▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 143.4MB | avg: 212.8MB | max: 1896.6MB | trend: decreasing (-3.06MB/hr))
```
▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,146 | 14,071 | +75 | 15,286 | 84,644 | decreasing (-47.56/hr) |
| Heap InUse | 143.4MB | 168.7MB | -25.3MB | 212.8MB | 1896.6MB | decreasing (-3.06MB/hr) |
| Heap Sys | 3885.6MB | 3885.6MB | +0.0MB | 4126.3MB | 5842.7MB | |
| Heap Objects | 709,341 | 1,183,628 | -474287 | 943,702 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 1 | 14,146 | 143.4MB | 143.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 8.58MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `compress/flate.(*compressor).initDeflate` | 2.13MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.03MB |
| 9 | `encoding/json.typeFields` | 1.5MB |
| 10 | `reflect.mapassign_faststr0` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 45.96GB |
| 2 | `internal/evaluation.mergeMetadata` | 34.85GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 20.96GB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 20.95GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 20.88GB |
| 6 | `experiment/local.topologicalSort` | 13.97GB |
| 7 | `segmentio/kafka-go.makePartitions` | 12.25GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 10.22GB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 7.29GB |
| 10 | `database/sql.convertAssignRows` | 6.71GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 106/108 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 36.12MB | 6/108 | `██████████████░ 98%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/108 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 22.26MB | 106/108 | `█████████░░░░░░ 60%` |
| 5 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/108 | `███████░░░░░░░░ 50%` |
| 6 | `database/sql.convertAssignRows` | 15.43MB | 7/108 | `██████░░░░░░░░░ 42%` |
| 7 | `bytes.growSlice` | 13.14MB | 51/108 | `█████░░░░░░░░░░ 35%` |
| 8 | `crypto/tls.Client` | 13.01MB | 3/108 | `█████░░░░░░░░░░ 35%` |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.03MB | 23/108 | `████░░░░░░░░░░░ 32%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 12.01MB | 7/108 | `████░░░░░░░░░░░ 32%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 50.83GB | 101/108 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 29.7GB | 97/108 | `████████░░░░░░░ 58%` |
| 3 | `fmt.(*buffer).writeString` | 24.13GB | 16/108 | `███████░░░░░░░░ 47%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 20.77GB | 99/108 | `██████░░░░░░░░░ 40%` |
| 5 | `reflect.growslice` | 20.37GB | 36/108 | `██████░░░░░░░░░ 40%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 17.87GB | 103/108 | `█████░░░░░░░░░░ 35%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 17.78GB | 103/108 | `█████░░░░░░░░░░ 34%` |
| 8 | `jackskj/carta.getUniqueId` | 17.48GB | 25/108 | `█████░░░░░░░░░░ 34%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 16.01GB | 5/108 | `████░░░░░░░░░░░ 31%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 12.43GB | 53/108 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
