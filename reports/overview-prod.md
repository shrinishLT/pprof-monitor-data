# Overview: prod
*Last updated: 2026-06-04 16:45 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T16:45 (1156 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 21,126 | avg: 11,172 | max: 84,644 | trend: decreasing (-14.25/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▄▆▇█▇▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂
```

**Heap InUse** (current: 396.4MB | avg: 170.2MB | max: 2823.8MB | trend: stable (-0.17MB/hr))
```
▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▃▅▇█▇▆▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▂▂▂▂▁▁▁▂▂▂▁▁▁▁▂▁▁▁▁▃▁▂▂▁▂▂▂▂▂▁▂▂▁▁▁▁▁▂▁▁▁▁▂▂▂▂
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 24%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 21,126 | 18,299 | +2827 | 11,172 | 84,644 | decreasing (-14.25/hr) |
| Heap InUse | 396.4MB | 468.9MB | -72.5MB | 170.2MB | 2823.8MB | stable (-0.17MB/hr) |
| Heap Sys | 4147.1MB | 4155.5MB | -8.4MB | 2659.2MB | 6883.9MB | |
| Heap Objects | 1,451,114 | 4,542,121 | -3091007 | 735,413 | 14,090,816 | |

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
| 2026-06-04 | 202 | 16,953 | 281.4MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 38.79MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 26.62MB |
| 4 | `bufio.NewReaderSize` | 19.07MB |
| 5 | `bufio.NewWriterSize` | 14.56MB |
| 6 | `runtime.mallocgc` | 11.51MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `aes/gcm.NewGCMForTLS13` | 6.01MB |
| 9 | `http2/hpack.(*headerFieldTable).addEntry` | 6.0MB |
| 10 | `net/http.(*Transport).tryPutIdleConn` | 4.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 22.86GB |
| 2 | `fmt.Sprintf` | 10.56GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 9.05GB |
| 4 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 8.65GB |
| 5 | `segmentio/kafka-go.makePartitions` | 7.15GB |
| 6 | `reflect.growslice` | 6.43GB |
| 7 | `jackskj/carta.getUniqueId` | 6.35GB |
| 8 | `reflect.unsafe_New` | 5.36GB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 5.19GB |
| 10 | `fmt.Sprint` | 5.14GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 670.16MB | 659.55MB | 412.05MB | 0B |
| `evaluation.mergeMetadata` | 346.08MB | 339.58MB | 214.14MB | 0B |
| `local.(*Client).EvaluateV2` | 1.02GB | 1.00GB | 632.23MB | 0B |
| `local.topologicalSort` | 147.77MB | 145.74MB | 88.74MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 962.18MB | 947.50MB | 588.48MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 163.66MB | 161.07MB | 99.75MB | 0B |
| `localEvaluation.getMapOfValue` | 962.18MB | 947.50MB | 588.48MB | 0B |
| `utils.ParseFeatureFlag` | 962.18MB | 947.50MB | 588.48MB | 0B |

**Total FF alloc (current snapshot):** 5.13GB  |  **24h avg:** 3.14GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 64.9MB | 40/1156 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 58.21MB | 24/1156 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 807/1156 | `████████░░░░░░░ 56%` |
| 4 | `database/sql.convertAssignRows` | 32.21MB | 50/1156 | `███████░░░░░░░░ 49%` |
| 5 | `runtime.mallocgc` | 20.0MB | 807/1156 | `████░░░░░░░░░░░ 30%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1156 | `████░░░░░░░░░░░ 27%` |
| 7 | `bytes.growSlice` | 15.59MB | 594/1156 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1156 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1156 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1156 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1156 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1156 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1156 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1156 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1156 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 40.43GB | 780/1156 | `████░░░░░░░░░░░ 32%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1156 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 18.31GB | 704/1156 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `fmt.Sprintf` | 12.35GB | 399/1156 | `█░░░░░░░░░░░░░░ 9%` |
| 10 | `segmentio/kafka-go.makePartitions` | 11.0GB | 541/1156 | `█░░░░░░░░░░░░░░ 8%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (11.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.6x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.5x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.8x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.5x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.9x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.1x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.9x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.4x avg)
