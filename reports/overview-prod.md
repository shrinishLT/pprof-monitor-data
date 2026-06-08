# Overview: prod
*Last updated: 2026-06-08 20:35 IST*
*Data range: 2026-05-15T16:03 to 2026-06-08T20:35 (2353 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,895 | avg: 13,580 | max: 84,644 | trend: INCREASING (+4.41/hr))
```
▃▃▃▂▃▄▁▁▁▁▃▃▁▁▂▂▅▃▃▂▃▆▇▅▇▆▇▄▃▄▄▃▂▃▃▄▃▂▄▃▄▅▃▁▁▁▄▆▅▄▅█▃▁▁▄▃▃▂▁▁▁▁▁▁▆▂▂▂▂▁▂▁▁▁▁▁▁▁▃▂▁▁▂▆▃▄▂▂▆▃▂▄▂▂▂
```

**Heap InUse** (current: 344.7MB | avg: 209.8MB | max: 3154.1MB | trend: stable (+0.10MB/hr))
```
▂▁▁▂▁▂▁▁▁▁▁▂▁▁▁▁▂▂▂▁▂▂▃▃▃▃▂▂▂▂▂▂▁▁▂▂▂▁█▁▂▂▂▁▁▁▂▃▃▂▂▂▄▁▁▂▁▁▂▁▁▁▁▁▁▃▂▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▃▂▂▁▁▃▂▁▂▁▁▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,895 | 15,468 | +427 | 13,580 | 84,644 | INCREASING (+4.41/hr) |
| Heap InUse | 344.7MB | 282.7MB | +62.0MB | 209.8MB | 3154.1MB | stable (+0.10MB/hr) |
| Heap Sys | 3336.5MB | 3336.5MB | +0.0MB | 2401.5MB | 6883.9MB | |
| Heap Objects | 1,784,030 | 1,255,727 | +528303 | 927,254 | 17,165,538 | |

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
| 2026-06-08 | 248 | 16,564 | 311.5MB | 2130.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 14.45MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 6 | `bufio.NewReaderSize` | 6.02MB |
| 7 | `bufio.NewWriterSize` | 5.52MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.52MB |
| 9 | `net/http.(*Transport).queueForIdleConn` | 3.0MB |
| 10 | `compress/flate.NewWriter` | 2.64MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 75.64GB |
| 2 | `reflect.growslice` | 65.91GB |
| 3 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 60.17GB |
| 4 | `jackskj/carta.getUniqueId` | 57.37GB |
| 5 | `reflect.unsafe_New` | 51.51GB |
| 6 | `fmt.(*buffer).writeString` | 41.08GB |
| 7 | `fmt.Sprintf` | 40.65GB |
| 8 | `reflect.unsafe_NewArray` | 38.62GB |
| 9 | `carta/value.NewCell` | 36.86GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 25.13GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 3.12GB | 3.11GB | 2.85GB | 0B |
| `evaluation.mergeMetadata` | 1.63GB | 1.62GB | 1.48GB | 0B |
| `local.(*Client).EvaluateV2` | 4.75GB | 4.73GB | 4.32GB | 0B |
| `local.topologicalSort` | 673.83MB | 670.28MB | 606.66MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 4.54GB | 4.52GB | 4.18GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 670.25MB | 665.64MB | 569.64MB | 0B |
| `localEvaluation.getMapOfValue` | 4.54GB | 4.52GB | 4.18GB | 0B |
| `utils.ParseFeatureFlag` | 4.55GB | 4.53GB | 4.18GB | 0B |

**Total FF alloc (current snapshot):** 24.43GB  |  **24h avg:** 22.35GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 85.75MB | 39/2353 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 63.86MB | 66/2353 | `███████████░░░░ 74%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2004/2353 | `██████░░░░░░░░░ 42%` |
| 4 | `database/sql.convertAssignRows` | 31.33MB | 89/2353 | `█████░░░░░░░░░░ 36%` |
| 5 | `runtime.mallocgc` | 23.41MB | 2004/2353 | `████░░░░░░░░░░░ 27%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2353 | `███░░░░░░░░░░░░ 20%` |
| 7 | `bytes.growSlice` | 15.45MB | 1482/2353 | `██░░░░░░░░░░░░░ 18%` |
| 8 | `net/http.(*Transport).dialConn` | 14.36MB | 47/2353 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2353 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `crypto/tls.Client` | 10.66MB | 64/2353 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2353 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2353 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2353 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2353 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2353 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 28.18GB | 870/2353 | `███░░░░░░░░░░░░ 22%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2353 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2353 | `███░░░░░░░░░░░░ 21%` |
| 9 | `segmentio/kafka-go.makePartitions` | 21.54GB | 1727/2353 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `reflect.growslice` | 19.53GB | 1565/2353 | `██░░░░░░░░░░░░░ 15%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.2x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.1x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.2x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.2x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.8x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.6x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.5x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (3.0x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.8x avg)
