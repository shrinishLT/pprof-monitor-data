# Overview: prod
*Last updated: 2026-06-08 13:55 IST*
*Data range: 2026-05-15T16:03 to 2026-06-08T13:55 (2273 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,614 | avg: 13,480 | max: 84,644 | trend: INCREASING (+4.35/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▃▄▅█▇▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 311.6MB | avg: 205.1MB | max: 3154.1MB | trend: stable (+0.08MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▃▃▄▇█▆▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,614 | 15,293 | +321 | 13,480 | 84,644 | INCREASING (+4.35/hr) |
| Heap InUse | 311.6MB | 297.0MB | +14.6MB | 205.1MB | 3154.1MB | stable (+0.08MB/hr) |
| Heap Sys | 3210.1MB | 3210.8MB | -0.7MB | 2369.9MB | 6883.9MB | |
| Heap Objects | 1,298,189 | 1,366,398 | -68209 | 913,823 | 17,165,538 | |

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
| 2026-06-08 | 168 | 16,631 | 296.7MB | 2130.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 12.49MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 6.03MB |
| 7 | `compress/flate.NewWriter` | 3.53MB |
| 8 | `segmentio/kafka-go.makePartitions` | 3.01MB |
| 9 | `bufio.NewWriterSize` | 2.54MB |
| 10 | `crypto/tls.Client` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 66.54GB |
| 2 | `reflect.growslice` | 64.71GB |
| 3 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 59.25GB |
| 4 | `jackskj/carta.getUniqueId` | 55.66GB |
| 5 | `reflect.unsafe_New` | 50.25GB |
| 6 | `fmt.(*buffer).writeString` | 40.45GB |
| 7 | `carta/value.NewCell` | 35.9GB |
| 8 | `reflect.unsafe_NewArray` | 33.96GB |
| 9 | `fmt.Sprintf` | 29.69GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 24.13GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 2.15GB | 2.14GB | 1.93GB | 0B |
| `evaluation.mergeMetadata` | 1.11GB | 1.10GB | 1022.01MB | 0B |
| `local.(*Client).EvaluateV2` | 3.26GB | 3.24GB | 2.93GB | 0B |
| `local.topologicalSort` | 448.11MB | 444.06MB | 403.19MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 3.25GB | 3.23GB | 2.94GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 345.80MB | 340.65MB | 289.72MB | 0B |
| `localEvaluation.getMapOfValue` | 3.25GB | 3.23GB | 2.94GB | 0B |
| `utils.ParseFeatureFlag` | 3.25GB | 3.24GB | 2.95GB | 0B |

**Total FF alloc (current snapshot):** 17.06GB  |  **24h avg:** 15.37GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 83.58MB | 38/2273 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 64.17MB | 64/2273 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1924/2273 | `██████░░░░░░░░░ 43%` |
| 4 | `database/sql.convertAssignRows` | 31.29MB | 87/2273 | `█████░░░░░░░░░░ 37%` |
| 5 | `runtime.mallocgc` | 22.29MB | 1924/2273 | `████░░░░░░░░░░░ 26%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2273 | `███░░░░░░░░░░░░ 21%` |
| 7 | `bytes.growSlice` | 15.38MB | 1402/2273 | `██░░░░░░░░░░░░░ 18%` |
| 8 | `net/http.(*Transport).dialConn` | 15.08MB | 44/2273 | `██░░░░░░░░░░░░░ 18%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2273 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `crypto/tls.Client` | 10.88MB | 62/2273 | `█░░░░░░░░░░░░░░ 13%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2273 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2273 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2273 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2273 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2273 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2273 | `███░░░░░░░░░░░░ 22%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2273 | `███░░░░░░░░░░░░ 21%` |
| 8 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 24.97GB | 790/2273 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `segmentio/kafka-go.makePartitions` | 19.13GB | 1647/2273 | `██░░░░░░░░░░░░░ 15%` |
| 10 | `reflect.growslice` | 17.05GB | 1485/2273 | `██░░░░░░░░░░░░░ 13%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.3x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.1x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.3x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.2x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.8x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.7x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.5x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (3.0x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.9x avg)
