# Overview: prod
*Last updated: 2026-05-18 01:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T01:31 (111 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,067 | avg: 15,254 | max: 84,644 | trend: decreasing (-47.18/hr))
```
▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 137.4MB | avg: 210.5MB | max: 1896.6MB | trend: decreasing (-3.05MB/hr))
```
▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,067 | 14,143 | -76 | 15,254 | 84,644 | decreasing (-47.18/hr) |
| Heap InUse | 137.4MB | 124.9MB | +12.5MB | 210.5MB | 1896.6MB | decreasing (-3.05MB/hr) |
| Heap Sys | 4165.8MB | 4165.8MB | +0.0MB | 4127.3MB | 5842.7MB | |
| Heap Objects | 841,638 | 577,420 | +264218 | 936,483 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 4 | 14,113 | 132.1MB | 143.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 8.58MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.51MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.unsafe_NewArray` | 2.01MB |
| 9 | `reflect.mapassign_faststr0` | 2.0MB |
| 10 | `encoding/json.typeFields` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 55.28GB |
| 2 | `internal/evaluation.mergeMetadata` | 36.25GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 25.25GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 21.77GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 21.71GB |
| 6 | `experiment/local.topologicalSort` | 14.51GB |
| 7 | `segmentio/kafka-go.makePartitions` | 13.96GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 10.63GB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 8.65GB |
| 10 | `database/sql.convertAssignRows` | 7.95GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 109/111 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 36.12MB | 6/111 | `██████████████░ 98%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/111 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 21.88MB | 109/111 | `████████░░░░░░░ 59%` |
| 5 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/111 | `███████░░░░░░░░ 50%` |
| 6 | `database/sql.convertAssignRows` | 15.43MB | 7/111 | `██████░░░░░░░░░ 42%` |
| 7 | `bytes.growSlice` | 13.14MB | 51/111 | `█████░░░░░░░░░░ 35%` |
| 8 | `crypto/tls.Client` | 13.01MB | 3/111 | `█████░░░░░░░░░░ 35%` |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.03MB | 23/111 | `████░░░░░░░░░░░ 32%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 12.01MB | 7/111 | `████░░░░░░░░░░░ 32%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 50.88GB | 104/111 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 29.88GB | 100/111 | `████████░░░░░░░ 58%` |
| 3 | `fmt.(*buffer).writeString` | 24.13GB | 16/111 | `███████░░░░░░░░ 47%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 20.86GB | 102/111 | `██████░░░░░░░░░ 40%` |
| 5 | `reflect.growslice` | 20.37GB | 36/111 | `██████░░░░░░░░░ 40%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 17.97GB | 106/111 | `█████░░░░░░░░░░ 35%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 17.88GB | 106/111 | `█████░░░░░░░░░░ 35%` |
| 8 | `jackskj/carta.getUniqueId` | 17.48GB | 25/111 | `█████░░░░░░░░░░ 34%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 16.01GB | 5/111 | `████░░░░░░░░░░░ 31%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 12.33GB | 56/111 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
