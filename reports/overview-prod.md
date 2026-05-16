# Overview: prod
*Last updated: 2026-05-16 21:32 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T21:32 (55 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,241 | avg: 15,818 | max: 84,644 | trend: decreasing (-127.91/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 132.3MB | avg: 250.8MB | max: 1896.6MB | trend: decreasing (-6.22MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,241 | 14,093 | +148 | 15,818 | 84,644 | decreasing (-127.91/hr) |
| Heap InUse | 132.3MB | 118.5MB | +13.8MB | 250.8MB | 1896.6MB | decreasing (-6.22MB/hr) |
| Heap Sys | 3471.6MB | 3471.4MB | +0.2MB | 4727.5MB | 5842.7MB | |
| Heap Objects | 635,198 | 532,379 | +102819 | 1,030,460 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 45 | 16,153 | 253.3MB | 1896.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.01MB |
| 6 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `compress/flate.NewWriter` | 1.76MB |
| 9 | `bufio.NewReaderSize` | 1.5MB |
| 10 | `aws/endpoints.init` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 33.0GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.01GB |
| 3 | `internal/evaluation.mergeMetadata` | 12.22GB |
| 4 | `segmentio/kafka-go.makePartitions` | 10.01GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 7.6GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 7.52GB |
| 7 | `reflect.unsafe_NewArray` | 5.32GB |
| 8 | `go-sql-driver/mysql.(*binaryRows).readRow` | 5.1GB |
| 9 | `experiment/local.topologicalSort` | 4.95GB |
| 10 | `database/sql.convertAssignRows` | 4.52GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 53/55 | `███████████████ 100%` |
| 2 | `runtime.mallocgc` | 31.48MB | 53/55 | `████████████░░░ 85%` |
| 3 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/55 | `████████████░░░ 83%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 30.07MB | 3/55 | `████████████░░░ 82%` |
| 5 | `net/http.(*Transport).dialConn` | 30.0MB | 1/55 | `████████████░░░ 81%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 23.0MB | 9/55 | `█████████░░░░░░ 62%` |
| 7 | `bytes.growSlice` | 18.32MB | 25/55 | `███████░░░░░░░░ 50%` |
| 8 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/55 | `██████░░░░░░░░░ 45%` |
| 9 | `crypto/tls.Client` | 16.51MB | 2/55 | `██████░░░░░░░░░ 45%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB | 1/55 | `██████░░░░░░░░░ 44%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 53.94GB | 50/55 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 36.57GB | 44/55 | `██████████░░░░░ 67%` |
| 3 | `reflect.growslice` | 25.45GB | 23/55 | `███████░░░░░░░░ 47%` |
| 4 | `fmt.(*buffer).writeString` | 24.63GB | 15/55 | `██████░░░░░░░░░ 45%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 21.38GB | 50/55 | `█████░░░░░░░░░░ 39%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 21.23GB | 50/55 | `█████░░░░░░░░░░ 39%` |
| 7 | `jackskj/carta.getUniqueId` | 19.62GB | 17/55 | `█████░░░░░░░░░░ 36%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.37GB | 49/55 | `█████░░░░░░░░░░ 35%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.87GB | 28/55 | `████░░░░░░░░░░░ 31%` |
| 10 | `experiment/local.topologicalSort` | 15.25GB | 42/55 | `████░░░░░░░░░░░ 28%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.6x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
