# Overview: prod
*Last updated: 2026-05-16 09:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T09:31 (31 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,710 | avg: 16,981 | max: 84,644 | trend: INCREASING (+100.20/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 235.1MB | avg: 300.0MB | max: 1896.6MB | trend: INCREASING (+5.33MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,710 | 14,245 | +465 | 16,981 | 84,644 | INCREASING (+100.20/hr) |
| Heap InUse | 235.1MB | 220.6MB | +14.5MB | 300.0MB | 1896.6MB | INCREASING (+5.33MB/hr) |
| Heap Sys | 5837.6MB | 5836.6MB | +1.0MB | 5044.6MB | 5837.6MB | |
| Heap Objects | 728,646 | 872,060 | -143414 | 1,168,654 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 21 | 18,252 | 328.8MB | 1896.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 60.12MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `bytes.growSlice` | 3.52MB |
| 6 | `bufio.NewWriterSize` | 2.52MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.51MB |
| 8 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `bufio.NewReaderSize` | 2.02MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 65.54GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 64.55GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 40.01GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 39.62GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 29.33GB |
| 6 | `experiment/local.topologicalSort` | 26.16GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 20.56GB |
| 8 | `jackskj/carta.getUniqueId` | 14.91GB |
| 9 | `reflect.growslice` | 14.63GB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 12.9GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 29/31 | `███████████████ 100%` |
| 2 | `runtime.mallocgc` | 33.49MB | 29/31 | `█████████████░░ 91%` |
| 3 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 32.65MB | 6/31 | `█████████████░░ 89%` |
| 4 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/31 | `████████████░░░ 83%` |
| 5 | `net/http.(*Transport).dialConn` | 30.0MB | 1/31 | `████████████░░░ 81%` |
| 6 | `bytes.growSlice` | 24.99MB | 17/31 | `██████████░░░░░ 68%` |
| 7 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/31 | `██████░░░░░░░░░ 45%` |
| 8 | `crypto/tls.Client` | 16.51MB | 2/31 | `██████░░░░░░░░░ 45%` |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 15.01MB | 1/31 | `██████░░░░░░░░░ 40%` |
| 10 | `reflect.growslice` | 11.07MB | 2/31 | `████░░░░░░░░░░░ 30%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 67.57GB | 26/31 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 41.03GB | 20/31 | `█████████░░░░░░ 60%` |
| 3 | `fmt.(*buffer).writeString` | 31.53GB | 6/31 | `██████░░░░░░░░░ 46%` |
| 4 | `reflect.growslice` | 26.59GB | 14/31 | `█████░░░░░░░░░░ 39%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 22.6GB | 26/31 | `█████░░░░░░░░░░ 33%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 22.45GB | 26/31 | `████░░░░░░░░░░░ 33%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 20.88GB | 25/31 | `████░░░░░░░░░░░ 30%` |
| 8 | `experiment/local.topologicalSort` | 16.41GB | 20/31 | `███░░░░░░░░░░░░ 24%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 13.55GB | 19/31 | `███░░░░░░░░░░░░ 20%` |
| 10 | `jackskj/carta.getUniqueId` | 13.28GB | 8/31 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (6.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.0x avg)
