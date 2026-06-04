# Overview: prod
*Last updated: 2026-06-04 13:05 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T13:05 (1112 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 18,188 | avg: 10,944 | max: 84,644 | trend: decreasing (-18.57/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▄▆▇█▇▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▁
```

**Heap InUse** (current: 433.8MB | avg: 165.0MB | max: 2823.8MB | trend: stable (-0.25MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▂▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▃▅▇█▇▆▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▂▂
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 21%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 18,188 | 21,507 | -3319 | 10,944 | 84,644 | decreasing (-18.57/hr) |
| Heap InUse | 433.8MB | 408.2MB | +25.6MB | 165.0MB | 2823.8MB | stable (-0.25MB/hr) |
| Heap Sys | 1202.2MB | 1202.0MB | +0.2MB | 2624.0MB | 6883.9MB | |
| Heap Objects | 1,404,702 | 947,713 | +456989 | 708,525 | 14,090,816 | |

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
| 2026-06-04 | 158 | 16,956 | 275.4MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 21.26MB |
| 3 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 14.02MB |
| 4 | `bufio.NewReaderSize` | 12.05MB |
| 5 | `runtime.mallocgc` | 11.6MB |
| 6 | `bufio.NewWriterSize` | 10.54MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 10.05MB |
| 8 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 9 | `reflect.growslice` | 7.15MB |
| 10 | `aes/gcm.NewGCMForTLS13` | 4.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 4.12GB |
| 2 | `reflect.growslice` | 3.87GB |
| 3 | `jackskj/carta.getUniqueId` | 3.57GB |
| 4 | `fmt.Sprintf` | 3.29GB |
| 5 | `reflect.unsafe_New` | 3.13GB |
| 6 | `carta/value.NewCell` | 2.27GB |
| 7 | `fmt.(*buffer).writeString` | 2.27GB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.19GB |
| 9 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 2.05GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 1.65GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 196.99MB | 181.82MB | 221.02MB | 0B |
| `evaluation.mergeMetadata` | 108.03MB | 101.53MB | 115.34MB | 0B |
| `local.(*Client).EvaluateV2` | 289.60MB | 267.71MB | 336.91MB | 0B |
| `local.topologicalSort` | 37.42MB | 34.90MB | 47.58MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 267.15MB | 247.72MB | 334.81MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 47.52MB | 43.52MB | 33.94MB | 0B |
| `localEvaluation.getMapOfValue` | 267.15MB | 247.72MB | 334.81MB | 0B |
| `utils.ParseFeatureFlag` | 267.15MB | 247.72MB | 335.15MB | 0B |

**Total FF alloc (current snapshot):** 1.45GB  |  **24h avg:** 1.72GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 62.4MB | 37/1112 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 54.44MB | 22/1112 | `█████████████░░ 87%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 763/1112 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 31.23MB | 46/1112 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 20.5MB | 763/1112 | `████░░░░░░░░░░░ 32%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1112 | `████░░░░░░░░░░░ 28%` |
| 7 | `bytes.growSlice` | 15.26MB | 550/1112 | `███░░░░░░░░░░░░ 24%` |
| 8 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1112 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1112 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.59MB | 349/1112 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1112 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1112 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1112 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1112 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1112 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 41.91GB | 736/1112 | `█████░░░░░░░░░░ 33%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1112 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.01GB | 664/1112 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `fmt.Sprintf` | 13.01GB | 355/1112 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `segmentio/kafka-go.makePartitions` | 11.56GB | 497/1112 | `█░░░░░░░░░░░░░░ 9%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (11.5x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.7x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.6x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.9x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.6x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (3.0x avg)
- Heap spike to 424.1MB at 2026-05-18T18:33 (2.6x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (4.1x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.1x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (4.0x avg)
