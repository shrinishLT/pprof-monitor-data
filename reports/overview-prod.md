# Overview: prod
*Last updated: 2026-06-12 10:06 IST*
*Data range: 2026-05-15T16:03 to 2026-06-12T10:06 (3378 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 20,267 | avg: 14,351 | max: 84,644 | trend: INCREASING (+3.38/hr))
```
▂▁▁▁▁▂▂▂▁▁▁▁▁▁▅▂▁▂▂▂▂▂▂▂▁▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▄▂▁▁▁▁▁▂▁▁▁▁▁▁▁▁▄▁▁▁▁▁▁▃▇▁▁▁▁▁▁▁▁▁▁▁▃▅▆▂▂▂▃▅█
```

**Heap InUse** (current: 410.6MB | avg: 237.7MB | max: 3154.1MB | trend: stable (+0.10MB/hr))
```
▃▁▃▁▁▁▃▃▁▃▂▁▂▂▄▂▃▂▂▂▄▂▁▄▂▁▃▃▂▁▂▂▃▂▃▂▂▃▂▁▂▁▁▃▃▂▂▁▂▃▃▄▄▂▂▃▁▂▃▂▁▃▂▁▃▁▂▄▂▁▁▁▃▁▄█▃▂▃▁▃▂▃▃▃▂▂▃▄▅▄▂▂▃▅▆
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 23%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 20,267 | 18,339 | +1928 | 14,351 | 84,644 | INCREASING (+3.38/hr) |
| Heap InUse | 410.6MB | 387.4MB | +23.2MB | 237.7MB | 3154.1MB | stable (+0.10MB/hr) |
| Heap Sys | 3331.8MB | 3333.5MB | -1.7MB | 2683.0MB | 6883.9MB | |
| Heap Objects | 1,983,932 | 1,942,706 | +41226 | 1,020,268 | 17,165,538 | |

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
| 2026-06-12 | 122 | 15,019 | 267.2MB | 490.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 33.31MB |
| 4 | `bufio.NewWriterSize` | 14.58MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 14.07MB |
| 6 | `bufio.NewReaderSize` | 13.08MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 9 | `crypto/tls.Client` | 5.5MB |
| 10 | `aes/gcm.NewGCMForTLS13` | 4.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 198.2GB |
| 2 | `segmentio/kafka-go.makePartitions` | 193.27GB |
| 3 | `jackskj/carta.getUniqueId` | 179.16GB |
| 4 | `reflect.unsafe_New` | 158.02GB |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 154.37GB |
| 6 | `fmt.Sprintf` | 143.14GB |
| 7 | `fmt.(*buffer).writeString` | 123.73GB |
| 8 | `carta/value.NewCell` | 113.04GB |
| 9 | `reflect.unsafe_NewArray` | 98.58GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 88.48GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 10.60GB | 10.59GB | 10.47GB | 0B |
| `evaluation.mergeMetadata` | 5.53GB | 5.53GB | 5.46GB | 0B |
| `local.(*Client).EvaluateV2` | 16.15GB | 16.13GB | 15.94GB | 0B |
| `local.topologicalSort` | 2.25GB | 2.25GB | 2.22GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 15.45GB | 15.43GB | 15.23GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 2.19GB | 2.19GB | 2.18GB | 0B |
| `localEvaluation.getMapOfValue` | 15.45GB | 15.43GB | 15.23GB | 0B |
| `utils.ParseFeatureFlag` | 15.47GB | 15.46GB | 15.26GB | 0B |

**Total FF alloc (current snapshot):** 83.09GB  |  **24h avg:** 81.99GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 54.78MB | 65/3378 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 48.07MB | 92/3378 | `█████████████░░ 87%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3029/3378 | `██████████░░░░░ 66%` |
| 4 | `runtime.mallocgc` | 32.57MB | 3029/3378 | `████████░░░░░░░ 59%` |
| 5 | `database/sql.convertAssignRows` | 25.59MB | 114/3378 | `███████░░░░░░░░ 46%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3378 | `████░░░░░░░░░░░ 32%` |
| 7 | `bytes.growSlice` | 15.42MB | 2380/3378 | `████░░░░░░░░░░░ 28%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3378 | `███░░░░░░░░░░░░ 25%` |
| 9 | `net/http.(*Transport).dialConn` | 13.81MB | 75/3378 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3378 | `██░░░░░░░░░░░░░ 19%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3378 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3378 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3378 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 72.23GB | 1895/3378 | `████████░░░░░░░ 57%` |
| 5 | `reflect.growslice` | 64.34GB | 2590/3378 | `███████░░░░░░░░ 51%` |
| 6 | `segmentio/kafka-go.makePartitions` | 63.56GB | 2752/3378 | `███████░░░░░░░░ 50%` |
| 7 | `jackskj/carta.getUniqueId` | 56.96GB | 2606/3378 | `██████░░░░░░░░░ 45%` |
| 8 | `reflect.unsafe_New` | 55.03GB | 2370/3378 | `██████░░░░░░░░░ 44%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/3378 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 48.86GB | 2117/3378 | `█████░░░░░░░░░░ 39%` |

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
