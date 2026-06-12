# Overview: prod
*Last updated: 2026-06-12 10:51 IST*
*Data range: 2026-05-15T16:03 to 2026-06-12T10:51 (3387 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 62,068 | avg: 14,422 | max: 84,644 | trend: INCREASING (+3.61/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▄▆▆▆█
```

**Heap InUse** (current: 1306.5MB | avg: 239.6MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▂▂▃▄▃▃▄▆▅█▇
```

## Current Status

Goroutines: `██████████████░░░░░░ 73%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 18%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 62,068 | 54,704 | +7364 | 14,422 | 84,644 | INCREASING (+3.61/hr) |
| Heap InUse | 1306.5MB | 1418.7MB | -112.2MB | 239.6MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3167.9MB | 3190.0MB | -22.1MB | 2684.5MB | 6883.9MB | |
| Heap Objects | 4,533,993 | 6,549,013 | -2015020 | 1,027,635 | 17,165,538 | |

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
| 2026-06-12 | 131 | 16,819 | 313.0MB | 1418.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 232.15MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 99.45MB |
| 3 | `bufio.NewReaderSize` | 87.83MB |
| 4 | `bufio.NewWriterSize` | 78.81MB |
| 5 | `runtime.mallocgc` | 50.47MB |
| 6 | `aes/gcm.NewGCMForTLS13` | 44.04MB |
| 7 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 8 | `net/http.(*Transport).queueForIdleConn` | 23.02MB |
| 9 | `net/http.(*Transport).dialConn` | 20.5MB |
| 10 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 204.86GB |
| 2 | `segmentio/kafka-go.makePartitions` | 194.25GB |
| 3 | `jackskj/carta.getUniqueId` | 185.02GB |
| 4 | `reflect.unsafe_New` | 163.52GB |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 163.18GB |
| 6 | `fmt.Sprintf` | 145.25GB |
| 7 | `fmt.(*buffer).writeString` | 127.95GB |
| 8 | `carta/value.NewCell` | 116.92GB |
| 9 | `reflect.unsafe_NewArray` | 99.1GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 90.38GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 10.65GB | 10.65GB | 10.52GB | 0B |
| `evaluation.mergeMetadata` | 5.55GB | 5.55GB | 5.48GB | 0B |
| `local.(*Client).EvaluateV2` | 16.23GB | 16.23GB | 16.02GB | 0B |
| `local.topologicalSort` | 2.27GB | 2.27GB | 2.23GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 15.54GB | 15.54GB | 15.31GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 2.19GB | 2.19GB | 2.18GB | 0B |
| `localEvaluation.getMapOfValue` | 15.54GB | 15.54GB | 15.31GB | 0B |
| `utils.ParseFeatureFlag` | 15.57GB | 15.56GB | 15.34GB | 0B |

**Total FF alloc (current snapshot):** 83.55GB  |  **24h avg:** 82.39GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 54.78MB | 65/3387 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 48.07MB | 92/3387 | `█████████████░░ 87%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3038/3387 | `██████████░░░░░ 66%` |
| 4 | `runtime.mallocgc` | 32.62MB | 3038/3387 | `████████░░░░░░░ 59%` |
| 5 | `database/sql.convertAssignRows` | 25.59MB | 114/3387 | `███████░░░░░░░░ 46%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3387 | `████░░░░░░░░░░░ 32%` |
| 7 | `bytes.growSlice` | 15.87MB | 2389/3387 | `████░░░░░░░░░░░ 28%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3387 | `███░░░░░░░░░░░░ 25%` |
| 9 | `net/http.(*Transport).dialConn` | 14.01MB | 80/3387 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3387 | `██░░░░░░░░░░░░░ 19%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3387 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3387 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3387 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 72.64GB | 1904/3387 | `████████░░░░░░░ 58%` |
| 5 | `reflect.growslice` | 64.82GB | 2599/3387 | `███████░░░░░░░░ 51%` |
| 6 | `segmentio/kafka-go.makePartitions` | 63.99GB | 2761/3387 | `███████░░░░░░░░ 51%` |
| 7 | `jackskj/carta.getUniqueId` | 57.39GB | 2615/3387 | `██████░░░░░░░░░ 45%` |
| 8 | `reflect.unsafe_New` | 55.43GB | 2379/3387 | `██████░░░░░░░░░ 44%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/3387 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 49.19GB | 2126/3387 | `█████░░░░░░░░░░ 39%` |

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
