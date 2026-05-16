# Overview: prod
*Last updated: 2026-05-16 18:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T18:31 (49 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,090 | avg: 16,006 | max: 84,644 | trend: decreasing (-128.85/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 159.0MB | avg: 264.5MB | max: 1896.6MB | trend: decreasing (-4.97MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,090 | 14,100 | -10 | 16,006 | 84,644 | decreasing (-128.85/hr) |
| Heap InUse | 159.0MB | 107.3MB | +51.7MB | 264.5MB | 1896.6MB | decreasing (-4.97MB/hr) |
| Heap Sys | 3474.7MB | 3474.4MB | +0.3MB | 4881.2MB | 5842.7MB | |
| Heap Objects | 1,111,800 | 392,723 | +719077 | 1,073,022 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 39 | 16,440 | 270.9MB | 1896.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 10.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `reflect.mapassign_faststr0` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `reflect.unsafe_NewArray` | 2.0MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 1.61MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 23.77GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 10.78GB |
| 3 | `internal/evaluation.mergeMetadata` | 7.02GB |
| 4 | `segmentio/kafka-go.makePartitions` | 5.9GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 4.38GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 4.27GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 3.64GB |
| 8 | `database/sql.convertAssignRows` | 3.22GB |
| 9 | `reflect.unsafe_NewArray` | 3.13GB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 2.91GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 47/49 | `███████████████ 100%` |
| 2 | `runtime.mallocgc` | 34.1MB | 47/49 | `█████████████░░ 93%` |
| 3 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/49 | `████████████░░░ 83%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 30.07MB | 3/49 | `████████████░░░ 82%` |
| 5 | `net/http.(*Transport).dialConn` | 30.0MB | 1/49 | `████████████░░░ 81%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 25.43MB | 8/49 | `██████████░░░░░ 69%` |
| 7 | `bytes.growSlice` | 18.91MB | 24/49 | `███████░░░░░░░░ 51%` |
| 8 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/49 | `██████░░░░░░░░░ 45%` |
| 9 | `crypto/tls.Client` | 16.51MB | 2/49 | `██████░░░░░░░░░ 45%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB | 1/49 | `██████░░░░░░░░░ 44%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 57.42GB | 44/49 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 40.67GB | 38/49 | `██████████░░░░░ 70%` |
| 3 | `reflect.growslice` | 25.45GB | 23/49 | `██████░░░░░░░░░ 44%` |
| 4 | `fmt.(*buffer).writeString` | 24.63GB | 15/49 | `██████░░░░░░░░░ 42%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 23.4GB | 44/49 | `██████░░░░░░░░░ 40%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 23.23GB | 44/49 | `██████░░░░░░░░░ 40%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 20.27GB | 43/49 | `█████░░░░░░░░░░ 35%` |
| 8 | `jackskj/carta.getUniqueId` | 19.62GB | 17/49 | `█████░░░░░░░░░░ 34%` |
| 9 | `experiment/local.topologicalSort` | 17.07GB | 36/49 | `████░░░░░░░░░░░ 29%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.87GB | 28/49 | `████░░░░░░░░░░░ 29%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.3x avg)
