# Overview: prod
*Last updated: 2026-06-13 10:56 IST*
*Data range: 2026-05-15T16:03 to 2026-06-13T10:56 (3676 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 38,414 | avg: 14,607 | max: 84,644 | trend: INCREASING (+3.40/hr))
```
▅▃▃▂▂▂▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▃▄▂▄▆▇▇█▄
```

**Heap InUse** (current: 761.8MB | avg: 241.1MB | max: 3154.1MB | trend: stable (+0.09MB/hr))
```
▅▂▃▃▁▂▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▂▄▆▆▅█▄
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 45%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 11%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 38,414 | 56,844 | -18430 | 14,607 | 84,644 | INCREASING (+3.40/hr) |
| Heap InUse | 761.8MB | 1566.3MB | -804.5MB | 241.1MB | 3154.1MB | stable (+0.09MB/hr) |
| Heap Sys | 1891.7MB | 1840.3MB | +51.4MB | 2559.5MB | 6883.9MB | |
| Heap Objects | 2,485,980 | 7,364,257 | -4878277 | 1,037,916 | 17,165,538 | |

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
| 2026-06-13 | 132 | 18,195 | 310.7MB | 1566.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 137.03MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 57.77MB |
| 3 | `bufio.NewWriterSize` | 49.21MB |
| 4 | `bufio.NewReaderSize` | 45.69MB |
| 5 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 6 | `runtime.mallocgc` | 30.86MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 27.52MB |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 11.0MB |
| 9 | `net/http.(*Transport).dialConn` | 11.0MB |
| 10 | `net/http.(*Transport).queueForIdleConn` | 10.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 33.78GB |
| 2 | `segmentio/kafka-go.makePartitions` | 31.42GB |
| 3 | `jackskj/carta.getUniqueId` | 30.11GB |
| 4 | `reflect.unsafe_New` | 27.24GB |
| 5 | `fmt.Sprintf` | 22.3GB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 21.97GB |
| 7 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 20.27GB |
| 8 | `fmt.(*buffer).writeString` | 20.11GB |
| 9 | `carta/value.NewCell` | 19.74GB |
| 10 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 18.07GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.65GB | 1.64GB | 1.57GB | 0B |
| `evaluation.mergeMetadata` | 870.71MB | 866.71MB | 823.02MB | 0B |
| `local.(*Client).EvaluateV2` | 2.53GB | 2.53GB | 2.41GB | 0B |
| `local.topologicalSort` | 364.58MB | 363.56MB | 347.29MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.44GB | 2.44GB | 2.31GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 337.45MB | 336.94MB | 333.56MB | 0B |
| `localEvaluation.getMapOfValue` | 2.44GB | 2.44GB | 2.31GB | 0B |
| `utils.ParseFeatureFlag` | 2.45GB | 2.44GB | 2.31GB | 0B |

**Total FF alloc (current snapshot):** 13.06GB  |  **24h avg:** 12.37GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 49.43MB | 73/3676 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 44.97MB | 99/3676 | `█████████████░░ 90%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3327/3676 | `███████████░░░░ 74%` |
| 4 | `runtime.mallocgc` | 31.26MB | 3327/3676 | `█████████░░░░░░ 63%` |
| 5 | `database/sql.convertAssignRows` | 24.02MB | 123/3676 | `███████░░░░░░░░ 48%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3676 | `█████░░░░░░░░░░ 36%` |
| 7 | `bytes.growSlice` | 16.14MB | 2638/3676 | `████░░░░░░░░░░░ 32%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 13.5MB | 5/3676 | `████░░░░░░░░░░░ 27%` |
| 9 | `net/http.(*Transport).dialConn` | 13.43MB | 99/3676 | `████░░░░░░░░░░░ 27%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3676 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3676 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3676 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3676 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 72.85GB | 1927/3676 | `████████░░░░░░░ 58%` |
| 5 | `reflect.growslice` | 60.26GB | 2888/3676 | `███████░░░░░░░░ 48%` |
| 6 | `segmentio/kafka-go.makePartitions` | 60.12GB | 3050/3676 | `███████░░░░░░░░ 48%` |
| 7 | `jackskj/carta.getUniqueId` | 53.46GB | 2904/3676 | `██████░░░░░░░░░ 42%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/3676 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 51.14GB | 2668/3676 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 47.63GB | 2250/3676 | `█████░░░░░░░░░░ 38%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.8x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.3x avg)
