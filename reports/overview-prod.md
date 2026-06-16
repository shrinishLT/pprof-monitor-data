# Overview: prod
*Last updated: 2026-06-16 10:21 IST*
*Data range: 2026-05-15T16:03 to 2026-06-16T10:20 (4530 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 37,327 | avg: 14,815 | max: 84,644 | trend: INCREASING (+2.28/hr))
```
▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▅▆█
```

**Heap InUse** (current: 895.4MB | avg: 245.4MB | max: 3154.1MB | trend: stable (+0.06MB/hr))
```
▂▁▂▂▁▁▁▁▂▃▁▁▁▁▁▂▁▁▁▂▂▁▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▁▁▂▁▁▂▂▃▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▅█
```

## Current Status

Goroutines: `████████░░░░░░░░░░░░ 44%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 13%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 37,327 | 32,159 | +5168 | 14,815 | 84,644 | INCREASING (+2.28/hr) |
| Heap InUse | 895.4MB | 596.8MB | +298.6MB | 245.4MB | 3154.1MB | stable (+0.06MB/hr) |
| Heap Sys | 2350.8MB | 2374.4MB | -23.6MB | 2520.0MB | 6883.9MB | |
| Heap Objects | 4,294,815 | 1,964,682 | +2330133 | 1,051,035 | 17,165,538 | |

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
| 2026-06-15 | 286 | 16,144 | 281.9MB | 1342.8MB |
| 2026-06-16 | 124 | 15,703 | 265.1MB | 895.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 118.32MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 56.76MB |
| 3 | `bufio.NewReaderSize` | 50.7MB |
| 4 | `bufio.NewWriterSize` | 46.7MB |
| 5 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 6 | `runtime.mallocgc` | 32.36MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 17.01MB |
| 8 | `net/http.(*Transport).queueForIdleConn` | 16.52MB |
| 9 | `net/http.(*Transport).dialConn` | 10.5MB |
| 10 | `crypto/tls.Client` | 9.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 132.52GB |
| 2 | `segmentio/kafka-go.makePartitions` | 129.13GB |
| 3 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 124.68GB |
| 4 | `jackskj/carta.getUniqueId` | 119.39GB |
| 5 | `reflect.unsafe_New` | 104.91GB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 93.08GB |
| 7 | `fmt.Sprintf` | 91.96GB |
| 8 | `fmt.(*buffer).writeString` | 81.91GB |
| 9 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 76.57GB |
| 10 | `carta/value.NewCell` | 75.66GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 5.92GB | 5.91GB | 5.74GB | 0B |
| `evaluation.mergeMetadata` | 3.07GB | 3.07GB | 2.98GB | 0B |
| `local.(*Client).EvaluateV2` | 9.09GB | 9.08GB | 8.83GB | 0B |
| `local.topologicalSort` | 1.28GB | 1.28GB | 1.25GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 8.81GB | 8.81GB | 8.55GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.12GB | 1.12GB | 1.10GB | 0B |
| `localEvaluation.getMapOfValue` | 8.81GB | 8.81GB | 8.55GB | 0B |
| `utils.ParseFeatureFlag` | 8.83GB | 8.82GB | 8.56GB | 512.00kB |

**Total FF alloc (current snapshot):** 46.94GB  |  **24h avg:** 45.57GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 40.53MB | 95/4530 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 4181/4530 | `█████████████░░ 90%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 36.43MB | 129/4530 | `█████████████░░ 89%` |
| 4 | `runtime.mallocgc` | 31.38MB | 4181/4530 | `███████████░░░░ 77%` |
| 5 | `database/sql.convertAssignRows` | 20.84MB | 151/4530 | `███████░░░░░░░░ 51%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4530 | `██████░░░░░░░░░ 44%` |
| 7 | `bytes.growSlice` | 15.67MB | 3285/4530 | `█████░░░░░░░░░░ 38%` |
| 8 | `net/http.(*Transport).dialConn` | 13.16MB | 122/4530 | `████░░░░░░░░░░░ 32%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/4530 | `████░░░░░░░░░░░ 29%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4530 | `███░░░░░░░░░░░░ 26%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4530 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 75.7GB | 2719/4530 | `█████████░░░░░░ 60%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4530 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4530 | `████████░░░░░░░ 59%` |
| 5 | `reflect.growslice` | 64.72GB | 3742/4530 | `███████░░░░░░░░ 51%` |
| 6 | `segmentio/kafka-go.makePartitions` | 64.52GB | 3904/4530 | `███████░░░░░░░░ 51%` |
| 7 | `jackskj/carta.getUniqueId` | 57.81GB | 3758/4530 | `██████░░░░░░░░░ 46%` |
| 8 | `reflect.unsafe_New` | 54.14GB | 3522/4530 | `██████░░░░░░░░░ 43%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/4530 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 48.29GB | 3076/4530 | `█████░░░░░░░░░░ 38%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.7x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.7x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.7x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.2x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (3.9x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.5x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.3x avg)
