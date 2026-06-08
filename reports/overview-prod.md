# Overview: prod
*Last updated: 2026-06-08 10:26 IST*
*Data range: 2026-05-15T16:03 to 2026-06-08T10:26 (2231 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 73,475 | avg: 13,422 | max: 84,644 | trend: INCREASING (+4.29/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▃▄▅█▇
```

**Heap InUse** (current: 2130.6MB | avg: 203.0MB | max: 3154.1MB | trend: stable (+0.07MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▃▃▄▇█
```

## Current Status

Goroutines: `█████████████████░░░ 86%`
Heap InUse: `██████░░░░░░░░░░░░░░ 30%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 73,475 | 82,867 | -9392 | 13,422 | 84,644 | INCREASING (+4.29/hr) |
| Heap InUse | 2130.6MB | 1987.5MB | +143.1MB | 203.0MB | 3154.1MB | stable (+0.07MB/hr) |
| Heap Sys | 2948.9MB | 2935.4MB | +13.5MB | 2354.3MB | 6883.9MB | |
| Heap Objects | 9,333,257 | 7,652,869 | +1680388 | 908,894 | 17,165,538 | |

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
| 2026-06-08 | 126 | 16,669 | 290.6MB | 2130.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 351.23MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 185.86MB |
| 3 | `bufio.NewReaderSize` | 153.59MB |
| 4 | `bufio.NewWriterSize` | 149.07MB |
| 5 | `aes/gcm.NewGCMForTLS13` | 65.06MB |
| 6 | `runtime.mallocgc` | 50.47MB |
| 7 | `net/http.(*Transport).queueForIdleConn` | 39.04MB |
| 8 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 9 | `net/http.(*Transport).dialConn` | 36.01MB |
| 10 | `dotlapse-event-service/utils.CheckImageExists` | 22.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 61.66GB |
| 2 | `reflect.growslice` | 57.5GB |
| 3 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 54.49GB |
| 4 | `jackskj/carta.getUniqueId` | 48.6GB |
| 5 | `reflect.unsafe_New` | 44.44GB |
| 6 | `fmt.(*buffer).writeString` | 36.02GB |
| 7 | `carta/value.NewCell` | 31.62GB |
| 8 | `reflect.unsafe_NewArray` | 31.54GB |
| 9 | `fmt.Sprintf` | 24.87GB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 21.42GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.79GB | 1.79GB | 1.66GB | 0B |
| `evaluation.mergeMetadata` | 950.23MB | 949.73MB | 876.75MB | 0B |
| `local.(*Client).EvaluateV2` | 2.72GB | 2.72GB | 2.51GB | 0B |
| `local.topologicalSort` | 373.14MB | 373.14MB | 342.51MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.74GB | 2.74GB | 2.52GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 264.35MB | 264.35MB | 252.74MB | 0B |
| `localEvaluation.getMapOfValue` | 2.74GB | 2.74GB | 2.52GB | 0B |
| `utils.ParseFeatureFlag` | 2.74GB | 2.74GB | 2.52GB | 0B |

**Total FF alloc (current snapshot):** 14.28GB  |  **24h avg:** 13.16GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 83.58MB | 38/2231 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 64.17MB | 64/2231 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1882/2231 | `██████░░░░░░░░░ 43%` |
| 4 | `database/sql.convertAssignRows` | 31.29MB | 87/2231 | `█████░░░░░░░░░░ 37%` |
| 5 | `runtime.mallocgc` | 21.66MB | 1882/2231 | `███░░░░░░░░░░░░ 25%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2231 | `███░░░░░░░░░░░░ 21%` |
| 7 | `bytes.growSlice` | 15.18MB | 1366/2231 | `██░░░░░░░░░░░░░ 18%` |
| 8 | `net/http.(*Transport).dialConn` | 14.79MB | 42/2231 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2231 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `crypto/tls.Client` | 10.83MB | 58/2231 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2231 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2231 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2231 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2231 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2231 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2231 | `███░░░░░░░░░░░░ 22%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2231 | `███░░░░░░░░░░░░ 21%` |
| 8 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 23.15GB | 748/2231 | `██░░░░░░░░░░░░░ 18%` |
| 9 | `segmentio/kafka-go.makePartitions` | 17.95GB | 1605/2231 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `reflect.growslice` | 15.77GB | 1443/2231 | `█░░░░░░░░░░░░░░ 12%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.3x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.1x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.3x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.3x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.0x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.9x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.7x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.5x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (3.1x avg)
