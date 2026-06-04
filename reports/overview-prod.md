# Overview: prod
*Last updated: 2026-06-04 05:45 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T05:45 (1024 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 17,270 | avg: 10,336 | max: 84,644 | trend: decreasing (-31.64/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▄▁▅▅▅▅▅▅▄▅▅▅▅▄▄▄▄▄▅▅▅▅▅▅▄█▆▄▅▄▅▅▅▅▅▅▅▅▄▅▅▅▅▅▄▄▅▄▅▆▅▅▅▅▅▅▅▅▅▅▅▆▅▆▇▅▅▄▅▆▅▅▅▅▅▅▅▅
```

**Heap InUse** (current: 291.1MB | avg: 154.7MB | max: 2823.8MB | trend: stable (-0.45MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 20%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 17,270 | 16,384 | +886 | 10,336 | 84,644 | decreasing (-31.64/hr) |
| Heap InUse | 291.1MB | 214.1MB | +77.0MB | 154.7MB | 2823.8MB | stable (-0.45MB/hr) |
| Heap Sys | 1065.8MB | 1071.9MB | -6.1MB | 2553.8MB | 6883.9MB | |
| Heap Objects | 1,369,063 | 810,265 | +558798 | 661,375 | 14,090,816 | |

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
| 2026-06-04 | 70 | 15,622 | 263.8MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 21.74MB |
| 3 | `bufio.NewReaderSize` | 14.57MB |
| 4 | `runtime.mallocgc` | 12.6MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 8.04MB |
| 7 | `bufio.NewWriterSize` | 6.04MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 6.07GB |
| 2 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 6.02GB |
| 3 | `jackskj/carta.getUniqueId` | 4.83GB |
| 4 | `reflect.unsafe_New` | 4.45GB |
| 5 | `fmt.(*buffer).writeString` | 3.59GB |
| 6 | `carta/value.NewCell` | 3.14GB |
| 7 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 2.8GB |
| 8 | `fmt.Sprintf` | 2.27GB |
| 9 | `dotlapse-event-service/project.ApplyPagination` | 2.16GB |
| 10 | `fmt.Sprint` | 1.11GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 20.77MB | 20.27MB | 78.68MB | 0B |
| `evaluation.mergeMetadata` | 11.50MB | 11.00MB | 41.04MB | 0B |
| `local.(*Client).EvaluateV2` | 30.02MB | 28.52MB | 121.05MB | 0B |
| `local.topologicalSort` | 4.04MB | 3.04MB | 19.31MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 33.61MB | 29.54MB | 117.44MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 2.53MB | 2.53MB | 10.97MB | 0B |
| `localEvaluation.getMapOfValue` | 33.61MB | 29.54MB | 117.44MB | 0B |
| `utils.ParseFeatureFlag` | 33.61MB | 29.54MB | 117.44MB | 0B |

**Total FF alloc (current snapshot):** 169.71MB  |  **24h avg:** 623.36MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 69.34MB | 28/1024 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 62.95MB | 17/1024 | `█████████████░░ 90%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 675/1024 | `███████░░░░░░░░ 52%` |
| 4 | `database/sql.convertAssignRows` | 34.25MB | 36/1024 | `███████░░░░░░░░ 49%` |
| 5 | `runtime.mallocgc` | 21.24MB | 675/1024 | `████░░░░░░░░░░░ 30%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1024 | `███░░░░░░░░░░░░ 25%` |
| 7 | `bytes.growSlice` | 13.38MB | 482/1024 | `██░░░░░░░░░░░░░ 19%` |
| 8 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 11.12MB | 18/1024 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1024 | `██░░░░░░░░░░░░░ 15%` |
| 10 | `net/http.(*Transport).dialConn` | 10.5MB | 9/1024 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1024 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1024 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1024 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1024 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1024 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 43.28GB | 648/1024 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1024 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.76GB | 583/1024 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `fmt.Sprintf` | 13.38GB | 342/1024 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `segmentio/kafka-go.makePartitions` | 12.47GB | 441/1024 | `█░░░░░░░░░░░░░░ 9%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (12.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (8.2x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.8x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (3.1x avg)
- Heap spike to 391.4MB at 2026-05-17T10:03 (2.5x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.7x avg)
- Heap spike to 404.6MB at 2026-05-18T06:03 (2.6x avg)
- Goroutine spike to 21,569 at 2026-05-18T10:01 (2.1x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (3.2x avg)
- Heap spike to 408.3MB at 2026-05-18T16:02 (2.6x avg)
