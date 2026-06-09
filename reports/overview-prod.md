# Overview: prod
*Last updated: 2026-06-09 10:35 IST*
*Data range: 2026-05-15T16:03 to 2026-06-09T10:35 (2521 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 49,678 | avg: 13,735 | max: 84,644 | trend: INCREASING (+4.30/hr))
```
▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▆▃▇█
```

**Heap InUse** (current: 1284.5MB | avg: 215.2MB | max: 3154.1MB | trend: stable (+0.10MB/hr))
```
▁▁▁▃▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▂▁▁▂▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▃▅▄▅█
```

## Current Status

Goroutines: `███████████░░░░░░░░░ 58%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 18%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 49,678 | 49,648 | +30 | 13,735 | 84,644 | INCREASING (+4.30/hr) |
| Heap InUse | 1284.5MB | 926.4MB | +358.1MB | 215.2MB | 3154.1MB | stable (+0.10MB/hr) |
| Heap Sys | 3210.2MB | 3217.4MB | -7.2MB | 2463.7MB | 6883.9MB | |
| Heap Objects | 5,881,139 | 2,522,564 | +3358575 | 946,476 | 17,165,538 | |

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
| 2026-06-09 | 128 | 16,246 | 298.3MB | 1284.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 176.12MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 79.37MB |
| 3 | `bufio.NewWriterSize` | 76.32MB |
| 4 | `bufio.NewReaderSize` | 64.76MB |
| 5 | `runtime.mallocgc` | 50.47MB |
| 6 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 27.02MB |
| 8 | `net/http.(*Transport).queueForIdleConn` | 17.52MB |
| 9 | `net/http.(*Transport).tryPutIdleConn` | 17.51MB |
| 10 | `crypto/tls.Client` | 14.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 95.44GB |
| 2 | `segmentio/kafka-go.makePartitions` | 94.79GB |
| 3 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 85.09GB |
| 4 | `jackskj/carta.getUniqueId` | 84.4GB |
| 5 | `reflect.unsafe_New` | 75.06GB |
| 6 | `fmt.Sprintf` | 61.71GB |
| 7 | `fmt.(*buffer).writeString` | 61.04GB |
| 8 | `carta/value.NewCell` | 53.48GB |
| 9 | `reflect.unsafe_NewArray` | 48.49GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 43.27GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 4.14GB | 4.13GB | 4.01GB | 0B |
| `evaluation.mergeMetadata` | 2.17GB | 2.16GB | 2.09GB | 0B |
| `local.(*Client).EvaluateV2` | 6.31GB | 6.30GB | 6.10GB | 0B |
| `local.topologicalSort` | 897.73MB | 895.70MB | 862.46MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 6.12GB | 6.11GB | 5.90GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 799.03MB | 797.49MB | 781.58MB | 0B |
| `localEvaluation.getMapOfValue` | 6.12GB | 6.11GB | 5.90GB | 0B |
| `utils.ParseFeatureFlag` | 6.13GB | 6.12GB | 5.91GB | 0B |

**Total FF alloc (current snapshot):** 32.66GB  |  **24h avg:** 31.52GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 83.74MB | 40/2521 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 63.86MB | 66/2521 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2172/2521 | `██████░░░░░░░░░ 43%` |
| 4 | `database/sql.convertAssignRows` | 31.02MB | 90/2521 | `█████░░░░░░░░░░ 37%` |
| 5 | `runtime.mallocgc` | 25.5MB | 2172/2521 | `████░░░░░░░░░░░ 30%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2521 | `███░░░░░░░░░░░░ 21%` |
| 7 | `bytes.growSlice` | 15.27MB | 1626/2521 | `██░░░░░░░░░░░░░ 18%` |
| 8 | `net/http.(*Transport).dialConn` | 14.41MB | 48/2521 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2521 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2521 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2521 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2521 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2521 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2521 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2521 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 34.74GB | 1038/2521 | `████░░░░░░░░░░░ 27%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2521 | `███░░░░░░░░░░░░ 22%` |
| 8 | `segmentio/kafka-go.makePartitions` | 27.19GB | 1895/2521 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2521 | `███░░░░░░░░░░░░ 21%` |
| 10 | `reflect.growslice` | 25.0GB | 1733/2521 | `██░░░░░░░░░░░░░ 19%` |

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
