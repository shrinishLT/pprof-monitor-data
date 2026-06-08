# Overview: prod
*Last updated: 2026-06-08 10:24 IST*
*Data range: 2026-05-15T16:03 to 2026-06-08T10:24 (2230 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 82,867 | avg: 13,396 | max: 84,644 | trend: INCREASING (+4.15/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▃▄▅█
```

**Heap InUse** (current: 1987.5MB | avg: 202.2MB | max: 3154.1MB | trend: stable (+0.07MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▃▃▄█
```

## Current Status

Goroutines: `███████████████████░ 97%`
Heap InUse: `█████░░░░░░░░░░░░░░░ 28%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 82,867 | 59,253 | +23614 | 13,396 | 84,644 | INCREASING (+4.15/hr) |
| Heap InUse | 1987.5MB | 1076.6MB | +910.9MB | 202.2MB | 3154.1MB | stable (+0.07MB/hr) |
| Heap Sys | 2935.4MB | 3052.8MB | -117.4MB | 2354.0MB | 6883.9MB | |
| Heap Objects | 7,652,869 | 2,578,575 | +5074294 | 905,116 | 17,165,538 | |

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
| 2026-06-08 | 125 | 16,214 | 275.9MB | 1987.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 381.37MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 195.9MB |
| 3 | `bufio.NewReaderSize` | 159.11MB |
| 4 | `bufio.NewWriterSize` | 158.11MB |
| 5 | `aes/gcm.NewGCMForTLS13` | 67.56MB |
| 6 | `runtime.mallocgc` | 50.47MB |
| 7 | `net/http.(*Transport).queueForIdleConn` | 45.54MB |
| 8 | `net/http.(*Transport).dialConn` | 37.51MB |
| 9 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 10 | `dotlapse-event-service/utils.CheckImageExists` | 24.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 61.63GB |
| 2 | `reflect.growslice` | 57.29GB |
| 3 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 54.18GB |
| 4 | `jackskj/carta.getUniqueId` | 48.44GB |
| 5 | `reflect.unsafe_New` | 44.27GB |
| 6 | `fmt.(*buffer).writeString` | 35.89GB |
| 7 | `reflect.unsafe_NewArray` | 31.52GB |
| 8 | `carta/value.NewCell` | 31.48GB |
| 9 | `fmt.Sprintf` | 24.79GB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 21.42GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.79GB | 1.78GB | 1.65GB | 0B |
| `evaluation.mergeMetadata` | 949.73MB | 943.73MB | 873.72MB | 0B |
| `local.(*Client).EvaluateV2` | 2.72GB | 2.71GB | 2.50GB | 0B |
| `local.topologicalSort` | 373.14MB | 371.61MB | 341.33MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.74GB | 2.72GB | 2.51GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 264.35MB | 261.76MB | 252.31MB | 0B |
| `localEvaluation.getMapOfValue` | 2.74GB | 2.72GB | 2.51GB | 0B |
| `utils.ParseFeatureFlag` | 2.74GB | 2.73GB | 2.51GB | 0B |

**Total FF alloc (current snapshot):** 14.28GB  |  **24h avg:** 13.11GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 83.58MB | 38/2230 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 64.17MB | 64/2230 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1881/2230 | `██████░░░░░░░░░ 43%` |
| 4 | `database/sql.convertAssignRows` | 31.29MB | 87/2230 | `█████░░░░░░░░░░ 37%` |
| 5 | `runtime.mallocgc` | 21.64MB | 1881/2230 | `███░░░░░░░░░░░░ 25%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2230 | `███░░░░░░░░░░░░ 21%` |
| 7 | `bytes.growSlice` | 14.94MB | 1365/2230 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `net/http.(*Transport).dialConn` | 14.27MB | 41/2230 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.34MB | 3/2230 | `██░░░░░░░░░░░░░ 13%` |
| 10 | `crypto/tls.Client` | 10.83MB | 58/2230 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2230 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2230 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2230 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2230 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2230 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2230 | `███░░░░░░░░░░░░ 22%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2230 | `███░░░░░░░░░░░░ 21%` |
| 8 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 23.11GB | 747/2230 | `██░░░░░░░░░░░░░ 18%` |
| 9 | `segmentio/kafka-go.makePartitions` | 17.93GB | 1604/2230 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `reflect.growslice` | 15.74GB | 1442/2230 | `█░░░░░░░░░░░░░░ 12%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.4x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.3x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.1x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.3x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.3x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.0x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.9x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.7x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.5x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (3.1x avg)
