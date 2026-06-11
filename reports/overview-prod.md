# Overview: prod
*Last updated: 2026-06-11 20:41 IST*
*Data range: 2026-05-15T16:03 to 2026-06-11T20:41 (3217 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,796 | avg: 14,284 | max: 84,644 | trend: INCREASING (+3.66/hr))
```
▃▃▃▃▂▁▁▁▁▁▂▁▂▂▂▂▂▃▂▁▁▁▂▁▁▁▁▁▁▁▁▁▃▁▂▂▂▂▂▂▂▁▁▁▁▁▄▂▂▁▁▁▁▂▂▃▂▂▃▄▄▄▂▃▃▂▁▁▂▅▇▆▅▄█▂▃▃▄▁▁▁▂▅▇▆▇▇▆▁▁▁▂▁▁▁
```

**Heap InUse** (current: 229.0MB | avg: 235.1MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▄▃▃▂▄▂▃▁▂▂▃▃▂▂▁▃▂▂▄▂▂▁▄▁▂▂▂▂▁▁▃▁▂▁▃▁▃▂▂▃▂▃▂▁▁▁▆▃▁▂▂▁▂▂▁▄▂▂▄▄▄▃▃▂▃▃▁▂▃▄▇▆▅▄▆▃▄▃▄▂▁▂▁▄▅▆▇█▆▁▂▂▁▂▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,796 | 14,518 | +278 | 14,284 | 84,644 | INCREASING (+3.66/hr) |
| Heap InUse | 229.0MB | 218.9MB | +10.1MB | 235.1MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3334.9MB | 3335.0MB | -0.1MB | 2650.7MB | 6883.9MB | |
| Heap Objects | 835,996 | 649,183 | +186813 | 1,011,557 | 17,165,538 | |

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
| 2026-06-09 | 288 | 16,163 | 304.7MB | 1487.7MB |
| 2026-06-10 | 287 | 16,453 | 305.9MB | 1442.9MB |
| 2026-06-11 | 249 | 16,180 | 307.4MB | 1403.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `bytes.growSlice` | 5.03MB |
| 6 | `compress/flate.NewWriter` | 4.41MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.56MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `bufio.NewWriterSize` | 2.02MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 178.35GB |
| 2 | `segmentio/kafka-go.makePartitions` | 174.71GB |
| 3 | `jackskj/carta.getUniqueId` | 161.81GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 143.16GB |
| 5 | `reflect.unsafe_New` | 142.57GB |
| 6 | `fmt.Sprintf` | 129.96GB |
| 7 | `fmt.(*buffer).writeString` | 112.25GB |
| 8 | `carta/value.NewCell` | 101.83GB |
| 9 | `reflect.unsafe_NewArray` | 89.14GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 81.79GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 9.65GB | 9.65GB | 9.40GB | 0B |
| `evaluation.mergeMetadata` | 5.04GB | 5.04GB | 4.91GB | 0B |
| `local.(*Client).EvaluateV2` | 14.69GB | 14.68GB | 14.31GB | 512.01kB |
| `local.topologicalSort` | 2.03GB | 2.03GB | 1.98GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 14.01GB | 14.00GB | 13.66GB | 512.01kB |
| `localEvaluation.GetFeatureFlagPayload` | 2.03GB | 2.02GB | 1.96GB | 0B |
| `localEvaluation.getMapOfValue` | 14.01GB | 14.00GB | 13.66GB | 512.01kB |
| `utils.ParseFeatureFlag` | 14.03GB | 14.02GB | 13.68GB | 512.01kB |

**Total FF alloc (current snapshot):** 75.48GB  |  **24h avg:** 73.56GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.8MB | 60/3217 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 50.04MB | 88/3217 | `████████████░░░ 85%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2868/3217 | `█████████░░░░░░ 62%` |
| 4 | `runtime.mallocgc` | 31.56MB | 2868/3217 | `████████░░░░░░░ 53%` |
| 5 | `database/sql.convertAssignRows` | 27.04MB | 107/3217 | `██████░░░░░░░░░ 45%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3217 | `████░░░░░░░░░░░ 30%` |
| 7 | `bytes.growSlice` | 15.6MB | 2243/3217 | `███░░░░░░░░░░░░ 26%` |
| 8 | `net/http.(*Transport).dialConn` | 14.13MB | 71/3217 | `███░░░░░░░░░░░░ 24%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3217 | `███░░░░░░░░░░░░ 24%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3217 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3217 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3217 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3217 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 65.34GB | 1734/3217 | `███████░░░░░░░░ 52%` |
| 5 | `reflect.growslice` | 56.38GB | 2429/3217 | `██████░░░░░░░░░ 45%` |
| 6 | `segmentio/kafka-go.makePartitions` | 56.08GB | 2591/3217 | `██████░░░░░░░░░ 44%` |
| 7 | `experiment/local.topologicalSort` | 51.23GB | 375/3217 | `██████░░░░░░░░░ 40%` |
| 8 | `jackskj/carta.getUniqueId` | 49.69GB | 2445/3217 | `█████░░░░░░░░░░ 39%` |
| 9 | `reflect.unsafe_New` | 48.28GB | 2209/3217 | `█████░░░░░░░░░░ 38%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/3217 | `█████░░░░░░░░░░ 34%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.3x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
