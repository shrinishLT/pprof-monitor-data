# Overview: prod
*Last updated: 2026-05-17 02:33 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T02:33 (65 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,219 | avg: 15,577 | max: 84,644 | trend: decreasing (-114.76/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 118.5MB | avg: 236.8MB | max: 1896.6MB | trend: decreasing (-5.97MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,219 | 15,513 | -1294 | 15,577 | 84,644 | decreasing (-114.76/hr) |
| Heap InUse | 118.5MB | 184.2MB | -65.7MB | 236.8MB | 1896.6MB | decreasing (-5.97MB/hr) |
| Heap Sys | 3468.9MB | 3467.8MB | +1.1MB | 4534.2MB | 5842.7MB | |
| Heap Objects | 422,171 | 651,752 | -229581 | 1,019,573 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 6 | 14,348 | 157.2MB | 184.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `reflect.mapassign_faststr0` | 2.5MB |
| 6 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `bufio.NewReaderSize` | 1.52MB |
| 9 | `segmentio/kafka-go.makePartitions` | 1.51MB |
| 10 | `reflect.unsafe_NewArray` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 47.68GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 21.71GB |
| 3 | `internal/evaluation.mergeMetadata` | 17.29GB |
| 4 | `segmentio/kafka-go.makePartitions` | 16.92GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 10.69GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 10.59GB |
| 7 | `reflect.unsafe_NewArray` | 8.78GB |
| 8 | `go-sql-driver/mysql.(*binaryRows).readRow` | 7.76GB |
| 9 | `experiment/local.topologicalSort` | 6.91GB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 6.82GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 63/65 | `███████████████ 100%` |
| 2 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/65 | `████████████░░░ 83%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/65 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 28.23MB | 63/65 | `███████████░░░░ 77%` |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 23.43MB | 4/65 | `█████████░░░░░░ 63%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 21.1MB | 10/65 | `████████░░░░░░░ 57%` |
| 7 | `bytes.growSlice` | 17.92MB | 26/65 | `███████░░░░░░░░ 48%` |
| 8 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/65 | `██████░░░░░░░░░ 45%` |
| 9 | `crypto/tls.Client` | 16.51MB | 2/65 | `██████░░░░░░░░░ 45%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB | 1/65 | `██████░░░░░░░░░ 44%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 51.66GB | 60/65 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 32.44GB | 54/65 | `█████████░░░░░░ 62%` |
| 3 | `reflect.growslice` | 25.45GB | 23/65 | `███████░░░░░░░░ 49%` |
| 4 | `fmt.(*buffer).writeString` | 24.63GB | 15/65 | `███████░░░░░░░░ 47%` |
| 5 | `jackskj/carta.getUniqueId` | 19.62GB | 17/65 | `█████░░░░░░░░░░ 37%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 19.29GB | 60/65 | `█████░░░░░░░░░░ 37%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 19.2GB | 59/65 | `█████░░░░░░░░░░ 37%` |
| 8 | `experiment/local.(*Client).EvaluateV2` | 19.15GB | 60/65 | `█████░░░░░░░░░░ 37%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.87GB | 28/65 | `████░░░░░░░░░░░ 32%` |
| 10 | `experiment/local.topologicalSort` | 13.56GB | 51/65 | `███░░░░░░░░░░░░ 26%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
