# Overview: prod
*Last updated: 2026-06-12 10:56 IST*
*Data range: 2026-05-15T16:03 to 2026-06-12T10:56 (3388 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 33,855 | avg: 14,428 | max: 84,644 | trend: INCREASING (+3.63/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▄▆▆▆█▃
```

**Heap InUse** (current: 1183.3MB | avg: 239.8MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▂▂▃▄▃▃▄▆▅█▇▆
```

## Current Status

Goroutines: `███████░░░░░░░░░░░░░ 39%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 17%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 33,855 | 62,068 | -28213 | 14,428 | 84,644 | INCREASING (+3.63/hr) |
| Heap InUse | 1183.3MB | 1306.5MB | -123.2MB | 239.8MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3176.6MB | 3167.9MB | +8.7MB | 2684.7MB | 6883.9MB | |
| Heap Objects | 5,542,884 | 4,533,993 | +1008891 | 1,028,968 | 17,165,538 | |

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
| 2026-06-12 | 132 | 16,948 | 319.6MB | 1418.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 200.99MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 87.91MB |
| 3 | `bufio.NewReaderSize` | 80.81MB |
| 4 | `bufio.NewWriterSize` | 78.3MB |
| 5 | `runtime.mallocgc` | 50.47MB |
| 6 | `aes/gcm.NewGCMForTLS13` | 38.53MB |
| 7 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 8 | `net/http.(*Transport).queueForIdleConn` | 27.03MB |
| 9 | `crypto/tls.Client` | 18.01MB |
| 10 | `net/http.(*Transport).dialConn` | 16.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 205.28GB |
| 2 | `segmentio/kafka-go.makePartitions` | 194.33GB |
| 3 | `jackskj/carta.getUniqueId` | 185.46GB |
| 4 | `reflect.unsafe_New` | 163.91GB |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 163.87GB |
| 6 | `fmt.Sprintf` | 145.44GB |
| 7 | `fmt.(*buffer).writeString` | 128.23GB |
| 8 | `carta/value.NewCell` | 117.21GB |
| 9 | `reflect.unsafe_NewArray` | 99.14GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 90.59GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 10.66GB | 10.65GB | 10.52GB | 0B |
| `evaluation.mergeMetadata` | 5.56GB | 5.55GB | 5.49GB | 0B |
| `local.(*Client).EvaluateV2` | 16.24GB | 16.23GB | 16.03GB | 0B |
| `local.topologicalSort` | 2.27GB | 2.27GB | 2.23GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 15.55GB | 15.54GB | 15.32GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 2.19GB | 2.19GB | 2.18GB | 0B |
| `localEvaluation.getMapOfValue` | 15.55GB | 15.54GB | 15.32GB | 0B |
| `utils.ParseFeatureFlag` | 15.58GB | 15.57GB | 15.35GB | 0B |

**Total FF alloc (current snapshot):** 83.60GB  |  **24h avg:** 82.44GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 54.78MB | 65/3388 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 48.07MB | 92/3388 | `█████████████░░ 87%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3039/3388 | `██████████░░░░░ 66%` |
| 4 | `runtime.mallocgc` | 32.63MB | 3039/3388 | `████████░░░░░░░ 59%` |
| 5 | `database/sql.convertAssignRows` | 25.59MB | 114/3388 | `███████░░░░░░░░ 46%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3388 | `████░░░░░░░░░░░ 32%` |
| 7 | `bytes.growSlice` | 15.95MB | 2390/3388 | `████░░░░░░░░░░░ 29%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3388 | `███░░░░░░░░░░░░ 25%` |
| 9 | `net/http.(*Transport).dialConn` | 14.04MB | 81/3388 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3388 | `██░░░░░░░░░░░░░ 19%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3388 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3388 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3388 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 72.69GB | 1905/3388 | `████████░░░░░░░ 58%` |
| 5 | `reflect.growslice` | 64.87GB | 2600/3388 | `███████░░░░░░░░ 51%` |
| 6 | `segmentio/kafka-go.makePartitions` | 64.04GB | 2762/3388 | `███████░░░░░░░░ 51%` |
| 7 | `jackskj/carta.getUniqueId` | 57.44GB | 2616/3388 | `██████░░░░░░░░░ 45%` |
| 8 | `reflect.unsafe_New` | 55.48GB | 2380/3388 | `██████░░░░░░░░░ 44%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/3388 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 49.22GB | 2127/3388 | `█████░░░░░░░░░░ 39%` |

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
