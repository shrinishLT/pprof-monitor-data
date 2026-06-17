# Overview: prod
*Last updated: 2026-06-17 14:16 IST*
*Data range: 2026-05-15T16:03 to 2026-06-17T14:16 (4864 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,256 | avg: 14,944 | max: 84,644 | trend: INCREASING (+2.14/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▄▃▅▆▆█▇▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁
```

**Heap InUse** (current: 264.6MB | avg: 245.9MB | max: 3154.1MB | trend: stable (+0.05MB/hr))
```
▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▂▃▄▅▄▄▆█▇▇▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▂▁▂▁▂▃▂▂▁▁▂▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 19%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,256 | 17,123 | -867 | 14,944 | 84,644 | INCREASING (+2.14/hr) |
| Heap InUse | 264.6MB | 286.8MB | -22.2MB | 245.9MB | 3154.1MB | stable (+0.05MB/hr) |
| Heap Sys | 2222.7MB | 1889.5MB | +333.2MB | 2422.3MB | 6883.9MB | |
| Heap Objects | 987,766 | 916,703 | +71063 | 1,055,013 | 17,165,538 | |

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
| 2026-06-17 | 172 | 16,867 | 261.6MB | 1186.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 30.51MB |
| 3 | `bytes.growSlice` | 17.11MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `bufio.NewReaderSize` | 7.04MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 7.03MB |
| 7 | `bufio.NewWriterSize` | 6.54MB |
| 8 | `compress/flate.NewWriter` | 6.17MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 4.0MB |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 39.85GB |
| 2 | `segmentio/kafka-go.makePartitions` | 36.83GB |
| 3 | `jackskj/carta.getUniqueId` | 36.66GB |
| 4 | `reflect.unsafe_New` | 32.24GB |
| 5 | `fmt.Sprintf` | 28.45GB |
| 6 | `fmt.(*buffer).writeString` | 24.46GB |
| 7 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 24.08GB |
| 8 | `carta/value.NewCell` | 22.74GB |
| 9 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 22.15GB |
| 10 | `reflect.unsafe_NewArray` | 19.05GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 2.33GB | 2.32GB | 2.11GB | 0B |
| `evaluation.mergeMetadata` | 1.20GB | 1.20GB | 1.09GB | 0B |
| `local.(*Client).EvaluateV2` | 3.55GB | 3.54GB | 3.22GB | 0B |
| `local.topologicalSort` | 496.46MB | 495.96MB | 450.83MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 3.44GB | 3.43GB | 3.13GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 458.08MB | 457.58MB | 407.69MB | 0B |
| `localEvaluation.getMapOfValue` | 3.44GB | 3.43GB | 3.13GB | 0B |
| `utils.ParseFeatureFlag` | 3.45GB | 3.44GB | 3.14GB | 0B |

**Total FF alloc (current snapshot):** 18.36GB  |  **24h avg:** 16.66GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 37.87MB | 103/4864 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 4515/4864 | `██████████████░ 96%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 34.73MB | 137/4864 | `█████████████░░ 91%` |
| 4 | `runtime.mallocgc` | 30.29MB | 4515/4864 | `███████████░░░░ 79%` |
| 5 | `database/sql.convertAssignRows` | 19.85MB | 161/4864 | `███████░░░░░░░░ 52%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4864 | `███████░░░░░░░░ 47%` |
| 7 | `bytes.growSlice` | 15.83MB | 3585/4864 | `██████░░░░░░░░░ 41%` |
| 8 | `net/http.(*Transport).dialConn` | 13.27MB | 138/4864 | `█████░░░░░░░░░░ 35%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 10.86MB | 7/4864 | `████░░░░░░░░░░░ 28%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4864 | `████░░░░░░░░░░░ 27%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4864 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 74.95GB | 2781/4864 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4864 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4864 | `████████░░░░░░░ 59%` |
| 5 | `segmentio/kafka-go.makePartitions` | 61.2GB | 4238/4864 | `███████░░░░░░░░ 48%` |
| 6 | `reflect.growslice` | 60.94GB | 4076/4864 | `███████░░░░░░░░ 48%` |
| 7 | `jackskj/carta.getUniqueId` | 54.5GB | 4092/4864 | `██████░░░░░░░░░ 43%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/4864 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 50.76GB | 3856/4864 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 46.4GB | 3267/4864 | `█████░░░░░░░░░░ 37%` |

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
