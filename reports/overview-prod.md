# Overview: prod
*Last updated: 2026-06-14 10:56 IST*
*Data range: 2026-05-15T16:03 to 2026-06-14T10:55 (3964 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 36,234 | avg: 14,702 | max: 84,644 | trend: INCREASING (+2.99/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▄▆▇▇█▄
```

**Heap InUse** (current: 1047.9MB | avg: 242.8MB | max: 3154.1MB | trend: stable (+0.08MB/hr))
```
▂▁▁▁▁▁▁▂▁▁▁▂▁▁▁▁▃▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▂▄▃▄▆▆▆█▅
```

## Current Status

Goroutines: `████████░░░░░░░░░░░░ 42%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 15%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 36,234 | 60,822 | -24588 | 14,702 | 84,644 | INCREASING (+2.99/hr) |
| Heap InUse | 1047.9MB | 1419.6MB | -371.7MB | 242.8MB | 3154.1MB | stable (+0.08MB/hr) |
| Heap Sys | 2151.2MB | 2109.3MB | +41.9MB | 2536.4MB | 6883.9MB | |
| Heap Objects | 4,913,875 | 5,739,018 | -825143 | 1,042,817 | 17,165,538 | |

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
| 2026-06-14 | 132 | 17,405 | 307.8MB | 1419.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 131.21MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 63.8MB |
| 3 | `bufio.NewReaderSize` | 59.23MB |
| 4 | `bufio.NewWriterSize` | 57.72MB |
| 5 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 6 | `runtime.mallocgc` | 32.36MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 30.53MB |
| 8 | `net/http.(*Transport).queueForIdleConn` | 23.02MB |
| 9 | `net/http.(*Transport).dialConn` | 14.5MB |
| 10 | `crypto/tls.Client` | 14.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 69.98GB |
| 2 | `segmentio/kafka-go.makePartitions` | 64.36GB |
| 3 | `jackskj/carta.getUniqueId` | 64.03GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 63.72GB |
| 5 | `reflect.unsafe_New` | 56.08GB |
| 6 | `fmt.Sprintf` | 48.71GB |
| 7 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 48.53GB |
| 8 | `fmt.(*buffer).writeString` | 43.68GB |
| 9 | `carta/value.NewCell` | 40.52GB |
| 10 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 39.93GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 2.58GB | 2.57GB | 2.51GB | 0B |
| `evaluation.mergeMetadata` | 1.32GB | 1.32GB | 1.29GB | 0B |
| `local.(*Client).EvaluateV2` | 3.95GB | 3.95GB | 3.85GB | 0B |
| `local.topologicalSort` | 576.24MB | 575.72MB | 559.01MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 3.91GB | 3.90GB | 3.79GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 443.24MB | 443.24MB | 442.32MB | 0B |
| `localEvaluation.getMapOfValue` | 3.91GB | 3.90GB | 3.79GB | 0B |
| `utils.ParseFeatureFlag` | 3.92GB | 3.91GB | 3.80GB | 0B |

**Total FF alloc (current snapshot):** 20.59GB  |  **24h avg:** 20.00GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 46.31MB | 79/3964 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 41.22MB | 109/3964 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3615/3964 | `███████████░░░░ 79%` |
| 4 | `runtime.mallocgc` | 31.22MB | 3615/3964 | `██████████░░░░░ 67%` |
| 5 | `database/sql.convertAssignRows` | 23.09MB | 129/3964 | `███████░░░░░░░░ 49%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3964 | `█████░░░░░░░░░░ 38%` |
| 7 | `bytes.growSlice` | 16.08MB | 2850/3964 | `█████░░░░░░░░░░ 34%` |
| 8 | `net/http.(*Transport).dialConn` | 13.32MB | 108/3964 | `████░░░░░░░░░░░ 28%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/3964 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3964 | `███░░░░░░░░░░░░ 22%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3964 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3964 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3964 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 69.05GB | 2153/3964 | `████████░░░░░░░ 55%` |
| 5 | `segmentio/kafka-go.makePartitions` | 59.06GB | 3338/3964 | `███████░░░░░░░░ 47%` |
| 6 | `reflect.growslice` | 58.94GB | 3176/3964 | `███████░░░░░░░░ 47%` |
| 7 | `jackskj/carta.getUniqueId` | 52.4GB | 3192/3964 | `██████░░░░░░░░░ 41%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/3964 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 49.74GB | 2956/3964 | `█████░░░░░░░░░░ 39%` |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 45.9GB | 1498/3964 | `█████░░░░░░░░░░ 36%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.8x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.2x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (3.9x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.3x avg)
