# Overview: prod
*Last updated: 2026-06-08 10:30 IST*
*Data range: 2026-05-15T16:03 to 2026-06-08T10:30 (2232 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 65,585 | avg: 13,446 | max: 84,644 | trend: INCREASING (+4.41/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▃▄▅█▇▆
```

**Heap InUse** (current: 1683.7MB | avg: 203.7MB | max: 3154.1MB | trend: stable (+0.08MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▃▃▄▇█▆
```

## Current Status

Goroutines: `███████████████░░░░░ 77%`
Heap InUse: `████░░░░░░░░░░░░░░░░ 24%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 65,585 | 73,475 | -7890 | 13,446 | 84,644 | INCREASING (+4.41/hr) |
| Heap InUse | 1683.7MB | 2130.6MB | -446.9MB | 203.7MB | 3154.1MB | stable (+0.08MB/hr) |
| Heap Sys | 3005.1MB | 2948.9MB | +56.2MB | 2354.6MB | 6883.9MB | |
| Heap Objects | 6,660,777 | 9,333,257 | -2672480 | 911,471 | 17,165,538 | |

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
| 2026-06-08 | 127 | 17,054 | 301.6MB | 2130.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 282.4MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 138.64MB |
| 3 | `bufio.NewWriterSize` | 123.47MB |
| 4 | `bufio.NewReaderSize` | 117.45MB |
| 5 | `runtime.mallocgc` | 50.47MB |
| 6 | `aes/gcm.NewGCMForTLS13` | 47.54MB |
| 7 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 8 | `crypto/tls.Client` | 24.52MB |
| 9 | `net/http.(*Transport).dialConn` | 24.0MB |
| 10 | `net/http.(*Transport).queueForIdleConn` | 23.52MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 61.78GB |
| 2 | `reflect.growslice` | 58.29GB |
| 3 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 55.77GB |
| 4 | `jackskj/carta.getUniqueId` | 49.31GB |
| 5 | `reflect.unsafe_New` | 45.1GB |
| 6 | `fmt.(*buffer).writeString` | 36.53GB |
| 7 | `carta/value.NewCell` | 32.09GB |
| 8 | `reflect.unsafe_NewArray` | 31.58GB |
| 9 | `fmt.Sprintf` | 25.21GB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 21.42GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.80GB | 1.79GB | 1.66GB | 0B |
| `evaluation.mergeMetadata` | 952.23MB | 950.23MB | 879.80MB | 0B |
| `local.(*Client).EvaluateV2` | 2.73GB | 2.72GB | 2.52GB | 0B |
| `local.topologicalSort` | 373.65MB | 373.14MB | 343.70MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.74GB | 2.74GB | 2.53GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 264.35MB | 264.35MB | 253.15MB | 0B |
| `localEvaluation.getMapOfValue` | 2.74GB | 2.74GB | 2.53GB | 0B |
| `utils.ParseFeatureFlag` | 2.75GB | 2.74GB | 2.53GB | 0B |

**Total FF alloc (current snapshot):** 14.31GB  |  **24h avg:** 13.20GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 83.58MB | 38/2232 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 64.17MB | 64/2232 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1883/2232 | `██████░░░░░░░░░ 43%` |
| 4 | `database/sql.convertAssignRows` | 31.29MB | 87/2232 | `█████░░░░░░░░░░ 37%` |
| 5 | `runtime.mallocgc` | 21.67MB | 1883/2232 | `███░░░░░░░░░░░░ 25%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2232 | `███░░░░░░░░░░░░ 21%` |
| 7 | `bytes.growSlice` | 15.38MB | 1367/2232 | `██░░░░░░░░░░░░░ 18%` |
| 8 | `net/http.(*Transport).dialConn` | 15.0MB | 43/2232 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2232 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `crypto/tls.Client` | 11.06MB | 59/2232 | `█░░░░░░░░░░░░░░ 13%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2232 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2232 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2232 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2232 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2232 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2232 | `███░░░░░░░░░░░░ 22%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2232 | `███░░░░░░░░░░░░ 21%` |
| 8 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 23.2GB | 749/2232 | `██░░░░░░░░░░░░░ 18%` |
| 9 | `segmentio/kafka-go.makePartitions` | 17.98GB | 1606/2232 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `reflect.growslice` | 15.8GB | 1444/2232 | `█░░░░░░░░░░░░░░ 12%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.3x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.1x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.3x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.2x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.9x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.7x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.5x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (3.1x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.9x avg)
