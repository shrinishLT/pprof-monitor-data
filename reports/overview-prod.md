# Overview: prod
*Last updated: 2026-06-10 01:25 IST*
*Data range: 2026-05-15T16:03 to 2026-06-10T01:25 (2699 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 38,199 | avg: 13,907 | max: 84,644 | trend: INCREASING (+4.21/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▃▁▁▂▁▁▁▂▂▁▂▁▁▃▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▅█▇
```

**Heap InUse** (current: 797.0MB | avg: 221.8MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▂▁▂▁▁▁▁▁▁▁▂▂▂▁▂▄▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▁▁▁▄▂▁▂▂▁▁▃▃▁▂▂▁▄▃▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▅█▆
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 45%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 11%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 38,199 | 39,645 | -1446 | 13,907 | 84,644 | INCREASING (+4.21/hr) |
| Heap InUse | 797.0MB | 1004.9MB | -207.9MB | 221.8MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3245.2MB | 3247.9MB | -2.7MB | 2520.6MB | 6883.9MB | |
| Heap Objects | 1,520,159 | 4,998,056 | -3477897 | 967,923 | 17,165,538 | |

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
| 2026-06-10 | 18 | 18,531 | 356.3MB | 1004.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 147.56MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 58.27MB |
| 3 | `bufio.NewWriterSize` | 56.23MB |
| 4 | `runtime.mallocgc` | 50.47MB |
| 5 | `bufio.NewReaderSize` | 47.7MB |
| 6 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 25.02MB |
| 8 | `net/http.(*Transport).queueForIdleConn` | 15.01MB |
| 9 | `crypto/tls.Client` | 11.51MB |
| 10 | `net/http.(*Transport).tryPutIdleConn` | 10.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 115.08GB |
| 2 | `reflect.growslice` | 105.43GB |
| 3 | `jackskj/carta.getUniqueId` | 94.54GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 90.38GB |
| 5 | `reflect.unsafe_New` | 83.73GB |
| 6 | `fmt.Sprintf` | 77.0GB |
| 7 | `fmt.(*buffer).writeString` | 67.69GB |
| 8 | `carta/value.NewCell` | 59.7GB |
| 9 | `reflect.unsafe_NewArray` | 58.79GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 47.47GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 5.75GB | 5.74GB | 5.60GB | 0B |
| `evaluation.mergeMetadata` | 3.03GB | 3.02GB | 2.95GB | 0B |
| `local.(*Client).EvaluateV2` | 8.77GB | 8.76GB | 8.55GB | 0B |
| `local.topologicalSort` | 1.22GB | 1.22GB | 1.19GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 8.35GB | 8.34GB | 8.14GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.23GB | 1.22GB | 1.20GB | 0B |
| `localEvaluation.getMapOfValue` | 8.35GB | 8.34GB | 8.14GB | 0B |
| `utils.ParseFeatureFlag` | 8.36GB | 8.35GB | 8.15GB | 0B |

**Total FF alloc (current snapshot):** 45.04GB  |  **24h avg:** 43.91GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 79.04MB | 43/2699 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 59.71MB | 72/2699 | `███████████░░░░ 75%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2350/2699 | `██████░░░░░░░░░ 46%` |
| 4 | `database/sql.convertAssignRows` | 29.99MB | 94/2699 | `█████░░░░░░░░░░ 37%` |
| 5 | `runtime.mallocgc` | 27.4MB | 2350/2699 | `█████░░░░░░░░░░ 34%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2699 | `███░░░░░░░░░░░░ 22%` |
| 7 | `bytes.growSlice` | 15.49MB | 1789/2699 | `██░░░░░░░░░░░░░ 19%` |
| 8 | `net/http.(*Transport).dialConn` | 14.42MB | 54/2699 | `██░░░░░░░░░░░░░ 18%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2699 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2699 | `██░░░░░░░░░░░░░ 13%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2699 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2699 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2699 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2699 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2699 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 42.81GB | 1216/2699 | `█████░░░░░░░░░░ 34%` |
| 7 | `segmentio/kafka-go.makePartitions` | 33.87GB | 2073/2699 | `████░░░░░░░░░░░ 27%` |
| 8 | `reflect.growslice` | 32.32GB | 1911/2699 | `███░░░░░░░░░░░░ 25%` |
| 9 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2699 | `███░░░░░░░░░░░░ 22%` |
| 10 | `jackskj/carta.getUniqueId` | 27.98GB | 1927/2699 | `███░░░░░░░░░░░░ 22%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.6x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.1x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.0x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.0x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.5x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.3x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.8x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.5x avg)
