# Overview: prod
*Last updated: 2026-06-12 10:36 IST*
*Data range: 2026-05-15T16:03 to 2026-06-12T10:35 (3384 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 50,819 | avg: 14,385 | max: 84,644 | trend: INCREASING (+3.49/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▅▂▅█
```

**Heap InUse** (current: 1238.2MB | avg: 238.7MB | max: 3154.1MB | trend: stable (+0.10MB/hr))
```
▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▂▂▃▄▄▃▅█
```

## Current Status

Goroutines: `████████████░░░░░░░░ 60%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 17%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 50,819 | 36,688 | +14131 | 14,385 | 84,644 | INCREASING (+3.49/hr) |
| Heap InUse | 1238.2MB | 809.9MB | +428.3MB | 238.7MB | 3154.1MB | stable (+0.10MB/hr) |
| Heap Sys | 3208.1MB | 3268.2MB | -60.1MB | 2684.1MB | 6883.9MB | |
| Heap Objects | 5,548,580 | 3,670,686 | +1877894 | 1,024,397 | 17,165,538 | |

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
| 2026-06-12 | 128 | 15,887 | 291.2MB | 1238.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 164.82MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 79.87MB |
| 3 | `bufio.NewWriterSize` | 71.28MB |
| 4 | `bufio.NewReaderSize` | 68.76MB |
| 5 | `runtime.mallocgc` | 50.47MB |
| 6 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 32.03MB |
| 8 | `net/http.(*Transport).dialConn` | 22.5MB |
| 9 | `net/http.(*Transport).queueForIdleConn` | 19.02MB |
| 10 | `net/http.(*Transport).tryPutIdleConn` | 13.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 202.67GB |
| 2 | `segmentio/kafka-go.makePartitions` | 193.92GB |
| 3 | `jackskj/carta.getUniqueId` | 183.16GB |
| 4 | `reflect.unsafe_New` | 161.69GB |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 160.03GB |
| 6 | `fmt.Sprintf` | 144.36GB |
| 7 | `fmt.(*buffer).writeString` | 126.53GB |
| 8 | `carta/value.NewCell` | 115.61GB |
| 9 | `reflect.unsafe_NewArray` | 98.92GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 89.58GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 10.64GB | 10.63GB | 10.50GB | 0B |
| `evaluation.mergeMetadata` | 5.54GB | 5.54GB | 5.48GB | 0B |
| `local.(*Client).EvaluateV2` | 16.20GB | 16.19GB | 15.99GB | 0B |
| `local.topologicalSort` | 2.26GB | 2.25GB | 2.23GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 15.51GB | 15.50GB | 15.28GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 2.19GB | 2.19GB | 2.18GB | 0B |
| `localEvaluation.getMapOfValue` | 15.51GB | 15.50GB | 15.28GB | 0B |
| `utils.ParseFeatureFlag` | 15.54GB | 15.52GB | 15.31GB | 0B |

**Total FF alloc (current snapshot):** 83.39GB  |  **24h avg:** 82.26GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 54.78MB | 65/3384 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 48.07MB | 92/3384 | `█████████████░░ 87%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3035/3384 | `██████████░░░░░ 66%` |
| 4 | `runtime.mallocgc` | 32.6MB | 3035/3384 | `████████░░░░░░░ 59%` |
| 5 | `database/sql.convertAssignRows` | 25.59MB | 114/3384 | `███████░░░░░░░░ 46%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3384 | `████░░░░░░░░░░░ 32%` |
| 7 | `bytes.growSlice` | 15.64MB | 2386/3384 | `████░░░░░░░░░░░ 28%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3384 | `███░░░░░░░░░░░░ 25%` |
| 9 | `net/http.(*Transport).dialConn` | 13.86MB | 77/3384 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3384 | `██░░░░░░░░░░░░░ 19%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3384 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3384 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3384 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 72.5GB | 1901/3384 | `████████░░░░░░░ 57%` |
| 5 | `reflect.growslice` | 64.66GB | 2596/3384 | `███████░░░░░░░░ 51%` |
| 6 | `segmentio/kafka-go.makePartitions` | 63.85GB | 2758/3384 | `███████░░░░░░░░ 51%` |
| 7 | `jackskj/carta.getUniqueId` | 57.25GB | 2612/3384 | `██████░░░░░░░░░ 45%` |
| 8 | `reflect.unsafe_New` | 55.3GB | 2376/3384 | `██████░░░░░░░░░ 44%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/3384 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 49.07GB | 2123/3384 | `█████░░░░░░░░░░ 39%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
