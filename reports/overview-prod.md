# Overview: prod
*Last updated: 2026-06-06 13:40 IST*
*Data range: 2026-05-15T16:03 to 2026-06-06T13:40 (1694 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,143 | avg: 12,778 | max: 84,644 | trend: INCREASING (+3.43/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▄▇█▇▄▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 161.5MB | avg: 194.9MB | max: 3154.1MB | trend: stable (+0.07MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▄▆▇█▄▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,143 | 14,200 | -57 | 12,778 | 84,644 | INCREASING (+3.43/hr) |
| Heap InUse | 161.5MB | 129.9MB | +31.6MB | 194.9MB | 3154.1MB | stable (+0.07MB/hr) |
| Heap Sys | 871.4MB | 871.5MB | -0.1MB | 2427.6MB | 6883.9MB | |
| Heap Objects | 1,013,181 | 571,783 | +441398 | 863,408 | 17,165,538 | |

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
| 2026-06-06 | 165 | 16,993 | 273.6MB | 1932.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.08MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `aws/endpoints.init` | 2.0MB |
| 8 | `segmentio/kafka-go.makePartitions` | 1.5MB |
| 9 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 1.5MB |
| 10 | `reflect.mapassign_faststr0` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 1.27GB |
| 2 | `jackskj/carta.getUniqueId` | 1.04GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 969.28MB |
| 4 | `reflect.unsafe_New` | 954.92MB |
| 5 | `fmt.(*buffer).writeString` | 867.15MB |
| 6 | `carta/value.NewCell` | 660.05MB |
| 7 | `segmentio/kafka-go.makePartitions` | 575.54MB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 386.02MB |
| 9 | `reflect.unsafe_NewArray` | 296.65MB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 286.01MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 21.81MB | 17.73MB | 1.46GB | 0B |
| `evaluation.mergeMetadata` | 14.00MB | 12.00MB | 772.12MB | 0B |
| `local.(*Client).EvaluateV2` | 29.62MB | 22.95MB | 2.23GB | 0B |
| `local.topologicalSort` | 2.03MB | 518.65kB | 319.45MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 32.20MB | 24.51MB | 2.16GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 512.14kB | 512.14kB | 282.65MB | 0B |
| `localEvaluation.getMapOfValue` | 32.20MB | 24.51MB | 2.16GB | 0B |
| `utils.ParseFeatureFlag` | 32.20MB | 24.51MB | 2.16GB | 0B |

**Total FF alloc (current snapshot):** 164.56MB  |  **24h avg:** 11.51GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 90.47MB | 35/1694 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 72.55MB | 56/1694 | `████████████░░░ 80%` |
| 3 | `database/sql.convertAssignRows` | 38.68MB | 69/1694 | `██████░░░░░░░░░ 42%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1345/1694 | `██████░░░░░░░░░ 40%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1694 | `██░░░░░░░░░░░░░ 19%` |
| 6 | `runtime.mallocgc` | 17.48MB | 1345/1694 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `bytes.growSlice` | 15.53MB | 1049/1694 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `net/http.(*Transport).dialConn` | 12.61MB | 32/1694 | `██░░░░░░░░░░░░░ 13%` |
| 9 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1694 | `██░░░░░░░░░░░░░ 13%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1694 | `█░░░░░░░░░░░░░░ 11%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1694 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1694 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1694 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1694 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1694 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 30.79GB | 1108/1694 | `███░░░░░░░░░░░░ 24%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1694 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.77GB | 931/1694 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 12.86GB | 401/1694 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `fmt.Sprintf` | 12.8GB | 873/1694 | `█░░░░░░░░░░░░░░ 10%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.7x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.6x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.2x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.4x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.4x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.1x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.0x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.9x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.6x avg)
