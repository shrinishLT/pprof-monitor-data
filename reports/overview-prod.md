# Overview: prod
*Last updated: 2026-06-09 10:25 IST*
*Data range: 2026-05-15T16:03 to 2026-06-09T10:25 (2519 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 28,165 | avg: 13,707 | max: 84,644 | trend: INCREASING (+4.17/hr))
```
▁▁▁▁▁▃▂▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▂▁▁▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▅█▄
```

**Heap InUse** (current: 767.4MB | avg: 214.5MB | max: 3154.1MB | trend: stable (+0.10MB/hr))
```
▁▁▁▂▁▄▃▂▁▁▁▁▁▁▁▁▁▃▃▁▁▁▁▁▁▂▂▂▃▂▁▁▂▃▁▁▂▂▁▁▁▁▂▂▁▂▁▁▂▁▁▁▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▁▂▁▁▁▂▃▃▄▅█▇
```

## Current Status

Goroutines: `██████░░░░░░░░░░░░░░ 33%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 11%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 28,165 | 40,356 | -12191 | 13,707 | 84,644 | INCREASING (+4.17/hr) |
| Heap InUse | 767.4MB | 862.4MB | -95.0MB | 214.5MB | 3154.1MB | stable (+0.10MB/hr) |
| Heap Sys | 3274.8MB | 3252.0MB | +22.8MB | 2463.1MB | 6883.9MB | |
| Heap Objects | 2,263,444 | 3,852,980 | -1589536 | 943,892 | 17,165,538 | |

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
| 2026-06-09 | 126 | 15,715 | 285.5MB | 862.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 87.71MB |
| 2 | `runtime.mallocgc` | 50.47MB |
| 3 | `bufio.NewWriterSize` | 37.67MB |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 31.14MB |
| 6 | `bufio.NewReaderSize` | 26.61MB |
| 7 | `net/http.(*Transport).queueForIdleConn` | 11.51MB |
| 8 | `aes/gcm.NewGCMForTLS13` | 9.51MB |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 10 | `crypto/tls.Client` | 8.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 94.57GB |
| 2 | `reflect.growslice` | 93.86GB |
| 3 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 83.3GB |
| 4 | `jackskj/carta.getUniqueId` | 83.01GB |
| 5 | `reflect.unsafe_New` | 73.77GB |
| 6 | `fmt.Sprintf` | 61.18GB |
| 7 | `fmt.(*buffer).writeString` | 60.07GB |
| 8 | `carta/value.NewCell` | 52.58GB |
| 9 | `reflect.unsafe_NewArray` | 48.39GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 42.69GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 4.13GB | 4.12GB | 4.00GB | 0B |
| `evaluation.mergeMetadata` | 2.16GB | 2.15GB | 2.09GB | 0B |
| `local.(*Client).EvaluateV2` | 6.29GB | 6.27GB | 6.08GB | 0B |
| `local.topologicalSort` | 892.16MB | 888.62MB | 860.09MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 6.10GB | 6.08GB | 5.89GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 797.49MB | 793.35MB | 780.54MB | 0B |
| `localEvaluation.getMapOfValue` | 6.10GB | 6.08GB | 5.89GB | 0B |
| `utils.ParseFeatureFlag` | 6.11GB | 6.09GB | 5.90GB | 0B |

**Total FF alloc (current snapshot):** 32.52GB  |  **24h avg:** 31.44GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 83.74MB | 40/2519 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 63.86MB | 66/2519 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2170/2519 | `██████░░░░░░░░░ 43%` |
| 4 | `database/sql.convertAssignRows` | 31.02MB | 90/2519 | `█████░░░░░░░░░░ 37%` |
| 5 | `runtime.mallocgc` | 25.48MB | 2170/2519 | `████░░░░░░░░░░░ 30%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2519 | `███░░░░░░░░░░░░ 21%` |
| 7 | `bytes.growSlice` | 15.09MB | 1624/2519 | `██░░░░░░░░░░░░░ 18%` |
| 8 | `net/http.(*Transport).dialConn` | 14.36MB | 47/2519 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2519 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2519 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2519 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2519 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2519 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2519 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2519 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 34.64GB | 1036/2519 | `████░░░░░░░░░░░ 27%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2519 | `███░░░░░░░░░░░░ 22%` |
| 8 | `segmentio/kafka-go.makePartitions` | 27.12GB | 1893/2519 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2519 | `███░░░░░░░░░░░░ 21%` |
| 10 | `reflect.growslice` | 24.92GB | 1731/2519 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.2x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.1x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.1x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.7x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.5x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.5x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.9x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.7x avg)
