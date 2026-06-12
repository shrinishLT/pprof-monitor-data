# Overview: prod
*Last updated: 2026-06-12 10:21 IST*
*Data range: 2026-05-15T16:03 to 2026-06-12T10:20 (3381 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 35,319 | avg: 14,365 | max: 84,644 | trend: INCREASING (+3.42/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▂▃▄▆█
```

**Heap InUse** (current: 673.8MB | avg: 238.1MB | max: 3154.1MB | trend: stable (+0.10MB/hr))
```
▁▁▁▂▂▁▂▁▁▁▂▃▁▂▁▁▁▂▁▁▂▁▁▂▂▁▁▁▁▂▁▂▁▁▂▁▁▂▁▁▂▂▁▂▁▁▂▂▂▂▁▁▂▁▂▂▁▁▂▁▁▂▁▁▂▁▁▁▁▂▁▂▄▂▂▂▁▂▁▂▂▂▁▁▂▂▃▂▁▁▂▃▃▅█▆
```

## Current Status

Goroutines: `████████░░░░░░░░░░░░ 41%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 35,319 | 29,841 | +5478 | 14,365 | 84,644 | INCREASING (+3.42/hr) |
| Heap InUse | 673.8MB | 775.4MB | -101.6MB | 238.1MB | 3154.1MB | stable (+0.10MB/hr) |
| Heap Sys | 3266.8MB | 3293.5MB | -26.7MB | 2683.6MB | 6883.9MB | |
| Heap Objects | 2,026,736 | 4,216,957 | -2190221 | 1,022,033 | 17,165,538 | |

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
| 2026-06-12 | 125 | 15,375 | 276.9MB | 775.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 107.55MB |
| 2 | `bufio.NewReaderSize` | 50.72MB |
| 3 | `runtime.mallocgc` | 50.47MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 45.21MB |
| 5 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 6 | `bufio.NewWriterSize` | 34.66MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 21.02MB |
| 8 | `crypto/tls.Client` | 12.01MB |
| 9 | `net/http.(*Transport).queueForIdleConn` | 11.01MB |
| 10 | `net/http.(*Transport).tryPutIdleConn` | 10.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 200.83GB |
| 2 | `segmentio/kafka-go.makePartitions` | 193.58GB |
| 3 | `jackskj/carta.getUniqueId` | 181.55GB |
| 4 | `reflect.unsafe_New` | 160.16GB |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 158.28GB |
| 6 | `fmt.Sprintf` | 143.78GB |
| 7 | `fmt.(*buffer).writeString` | 125.38GB |
| 8 | `carta/value.NewCell` | 114.52GB |
| 9 | `reflect.unsafe_NewArray` | 98.75GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 89.01GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 10.62GB | 10.61GB | 10.48GB | 0B |
| `evaluation.mergeMetadata` | 5.54GB | 5.53GB | 5.47GB | 0B |
| `local.(*Client).EvaluateV2` | 16.17GB | 16.16GB | 15.97GB | 0B |
| `local.topologicalSort` | 2.25GB | 2.25GB | 2.22GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 15.48GB | 15.47GB | 15.26GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 2.19GB | 2.19GB | 2.18GB | 0B |
| `localEvaluation.getMapOfValue` | 15.48GB | 15.47GB | 15.26GB | 0B |
| `utils.ParseFeatureFlag` | 15.50GB | 15.49GB | 15.28GB | 0B |

**Total FF alloc (current snapshot):** 83.23GB  |  **24h avg:** 82.12GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 54.78MB | 65/3381 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 48.07MB | 92/3381 | `█████████████░░ 87%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3032/3381 | `██████████░░░░░ 66%` |
| 4 | `runtime.mallocgc` | 32.59MB | 3032/3381 | `████████░░░░░░░ 59%` |
| 5 | `database/sql.convertAssignRows` | 25.59MB | 114/3381 | `███████░░░░░░░░ 46%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3381 | `████░░░░░░░░░░░ 32%` |
| 7 | `bytes.growSlice` | 15.5MB | 2383/3381 | `████░░░░░░░░░░░ 28%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3381 | `███░░░░░░░░░░░░ 25%` |
| 9 | `net/http.(*Transport).dialConn` | 13.81MB | 75/3381 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3381 | `██░░░░░░░░░░░░░ 19%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3381 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3381 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3381 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 72.37GB | 1898/3381 | `████████░░░░░░░ 57%` |
| 5 | `reflect.growslice` | 64.5GB | 2593/3381 | `███████░░░░░░░░ 51%` |
| 6 | `segmentio/kafka-go.makePartitions` | 63.71GB | 2755/3381 | `███████░░░░░░░░ 50%` |
| 7 | `jackskj/carta.getUniqueId` | 57.1GB | 2609/3381 | `██████░░░░░░░░░ 45%` |
| 8 | `reflect.unsafe_New` | 55.16GB | 2373/3381 | `██████░░░░░░░░░ 44%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/3381 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 48.97GB | 2120/3381 | `█████░░░░░░░░░░ 39%` |

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
