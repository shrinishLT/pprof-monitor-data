# Overview: prod
*Last updated: 2026-06-15 10:31 IST*
*Data range: 2026-05-15T16:03 to 2026-06-15T10:30 (4247 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 32,653 | avg: 14,711 | max: 84,644 | trend: INCREASING (+2.46/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▅█▃▆
```

**Heap InUse** (current: 796.6MB | avg: 242.3MB | max: 3154.1MB | trend: stable (+0.06MB/hr))
```
▂▂▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▂▂▂▂▁▂▂▁▁▁▂▂▁▂▁▂▁▁▁▁▁▂▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▂▁▂▁▂▁▁▂▁▁▁▂▂▁▁▁▂▂▂▂▃▄▆▆▆█
```

## Current Status

Goroutines: `███████░░░░░░░░░░░░░ 38%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 11%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 32,653 | 24,688 | +7965 | 14,711 | 84,644 | INCREASING (+2.46/hr) |
| Heap InUse | 796.6MB | 634.2MB | +162.4MB | 242.3MB | 3154.1MB | stable (+0.06MB/hr) |
| Heap Sys | 2346.4MB | 2346.4MB | +0.0MB | 2526.7MB | 6883.9MB | |
| Heap Objects | 4,044,953 | 2,925,023 | +1119930 | 1,041,867 | 17,165,538 | |

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
| 2026-06-15 | 127 | 15,195 | 244.2MB | 796.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 92.95MB |
| 2 | `bufio.NewWriterSize` | 38.66MB |
| 3 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 36.67MB |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 5 | `bufio.NewReaderSize` | 35.64MB |
| 6 | `runtime.mallocgc` | 32.36MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 12.01MB |
| 8 | `net/http.(*Transport).queueForIdleConn` | 11.01MB |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 10 | `net/http.(*Transport).dialConn` | 9.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 101.69GB |
| 2 | `reflect.growslice` | 99.47GB |
| 3 | `segmentio/kafka-go.makePartitions` | 96.56GB |
| 4 | `jackskj/carta.getUniqueId` | 89.32GB |
| 5 | `reflect.unsafe_New` | 78.54GB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 75.32GB |
| 7 | `fmt.Sprintf` | 62.29GB |
| 8 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 61.9GB |
| 9 | `fmt.(*buffer).writeString` | 61.29GB |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 57.53GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 3.58GB | 3.58GB | 3.45GB | 0B |
| `evaluation.mergeMetadata` | 1.84GB | 1.84GB | 1.77GB | 0B |
| `local.(*Client).EvaluateV2` | 5.51GB | 5.50GB | 5.30GB | 0B |
| `local.topologicalSort` | 799.38MB | 797.34MB | 766.36MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 5.44GB | 5.44GB | 5.22GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 626.16MB | 625.65MB | 615.99MB | 0B |
| `localEvaluation.getMapOfValue` | 5.44GB | 5.44GB | 5.22GB | 0B |
| `utils.ParseFeatureFlag` | 5.45GB | 5.45GB | 5.23GB | 0B |

**Total FF alloc (current snapshot):** 28.66GB  |  **24h avg:** 27.55GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 42.64MB | 87/4247 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 37.99MB | 120/4247 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3898/4247 | `████████████░░░ 85%` |
| 4 | `runtime.mallocgc` | 31.31MB | 3898/4247 | `███████████░░░░ 73%` |
| 5 | `database/sql.convertAssignRows` | 21.35MB | 142/4247 | `███████░░░░░░░░ 50%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4247 | `██████░░░░░░░░░ 42%` |
| 7 | `bytes.growSlice` | 15.61MB | 3026/4247 | `█████░░░░░░░░░░ 36%` |
| 8 | `net/http.(*Transport).dialConn` | 13.23MB | 111/4247 | `████░░░░░░░░░░░ 31%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/4247 | `████░░░░░░░░░░░ 27%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4247 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4247 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4247 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4247 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 71.56GB | 2436/4247 | `████████░░░░░░░ 57%` |
| 5 | `reflect.growslice` | 60.77GB | 3459/4247 | `███████░░░░░░░░ 48%` |
| 6 | `segmentio/kafka-go.makePartitions` | 60.74GB | 3621/4247 | `███████░░░░░░░░ 48%` |
| 7 | `jackskj/carta.getUniqueId` | 54.18GB | 3475/4247 | `██████░░░░░░░░░ 43%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/4247 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 51.04GB | 3239/4247 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 46.1GB | 2793/4247 | `█████░░░░░░░░░░ 36%` |

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
