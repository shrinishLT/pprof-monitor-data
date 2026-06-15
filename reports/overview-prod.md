# Overview: prod
*Last updated: 2026-06-15 10:56 IST*
*Data range: 2026-05-15T16:03 to 2026-06-15T10:55 (4252 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 39,681 | avg: 14,752 | max: 84,644 | trend: INCREASING (+2.57/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▃▅▆▇█▅
```

**Heap InUse** (current: 1297.4MB | avg: 243.3MB | max: 3154.1MB | trend: stable (+0.06MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▃▄▄▆▆█▇
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 46%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 18%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 39,681 | 58,050 | -18369 | 14,752 | 84,644 | INCREASING (+2.57/hr) |
| Heap InUse | 1297.4MB | 1342.8MB | -45.4MB | 243.3MB | 3154.1MB | stable (+0.06MB/hr) |
| Heap Sys | 2252.3MB | 2233.3MB | +19.0MB | 2526.4MB | 6883.9MB | |
| Heap Objects | 6,457,598 | 5,222,444 | +1235154 | 1,045,769 | 17,165,538 | |

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
| 2026-06-15 | 132 | 16,511 | 277.2MB | 1342.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 191.95MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 91.91MB |
| 3 | `bufio.NewWriterSize` | 79.82MB |
| 4 | `bufio.NewReaderSize` | 66.75MB |
| 5 | `aes/gcm.NewGCMForTLS13` | 37.03MB |
| 6 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 7 | `runtime.mallocgc` | 32.36MB |
| 8 | `net/http.(*Transport).dialConn` | 20.5MB |
| 9 | `net/http.(*Transport).queueForIdleConn` | 18.02MB |
| 10 | `crypto/tls.Client` | 16.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 106.16GB |
| 2 | `reflect.growslice` | 102.69GB |
| 3 | `segmentio/kafka-go.makePartitions` | 97.1GB |
| 4 | `jackskj/carta.getUniqueId` | 92.14GB |
| 5 | `reflect.unsafe_New` | 81.21GB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 75.32GB |
| 7 | `fmt.Sprintf` | 63.49GB |
| 8 | `fmt.(*buffer).writeString` | 63.36GB |
| 9 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 61.9GB |
| 10 | `carta/value.NewCell` | 58.68GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 3.61GB | 3.60GB | 3.47GB | 0B |
| `evaluation.mergeMetadata` | 1.86GB | 1.86GB | 1.79GB | 0B |
| `local.(*Client).EvaluateV2` | 5.55GB | 5.54GB | 5.35GB | 0B |
| `local.topologicalSort` | 804.92MB | 804.42MB | 772.77MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 5.48GB | 5.48GB | 5.27GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 629.21MB | 629.21MB | 618.35MB | 0B |
| `localEvaluation.getMapOfValue` | 5.48GB | 5.48GB | 5.27GB | 0B |
| `utils.ParseFeatureFlag` | 5.49GB | 5.49GB | 5.28GB | 0B |

**Total FF alloc (current snapshot):** 28.87GB  |  **24h avg:** 27.77GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 42.64MB | 87/4252 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 37.99MB | 120/4252 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3903/4252 | `████████████░░░ 85%` |
| 4 | `runtime.mallocgc` | 31.31MB | 3903/4252 | `███████████░░░░ 73%` |
| 5 | `database/sql.convertAssignRows` | 21.35MB | 142/4252 | `███████░░░░░░░░ 50%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4252 | `██████░░░░░░░░░ 42%` |
| 7 | `bytes.growSlice` | 15.88MB | 3031/4252 | `█████░░░░░░░░░░ 37%` |
| 8 | `net/http.(*Transport).dialConn` | 13.44MB | 116/4252 | `████░░░░░░░░░░░ 31%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/4252 | `████░░░░░░░░░░░ 27%` |
| 10 | `crypto/tls.Client` | 10.6MB | 140/4252 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4252 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4252 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4252 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 71.63GB | 2441/4252 | `████████░░░░░░░ 57%` |
| 5 | `reflect.growslice` | 60.83GB | 3464/4252 | `███████░░░░░░░░ 48%` |
| 6 | `segmentio/kafka-go.makePartitions` | 60.79GB | 3626/4252 | `███████░░░░░░░░ 48%` |
| 7 | `jackskj/carta.getUniqueId` | 54.23GB | 3480/4252 | `██████░░░░░░░░░ 43%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/4252 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 51.08GB | 3244/4252 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 46.13GB | 2798/4252 | `█████░░░░░░░░░░ 36%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.7x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.2x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (3.9x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.3x avg)
