# Overview: prod
*Last updated: 2026-06-15 10:21 IST*
*Data range: 2026-05-15T16:03 to 2026-06-15T10:21 (4245 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 39,064 | avg: 14,704 | max: 84,644 | trend: INCREASING (+2.45/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▅█
```

**Heap InUse** (current: 661.6MB | avg: 242.1MB | max: 3154.1MB | trend: stable (+0.06MB/hr))
```
▂▁▂▂▂▁▁▁▂▁▂▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▂▁▁▂▂▃▂▂▁▂▂▁▁▂▂▂▁▃▂▂▁▁▂▁▁▂▁▁▂▁▁▂▂▁▁▁▁▁▁▁▁▂▁▂▂▂▂▁▃▁▁▁▂▂▁▁▁▂▂▂▂▄▅▇█
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 46%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 39,064 | 30,170 | +8894 | 14,704 | 84,644 | INCREASING (+2.45/hr) |
| Heap InUse | 661.6MB | 615.4MB | +46.2MB | 242.1MB | 3154.1MB | stable (+0.06MB/hr) |
| Heap Sys | 2323.2MB | 2353.0MB | -29.8MB | 2526.8MB | 6883.9MB | |
| Heap Objects | 1,878,774 | 2,715,493 | -836719 | 1,040,716 | 17,165,538 | |

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
| 2026-06-14 | 288 | 15,854 | 265.3MB | 1419.6MB |
| 2026-06-15 | 125 | 14,980 | 236.6MB | 661.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 126.66MB |
| 2 | `bufio.NewWriterSize` | 51.71MB |
| 3 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 47.22MB |
| 4 | `bufio.NewReaderSize` | 39.65MB |
| 5 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 6 | `runtime.mallocgc` | 32.36MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 20.52MB |
| 8 | `net/http.(*Transport).dialConn` | 13.5MB |
| 9 | `net/http.(*Transport).queueForIdleConn` | 13.01MB |
| 10 | `crypto/tls.Client` | 12.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 100.9GB |
| 2 | `reflect.growslice` | 98.54GB |
| 3 | `segmentio/kafka-go.makePartitions` | 96.33GB |
| 4 | `jackskj/carta.getUniqueId` | 88.5GB |
| 5 | `reflect.unsafe_New` | 77.77GB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 75.32GB |
| 7 | `fmt.Sprintf` | 62.0GB |
| 8 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 61.9GB |
| 9 | `fmt.(*buffer).writeString` | 60.7GB |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 57.53GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 3.57GB | 3.57GB | 3.43GB | 0B |
| `evaluation.mergeMetadata` | 1.84GB | 1.84GB | 1.77GB | 0B |
| `local.(*Client).EvaluateV2` | 5.50GB | 5.49GB | 5.29GB | 0B |
| `local.topologicalSort` | 796.34MB | 794.82MB | 763.87MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 5.43GB | 5.42GB | 5.20GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 624.11MB | 623.59MB | 615.01MB | 0B |
| `localEvaluation.getMapOfValue` | 5.43GB | 5.42GB | 5.20GB | 0B |
| `utils.ParseFeatureFlag` | 5.44GB | 5.43GB | 5.21GB | 0B |

**Total FF alloc (current snapshot):** 28.60GB  |  **24h avg:** 27.45GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 42.64MB | 87/4245 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 37.99MB | 120/4245 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3896/4245 | `████████████░░░ 85%` |
| 4 | `runtime.mallocgc` | 31.31MB | 3896/4245 | `███████████░░░░ 73%` |
| 5 | `database/sql.convertAssignRows` | 21.35MB | 142/4245 | `███████░░░░░░░░ 50%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4245 | `██████░░░░░░░░░ 42%` |
| 7 | `bytes.growSlice` | 15.57MB | 3024/4245 | `█████░░░░░░░░░░ 36%` |
| 8 | `net/http.(*Transport).dialConn` | 13.32MB | 109/4245 | `████░░░░░░░░░░░ 31%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/4245 | `████░░░░░░░░░░░ 27%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4245 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4245 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4245 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4245 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 71.54GB | 2434/4245 | `████████░░░░░░░ 57%` |
| 5 | `reflect.growslice` | 60.75GB | 3457/4245 | `███████░░░░░░░░ 48%` |
| 6 | `segmentio/kafka-go.makePartitions` | 60.72GB | 3619/4245 | `███████░░░░░░░░ 48%` |
| 7 | `jackskj/carta.getUniqueId` | 54.16GB | 3473/4245 | `██████░░░░░░░░░ 43%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/4245 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 51.02GB | 3237/4245 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 46.09GB | 2791/4245 | `█████░░░░░░░░░░ 36%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.8x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.3x avg)
