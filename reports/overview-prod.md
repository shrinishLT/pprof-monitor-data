# Overview: prod
*Last updated: 2026-05-16 23:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T23:01 (58 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,081 | avg: 15,729 | max: 84,644 | trend: decreasing (-126.53/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 177.8MB | avg: 246.9MB | max: 1896.6MB | trend: decreasing (-6.08MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,081 | 14,074 | +7 | 15,729 | 84,644 | decreasing (-126.53/hr) |
| Heap InUse | 177.8MB | 174.4MB | +3.4MB | 246.9MB | 1896.6MB | decreasing (-6.08MB/hr) |
| Heap Sys | 3471.8MB | 3471.8MB | +0.0MB | 4662.5MB | 5842.7MB | |
| Heap Objects | 1,341,908 | 1,275,799 | +66109 | 1,040,014 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 48 | 16,025 | 248.4MB | 1896.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `segmentio/kafka-go.makePartitions` | 4.02MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 1.5MB |
| 10 | `reflect.mapassign_faststr0` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 35.74GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 16.27GB |
| 3 | `internal/evaluation.mergeMetadata` | 12.94GB |
| 4 | `segmentio/kafka-go.makePartitions` | 12.01GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 8.02GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 7.96GB |
| 7 | `reflect.unsafe_NewArray` | 6.34GB |
| 8 | `go-sql-driver/mysql.(*binaryRows).readRow` | 5.52GB |
| 9 | `experiment/local.topologicalSort` | 5.21GB |
| 10 | `database/sql.convertAssignRows` | 4.92GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 56/58 | `███████████████ 100%` |
| 2 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/58 | `████████████░░░ 83%` |
| 3 | `runtime.mallocgc` | 30.38MB | 56/58 | `████████████░░░ 82%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 30.07MB | 3/58 | `████████████░░░ 82%` |
| 5 | `net/http.(*Transport).dialConn` | 30.0MB | 1/58 | `████████████░░░ 81%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 23.0MB | 9/58 | `█████████░░░░░░ 62%` |
| 7 | `bytes.growSlice` | 18.32MB | 25/58 | `███████░░░░░░░░ 50%` |
| 8 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/58 | `██████░░░░░░░░░ 45%` |
| 9 | `crypto/tls.Client` | 16.51MB | 2/58 | `██████░░░░░░░░░ 45%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB | 1/58 | `██████░░░░░░░░░ 44%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 52.85GB | 53/58 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 35.05GB | 47/58 | `█████████░░░░░░ 66%` |
| 3 | `reflect.growslice` | 25.45GB | 23/58 | `███████░░░░░░░░ 48%` |
| 4 | `fmt.(*buffer).writeString` | 24.63GB | 15/58 | `██████░░░░░░░░░ 46%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 20.62GB | 53/58 | `█████░░░░░░░░░░ 39%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 20.47GB | 53/58 | `█████░░░░░░░░░░ 38%` |
| 7 | `jackskj/carta.getUniqueId` | 19.62GB | 17/58 | `█████░░░░░░░░░░ 37%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.16GB | 52/58 | `█████░░░░░░░░░░ 36%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.87GB | 28/58 | `████░░░░░░░░░░░ 31%` |
| 10 | `experiment/local.topologicalSort` | 14.57GB | 45/58 | `████░░░░░░░░░░░ 27%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.7x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
