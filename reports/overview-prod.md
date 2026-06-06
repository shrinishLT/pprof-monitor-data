# Overview: prod
*Last updated: 2026-06-06 10:35 IST*
*Data range: 2026-05-15T16:03 to 2026-06-06T10:35 (1657 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 45,834 | avg: 12,732 | max: 84,644 | trend: INCREASING (+3.33/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▄▇█▇▄
```

**Heap InUse** (current: 1069.9MB | avg: 193.5MB | max: 3154.1MB | trend: stable (+0.06MB/hr))
```
▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▄▆▇█▄
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 54%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 15%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 45,834 | 73,965 | -28131 | 12,732 | 84,644 | INCREASING (+3.33/hr) |
| Heap InUse | 1069.9MB | 1932.8MB | -862.9MB | 193.5MB | 3154.1MB | stable (+0.06MB/hr) |
| Heap Sys | 2465.9MB | 2399.3MB | +66.6MB | 2431.1MB | 6883.9MB | |
| Heap Objects | 3,628,234 | 8,528,181 | -4899947 | 855,700 | 17,165,538 | |

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
| 2026-06-06 | 128 | 17,617 | 278.1MB | 1932.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 146.01MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 73.34MB |
| 3 | `bufio.NewWriterSize` | 65.75MB |
| 4 | `bufio.NewReaderSize` | 59.23MB |
| 5 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 6 | `runtime.mallocgc` | 36.02MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 26.52MB |
| 8 | `net/http.(*Transport).queueForIdleConn` | 16.52MB |
| 9 | `net/http.(*Transport).dialConn` | 14.0MB |
| 10 | `net/http.(*Transport).tryPutIdleConn` | 13.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 37.93GB |
| 2 | `jackskj/carta.getUniqueId` | 34.78GB |
| 3 | `fmt.Sprintf` | 33.09GB |
| 4 | `segmentio/kafka-go.makePartitions` | 31.68GB |
| 5 | `reflect.unsafe_New` | 30.79GB |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 26.56GB |
| 7 | `fmt.(*buffer).writeString` | 24.89GB |
| 8 | `carta/value.NewCell` | 21.76GB |
| 9 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 21.55GB |
| 10 | `reflect.unsafe_NewArray` | 16.16GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.63GB | 1.63GB | 1.55GB | 0B |
| `evaluation.mergeMetadata` | 862.71MB | 858.71MB | 819.65MB | 0B |
| `local.(*Client).EvaluateV2` | 2.50GB | 2.49GB | 2.37GB | 0B |
| `local.topologicalSort` | 357.30MB | 356.80MB | 342.24MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.42GB | 2.41GB | 2.28GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 319.93MB | 319.93MB | 316.87MB | 0B |
| `localEvaluation.getMapOfValue` | 2.42GB | 2.41GB | 2.28GB | 0B |
| `utils.ParseFeatureFlag` | 2.42GB | 2.41GB | 2.28GB | 0B |

**Total FF alloc (current snapshot):** 12.89GB  |  **24h avg:** 12.21GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 90.47MB | 35/1657 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 73.3MB | 55/1657 | `████████████░░░ 81%` |
| 3 | `database/sql.convertAssignRows` | 39.03MB | 68/1657 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1308/1657 | `██████░░░░░░░░░ 40%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1657 | `██░░░░░░░░░░░░░ 19%` |
| 6 | `runtime.mallocgc` | 17.07MB | 1308/1657 | `██░░░░░░░░░░░░░ 18%` |
| 7 | `bytes.growSlice` | 15.7MB | 1026/1657 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `net/http.(*Transport).dialConn` | 12.69MB | 31/1657 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1657 | `██░░░░░░░░░░░░░ 13%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 10.66MB | 37/1657 | `█░░░░░░░░░░░░░░ 11%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1657 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1657 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1657 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1657 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1657 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 30.87GB | 1105/1657 | `███░░░░░░░░░░░░ 24%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1657 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.82GB | 928/1657 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `fmt.Sprintf` | 12.04GB | 841/1657 | `█░░░░░░░░░░░░░░ 9%` |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 11.71GB | 368/1657 | `█░░░░░░░░░░░░░░ 9%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.6x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.2x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.5x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.4x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.1x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.1x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (5.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.6x avg)
