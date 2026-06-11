# Overview: prod
*Last updated: 2026-06-12 02:11 IST*
*Data range: 2026-05-15T16:03 to 2026-06-12T02:10 (3283 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,142 | avg: 14,331 | max: 84,644 | trend: INCREASING (+3.61/hr))
```
▁▁▁▂▂▂▂▂▃▁▁▁▁▁▁▁▁▂▂▂▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▂▁▁▁▁▁▂▂▂▁▁▁▁▁▁▁▁▁▅▅▆█▆▄▃▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 310.5MB | avg: 236.8MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▁▁▁▂▃▃▃▂▃▂▂▂▂▁▁▁▁▂▂▃▃▄▃▁▁▁▁▁▁▁▁▁▁▁▁▂▃▃▃▃▁▂▁▁▂▃▂▂▁▁▁▁▂▁▁▁▁▄▄▆█▆▄▃▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,142 | 15,293 | -151 | 14,331 | 84,644 | INCREASING (+3.61/hr) |
| Heap InUse | 310.5MB | 257.4MB | +53.1MB | 236.8MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3316.0MB | 3315.0MB | +1.0MB | 2664.1MB | 6883.9MB | |
| Heap Objects | 1,638,466 | 792,493 | +845973 | 1,016,879 | 17,165,538 | |

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
| 2026-06-12 | 27 | 14,915 | 256.0MB | 353.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 10.58MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 6 | `compress/flate.NewWriter` | 6.17MB |
| 7 | `bufio.NewWriterSize` | 4.55MB |
| 8 | `bufio.NewReaderSize` | 4.53MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.02MB |
| 10 | `segmentio/kafka-go.makePartitions` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 182.22GB |
| 2 | `reflect.growslice` | 181.23GB |
| 3 | `jackskj/carta.getUniqueId` | 165.13GB |
| 4 | `reflect.unsafe_New` | 145.46GB |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 144.81GB |
| 6 | `fmt.Sprintf` | 135.8GB |
| 7 | `fmt.(*buffer).writeString` | 113.79GB |
| 8 | `carta/value.NewCell` | 103.94GB |
| 9 | `reflect.unsafe_NewArray` | 92.96GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 83.98GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 10.12GB | 10.11GB | 9.98GB | 0B |
| `evaluation.mergeMetadata` | 5.28GB | 5.28GB | 5.21GB | 0B |
| `local.(*Client).EvaluateV2` | 15.41GB | 15.40GB | 15.19GB | 0B |
| `local.topologicalSort` | 2.14GB | 2.14GB | 2.11GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 14.68GB | 14.67GB | 14.47GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 2.14GB | 2.13GB | 2.11GB | 0B |
| `localEvaluation.getMapOfValue` | 14.68GB | 14.67GB | 14.47GB | 0B |
| `utils.ParseFeatureFlag` | 14.70GB | 14.69GB | 14.49GB | 0B |

**Total FF alloc (current snapshot):** 79.14GB  |  **24h avg:** 78.02GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.8MB | 60/3283 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 49.51MB | 89/3283 | `████████████░░░ 84%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2934/3283 | `█████████░░░░░░ 62%` |
| 4 | `runtime.mallocgc` | 31.99MB | 2934/3283 | `████████░░░░░░░ 54%` |
| 5 | `database/sql.convertAssignRows` | 26.83MB | 108/3283 | `██████░░░░░░░░░ 45%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3283 | `████░░░░░░░░░░░ 30%` |
| 7 | `bytes.growSlice` | 15.65MB | 2304/3283 | `███░░░░░░░░░░░░ 26%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3283 | `███░░░░░░░░░░░░ 24%` |
| 9 | `net/http.(*Transport).dialConn` | 13.92MB | 74/3283 | `███░░░░░░░░░░░░ 23%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3283 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3283 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3283 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3283 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 68.21GB | 1800/3283 | `████████░░░░░░░ 54%` |
| 5 | `reflect.growslice` | 59.62GB | 2495/3283 | `███████░░░░░░░░ 47%` |
| 6 | `segmentio/kafka-go.makePartitions` | 59.12GB | 2657/3283 | `███████░░░░░░░░ 47%` |
| 7 | `jackskj/carta.getUniqueId` | 52.66GB | 2511/3283 | `██████░░░░░░░░░ 42%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/3283 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 51.04GB | 2275/3283 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 45.61GB | 2022/3283 | `█████░░░░░░░░░░ 36%` |

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
