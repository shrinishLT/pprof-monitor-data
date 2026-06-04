# Overview: prod
*Last updated: 2026-06-04 14:26 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T14:26 (1128 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,011 | avg: 11,024 | max: 84,644 | trend: decreasing (-16.95/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▄▆▇█▇▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 237.2MB | avg: 166.6MB | max: 2823.8MB | trend: stable (-0.22MB/hr))
```
▂▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▃▅▇█▇▆▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▂▂▂▂▁▁▁▂▂▂▁▁▁▁▂▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,011 | 17,137 | -1126 | 11,024 | 84,644 | decreasing (-16.95/hr) |
| Heap InUse | 237.2MB | 284.1MB | -46.9MB | 166.6MB | 2823.8MB | stable (-0.22MB/hr) |
| Heap Sys | 3417.4MB | 3415.8MB | +1.6MB | 2627.3MB | 6883.9MB | |
| Heap Objects | 940,091 | 1,156,205 | -216114 | 716,669 | 14,090,816 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 68 | 16,073 | 267.1MB | 501.2MB |
| 2026-05-22 | 50 | 16,200 | 234.4MB | 962.7MB |
| 2026-05-23 | 48 | 14,757 | 174.9MB | 359.1MB |
| 2026-05-24 | 48 | 14,694 | 189.5MB | 689.3MB |
| 2026-05-25 | 48 | 15,445 | 248.9MB | 478.8MB |
| 2026-05-26 | 46 | 15,843 | 216.2MB | 639.8MB |
| 2026-05-27 | 47 | 11,771 | 179.8MB | 615.8MB |
| 2026-05-28 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-05-29 | 49 | 370 | 6.8MB | 333.9MB |
| 2026-05-30 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-05-31 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-06-01 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-06-02 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-06-03 | 54 | 2,097 | 29.7MB | 299.4MB |
| 2026-06-04 | 174 | 16,921 | 275.5MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 11.56MB |
| 3 | `runtime.mallocgc` | 11.01MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 6.53MB |
| 6 | `bufio.NewReaderSize` | 4.52MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 4.5MB |
| 8 | `bufio.NewWriterSize` | 4.02MB |
| 9 | `compress/flate.NewWriter` | 2.64MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 12.01GB |
| 2 | `fmt.Sprintf` | 5.78GB |
| 3 | `reflect.growslice` | 5.69GB |
| 4 | `jackskj/carta.getUniqueId` | 5.31GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 4.79GB |
| 6 | `reflect.unsafe_New` | 4.61GB |
| 7 | `segmentio/kafka-go.makePartitions` | 4.01GB |
| 8 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 3.93GB |
| 9 | `fmt.(*buffer).writeString` | 3.32GB |
| 10 | `carta/value.NewCell` | 3.29GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 346.35MB | 336.76MB | 223.96MB | 0B |
| `evaluation.mergeMetadata` | 181.54MB | 177.04MB | 118.69MB | 0B |
| `local.(*Client).EvaluateV2` | 534.16MB | 517.87MB | 339.47MB | 0B |
| `local.topologicalSort` | 75.92MB | 72.36MB | 47.32MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 504.59MB | 488.78MB | 327.15MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 82.83MB | 80.31MB | 43.53MB | 0B |
| `localEvaluation.getMapOfValue` | 504.59MB | 488.78MB | 327.15MB | 0B |
| `utils.ParseFeatureFlag` | 504.59MB | 488.78MB | 327.33MB | 0B |

**Total FF alloc (current snapshot):** 2.67GB  |  **24h avg:** 1.71GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 62.94MB | 38/1128 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 58.75MB | 23/1128 | `██████████████░ 93%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 779/1128 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 31.33MB | 48/1128 | `███████░░░░░░░░ 49%` |
| 5 | `runtime.mallocgc` | 20.31MB | 779/1128 | `████░░░░░░░░░░░ 32%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1128 | `████░░░░░░░░░░░ 28%` |
| 7 | `bytes.growSlice` | 15.33MB | 566/1128 | `███░░░░░░░░░░░░ 24%` |
| 8 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1128 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1128 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.44MB | 364/1128 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1128 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1128 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1128 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1128 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1128 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 41.22GB | 752/1128 | `████░░░░░░░░░░░ 32%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1128 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 18.75GB | 676/1128 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `fmt.Sprintf` | 12.65GB | 371/1128 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `segmentio/kafka-go.makePartitions` | 11.3GB | 513/1128 | `█░░░░░░░░░░░░░░ 9%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (11.4x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.7x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.6x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.9x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.5x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (3.0x avg)
- Heap spike to 424.1MB at 2026-05-18T18:33 (2.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (4.0x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.1x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (4.0x avg)
