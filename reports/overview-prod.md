# Overview: prod
*Last updated: 2026-06-10 10:35 IST*
*Data range: 2026-05-15T16:03 to 2026-06-10T10:35 (2809 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 43,683 | avg: 14,014 | max: 84,644 | trend: INCREASING (+4.18/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▆▄▆█
```

**Heap InUse** (current: 1132.6MB | avg: 225.1MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▂▃▃▄▅▄█
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 51%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 16%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 43,683 | 38,513 | +5170 | 14,014 | 84,644 | INCREASING (+4.18/hr) |
| Heap InUse | 1132.6MB | 684.9MB | +447.7MB | 225.1MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3232.5MB | 3258.8MB | -26.3MB | 2552.0MB | 6883.9MB | |
| Heap Objects | 5,417,190 | 2,088,502 | +3328688 | 979,580 | 17,165,538 | |

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
| 2026-06-10 | 128 | 16,895 | 312.8MB | 1132.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 163.36MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 81.38MB |
| 3 | `bufio.NewWriterSize` | 70.8MB |
| 4 | `bufio.NewReaderSize` | 65.26MB |
| 5 | `runtime.mallocgc` | 50.47MB |
| 6 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 23.52MB |
| 8 | `net/http.(*Transport).queueForIdleConn` | 19.52MB |
| 9 | `net/http.(*Transport).dialConn` | 14.5MB |
| 10 | `crypto/tls.Client` | 13.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 129.02GB |
| 2 | `segmentio/kafka-go.makePartitions` | 127.57GB |
| 3 | `jackskj/carta.getUniqueId` | 114.62GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 106.91GB |
| 5 | `reflect.unsafe_New` | 101.76GB |
| 6 | `fmt.Sprintf` | 86.74GB |
| 7 | `fmt.(*buffer).writeString` | 81.71GB |
| 8 | `carta/value.NewCell` | 72.63GB |
| 9 | `reflect.unsafe_NewArray` | 65.21GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 54.86GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 6.30GB | 6.29GB | 6.16GB | 0B |
| `evaluation.mergeMetadata` | 3.30GB | 3.30GB | 3.24GB | 0B |
| `local.(*Client).EvaluateV2` | 9.60GB | 9.59GB | 9.40GB | 0B |
| `local.topologicalSort` | 1.34GB | 1.33GB | 1.31GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 9.20GB | 9.19GB | 8.98GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.29GB | 1.29GB | 1.28GB | 0B |
| `localEvaluation.getMapOfValue` | 9.20GB | 9.19GB | 8.98GB | 0B |
| `utils.ParseFeatureFlag` | 9.21GB | 9.20GB | 8.99GB | 0B |

**Total FF alloc (current snapshot):** 49.43GB  |  **24h avg:** 48.34GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 71.38MB | 48/2809 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 56.12MB | 77/2809 | `███████████░░░░ 78%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2460/2809 | `███████░░░░░░░░ 51%` |
| 4 | `database/sql.convertAssignRows` | 28.64MB | 99/2809 | `██████░░░░░░░░░ 40%` |
| 5 | `runtime.mallocgc` | 28.43MB | 2460/2809 | `█████░░░░░░░░░░ 39%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2809 | `███░░░░░░░░░░░░ 25%` |
| 7 | `bytes.growSlice` | 15.64MB | 1876/2809 | `███░░░░░░░░░░░░ 21%` |
| 8 | `net/http.(*Transport).dialConn` | 14.21MB | 57/2809 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2809 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2809 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2809 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2809 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2809 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2809 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 47.23GB | 1326/2809 | `█████░░░░░░░░░░ 37%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2809 | `█████░░░░░░░░░░ 34%` |
| 7 | `segmentio/kafka-go.makePartitions` | 38.28GB | 2183/2809 | `████░░░░░░░░░░░ 30%` |
| 8 | `reflect.growslice` | 36.83GB | 2021/2809 | `████░░░░░░░░░░░ 29%` |
| 9 | `jackskj/carta.getUniqueId` | 32.01GB | 2037/2809 | `███░░░░░░░░░░░░ 25%` |
| 10 | `reflect.unsafe_New` | 31.62GB | 1801/2809 | `███░░░░░░░░░░░░ 25%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.4x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.0x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.5x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.3x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.8x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.5x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.5x avg)
