# Overview: prod
*Last updated: 2026-06-09 10:50 IST*
*Data range: 2026-05-15T16:03 to 2026-06-09T10:50 (2524 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 51,428 | avg: 13,784 | max: 84,644 | trend: INCREASING (+4.51/hr))
```
▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▃▆▆▆█▆
```

**Heap InUse** (current: 1268.1MB | avg: 216.6MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▃▄▄▄▆▆█▆
```

## Current Status

Goroutines: `████████████░░░░░░░░ 60%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 18%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 51,428 | 61,782 | -10354 | 13,784 | 84,644 | INCREASING (+4.51/hr) |
| Heap InUse | 1268.1MB | 1487.7MB | -219.6MB | 216.6MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3181.6MB | 3157.7MB | +23.9MB | 2464.5MB | 6883.9MB | |
| Heap Objects | 5,105,848 | 6,232,503 | -1126655 | 952,074 | 17,165,538 | |

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
| 2026-06-09 | 131 | 17,126 | 322.1MB | 1487.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 177.89MB |
| 2 | `bufio.NewWriterSize` | 93.89MB |
| 3 | `bufio.NewReaderSize` | 87.34MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 85.39MB |
| 5 | `runtime.mallocgc` | 50.47MB |
| 6 | `aes/gcm.NewGCMForTLS13` | 37.53MB |
| 7 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 8 | `net/http.(*Transport).dialConn` | 23.5MB |
| 9 | `net/http.(*Transport).queueForIdleConn` | 22.02MB |
| 10 | `net/http.(*Transport).tryPutIdleConn` | 17.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 97.53GB |
| 2 | `segmentio/kafka-go.makePartitions` | 95.12GB |
| 3 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 88.15GB |
| 4 | `jackskj/carta.getUniqueId` | 86.42GB |
| 5 | `reflect.unsafe_New` | 76.84GB |
| 6 | `fmt.Sprintf` | 62.53GB |
| 7 | `fmt.(*buffer).writeString` | 62.3GB |
| 8 | `carta/value.NewCell` | 54.92GB |
| 9 | `reflect.unsafe_NewArray` | 48.66GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 44.06GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 4.17GB | 4.16GB | 4.03GB | 0B |
| `evaluation.mergeMetadata` | 2.18GB | 2.18GB | 2.10GB | 0B |
| `local.(*Client).EvaluateV2` | 6.35GB | 6.34GB | 6.12GB | 0B |
| `local.topologicalSort` | 903.80MB | 902.27MB | 866.21MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 6.16GB | 6.15GB | 5.93GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 804.11MB | 802.60MB | 783.38MB | 0B |
| `localEvaluation.getMapOfValue` | 6.16GB | 6.15GB | 5.93GB | 0B |
| `utils.ParseFeatureFlag` | 6.17GB | 6.16GB | 5.94GB | 0B |

**Total FF alloc (current snapshot):** 32.86GB  |  **24h avg:** 31.66GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 83.74MB | 40/2524 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 63.86MB | 66/2524 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2175/2524 | `██████░░░░░░░░░ 43%` |
| 4 | `database/sql.convertAssignRows` | 31.02MB | 90/2524 | `█████░░░░░░░░░░ 37%` |
| 5 | `runtime.mallocgc` | 25.54MB | 2175/2524 | `████░░░░░░░░░░░ 30%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2524 | `███░░░░░░░░░░░░ 21%` |
| 7 | `bytes.growSlice` | 15.62MB | 1629/2524 | `██░░░░░░░░░░░░░ 18%` |
| 8 | `net/http.(*Transport).dialConn` | 14.92MB | 51/2524 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2524 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `crypto/tls.Client` | 10.75MB | 72/2524 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2524 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2524 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2524 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2524 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2524 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 34.89GB | 1041/2524 | `████░░░░░░░░░░░ 27%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2524 | `███░░░░░░░░░░░░ 22%` |
| 8 | `segmentio/kafka-go.makePartitions` | 27.3GB | 1898/2524 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2524 | `███░░░░░░░░░░░░ 21%` |
| 10 | `reflect.growslice` | 25.12GB | 1736/2524 | `███░░░░░░░░░░░░ 20%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.1x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.1x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.1x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.6x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.4x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.9x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.6x avg)
