# Overview: prod
*Last updated: 2026-06-04 14:45 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T14:45 (1132 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 19,124 | avg: 11,044 | max: 84,644 | trend: decreasing (-16.56/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▄▆▇█▇▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 355.3MB | avg: 167.3MB | max: 2823.8MB | trend: stable (-0.21MB/hr))
```
▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▃▅▇█▇▆▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▂▂▂▂▁▁▁▂▂▂▁▁▁▁▂▁▁▁▁▃▁▂
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 22%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 19,124 | 16,347 | +2777 | 11,044 | 84,644 | decreasing (-16.56/hr) |
| Heap InUse | 355.3MB | 246.7MB | +108.6MB | 167.3MB | 2823.8MB | stable (-0.21MB/hr) |
| Heap Sys | 3417.5MB | 3422.7MB | -5.2MB | 2630.1MB | 6883.9MB | |
| Heap Objects | 1,550,773 | 800,788 | +749985 | 721,055 | 14,090,816 | |

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
| 2026-06-04 | 178 | 16,916 | 277.7MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 29.33MB |
| 3 | `bufio.NewReaderSize` | 13.05MB |
| 4 | `runtime.mallocgc` | 11.01MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 10.05MB |
| 6 | `bufio.NewWriterSize` | 10.04MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 4.5MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 4.0MB |
| 10 | `net/http.(*http2Framer).startWriteDataPadded` | 3.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 14.15GB |
| 2 | `fmt.Sprintf` | 6.31GB |
| 3 | `reflect.growslice` | 5.74GB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 5.61GB |
| 5 | `jackskj/carta.getUniqueId` | 5.37GB |
| 6 | `reflect.unsafe_New` | 4.64GB |
| 7 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 4.58GB |
| 8 | `segmentio/kafka-go.makePartitions` | 4.44GB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 3.39GB |
| 10 | `fmt.(*buffer).writeString` | 3.34GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 408.46MB | 395.83MB | 227.80MB | 0B |
| `evaluation.mergeMetadata` | 208.55MB | 202.55MB | 120.69MB | 0B |
| `local.(*Client).EvaluateV2` | 622.55MB | 602.10MB | 344.44MB | 0B |
| `local.topologicalSort` | 87.54MB | 85.02MB | 47.63MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 584.20MB | 566.31MB | 329.01MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 96.69MB | 93.64MB | 47.14MB | 0B |
| `localEvaluation.getMapOfValue` | 584.20MB | 566.31MB | 329.01MB | 0B |
| `utils.ParseFeatureFlag` | 584.20MB | 566.31MB | 329.14MB | 0B |

**Total FF alloc (current snapshot):** 3.10GB  |  **24h avg:** 1.73GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 63.4MB | 39/1132 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 58.21MB | 24/1132 | `█████████████░░ 91%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 783/1132 | `████████░░░░░░░ 57%` |
| 4 | `database/sql.convertAssignRows` | 31.76MB | 49/1132 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 20.26MB | 783/1132 | `████░░░░░░░░░░░ 31%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1132 | `████░░░░░░░░░░░ 28%` |
| 7 | `bytes.growSlice` | 15.33MB | 570/1132 | `███░░░░░░░░░░░░ 24%` |
| 8 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1132 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1132 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.44MB | 25/1132 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1132 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1132 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1132 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1132 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1132 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 41.08GB | 756/1132 | `████░░░░░░░░░░░ 32%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1132 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 18.68GB | 680/1132 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `fmt.Sprintf` | 12.58GB | 375/1132 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `segmentio/kafka-go.makePartitions` | 11.24GB | 517/1132 | `█░░░░░░░░░░░░░░ 8%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (11.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.7x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.6x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.9x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.5x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.9x avg)
- Heap spike to 424.1MB at 2026-05-18T18:33 (2.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (4.0x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.1x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (4.0x avg)
