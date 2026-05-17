# Overview: prod
*Last updated: 2026-05-17 11:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T11:01 (82 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,116 | avg: 15,528 | max: 84,644 | trend: decreasing (-58.74/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁
```

**Heap InUse** (current: 254.2MB | avg: 228.1MB | max: 1896.6MB | trend: decreasing (-3.82MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,116 | 15,146 | -30 | 15,528 | 84,644 | decreasing (-58.74/hr) |
| Heap InUse | 254.2MB | 346.5MB | -92.3MB | 228.1MB | 1896.6MB | decreasing (-3.82MB/hr) |
| Heap Sys | 4095.3MB | 4083.6MB | +11.7MB | 4418.8MB | 5842.7MB | |
| Heap Objects | 714,332 | 1,459,858 | -745526 | 994,507 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 23 | 15,082 | 185.1MB | 391.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 57.81MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 5.53MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 6 | `bufio.NewReaderSize` | 3.53MB |
| 7 | `bufio.NewWriterSize` | 3.01MB |
| 8 | `compress/flate.NewWriter` | 2.64MB |
| 9 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 97.54GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 44.48GB |
| 3 | `internal/evaluation.mergeMetadata` | 41.55GB |
| 4 | `segmentio/kafka-go.makePartitions` | 28.44GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 25.27GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 25.02GB |
| 7 | `jackskj/carta.getUniqueId` | 21.82GB |
| 8 | `reflect.growslice` | 20.67GB |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 18.42GB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.27GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 80/82 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 35.48MB | 5/82 | `██████████████░ 96%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/82 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 25.78MB | 80/82 | `██████████░░░░░ 70%` |
| 5 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/82 | `███████░░░░░░░░ 50%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 15.89MB | 16/82 | `██████░░░░░░░░░ 43%` |
| 7 | `bytes.growSlice` | 15.8MB | 37/82 | `██████░░░░░░░░░ 43%` |
| 8 | `aes/gcm.NewGCMForTLS13` | 13.51MB | 6/82 | `█████░░░░░░░░░░ 36%` |
| 9 | `database/sql.convertAssignRows` | 13.33MB | 6/82 | `█████░░░░░░░░░░ 36%` |
| 10 | `crypto/tls.Client` | 13.01MB | 3/82 | `█████░░░░░░░░░░ 35%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 57.89GB | 77/82 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 31.06GB | 71/82 | `████████░░░░░░░ 53%` |
| 3 | `fmt.(*buffer).writeString` | 24.13GB | 16/82 | `██████░░░░░░░░░ 41%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 23.04GB | 76/82 | `█████░░░░░░░░░░ 39%` |
| 5 | `reflect.growslice` | 22.05GB | 32/82 | `█████░░░░░░░░░░ 38%` |
| 6 | `jackskj/carta.getUniqueId` | 18.67GB | 22/82 | `████░░░░░░░░░░░ 32%` |
| 7 | `internal/evaluation.(*Engine).Evaluate` | 18.64GB | 77/82 | `████░░░░░░░░░░░ 32%` |
| 8 | `experiment/local.(*Client).EvaluateV2` | 18.5GB | 77/82 | `████░░░░░░░░░░░ 31%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 18.42GB | 1/82 | `████░░░░░░░░░░░ 31%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.87GB | 28/82 | `████░░░░░░░░░░░ 29%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
