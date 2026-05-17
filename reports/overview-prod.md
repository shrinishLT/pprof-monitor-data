# Overview: prod
*Last updated: 2026-05-17 15:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T15:03 (90 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,373 | avg: 15,481 | max: 84,644 | trend: decreasing (-50.28/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 130.4MB | avg: 226.1MB | max: 1896.6MB | trend: decreasing (-3.15MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,373 | 14,751 | -378 | 15,481 | 84,644 | decreasing (-50.28/hr) |
| Heap InUse | 130.4MB | 273.4MB | -143.0MB | 226.1MB | 1896.6MB | decreasing (-3.15MB/hr) |
| Heap Sys | 2762.8MB | 2763.3MB | -0.5MB | 4240.5MB | 5842.7MB | |
| Heap Objects | 513,244 | 1,655,642 | -1142398 | 986,893 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 31 | 15,062 | 190.4MB | 391.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 8.58MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `bytes.growSlice` | 2.51MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `bufio.NewReaderSize` | 2.02MB |
| 9 | `bufio.NewWriterSize` | 1.51MB |
| 10 | `reflect.unsafe_NewArray` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 12.11GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 8.86GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 7.32GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 7.27GB |
| 5 | `experiment/local.topologicalSort` | 4.94GB |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 3.97GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 3.64GB |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 2.28GB |
| 9 | `segmentio/kafka-go.makePartitions` | 1.68GB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 1.42GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 88/90 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 36.12MB | 6/90 | `██████████████░ 98%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/90 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 25.05MB | 88/90 | `██████████░░░░░ 68%` |
| 5 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/90 | `███████░░░░░░░░ 50%` |
| 6 | `database/sql.convertAssignRows` | 15.43MB | 7/90 | `██████░░░░░░░░░ 42%` |
| 7 | `bytes.growSlice` | 14.69MB | 44/90 | `██████░░░░░░░░░ 40%` |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 13.39MB | 20/90 | `█████░░░░░░░░░░ 36%` |
| 9 | `crypto/tls.Client` | 13.01MB | 3/90 | `█████░░░░░░░░░░ 35%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 12.01MB | 7/90 | `████░░░░░░░░░░░ 32%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 55.37GB | 83/90 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 30.17GB | 79/90 | `████████░░░░░░░ 54%` |
| 3 | `fmt.(*buffer).writeString` | 24.13GB | 16/90 | `██████░░░░░░░░░ 43%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 22.37GB | 81/90 | `██████░░░░░░░░░ 40%` |
| 5 | `reflect.growslice` | 20.37GB | 36/90 | `█████░░░░░░░░░░ 36%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 18.15GB | 85/90 | `████░░░░░░░░░░░ 32%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 18.02GB | 85/90 | `████░░░░░░░░░░░ 32%` |
| 8 | `jackskj/carta.getUniqueId` | 17.48GB | 25/90 | `████░░░░░░░░░░░ 31%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 16.01GB | 5/90 | `████░░░░░░░░░░░ 28%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 14.67GB | 35/90 | `███░░░░░░░░░░░░ 26%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.4x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
