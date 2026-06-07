# Overview: prod
*Last updated: 2026-06-07 17:35 IST*
*Data range: 2026-05-15T16:03 to 2026-06-07T17:35 (2029 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,130 | avg: 13,191 | max: 84,644 | trend: INCREASING (+4.12/hr))
```
▁▁▁▁▁▁▃▅█▆▆▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 190.1MB | avg: 196.5MB | max: 3154.1MB | trend: stable (+0.05MB/hr))
```
▁▁▁▁▁▁▃▅█▇▅▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,130 | 14,116 | +14 | 13,191 | 84,644 | INCREASING (+4.12/hr) |
| Heap InUse | 190.1MB | 250.3MB | -60.2MB | 196.5MB | 3154.1MB | stable (+0.05MB/hr) |
| Heap Sys | 3220.4MB | 3220.4MB | +0.0MB | 2268.4MB | 6883.9MB | |
| Heap Objects | 647,023 | 1,346,142 | -699119 | 884,251 | 17,165,538 | |

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
| 2026-06-07 | 212 | 15,857 | 235.3MB | 1942.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 49.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.54MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.unsafe_NewArray` | 2.0MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `reflect.mapassign_faststr0` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 40.03GB |
| 2 | `segmentio/kafka-go.makePartitions` | 38.71GB |
| 3 | `reflect.growslice` | 34.18GB |
| 4 | `jackskj/carta.getUniqueId` | 29.47GB |
| 5 | `reflect.unsafe_New` | 26.4GB |
| 6 | `fmt.(*buffer).writeString` | 21.32GB |
| 7 | `reflect.unsafe_NewArray` | 19.75GB |
| 8 | `carta/value.NewCell` | 18.91GB |
| 9 | `fmt.Sprintf` | 16.31GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 14.02GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.09GB | 1.09GB | 1.01GB | 0B |
| `evaluation.mergeMetadata` | 574.14MB | 571.64MB | 528.51MB | 0B |
| `local.(*Client).EvaluateV2` | 1.65GB | 1.65GB | 1.53GB | 0B |
| `local.topologicalSort` | 227.20MB | 226.18MB | 211.40MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.67GB | 1.66GB | 1.57GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 159.02MB | 158.00MB | 132.32MB | 0B |
| `localEvaluation.getMapOfValue` | 1.67GB | 1.66GB | 1.57GB | 0B |
| `utils.ParseFeatureFlag` | 1.67GB | 1.66GB | 1.57GB | 0B |

**Total FF alloc (current snapshot):** 8.68GB  |  **24h avg:** 8.09GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 85.72MB | 37/2029 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 66.16MB | 62/2029 | `███████████░░░░ 77%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1680/2029 | `██████░░░░░░░░░ 42%` |
| 4 | `database/sql.convertAssignRows` | 34.17MB | 79/2029 | `█████░░░░░░░░░░ 39%` |
| 5 | `runtime.mallocgc` | 18.31MB | 1680/2029 | `███░░░░░░░░░░░░ 21%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2029 | `███░░░░░░░░░░░░ 20%` |
| 7 | `bytes.growSlice` | 15.09MB | 1246/2029 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `net/http.(*Transport).dialConn` | 13.47MB | 37/2029 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2029 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 10.48MB | 38/2029 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2029 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2029 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2029 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2029 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2029 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2029 | `███░░░░░░░░░░░░ 22%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2029 | `███░░░░░░░░░░░░ 21%` |
| 8 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 15.87GB | 546/2029 | `█░░░░░░░░░░░░░░ 12%` |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 14.23GB | 969/2029 | `█░░░░░░░░░░░░░░ 11%` |
| 10 | `segmentio/kafka-go.makePartitions` | 13.31GB | 1403/2029 | `█░░░░░░░░░░░░░░ 10%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.7x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.4x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.1x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.4x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.4x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.0x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.0x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.9x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.6x avg)
