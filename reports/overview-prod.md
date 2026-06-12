# Overview: prod
*Last updated: 2026-06-12 10:31 IST*
*Data range: 2026-05-15T16:03 to 2026-06-12T10:31 (3383 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 36,688 | avg: 14,374 | max: 84,644 | trend: INCREASING (+3.45/hr))
```
▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▂▂▄▅▇▄█
```

**Heap InUse** (current: 809.9MB | avg: 238.4MB | max: 3154.1MB | trend: stable (+0.10MB/hr))
```
▁▂▂▁▂▁▁▁▁▂▁▂▁▁▁▂▁▁▂▁▁▂▂▁▁▁▁▂▁▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▂▂▂▂▁▁▂▁▁▂▁▁▂▁▁▂▁▁▂▁▁▁▁▂▁▂▄▂▁▁▁▂▁▁▁▂▁▁▂▂▃▂▁▁▂▃▃▅▇▆▅█
```

## Current Status

Goroutines: `████████░░░░░░░░░░░░ 43%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 11%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 36,688 | 24,111 | +12577 | 14,374 | 84,644 | INCREASING (+3.45/hr) |
| Heap InUse | 809.9MB | 614.8MB | +195.1MB | 238.4MB | 3154.1MB | stable (+0.10MB/hr) |
| Heap Sys | 3268.2MB | 3274.1MB | -5.9MB | 2683.9MB | 6883.9MB | |
| Heap Objects | 3,670,686 | 1,846,233 | +1824453 | 1,023,060 | 17,165,538 | |

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
| 2026-06-12 | 127 | 15,612 | 283.8MB | 809.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 110.58MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 55.26MB |
| 3 | `bufio.NewReaderSize` | 52.7MB |
| 4 | `runtime.mallocgc` | 50.47MB |
| 5 | `bufio.NewWriterSize` | 47.68MB |
| 6 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 15.01MB |
| 8 | `net/http.(*Transport).queueForIdleConn` | 10.51MB |
| 9 | `net/http.(*Transport).tryPutIdleConn` | 9.51MB |
| 10 | `net/http.(*Transport).dialConn` | 9.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 201.89GB |
| 2 | `segmentio/kafka-go.makePartitions` | 193.83GB |
| 3 | `jackskj/carta.getUniqueId` | 182.49GB |
| 4 | `reflect.unsafe_New` | 161.06GB |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 159.2GB |
| 6 | `fmt.Sprintf` | 144.1GB |
| 7 | `fmt.(*buffer).writeString` | 126.04GB |
| 8 | `carta/value.NewCell` | 115.16GB |
| 9 | `reflect.unsafe_NewArray` | 98.86GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 89.32GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 10.63GB | 10.62GB | 10.50GB | 0B |
| `evaluation.mergeMetadata` | 5.54GB | 5.54GB | 5.47GB | 0B |
| `local.(*Client).EvaluateV2` | 16.19GB | 16.18GB | 15.99GB | 0B |
| `local.topologicalSort` | 2.25GB | 2.25GB | 2.22GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 15.50GB | 15.48GB | 15.28GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 2.19GB | 2.19GB | 2.18GB | 0B |
| `localEvaluation.getMapOfValue` | 15.50GB | 15.48GB | 15.28GB | 0B |
| `utils.ParseFeatureFlag` | 15.52GB | 15.51GB | 15.30GB | 0B |

**Total FF alloc (current snapshot):** 83.33GB  |  **24h avg:** 82.21GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 54.78MB | 65/3383 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 48.07MB | 92/3383 | `█████████████░░ 87%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3034/3383 | `██████████░░░░░ 66%` |
| 4 | `runtime.mallocgc` | 32.6MB | 3034/3383 | `████████░░░░░░░ 59%` |
| 5 | `database/sql.convertAssignRows` | 25.59MB | 114/3383 | `███████░░░░░░░░ 46%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3383 | `████░░░░░░░░░░░ 32%` |
| 7 | `bytes.growSlice` | 15.57MB | 2385/3383 | `████░░░░░░░░░░░ 28%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3383 | `███░░░░░░░░░░░░ 25%` |
| 9 | `net/http.(*Transport).dialConn` | 13.75MB | 76/3383 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3383 | `██░░░░░░░░░░░░░ 19%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3383 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3383 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3383 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 72.46GB | 1900/3383 | `████████░░░░░░░ 57%` |
| 5 | `reflect.growslice` | 64.6GB | 2595/3383 | `███████░░░░░░░░ 51%` |
| 6 | `segmentio/kafka-go.makePartitions` | 63.8GB | 2757/3383 | `███████░░░░░░░░ 51%` |
| 7 | `jackskj/carta.getUniqueId` | 57.2GB | 2611/3383 | `██████░░░░░░░░░ 45%` |
| 8 | `reflect.unsafe_New` | 55.25GB | 2375/3383 | `██████░░░░░░░░░ 44%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/3383 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 49.04GB | 2122/3383 | `█████░░░░░░░░░░ 39%` |

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
