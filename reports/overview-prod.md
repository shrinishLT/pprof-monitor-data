# Overview: prod
*Last updated: 2026-06-10 10:56 IST*
*Data range: 2026-05-15T16:03 to 2026-06-10T10:55 (2813 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 33,841 | avg: 14,066 | max: 84,644 | trend: INCREASING (+4.38/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▄▃▄▅▆█▇▄
```

**Heap InUse** (current: 1098.6MB | avg: 226.4MB | max: 3154.1MB | trend: stable (+0.12MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▄▃▆▅▆█▆
```

## Current Status

Goroutines: `███████░░░░░░░░░░░░░ 39%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 15%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 33,841 | 58,641 | -24800 | 14,066 | 84,644 | INCREASING (+4.38/hr) |
| Heap InUse | 1098.6MB | 1442.9MB | -344.3MB | 226.4MB | 3154.1MB | stable (+0.12MB/hr) |
| Heap Sys | 3198.8MB | 3154.1MB | +44.7MB | 2552.9MB | 6883.9MB | |
| Heap Objects | 4,920,809 | 5,968,079 | -1047270 | 983,829 | 17,165,538 | |

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
| 2026-06-10 | 132 | 17,927 | 338.1MB | 1442.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 143.79MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 60.78MB |
| 3 | `bufio.NewReaderSize` | 55.73MB |
| 4 | `runtime.mallocgc` | 50.47MB |
| 5 | `bufio.NewWriterSize` | 48.2MB |
| 6 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 21.02MB |
| 8 | `net/http.(*Transport).queueForIdleConn` | 10.51MB |
| 9 | `crypto/tls.Client` | 9.51MB |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 131.6GB |
| 2 | `segmentio/kafka-go.makePartitions` | 128.02GB |
| 3 | `jackskj/carta.getUniqueId` | 117.12GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 110.69GB |
| 5 | `reflect.unsafe_New` | 103.93GB |
| 6 | `fmt.Sprintf` | 87.76GB |
| 7 | `fmt.(*buffer).writeString` | 83.37GB |
| 8 | `carta/value.NewCell` | 74.36GB |
| 9 | `reflect.unsafe_NewArray` | 65.44GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 55.85GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 6.31GB | 6.31GB | 6.19GB | 0B |
| `evaluation.mergeMetadata` | 3.31GB | 3.31GB | 3.25GB | 0B |
| `local.(*Client).EvaluateV2` | 9.64GB | 9.63GB | 9.43GB | 0B |
| `local.topologicalSort` | 1.34GB | 1.34GB | 1.31GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 9.23GB | 9.23GB | 9.01GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.29GB | 1.29GB | 1.28GB | 0B |
| `localEvaluation.getMapOfValue` | 9.23GB | 9.23GB | 9.01GB | 0B |
| `utils.ParseFeatureFlag` | 9.25GB | 9.24GB | 9.03GB | 0B |

**Total FF alloc (current snapshot):** 49.61GB  |  **24h avg:** 48.52GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 71.38MB | 48/2813 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 56.12MB | 77/2813 | `███████████░░░░ 78%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2464/2813 | `███████░░░░░░░░ 51%` |
| 4 | `database/sql.convertAssignRows` | 28.64MB | 99/2813 | `██████░░░░░░░░░ 40%` |
| 5 | `runtime.mallocgc` | 28.46MB | 2464/2813 | `█████░░░░░░░░░░ 39%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2813 | `███░░░░░░░░░░░░ 25%` |
| 7 | `bytes.growSlice` | 16.03MB | 1880/2813 | `███░░░░░░░░░░░░ 22%` |
| 8 | `net/http.(*Transport).dialConn` | 14.56MB | 60/2813 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2813 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2813 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2813 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2813 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2813 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2813 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 47.41GB | 1330/2813 | `█████░░░░░░░░░░ 37%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2813 | `█████░░░░░░░░░░ 34%` |
| 7 | `segmentio/kafka-go.makePartitions` | 38.45GB | 2187/2813 | `████░░░░░░░░░░░ 30%` |
| 8 | `reflect.growslice` | 37.01GB | 2025/2813 | `████░░░░░░░░░░░ 29%` |
| 9 | `jackskj/carta.getUniqueId` | 32.18GB | 2041/2813 | `███░░░░░░░░░░░░ 25%` |
| 10 | `reflect.unsafe_New` | 31.77GB | 1805/2813 | `███░░░░░░░░░░░░ 25%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.4x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.0x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.5x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.2x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.7x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.4x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.5x avg)
