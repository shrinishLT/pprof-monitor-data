# Overview: prod
*Last updated: 2026-06-04 12:50 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T12:50 (1109 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 21,786 | avg: 10,919 | max: 84,644 | trend: decreasing (-19.00/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▄▆▇█▇▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂
```

**Heap InUse** (current: 468.6MB | avg: 164.3MB | max: 2823.8MB | trend: stable (-0.26MB/hr))
```
▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▂▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▃▅▇█▇▆▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂
```

## Current Status

Goroutines: `█████░░░░░░░░░░░░░░░ 25%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 21,786 | 21,937 | -151 | 10,919 | 84,644 | decreasing (-19.00/hr) |
| Heap InUse | 468.6MB | 454.9MB | +13.7MB | 164.3MB | 2823.8MB | stable (-0.26MB/hr) |
| Heap Sys | 1148.0MB | 1149.0MB | -1.0MB | 2627.9MB | 6883.9MB | |
| Heap Objects | 1,969,423 | 1,865,741 | +103682 | 706,524 | 14,090,816 | |

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
| 2026-06-04 | 155 | 16,891 | 272.4MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 45.4MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 20.09MB |
| 4 | `bufio.NewReaderSize` | 19.57MB |
| 5 | `bufio.NewWriterSize` | 18.07MB |
| 6 | `runtime.mallocgc` | 11.6MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 11.01MB |
| 8 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 9 | `crypto/tls.Client` | 5.0MB |
| 10 | `net/http.(*Transport).tryPutIdleConn` | 4.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 3.13GB |
| 2 | `jackskj/carta.getUniqueId` | 2.86GB |
| 3 | `reflect.unsafe_New` | 2.52GB |
| 4 | `fmt.Sprintf` | 2.32GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 2.2GB |
| 6 | `segmentio/kafka-go.makePartitions` | 1.85GB |
| 7 | `fmt.(*buffer).writeString` | 1.81GB |
| 8 | `carta/value.NewCell` | 1.78GB |
| 9 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 1.38GB |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 1.13GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 163.42MB | 152.79MB | 222.09MB | 0B |
| `evaluation.mergeMetadata` | 92.52MB | 86.52MB | 115.50MB | 0B |
| `local.(*Client).EvaluateV2` | 236.85MB | 219.89MB | 338.88MB | 0B |
| `local.topologicalSort` | 30.33MB | 29.33MB | 47.86MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 219.40MB | 203.06MB | 337.93MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 38.41MB | 35.25MB | 33.15MB | 0B |
| `localEvaluation.getMapOfValue` | 219.40MB | 203.06MB | 337.93MB | 0B |
| `utils.ParseFeatureFlag` | 219.40MB | 203.06MB | 338.30MB | 0B |

**Total FF alloc (current snapshot):** 1.19GB  |  **24h avg:** 1.73GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 62.4MB | 37/1109 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 54.44MB | 22/1109 | `█████████████░░ 87%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 760/1109 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 31.23MB | 46/1109 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 20.54MB | 760/1109 | `████░░░░░░░░░░░ 32%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1109 | `████░░░░░░░░░░░ 28%` |
| 7 | `bytes.growSlice` | 15.12MB | 547/1109 | `███░░░░░░░░░░░░ 24%` |
| 8 | `net/http.(*Transport).dialConn` | 12.77MB | 15/1109 | `███░░░░░░░░░░░░ 20%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1109 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.54MB | 346/1109 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1109 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1109 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1109 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1109 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1109 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 42.07GB | 733/1109 | `█████░░░░░░░░░░ 33%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1109 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.06GB | 662/1109 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `fmt.Sprintf` | 13.09GB | 352/1109 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `segmentio/kafka-go.makePartitions` | 11.62GB | 494/1109 | `█░░░░░░░░░░░░░░ 9%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (11.5x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.8x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.6x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.9x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.6x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (3.0x avg)
- Heap spike to 424.1MB at 2026-05-18T18:33 (2.6x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (4.1x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.1x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (4.0x avg)
