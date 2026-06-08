# Overview: prod
*Last updated: 2026-06-08 10:35 IST*
*Data range: 2026-05-15T16:03 to 2026-06-08T10:35 (2233 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 23,182 | avg: 13,450 | max: 84,644 | trend: INCREASING (+4.43/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▃▄▅█▇▆▁
```

**Heap InUse** (current: 943.8MB | avg: 204.0MB | max: 3154.1MB | trend: stable (+0.08MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▃▃▄▇█▆▃
```

## Current Status

Goroutines: `█████░░░░░░░░░░░░░░░ 27%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 13%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 23,182 | 65,585 | -42403 | 13,450 | 84,644 | INCREASING (+4.43/hr) |
| Heap InUse | 943.8MB | 1683.7MB | -739.9MB | 204.0MB | 3154.1MB | stable (+0.08MB/hr) |
| Heap Sys | 3062.3MB | 3005.1MB | +57.2MB | 2354.9MB | 6883.9MB | |
| Heap Objects | 2,888,735 | 6,660,777 | -3772042 | 912,357 | 17,165,538 | |

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
| 2026-06-08 | 128 | 17,102 | 306.6MB | 2130.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 238.18MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 111.01MB |
| 3 | `bufio.NewWriterSize` | 90.33MB |
| 4 | `bufio.NewReaderSize` | 81.81MB |
| 5 | `runtime.mallocgc` | 50.47MB |
| 6 | `aes/gcm.NewGCMForTLS13` | 39.03MB |
| 7 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 8 | `net/http.(*Transport).dialConn` | 18.5MB |
| 9 | `net/http.(*Transport).queueForIdleConn` | 17.52MB |
| 10 | `crypto/tls.Client` | 16.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 61.84GB |
| 2 | `reflect.growslice` | 58.56GB |
| 3 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 56.22GB |
| 4 | `jackskj/carta.getUniqueId` | 49.56GB |
| 5 | `reflect.unsafe_New` | 45.31GB |
| 6 | `fmt.(*buffer).writeString` | 36.69GB |
| 7 | `carta/value.NewCell` | 32.26GB |
| 8 | `reflect.unsafe_NewArray` | 31.61GB |
| 9 | `fmt.Sprintf` | 25.34GB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 21.42GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.80GB | 1.80GB | 1.67GB | 0B |
| `evaluation.mergeMetadata` | 953.23MB | 952.23MB | 882.71MB | 0B |
| `local.(*Client).EvaluateV2` | 2.73GB | 2.73GB | 2.53GB | 0B |
| `local.topologicalSort` | 374.66MB | 373.65MB | 344.88MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.75GB | 2.74GB | 2.53GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 264.35MB | 264.35MB | 253.54MB | 0B |
| `localEvaluation.getMapOfValue` | 2.75GB | 2.74GB | 2.53GB | 0B |
| `utils.ParseFeatureFlag` | 2.75GB | 2.75GB | 2.54GB | 0B |

**Total FF alloc (current snapshot):** 14.33GB  |  **24h avg:** 13.25GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 83.58MB | 38/2233 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 64.17MB | 64/2233 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1884/2233 | `██████░░░░░░░░░ 43%` |
| 4 | `database/sql.convertAssignRows` | 31.29MB | 87/2233 | `█████░░░░░░░░░░ 37%` |
| 5 | `runtime.mallocgc` | 21.69MB | 1884/2233 | `███░░░░░░░░░░░░ 25%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2233 | `███░░░░░░░░░░░░ 21%` |
| 7 | `bytes.growSlice` | 15.54MB | 1368/2233 | `██░░░░░░░░░░░░░ 18%` |
| 8 | `net/http.(*Transport).dialConn` | 15.08MB | 44/2233 | `██░░░░░░░░░░░░░ 18%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2233 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `crypto/tls.Client` | 11.15MB | 60/2233 | `██░░░░░░░░░░░░░ 13%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2233 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2233 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2233 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2233 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2233 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2233 | `███░░░░░░░░░░░░ 22%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2233 | `███░░░░░░░░░░░░ 21%` |
| 8 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 23.24GB | 750/2233 | `██░░░░░░░░░░░░░ 18%` |
| 9 | `segmentio/kafka-go.makePartitions` | 18.01GB | 1607/2233 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `reflect.growslice` | 15.83GB | 1445/2233 | `█░░░░░░░░░░░░░░ 12%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.3x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.1x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.3x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.2x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.9x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.7x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.5x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (3.0x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.9x avg)
