# Overview: prod
*Last updated: 2026-06-17 22:06 IST*
*Data range: 2026-05-15T16:03 to 2026-06-17T22:06 (4958 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 41,266 | avg: 14,962 | max: 84,644 | trend: INCREASING (+2.06/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▂▂▁▂▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█
```

**Heap InUse** (current: 759.7MB | avg: 246.3MB | max: 3154.1MB | trend: stable (+0.05MB/hr))
```
▂▂▁▁▂▂▂▂▂▁▁▁▂▂▁▁▂▁▂▁▁▂▁▁▁▁▁▁▁▁▁▂▂▂▃▂▂▂▂▁▂▁▁▃▃▂▃▃▃▁▂▁▁▁▁▁▁▂▁▂▄▃▂▂▂▁▁▂▁▁▁▂▁▂▂▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▂▁█
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 48%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 11%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 41,266 | 14,305 | +26961 | 14,962 | 84,644 | INCREASING (+2.06/hr) |
| Heap InUse | 759.7MB | 197.1MB | +562.6MB | 246.3MB | 3154.1MB | stable (+0.05MB/hr) |
| Heap Sys | 2147.3MB | 2232.4MB | -85.1MB | 2418.7MB | 6883.9MB | |
| Heap Objects | 1,640,658 | 862,531 | +778127 | 1,055,478 | 17,165,538 | |

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
| 2026-06-17 | 266 | 16,522 | 263.9MB | 1186.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 120.68MB |
| 2 | `bufio.NewReaderSize` | 57.23MB |
| 3 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 54.75MB |
| 4 | `bufio.NewWriterSize` | 51.2MB |
| 5 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 6 | `runtime.mallocgc` | 30.51MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 22.02MB |
| 8 | `crypto/tls.Client` | 15.51MB |
| 9 | `net/http.(*Transport).queueForIdleConn` | 13.01MB |
| 10 | `net/http.(*Transport).dialConn` | 9.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 47.5GB |
| 2 | `reflect.growslice` | 41.62GB |
| 3 | `jackskj/carta.getUniqueId` | 39.39GB |
| 4 | `fmt.Sprintf` | 36.58GB |
| 5 | `reflect.unsafe_New` | 34.25GB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 28.06GB |
| 7 | `fmt.(*buffer).writeString` | 25.87GB |
| 8 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 24.78GB |
| 9 | `reflect.unsafe_NewArray` | 24.53GB |
| 10 | `carta/value.NewCell` | 24.11GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 3.34GB | 3.33GB | 3.09GB | 0B |
| `evaluation.mergeMetadata` | 1.73GB | 1.72GB | 1.59GB | 0B |
| `local.(*Client).EvaluateV2` | 5.06GB | 5.05GB | 4.69GB | 0B |
| `local.topologicalSort` | 716.75MB | 715.22MB | 660.78MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 4.82GB | 4.81GB | 4.48GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 738.48MB | 737.48MB | 676.90MB | 0B |
| `localEvaluation.getMapOfValue` | 4.82GB | 4.81GB | 4.48GB | 0B |
| `utils.ParseFeatureFlag` | 4.83GB | 4.82GB | 4.49GB | 0B |

**Total FF alloc (current snapshot):** 26.02GB  |  **24h avg:** 24.13GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 37.25MB | 105/4958 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 4609/4958 | `██████████████░ 98%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 34.39MB | 140/4958 | `█████████████░░ 92%` |
| 4 | `runtime.mallocgc` | 30.29MB | 4609/4958 | `████████████░░░ 81%` |
| 5 | `database/sql.convertAssignRows` | 19.66MB | 164/4958 | `███████░░░░░░░░ 52%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4958 | `███████░░░░░░░░ 48%` |
| 7 | `bytes.growSlice` | 15.76MB | 3676/4958 | `██████░░░░░░░░░ 42%` |
| 8 | `net/http.(*Transport).dialConn` | 13.24MB | 139/4958 | `█████░░░░░░░░░░ 35%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 10.86MB | 7/4958 | `████░░░░░░░░░░░ 29%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4958 | `████░░░░░░░░░░░ 28%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4958 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4958 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4958 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 73.3GB | 2875/4958 | `████████░░░░░░░ 58%` |
| 5 | `segmentio/kafka-go.makePartitions` | 60.79GB | 4332/4958 | `███████░░░░░░░░ 48%` |
| 6 | `reflect.growslice` | 60.48GB | 4170/4958 | `███████░░░░░░░░ 48%` |
| 7 | `jackskj/carta.getUniqueId` | 54.13GB | 4186/4958 | `██████░░░░░░░░░ 43%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/4958 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 50.34GB | 3950/4958 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 45.81GB | 3361/4958 | `█████░░░░░░░░░░ 36%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.7x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.7x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.7x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.2x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (3.9x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.2x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.5x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.3x avg)
