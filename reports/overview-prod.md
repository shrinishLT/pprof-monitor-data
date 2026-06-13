# Overview: prod
*Last updated: 2026-06-13 10:14 IST*
*Data range: 2026-05-15T16:03 to 2026-06-13T10:14 (3667 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 29,027 | avg: 14,539 | max: 84,644 | trend: INCREASING (+3.20/hr))
```
▁▁▁▁▁▁▁▁▁█▄▄▃▂▂▂▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▄
```

**Heap InUse** (current: 481.0MB | avg: 239.5MB | max: 3154.1MB | trend: stable (+0.08MB/hr))
```
▁▂▁▁▁▁▁▁▁█▃▄▄▂▃▂▁▁▁▁▁▁▁▁▂▃▁▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃
```

## Current Status

Goroutines: `██████░░░░░░░░░░░░░░ 34%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 29,027 | 19,517 | +9510 | 14,539 | 84,644 | INCREASING (+3.20/hr) |
| Heap InUse | 481.0MB | 375.4MB | +105.6MB | 239.5MB | 3154.1MB | stable (+0.08MB/hr) |
| Heap Sys | 1385.9MB | 1423.7MB | -37.8MB | 2562.0MB | 6883.9MB | |
| Heap Objects | 1,734,108 | 2,049,446 | -315338 | 1,031,181 | 17,165,538 | |

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
| 2026-06-13 | 123 | 16,425 | 265.4MB | 1133.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 63.31MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 34.66MB |
| 4 | `bufio.NewWriterSize` | 29.14MB |
| 5 | `bufio.NewReaderSize` | 28.12MB |
| 6 | `runtime.mallocgc` | 23.22MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 13.01MB |
| 8 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 9 | `net/http.(*Transport).dialConn` | 9.0MB |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 30.49GB |
| 2 | `reflect.growslice` | 28.52GB |
| 3 | `jackskj/carta.getUniqueId` | 25.29GB |
| 4 | `reflect.unsafe_New` | 22.89GB |
| 5 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 21.97GB |
| 6 | `fmt.Sprintf` | 20.38GB |
| 7 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 18.07GB |
| 8 | `fmt.(*buffer).writeString` | 16.7GB |
| 9 | `dotlapse-event-service/project.ApplyPagination` | 16.55GB |
| 10 | `carta/value.NewCell` | 16.45GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.61GB | 1.61GB | 1.53GB | 0B |
| `evaluation.mergeMetadata` | 847.21MB | 843.70MB | 805.95MB | 0B |
| `local.(*Client).EvaluateV2` | 2.48GB | 2.47GB | 2.36GB | 0B |
| `local.topologicalSort` | 358.50MB | 355.96MB | 340.47MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.38GB | 2.37GB | 2.25GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 336.42MB | 336.42MB | 331.44MB | 0B |
| `localEvaluation.getMapOfValue` | 2.38GB | 2.37GB | 2.25GB | 0B |
| `utils.ParseFeatureFlag` | 2.39GB | 2.38GB | 2.26GB | 0B |

**Total FF alloc (current snapshot):** 12.75GB  |  **24h avg:** 12.11GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 49.43MB | 73/3667 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 44.97MB | 99/3667 | `█████████████░░ 90%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3318/3667 | `███████████░░░░ 74%` |
| 4 | `runtime.mallocgc` | 31.27MB | 3318/3667 | `█████████░░░░░░ 63%` |
| 5 | `database/sql.convertAssignRows` | 24.02MB | 123/3667 | `███████░░░░░░░░ 48%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3667 | `█████░░░░░░░░░░ 36%` |
| 7 | `bytes.growSlice` | 15.71MB | 2629/3667 | `████░░░░░░░░░░░ 31%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3667 | `████░░░░░░░░░░░ 28%` |
| 9 | `net/http.(*Transport).dialConn` | 13.27MB | 92/3667 | `████░░░░░░░░░░░ 26%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3667 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3667 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3667 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3667 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 72.96GB | 1923/3667 | `████████░░░░░░░ 58%` |
| 5 | `reflect.growslice` | 60.36GB | 2879/3667 | `███████░░░░░░░░ 48%` |
| 6 | `segmentio/kafka-go.makePartitions` | 60.2GB | 3041/3667 | `███████░░░░░░░░ 48%` |
| 7 | `jackskj/carta.getUniqueId` | 53.54GB | 2895/3667 | `██████░░░░░░░░░ 42%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/3667 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 51.22GB | 2659/3667 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 47.75GB | 2241/3667 | `█████░░░░░░░░░░ 38%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.8x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
