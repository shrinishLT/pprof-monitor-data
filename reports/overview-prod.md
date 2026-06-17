# Overview: prod
*Last updated: 2026-06-17 10:12 IST*
*Data range: 2026-05-15T16:03 to 2026-06-17T10:12 (4815 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 28,166 | avg: 14,890 | max: 84,644 | trend: INCREASING (+2.07/hr))
```
▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▄█▅▅▂▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▆
```

**Heap InUse** (current: 529.4MB | avg: 244.6MB | max: 3154.1MB | trend: stable (+0.05MB/hr))
```
▁▁▁▁▂▁▂▄▂▁▁▁▁▁▁▁▁▁▂▁▁▁▁▂▂▄█▅▅▅▂▁▂▂▁▂▂▂▁▂▂▂▁▁▁▁▂▂▂▃▃▂▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▂▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▂▃▂▁▃▃▆
```

## Current Status

Goroutines: `██████░░░░░░░░░░░░░░ 33%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 28,166 | 20,988 | +7178 | 14,890 | 84,644 | INCREASING (+2.07/hr) |
| Heap InUse | 529.4MB | 306.5MB | +222.9MB | 244.6MB | 3154.1MB | stable (+0.05MB/hr) |
| Heap Sys | 1025.4MB | 1052.1MB | -26.7MB | 2428.6MB | 6883.9MB | |
| Heap Objects | 2,468,145 | 914,338 | +1553807 | 1,050,619 | 17,165,538 | |

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
| 2026-06-16 | 286 | 16,159 | 253.2MB | 1286.4MB |
| 2026-06-17 | 123 | 15,527 | 217.0MB | 638.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 63.82MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 29.64MB |
| 4 | `bufio.NewWriterSize` | 28.11MB |
| 5 | `bufio.NewReaderSize` | 25.61MB |
| 6 | `runtime.mallocgc` | 17.51MB |
| 7 | `reflect.growslice` | 10.43MB |
| 8 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 7.51MB |
| 10 | `dotlapse-event-service/utils.CheckImageExists` | 5.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 31.26GB |
| 2 | `reflect.growslice` | 27.62GB |
| 3 | `jackskj/carta.getUniqueId` | 25.1GB |
| 4 | `fmt.Sprintf` | 22.65GB |
| 5 | `reflect.unsafe_New` | 22.15GB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 19.35GB |
| 7 | `fmt.(*buffer).writeString` | 16.63GB |
| 8 | `reflect.unsafe_NewArray` | 16.15GB |
| 9 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 15.86GB |
| 10 | `carta/value.NewCell` | 15.51GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.92GB | 1.91GB | 1.79GB | 0B |
| `evaluation.mergeMetadata` | 1008.75MB | 1006.75MB | 945.04MB | 0B |
| `local.(*Client).EvaluateV2` | 2.93GB | 2.92GB | 2.74GB | 0B |
| `local.topologicalSort` | 411.92MB | 411.41MB | 383.25MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.85GB | 2.84GB | 2.65GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 379.85MB | 379.85MB | 369.61MB | 0B |
| `localEvaluation.getMapOfValue` | 2.85GB | 2.84GB | 2.65GB | 0B |
| `utils.ParseFeatureFlag` | 2.85GB | 2.84GB | 2.65GB | 0B |

**Total FF alloc (current snapshot):** 15.15GB  |  **24h avg:** 14.13GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 37.87MB | 103/4815 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 4466/4815 | `██████████████░ 96%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 34.73MB | 137/4815 | `█████████████░░ 91%` |
| 4 | `runtime.mallocgc` | 30.29MB | 4466/4815 | `███████████░░░░ 79%` |
| 5 | `database/sql.convertAssignRows` | 19.85MB | 161/4815 | `███████░░░░░░░░ 52%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4815 | `███████░░░░░░░░ 47%` |
| 7 | `bytes.growSlice` | 15.53MB | 3542/4815 | `██████░░░░░░░░░ 41%` |
| 8 | `net/http.(*Transport).dialConn` | 13.18MB | 129/4815 | `█████░░░░░░░░░░ 34%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 10.86MB | 7/4815 | `████░░░░░░░░░░░ 28%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4815 | `████░░░░░░░░░░░ 27%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4815 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 75.85GB | 2734/4815 | `█████████░░░░░░ 60%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4815 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4815 | `████████░░░░░░░ 59%` |
| 5 | `segmentio/kafka-go.makePartitions` | 61.52GB | 4189/4815 | `███████░░░░░░░░ 49%` |
| 6 | `reflect.growslice` | 61.24GB | 4027/4815 | `███████░░░░░░░░ 48%` |
| 7 | `jackskj/carta.getUniqueId` | 54.76GB | 4043/4815 | `██████░░░░░░░░░ 43%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/4815 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 51.04GB | 3807/4815 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 46.77GB | 3218/4815 | `█████░░░░░░░░░░ 37%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.7x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.7x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.2x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (3.9x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.5x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.3x avg)
