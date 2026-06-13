# Overview: prod
*Last updated: 2026-06-13 10:16 IST*
*Data range: 2026-05-15T16:03 to 2026-06-13T10:16 (3668 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 32,155 | avg: 14,544 | max: 84,644 | trend: INCREASING (+3.21/hr))
```
▁▁▁▁▁▁▁▁█▄▄▃▂▂▂▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▄▅
```

**Heap InUse** (current: 648.9MB | avg: 239.6MB | max: 3154.1MB | trend: stable (+0.08MB/hr))
```
▂▁▁▁▁▁▁▁█▃▄▄▂▃▂▁▁▁▁▁▁▁▁▂▃▁▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄
```

## Current Status

Goroutines: `███████░░░░░░░░░░░░░ 37%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 32,155 | 29,027 | +3128 | 14,544 | 84,644 | INCREASING (+3.21/hr) |
| Heap InUse | 648.9MB | 481.0MB | +167.9MB | 239.6MB | 3154.1MB | stable (+0.08MB/hr) |
| Heap Sys | 1373.0MB | 1385.9MB | -12.9MB | 2561.7MB | 6883.9MB | |
| Heap Objects | 3,131,986 | 1,734,108 | +1397878 | 1,031,753 | 17,165,538 | |

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
| 2026-06-13 | 124 | 16,552 | 268.5MB | 1133.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 81.4MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 43.2MB |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 4 | `bufio.NewWriterSize` | 30.15MB |
| 5 | `bufio.NewReaderSize` | 29.13MB |
| 6 | `runtime.mallocgc` | 23.22MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 17.51MB |
| 8 | `net/http.(*Transport).dialConn` | 13.5MB |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 10 | `net/http.(*Transport).tryPutIdleConn` | 9.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 30.54GB |
| 2 | `reflect.growslice` | 28.82GB |
| 3 | `jackskj/carta.getUniqueId` | 25.55GB |
| 4 | `reflect.unsafe_New` | 23.13GB |
| 5 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 21.97GB |
| 6 | `fmt.Sprintf` | 20.43GB |
| 7 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 18.07GB |
| 8 | `fmt.(*buffer).writeString` | 16.89GB |
| 9 | `carta/value.NewCell` | 16.62GB |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 16.55GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.61GB | 1.61GB | 1.54GB | 0B |
| `evaluation.mergeMetadata` | 847.21MB | 847.21MB | 807.82MB | 0B |
| `local.(*Client).EvaluateV2` | 2.48GB | 2.48GB | 2.37GB | 0B |
| `local.topologicalSort` | 358.50MB | 358.50MB | 341.29MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.38GB | 2.38GB | 2.26GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 336.42MB | 336.42MB | 331.76MB | 0B |
| `localEvaluation.getMapOfValue` | 2.38GB | 2.38GB | 2.26GB | 0B |
| `utils.ParseFeatureFlag` | 2.39GB | 2.39GB | 2.27GB | 0B |

**Total FF alloc (current snapshot):** 12.76GB  |  **24h avg:** 12.14GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 49.43MB | 73/3668 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 44.97MB | 99/3668 | `█████████████░░ 90%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3319/3668 | `███████████░░░░ 74%` |
| 4 | `runtime.mallocgc` | 31.27MB | 3319/3668 | `█████████░░░░░░ 63%` |
| 5 | `database/sql.convertAssignRows` | 24.02MB | 123/3668 | `███████░░░░░░░░ 48%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3668 | `█████░░░░░░░░░░ 36%` |
| 7 | `bytes.growSlice` | 15.74MB | 2630/3668 | `████░░░░░░░░░░░ 31%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3668 | `████░░░░░░░░░░░ 28%` |
| 9 | `net/http.(*Transport).dialConn` | 13.27MB | 93/3668 | `████░░░░░░░░░░░ 26%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3668 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3668 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3668 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3668 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 72.96GB | 1923/3668 | `████████░░░░░░░ 58%` |
| 5 | `reflect.growslice` | 60.34GB | 2880/3668 | `███████░░░░░░░░ 48%` |
| 6 | `segmentio/kafka-go.makePartitions` | 60.19GB | 3042/3668 | `███████░░░░░░░░ 48%` |
| 7 | `jackskj/carta.getUniqueId` | 53.53GB | 2896/3668 | `██████░░░░░░░░░ 42%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/3668 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 51.21GB | 2660/3668 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 47.74GB | 2242/3668 | `█████░░░░░░░░░░ 38%` |

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
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.3x avg)
