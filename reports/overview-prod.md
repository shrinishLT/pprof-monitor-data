# Overview: prod
*Last updated: 2026-05-16 07:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T07:03 (27 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,204 | avg: 17,366 | max: 84,644 | trend: INCREASING (+347.64/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 202.3MB | avg: 309.2MB | max: 1896.6MB | trend: INCREASING (+12.83MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,204 | 14,441 | -237 | 17,366 | 84,644 | INCREASING (+347.64/hr) |
| Heap InUse | 202.3MB | 320.3MB | -118.0MB | 309.2MB | 1896.6MB | INCREASING (+12.83MB/hr) |
| Heap Sys | 5833.1MB | 5832.7MB | +0.4MB | 4927.5MB | 5833.1MB | |
| Heap Objects | 527,051 | 1,788,140 | -1261089 | 1,206,680 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 17 | 19,162 | 350.2MB | 1896.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 60.12MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `reflect.growslice` | 2.85MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `bytes.growSlice` | 1.51MB |
| 10 | `aws/endpoints.init` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 59.37GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 56.76GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 36.19GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 35.89GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 25.78GB |
| 6 | `experiment/local.topologicalSort` | 23.68GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 18.62GB |
| 8 | `reflect.growslice` | 13.56GB |
| 9 | `jackskj/carta.getUniqueId` | 13.24GB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 11.44GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 38.68MB | 5/27 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 25/27 | `██████████████░ 94%` |
| 3 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/27 | `███████████░░░░ 78%` |
| 4 | `net/http.(*Transport).dialConn` | 30.0MB | 1/27 | `███████████░░░░ 77%` |
| 5 | `runtime.mallocgc` | 29.23MB | 25/27 | `███████████░░░░ 75%` |
| 6 | `bytes.growSlice` | 26.33MB | 16/27 | `██████████░░░░░ 68%` |
| 7 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/27 | `██████░░░░░░░░░ 42%` |
| 8 | `crypto/tls.Client` | 16.51MB | 2/27 | `██████░░░░░░░░░ 42%` |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 15.01MB | 1/27 | `█████░░░░░░░░░░ 38%` |
| 10 | `bufio.NewReaderSize` | 12.5MB | 13/27 | `████░░░░░░░░░░░ 32%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 68.4GB | 22/27 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 35.62GB | 16/27 | `███████░░░░░░░░ 52%` |
| 3 | `reflect.growslice` | 31.6GB | 10/27 | `██████░░░░░░░░░ 46%` |
| 4 | `fmt.(*buffer).writeString` | 31.53GB | 6/27 | `██████░░░░░░░░░ 46%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 19.76GB | 22/27 | `████░░░░░░░░░░░ 28%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 19.65GB | 22/27 | `████░░░░░░░░░░░ 28%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 19.41GB | 21/27 | `████░░░░░░░░░░░ 28%` |
| 8 | `experiment/local.topologicalSort` | 14.27GB | 16/27 | `███░░░░░░░░░░░░ 20%` |
| 9 | `jackskj/carta.getUniqueId` | 12.58GB | 4/27 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 11.93GB | 15/27 | `██░░░░░░░░░░░░░ 17%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (6.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (4.9x avg)
