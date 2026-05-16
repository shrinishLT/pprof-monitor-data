# Overview: prod
*Last updated: 2026-05-16 07:32 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T07:32 (28 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,420 | avg: 17,260 | max: 84,644 | trend: INCREASING (+268.15/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 241.5MB | avg: 306.8MB | max: 1896.6MB | trend: INCREASING (+10.50MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,420 | 14,204 | +216 | 17,260 | 84,644 | INCREASING (+268.15/hr) |
| Heap InUse | 241.5MB | 202.3MB | +39.2MB | 306.8MB | 1896.6MB | INCREASING (+10.50MB/hr) |
| Heap Sys | 5833.1MB | 5833.1MB | +0.0MB | 4959.8MB | 5833.1MB | |
| Heap Objects | 877,164 | 527,051 | +350113 | 1,194,912 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 18 | 18,899 | 344.2MB | 1896.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 60.12MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `bufio.NewReaderSize` | 3.03MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `segmentio/kafka-go.makePartitions` | 1.5MB |
| 10 | `aws/endpoints.init` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 61.51GB |
| 2 | `internal/evaluation.mergeMetadata` | 60.12GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 36.67GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 36.35GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 27.94GB |
| 6 | `experiment/local.topologicalSort` | 23.98GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 18.84GB |
| 8 | `reflect.growslice` | 13.7GB |
| 9 | `jackskj/carta.getUniqueId` | 13.45GB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 12.16GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 38.68MB | 5/28 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 26/28 | `██████████████░ 94%` |
| 3 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/28 | `███████████░░░░ 78%` |
| 4 | `runtime.mallocgc` | 30.41MB | 26/28 | `███████████░░░░ 78%` |
| 5 | `net/http.(*Transport).dialConn` | 30.0MB | 1/28 | `███████████░░░░ 77%` |
| 6 | `bytes.growSlice` | 26.33MB | 16/28 | `██████████░░░░░ 68%` |
| 7 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/28 | `██████░░░░░░░░░ 42%` |
| 8 | `crypto/tls.Client` | 16.51MB | 2/28 | `██████░░░░░░░░░ 42%` |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 15.01MB | 1/28 | `█████░░░░░░░░░░ 38%` |
| 10 | `bufio.NewReaderSize` | 11.82MB | 14/28 | `████░░░░░░░░░░░ 30%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 68.1GB | 23/28 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 37.06GB | 17/28 | `████████░░░░░░░ 54%` |
| 3 | `fmt.(*buffer).writeString` | 31.53GB | 6/28 | `██████░░░░░░░░░ 46%` |
| 4 | `reflect.growslice` | 29.97GB | 11/28 | `██████░░░░░░░░░ 44%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 20.49GB | 23/28 | `████░░░░░░░░░░░ 30%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 20.37GB | 23/28 | `████░░░░░░░░░░░ 29%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 19.79GB | 22/28 | `████░░░░░░░░░░░ 29%` |
| 8 | `experiment/local.topologicalSort` | 14.84GB | 17/28 | `███░░░░░░░░░░░░ 21%` |
| 9 | `jackskj/carta.getUniqueId` | 12.75GB | 5/28 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 12.36GB | 16/28 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (6.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (4.9x avg)
