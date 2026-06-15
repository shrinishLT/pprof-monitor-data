# Overview: prod
*Last updated: 2026-06-15 10:06 IST*
*Data range: 2026-05-15T16:03 to 2026-06-15T10:05 (4242 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 20,029 | avg: 14,692 | max: 84,644 | trend: INCREASING (+2.42/hr))
```
▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▃▂▁▁▁▁▁▁▂▁▁▃▂▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▂▂▁▁▂▂▂▂▁▁▁▁▅█
```

**Heap InUse** (current: 422.4MB | avg: 241.8MB | max: 3154.1MB | trend: stable (+0.06MB/hr))
```
▁▅▁▃▁▃▃▃▁▂▁▃▁▃▁▂▁▂▂▁▁▂▂▂▃▂▂▁▁▃▂▂▂▂▃▂▂▂▄▅▄▃▁▃▃▂▁▂▃▃▂▅▃▃▁▂▃▂▂▄▂▂▃▂▁▃▃▁▂▁▂▂▂▂▁▃▂▄▂▄▃▁▅▂▁▂▃▄▂▂▂▃▃▄▃█
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 23%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 20,029 | 18,057 | +1972 | 14,692 | 84,644 | INCREASING (+2.42/hr) |
| Heap InUse | 422.4MB | 258.4MB | +164.0MB | 241.8MB | 3154.1MB | stable (+0.06MB/hr) |
| Heap Sys | 2397.1MB | 2405.7MB | -8.6MB | 2526.9MB | 6883.9MB | |
| Heap Objects | 2,298,134 | 611,442 | +1686692 | 1,039,898 | 17,165,538 | |

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
| 2026-06-15 | 122 | 14,565 | 228.0MB | 422.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 32.36MB |
| 3 | `bytes.growSlice` | 25.13MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 15.07MB |
| 5 | `bufio.NewWriterSize` | 11.56MB |
| 6 | `bufio.NewReaderSize` | 10.54MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 4.5MB |
| 10 | `segmentio/kafka-go.makePartitions` | 4.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 99.67GB |
| 2 | `reflect.growslice` | 96.29GB |
| 3 | `segmentio/kafka-go.makePartitions` | 96.01GB |
| 4 | `jackskj/carta.getUniqueId` | 86.52GB |
| 5 | `reflect.unsafe_New` | 75.93GB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 75.32GB |
| 7 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 61.9GB |
| 8 | `fmt.Sprintf` | 61.58GB |
| 9 | `fmt.(*buffer).writeString` | 59.31GB |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 57.53GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 3.55GB | 3.54GB | 3.42GB | 0B |
| `evaluation.mergeMetadata` | 1.83GB | 1.83GB | 1.76GB | 0B |
| `local.(*Client).EvaluateV2` | 5.47GB | 5.45GB | 5.26GB | 0B |
| `local.topologicalSort` | 791.27MB | 789.22MB | 760.19MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 5.40GB | 5.38GB | 5.18GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 623.59MB | 622.08MB | 613.51MB | 0B |
| `localEvaluation.getMapOfValue` | 5.40GB | 5.38GB | 5.18GB | 0B |
| `utils.ParseFeatureFlag` | 5.41GB | 5.39GB | 5.19GB | 0B |

**Total FF alloc (current snapshot):** 28.44GB  |  **24h avg:** 27.32GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 42.64MB | 87/4242 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 37.99MB | 120/4242 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3893/4242 | `████████████░░░ 85%` |
| 4 | `runtime.mallocgc` | 31.31MB | 3893/4242 | `███████████░░░░ 73%` |
| 5 | `database/sql.convertAssignRows` | 21.35MB | 142/4242 | `███████░░░░░░░░ 50%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4242 | `██████░░░░░░░░░ 42%` |
| 7 | `bytes.growSlice` | 15.5MB | 3021/4242 | `█████░░░░░░░░░░ 36%` |
| 8 | `net/http.(*Transport).dialConn` | 13.32MB | 108/4242 | `████░░░░░░░░░░░ 31%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/4242 | `████░░░░░░░░░░░ 27%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4242 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4242 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4242 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4242 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 71.5GB | 2431/4242 | `████████░░░░░░░ 57%` |
| 5 | `reflect.growslice` | 60.71GB | 3454/4242 | `███████░░░░░░░░ 48%` |
| 6 | `segmentio/kafka-go.makePartitions` | 60.69GB | 3616/4242 | `███████░░░░░░░░ 48%` |
| 7 | `jackskj/carta.getUniqueId` | 54.13GB | 3470/4242 | `██████░░░░░░░░░ 43%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/4242 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 51.0GB | 3234/4242 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 46.08GB | 2788/4242 | `█████░░░░░░░░░░ 36%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.8x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.3x avg)
