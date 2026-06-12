# Overview: prod
*Last updated: 2026-06-12 10:26 IST*
*Data range: 2026-05-15T16:03 to 2026-06-12T10:25 (3382 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 24,111 | avg: 14,368 | max: 84,644 | trend: INCREASING (+3.43/hr))
```
▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▂▃▄▆█▄
```

**Heap InUse** (current: 614.8MB | avg: 238.2MB | max: 3154.1MB | trend: stable (+0.10MB/hr))
```
▁▁▂▂▁▂▁▁▁▂▃▁▂▁▁▁▂▁▁▂▁▁▂▂▁▁▁▁▂▁▂▁▁▂▁▁▂▁▁▂▂▁▂▁▁▂▂▂▂▁▁▂▁▂▂▁▁▂▁▁▂▁▁▂▁▁▁▁▂▁▂▄▂▂▂▁▂▁▂▂▂▁▁▂▂▃▂▁▁▂▃▃▅█▆▆
```

## Current Status

Goroutines: `█████░░░░░░░░░░░░░░░ 28%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 24,111 | 35,319 | -11208 | 14,368 | 84,644 | INCREASING (+3.43/hr) |
| Heap InUse | 614.8MB | 673.8MB | -59.0MB | 238.2MB | 3154.1MB | stable (+0.10MB/hr) |
| Heap Sys | 3274.1MB | 3266.8MB | +7.3MB | 2683.7MB | 6883.9MB | |
| Heap Objects | 1,846,233 | 2,026,736 | -180503 | 1,022,277 | 17,165,538 | |

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
| 2026-06-04 | 288 | 16,555 | 265.7MB | 2823.8MB |
| 2026-06-05 | 287 | 15,969 | 239.1MB | 3154.1MB |
| 2026-06-06 | 288 | 15,841 | 221.6MB | 1932.8MB |
| 2026-06-07 | 288 | 15,421 | 234.3MB | 1942.9MB |
| 2026-06-08 | 288 | 16,327 | 305.6MB | 2130.6MB |
| 2026-06-09 | 288 | 16,163 | 304.7MB | 1487.7MB |
| 2026-06-10 | 287 | 16,453 | 305.9MB | 1442.9MB |
| 2026-06-11 | 288 | 16,393 | 314.0MB | 1403.5MB |
| 2026-06-12 | 126 | 15,445 | 279.6MB | 775.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 88.7MB |
| 2 | `runtime.mallocgc` | 50.47MB |
| 3 | `bufio.NewWriterSize` | 42.69MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 41.69MB |
| 5 | `bufio.NewReaderSize` | 41.69MB |
| 6 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 19.02MB |
| 8 | `crypto/tls.Client` | 11.01MB |
| 9 | `net/http.(*Transport).queueForIdleConn` | 10.01MB |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 201.28GB |
| 2 | `segmentio/kafka-go.makePartitions` | 193.67GB |
| 3 | `jackskj/carta.getUniqueId` | 181.93GB |
| 4 | `reflect.unsafe_New` | 160.55GB |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 158.65GB |
| 6 | `fmt.Sprintf` | 143.9GB |
| 7 | `fmt.(*buffer).writeString` | 125.66GB |
| 8 | `carta/value.NewCell` | 114.8GB |
| 9 | `reflect.unsafe_NewArray` | 98.79GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 89.12GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 10.62GB | 10.62GB | 10.49GB | 0B |
| `evaluation.mergeMetadata` | 5.54GB | 5.54GB | 5.47GB | 0B |
| `local.(*Client).EvaluateV2` | 16.18GB | 16.17GB | 15.98GB | 0B |
| `local.topologicalSort` | 2.25GB | 2.25GB | 2.22GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 15.48GB | 15.48GB | 15.27GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 2.19GB | 2.19GB | 2.18GB | 0B |
| `localEvaluation.getMapOfValue` | 15.48GB | 15.48GB | 15.27GB | 0B |
| `utils.ParseFeatureFlag` | 15.51GB | 15.50GB | 15.29GB | 0B |

**Total FF alloc (current snapshot):** 83.26GB  |  **24h avg:** 82.17GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 54.78MB | 65/3382 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 48.07MB | 92/3382 | `█████████████░░ 87%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3033/3382 | `██████████░░░░░ 66%` |
| 4 | `runtime.mallocgc` | 32.59MB | 3033/3382 | `████████░░░░░░░ 59%` |
| 5 | `database/sql.convertAssignRows` | 25.59MB | 114/3382 | `███████░░░░░░░░ 46%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3382 | `████░░░░░░░░░░░ 32%` |
| 7 | `bytes.growSlice` | 15.53MB | 2384/3382 | `████░░░░░░░░░░░ 28%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3382 | `███░░░░░░░░░░░░ 25%` |
| 9 | `net/http.(*Transport).dialConn` | 13.81MB | 75/3382 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3382 | `██░░░░░░░░░░░░░ 19%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3382 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3382 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3382 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 72.41GB | 1899/3382 | `████████░░░░░░░ 57%` |
| 5 | `reflect.growslice` | 64.55GB | 2594/3382 | `███████░░░░░░░░ 51%` |
| 6 | `segmentio/kafka-go.makePartitions` | 63.75GB | 2756/3382 | `███████░░░░░░░░ 50%` |
| 7 | `jackskj/carta.getUniqueId` | 57.15GB | 2610/3382 | `██████░░░░░░░░░ 45%` |
| 8 | `reflect.unsafe_New` | 55.21GB | 2374/3382 | `██████░░░░░░░░░ 44%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/3382 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 49.0GB | 2121/3382 | `█████░░░░░░░░░░ 39%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
