# Overview: prod
*Last updated: 2026-06-14 10:47 IST*
*Data range: 2026-05-15T16:03 to 2026-06-14T10:46 (3962 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 60,239 | avg: 14,685 | max: 84,644 | trend: INCREASING (+2.95/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▃▄▆▇█
```

**Heap InUse** (current: 1099.7MB | avg: 242.3MB | max: 3154.1MB | trend: stable (+0.07MB/hr))
```
▁▁▂▂▁▂▁▁▁▂▁▁▁▂▁▂▁▁▃▂▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▃▅▄▅▇█▇
```

## Current Status

Goroutines: `██████████████░░░░░░ 71%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 15%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 60,239 | 59,261 | +978 | 14,685 | 84,644 | INCREASING (+2.95/hr) |
| Heap InUse | 1099.7MB | 1198.2MB | -98.5MB | 242.3MB | 3154.1MB | stable (+0.07MB/hr) |
| Heap Sys | 2128.1MB | 2128.2MB | -0.1MB | 2536.6MB | 6883.9MB | |
| Heap Objects | 2,418,353 | 3,836,884 | -1418531 | 1,040,655 | 17,165,538 | |

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
| 2026-06-12 | 288 | 16,142 | 260.8MB | 1418.7MB |
| 2026-06-13 | 288 | 16,274 | 264.7MB | 1566.3MB |
| 2026-06-14 | 130 | 16,926 | 293.6MB | 1198.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 196.54MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 99.96MB |
| 3 | `bufio.NewWriterSize` | 86.84MB |
| 4 | `bufio.NewReaderSize` | 76.8MB |
| 5 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 6 | `aes/gcm.NewGCMForTLS13` | 31.53MB |
| 7 | `runtime.mallocgc` | 30.86MB |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 21.01MB |
| 9 | `net/http.(*Transport).queueForIdleConn` | 20.52MB |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 20.43MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 69.12GB |
| 2 | `segmentio/kafka-go.makePartitions` | 64.2GB |
| 3 | `jackskj/carta.getUniqueId` | 63.27GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 62.36GB |
| 5 | `reflect.unsafe_New` | 55.37GB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 48.53GB |
| 7 | `fmt.Sprintf` | 48.21GB |
| 8 | `fmt.(*buffer).writeString` | 43.12GB |
| 9 | `carta/value.NewCell` | 39.97GB |
| 10 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 39.93GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 2.57GB | 2.56GB | 2.50GB | 0B |
| `evaluation.mergeMetadata` | 1.32GB | 1.32GB | 1.29GB | 0B |
| `local.(*Client).EvaluateV2` | 3.94GB | 3.93GB | 3.84GB | 0B |
| `local.topologicalSort` | 574.21MB | 572.69MB | 557.79MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 3.89GB | 3.88GB | 3.78GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 443.24MB | 443.24MB | 442.17MB | 0B |
| `localEvaluation.getMapOfValue` | 3.89GB | 3.88GB | 3.78GB | 0B |
| `utils.ParseFeatureFlag` | 3.90GB | 3.89GB | 3.79GB | 0B |

**Total FF alloc (current snapshot):** 20.51GB  |  **24h avg:** 19.96GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 46.31MB | 79/3962 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 41.22MB | 109/3962 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3613/3962 | `███████████░░░░ 79%` |
| 4 | `runtime.mallocgc` | 31.22MB | 3613/3962 | `██████████░░░░░ 67%` |
| 5 | `database/sql.convertAssignRows` | 23.09MB | 129/3962 | `███████░░░░░░░░ 49%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3962 | `█████░░░░░░░░░░ 38%` |
| 7 | `bytes.growSlice` | 15.96MB | 2848/3962 | `█████░░░░░░░░░░ 34%` |
| 8 | `net/http.(*Transport).dialConn` | 13.19MB | 106/3962 | `████░░░░░░░░░░░ 28%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/3962 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3962 | `███░░░░░░░░░░░░ 22%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3962 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3962 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3962 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 69.05GB | 2151/3962 | `████████░░░░░░░ 55%` |
| 5 | `segmentio/kafka-go.makePartitions` | 59.06GB | 3336/3962 | `███████░░░░░░░░ 47%` |
| 6 | `reflect.growslice` | 58.93GB | 3174/3962 | `███████░░░░░░░░ 47%` |
| 7 | `jackskj/carta.getUniqueId` | 52.4GB | 3190/3962 | `██████░░░░░░░░░ 41%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/3962 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 49.73GB | 2954/3962 | `█████░░░░░░░░░░ 39%` |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 45.9GB | 1498/3962 | `█████░░░░░░░░░░ 36%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.8x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.2x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.3x avg)
