# Overview: prod
*Last updated: 2026-06-11 10:21 IST*
*Data range: 2026-05-15T16:03 to 2026-06-11T10:20 (3093 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 37,724 | avg: 14,172 | max: 84,644 | trend: INCREASING (+3.68/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▅█
```

**Heap InUse** (current: 663.4MB | avg: 231.1MB | max: 3154.1MB | trend: stable (+0.10MB/hr))
```
▁▂▂▁▁▂▁▂▂▂▂▄▂▂▂▁▂▂▁▁▂▂▁▂▁▂▂▂▂▃▁▂▁▂▂▂▃▂▃▂▁▁▂▁▁▁▂▂▂▃▂▂▁▁▁▂▁▁▂▂▁▂▁▁▁▂▁▂▁▂▂▂▂▁▂▁▁▁▂▁▁▁▂▂▂▂▁▂▁▂▃▄▄▆█▇
```

## Current Status

Goroutines: `████████░░░░░░░░░░░░ 44%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 37,724 | 30,715 | +7009 | 14,172 | 84,644 | INCREASING (+3.68/hr) |
| Heap InUse | 663.4MB | 680.0MB | -16.6MB | 231.1MB | 3154.1MB | stable (+0.10MB/hr) |
| Heap Sys | 3263.2MB | 3290.9MB | -27.7MB | 2623.8MB | 6883.9MB | |
| Heap Objects | 1,562,146 | 3,241,398 | -1679252 | 998,665 | 17,165,538 | |

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
| 2026-06-11 | 125 | 15,291 | 278.3MB | 680.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 118.25MB |
| 2 | `runtime.mallocgc` | 50.47MB |
| 3 | `bufio.NewWriterSize` | 50.23MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 47.22MB |
| 5 | `bufio.NewReaderSize` | 42.18MB |
| 6 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 27.52MB |
| 8 | `reflect.growslice` | 13.9MB |
| 9 | `net/http.(*Transport).dialConn` | 12.0MB |
| 10 | `net/http.(*Transport).queueForIdleConn` | 9.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 166.43GB |
| 2 | `segmentio/kafka-go.makePartitions` | 160.51GB |
| 3 | `jackskj/carta.getUniqueId` | 150.23GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 133.69GB |
| 5 | `reflect.unsafe_New` | 132.43GB |
| 6 | `fmt.Sprintf` | 117.5GB |
| 7 | `fmt.(*buffer).writeString` | 105.05GB |
| 8 | `carta/value.NewCell` | 94.62GB |
| 9 | `reflect.unsafe_NewArray` | 81.94GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 76.93GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 8.42GB | 8.41GB | 8.27GB | 0B |
| `evaluation.mergeMetadata` | 4.40GB | 4.39GB | 4.32GB | 0B |
| `local.(*Client).EvaluateV2` | 12.82GB | 12.81GB | 12.60GB | 0B |
| `local.topologicalSort` | 1.77GB | 1.77GB | 1.74GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 12.26GB | 12.25GB | 12.03GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.73GB | 1.73GB | 1.72GB | 0B |
| `localEvaluation.getMapOfValue` | 12.26GB | 12.25GB | 12.03GB | 0B |
| `utils.ParseFeatureFlag` | 12.28GB | 12.27GB | 12.05GB | 0B |

**Total FF alloc (current snapshot):** 65.94GB  |  **24h avg:** 64.76GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 59.59MB | 59/3093 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 51.07MB | 86/3093 | `████████████░░░ 85%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2744/3093 | `█████████░░░░░░ 61%` |
| 4 | `runtime.mallocgc` | 30.71MB | 2744/3093 | `███████░░░░░░░░ 51%` |
| 5 | `database/sql.convertAssignRows` | 27.21MB | 106/3093 | `██████░░░░░░░░░ 45%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3093 | `████░░░░░░░░░░░ 30%` |
| 7 | `bytes.growSlice` | 15.33MB | 2125/3093 | `███░░░░░░░░░░░░ 25%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3093 | `███░░░░░░░░░░░░ 23%` |
| 9 | `net/http.(*Transport).dialConn` | 14.11MB | 64/3093 | `███░░░░░░░░░░░░ 23%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3093 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3093 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3093 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3093 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 59.43GB | 1610/3093 | `███████░░░░░░░░ 47%` |
| 5 | `experiment/local.topologicalSort` | 51.23GB | 375/3093 | `██████░░░░░░░░░ 40%` |
| 6 | `segmentio/kafka-go.makePartitions` | 50.47GB | 2467/3093 | `██████░░░░░░░░░ 40%` |
| 7 | `reflect.growslice` | 49.94GB | 2305/3093 | `█████░░░░░░░░░░ 39%` |
| 8 | `jackskj/carta.getUniqueId` | 43.83GB | 2321/3093 | `█████░░░░░░░░░░ 35%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/3093 | `█████░░░░░░░░░░ 34%` |
| 10 | `reflect.unsafe_New` | 42.79GB | 2085/3093 | `█████░░░░░░░░░░ 34%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.7x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.3x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
