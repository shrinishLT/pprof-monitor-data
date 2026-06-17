# Overview: prod
*Last updated: 2026-06-17 10:31 IST*
*Data range: 2026-05-15T16:03 to 2026-06-17T10:31 (4819 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 41,949 | avg: 14,907 | max: 84,644 | trend: INCREASING (+2.11/hr))
```
▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▅▃▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▄▅▇▄█
```

**Heap InUse** (current: 702.2MB | avg: 245.0MB | max: 3154.1MB | trend: stable (+0.05MB/hr))
```
▂▁▁▃▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▂▂▃▆▄▄▄▁▁▁▂▁▂▁▂▁▂▂▂▁▁▁▁▁▁▂▃▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▁▂▂▅▇█▆▇
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 41,949 | 27,164 | +14785 | 14,907 | 84,644 | INCREASING (+2.11/hr) |
| Heap InUse | 702.2MB | 665.7MB | +36.5MB | 245.0MB | 3154.1MB | stable (+0.05MB/hr) |
| Heap Sys | 1248.8MB | 1277.7MB | -28.9MB | 2427.6MB | 6883.9MB | |
| Heap Objects | 1,728,146 | 3,018,757 | -1290611 | 1,052,002 | 17,165,538 | |

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
| 2026-06-17 | 127 | 16,149 | 232.3MB | 758.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 144.71MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 69.82MB |
| 3 | `bufio.NewReaderSize` | 62.24MB |
| 4 | `bufio.NewWriterSize` | 56.72MB |
| 5 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 6 | `aes/gcm.NewGCMForTLS13` | 26.02MB |
| 7 | `runtime.mallocgc` | 23.72MB |
| 8 | `net/http.(*Transport).dialConn` | 14.0MB |
| 9 | `net/http.(*Transport).queueForIdleConn` | 13.51MB |
| 10 | `crypto/tls.Client` | 11.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 31.72GB |
| 2 | `reflect.growslice` | 30.75GB |
| 3 | `jackskj/carta.getUniqueId` | 28.01GB |
| 4 | `reflect.unsafe_New` | 24.67GB |
| 5 | `fmt.Sprintf` | 23.5GB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 19.35GB |
| 7 | `fmt.(*buffer).writeString` | 18.63GB |
| 8 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 17.97GB |
| 9 | `carta/value.NewCell` | 17.29GB |
| 10 | `reflect.unsafe_NewArray` | 16.38GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.95GB | 1.94GB | 1.81GB | 0B |
| `evaluation.mergeMetadata` | 1.00GB | 1022.75MB | 956.27MB | 0B |
| `local.(*Client).EvaluateV2` | 2.98GB | 2.97GB | 2.77GB | 0B |
| `local.topologicalSort` | 416.98MB | 415.47MB | 388.04MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.89GB | 2.88GB | 2.68GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 384.89MB | 384.89MB | 372.04MB | 0B |
| `localEvaluation.getMapOfValue` | 2.89GB | 2.88GB | 2.68GB | 0B |
| `utils.ParseFeatureFlag` | 2.90GB | 2.89GB | 2.69GB | 0B |

**Total FF alloc (current snapshot):** 15.39GB  |  **24h avg:** 14.31GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 37.87MB | 103/4819 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 4470/4819 | `██████████████░ 96%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 34.73MB | 137/4819 | `█████████████░░ 91%` |
| 4 | `runtime.mallocgc` | 30.28MB | 4470/4819 | `███████████░░░░ 79%` |
| 5 | `database/sql.convertAssignRows` | 19.85MB | 161/4819 | `███████░░░░░░░░ 52%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4819 | `███████░░░░░░░░ 47%` |
| 7 | `bytes.growSlice` | 15.64MB | 3546/4819 | `██████░░░░░░░░░ 41%` |
| 8 | `net/http.(*Transport).dialConn` | 13.12MB | 133/4819 | `█████░░░░░░░░░░ 34%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 10.86MB | 7/4819 | `████░░░░░░░░░░░ 28%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4819 | `████░░░░░░░░░░░ 27%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4819 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 75.8GB | 2736/4819 | `█████████░░░░░░ 60%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4819 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4819 | `████████░░░░░░░ 59%` |
| 5 | `segmentio/kafka-go.makePartitions` | 61.49GB | 4193/4819 | `███████░░░░░░░░ 49%` |
| 6 | `reflect.growslice` | 61.21GB | 4031/4819 | `███████░░░░░░░░ 48%` |
| 7 | `jackskj/carta.getUniqueId` | 54.74GB | 4047/4819 | `██████░░░░░░░░░ 43%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/4819 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 51.01GB | 3811/4819 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 46.74GB | 3222/4819 | `█████░░░░░░░░░░ 37%` |

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
