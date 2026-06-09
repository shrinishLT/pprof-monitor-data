# Overview: prod
*Last updated: 2026-06-09 10:05 IST*
*Data range: 2026-05-15T16:03 to 2026-06-09T10:05 (2515 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 20,521 | avg: 13,678 | max: 84,644 | trend: INCREASING (+4.05/hr))
```
▂▁▁▁▁▁▁▁▁█▄▁▁▁▁▁▁▁▁▁▁▅▂▁▁▁▁▁▁▃▂▁▃▂▁▁▃▃▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▁▄▅
```

**Heap InUse** (current: 418.4MB | avg: 213.8MB | max: 3154.1MB | trend: stable (+0.10MB/hr))
```
▄▃▃▂▂▂▂▃▁█▆▃▁▂▁▂▁▂▁▂▂▆▅▁▂▁▂▂▂▄▃▃▅▃▂▁▄▅▂▂▃▃▂▁▁▁▃▃▁▃▂▂▃▂▂▁▂▂▂▁▂▃▁▁▁▂▃▂▂▂▁▂▃▁▁▂▁▁▂▁▂▁▃▂▃▂▂▂▁▃▂▂▂▃▅▅
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 24%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 20,521 | 18,745 | +1776 | 13,678 | 84,644 | INCREASING (+4.05/hr) |
| Heap InUse | 418.4MB | 416.5MB | +1.9MB | 213.8MB | 3154.1MB | stable (+0.10MB/hr) |
| Heap Sys | 3331.0MB | 3338.8MB | -7.8MB | 2461.8MB | 6883.9MB | |
| Heap Objects | 2,003,233 | 2,400,307 | -397074 | 941,694 | 17,165,538 | |

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
| 2026-06-09 | 122 | 15,188 | 272.9MB | 527.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 30.15MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 13.56MB |
| 5 | `bufio.NewWriterSize` | 10.07MB |
| 6 | `bufio.NewReaderSize` | 10.05MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `aes/gcm.NewGCMForTLS13` | 8.51MB |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 10 | `reflect.unsafe_New` | 5.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 94.09GB |
| 2 | `reflect.growslice` | 90.43GB |
| 3 | `jackskj/carta.getUniqueId` | 79.9GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 78.79GB |
| 5 | `reflect.unsafe_New` | 70.98GB |
| 6 | `fmt.Sprintf` | 60.15GB |
| 7 | `fmt.(*buffer).writeString` | 58.0GB |
| 8 | `carta/value.NewCell` | 50.65GB |
| 9 | `reflect.unsafe_NewArray` | 48.14GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 41.65GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 4.09GB | 4.09GB | 3.98GB | 0B |
| `evaluation.mergeMetadata` | 2.14GB | 2.14GB | 2.08GB | 0B |
| `local.(*Client).EvaluateV2` | 6.22GB | 6.22GB | 6.05GB | 0B |
| `local.topologicalSort` | 878.51MB | 876.99MB | 855.83MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 6.04GB | 6.03GB | 5.85GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 788.21MB | 788.21MB | 778.69MB | 0B |
| `localEvaluation.getMapOfValue` | 6.04GB | 6.03GB | 5.85GB | 0B |
| `utils.ParseFeatureFlag` | 6.05GB | 6.04GB | 5.86GB | 0B |

**Total FF alloc (current snapshot):** 32.20GB  |  **24h avg:** 31.28GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 83.74MB | 40/2515 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 63.86MB | 66/2515 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2166/2515 | `██████░░░░░░░░░ 43%` |
| 4 | `database/sql.convertAssignRows` | 31.02MB | 90/2515 | `█████░░░░░░░░░░ 37%` |
| 5 | `runtime.mallocgc` | 25.43MB | 2166/2515 | `████░░░░░░░░░░░ 30%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2515 | `███░░░░░░░░░░░░ 21%` |
| 7 | `bytes.growSlice` | 14.89MB | 1620/2515 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `net/http.(*Transport).dialConn` | 14.36MB | 47/2515 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2515 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2515 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2515 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2515 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2515 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2515 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2515 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 34.46GB | 1032/2515 | `████░░░░░░░░░░░ 27%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2515 | `███░░░░░░░░░░░░ 22%` |
| 8 | `segmentio/kafka-go.makePartitions` | 26.98GB | 1889/2515 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2515 | `███░░░░░░░░░░░░ 21%` |
| 10 | `reflect.growslice` | 24.76GB | 1727/2515 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.2x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.1x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.1x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.7x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.5x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.5x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.9x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.7x avg)
