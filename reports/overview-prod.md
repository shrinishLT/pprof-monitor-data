# Overview: prod
*Last updated: 2026-05-16 09:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T09:02 (30 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,245 | avg: 17,057 | max: 84,644 | trend: INCREASING (+141.89/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 220.6MB | avg: 302.1MB | max: 1896.6MB | trend: INCREASING (+6.78MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,245 | 14,166 | +79 | 17,057 | 84,644 | INCREASING (+141.89/hr) |
| Heap InUse | 220.6MB | 253.2MB | -32.6MB | 302.1MB | 1896.6MB | INCREASING (+6.78MB/hr) |
| Heap Sys | 5836.6MB | 5833.4MB | +3.2MB | 5018.2MB | 5836.6MB | |
| Heap Objects | 872,060 | 1,170,051 | -297991 | 1,183,321 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 20 | 18,430 | 333.5MB | 1896.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 60.12MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `bufio.NewReaderSize` | 2.52MB |
| 6 | `reflect.mapassign_faststr0` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `reflect.unsafe_NewArray` | 2.02MB |
| 10 | `segmentio/kafka-go.makePartitions` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 64.55GB |
| 2 | `internal/evaluation.mergeMetadata` | 64.27GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 39.22GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 38.88GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 29.33GB |
| 6 | `experiment/local.topologicalSort` | 25.65GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 20.15GB |
| 8 | `reflect.growslice` | 14.05GB |
| 9 | `jackskj/carta.getUniqueId` | 13.95GB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 12.74GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 38.68MB | 5/30 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 28/30 | `██████████████░ 94%` |
| 3 | `runtime.mallocgc` | 32.54MB | 28/30 | `████████████░░░ 84%` |
| 4 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/30 | `███████████░░░░ 78%` |
| 5 | `net/http.(*Transport).dialConn` | 30.0MB | 1/30 | `███████████░░░░ 77%` |
| 6 | `bytes.growSlice` | 26.33MB | 16/30 | `██████████░░░░░ 68%` |
| 7 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/30 | `██████░░░░░░░░░ 42%` |
| 8 | `crypto/tls.Client` | 16.51MB | 2/30 | `██████░░░░░░░░░ 42%` |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 15.01MB | 1/30 | `█████░░░░░░░░░░ 38%` |
| 10 | `bufio.NewReaderSize` | 11.2MB | 15/30 | `████░░░░░░░░░░░ 28%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 67.69GB | 25/30 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 39.74GB | 19/30 | `████████░░░░░░░ 58%` |
| 3 | `fmt.(*buffer).writeString` | 31.53GB | 6/30 | `██████░░░░░░░░░ 46%` |
| 4 | `reflect.growslice` | 27.51GB | 13/30 | `██████░░░░░░░░░ 40%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 21.9GB | 25/30 | `████░░░░░░░░░░░ 32%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 21.77GB | 25/30 | `████░░░░░░░░░░░ 32%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 20.53GB | 24/30 | `████░░░░░░░░░░░ 30%` |
| 8 | `experiment/local.topologicalSort` | 15.9GB | 19/30 | `███░░░░░░░░░░░░ 23%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 13.17GB | 18/30 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `jackskj/carta.getUniqueId` | 13.05GB | 7/30 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (6.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.0x avg)
