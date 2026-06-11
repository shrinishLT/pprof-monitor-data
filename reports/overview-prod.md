# Overview: prod
*Last updated: 2026-06-11 22:46 IST*
*Data range: 2026-05-15T16:03 to 2026-06-11T22:45 (3242 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,645 | avg: 14,297 | max: 84,644 | trend: INCREASING (+3.62/hr))
```
▁▁▁▁▁▁▁▃▁▂▂▂▂▂▂▂▁▁▁▁▁▄▂▂▁▁▁▁▂▂▃▂▂▃▄▄▄▂▂▃▂▁▁▂▅▇▆▅▄▇▂▃▃▄▁▁▁▂▅▇▆▆▇▆▁▁▁▂▁▁▁▁▁▁▁▁▆▆█▆▄▂▁▁▁▃▅▆▅▁▁▁▁▁▁▁
```

**Heap InUse** (current: 221.3MB | avg: 235.7MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▃▂▂▁▁▃▁▃▁▃▂▃▂▂▄▂▃▂▁▁▁▆▃▂▂▂▁▂▂▂▄▃▂▄▄▄▄▄▂▃▃▁▂▃▄▇▆▅▄▆▃▄▃▄▂▁▂▂▄▅▆▇█▆▁▂▂▂▂▁▁▁▁▁▁▂▅▆▆▆▆▂▃▁▁▄▆▅▅▂▁▂▁▃▂▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,645 | 14,372 | +273 | 14,297 | 84,644 | INCREASING (+3.62/hr) |
| Heap InUse | 221.3MB | 273.0MB | -51.7MB | 235.7MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3334.1MB | 3334.8MB | -0.7MB | 2656.0MB | 6883.9MB | |
| Heap Objects | 596,847 | 1,625,031 | -1028184 | 1,013,268 | 17,165,538 | |

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
| 2026-06-11 | 274 | 16,156 | 307.1MB | 1403.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.52MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `bufio.NewWriterSize` | 2.52MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `bytes.growSlice` | 2.01MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 178.92GB |
| 2 | `segmentio/kafka-go.makePartitions` | 177.6GB |
| 3 | `jackskj/carta.getUniqueId` | 162.73GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 143.54GB |
| 5 | `reflect.unsafe_New` | 143.32GB |
| 6 | `fmt.Sprintf` | 132.4GB |
| 7 | `fmt.(*buffer).writeString` | 112.53GB |
| 8 | `carta/value.NewCell` | 102.37GB |
| 9 | `reflect.unsafe_NewArray` | 90.6GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 82.06GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 9.88GB | 9.86GB | 9.66GB | 0B |
| `evaluation.mergeMetadata` | 5.15GB | 5.15GB | 5.04GB | 0B |
| `local.(*Client).EvaluateV2` | 15.03GB | 15.02GB | 14.70GB | 0B |
| `local.topologicalSort` | 2.08GB | 2.08GB | 2.04GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 14.33GB | 14.31GB | 14.02GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 2.08GB | 2.08GB | 2.03GB | 0B |
| `localEvaluation.getMapOfValue` | 14.33GB | 14.31GB | 14.02GB | 0B |
| `utils.ParseFeatureFlag` | 14.35GB | 14.33GB | 14.04GB | 0B |

**Total FF alloc (current snapshot):** 77.23GB  |  **24h avg:** 75.54GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.8MB | 60/3242 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 50.04MB | 88/3242 | `████████████░░░ 85%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2893/3242 | `█████████░░░░░░ 62%` |
| 4 | `runtime.mallocgc` | 31.73MB | 2893/3242 | `████████░░░░░░░ 53%` |
| 5 | `database/sql.convertAssignRows` | 27.04MB | 107/3242 | `██████░░░░░░░░░ 45%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3242 | `████░░░░░░░░░░░ 30%` |
| 7 | `bytes.growSlice` | 15.59MB | 2267/3242 | `███░░░░░░░░░░░░ 26%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3242 | `███░░░░░░░░░░░░ 24%` |
| 9 | `net/http.(*Transport).dialConn` | 13.99MB | 72/3242 | `███░░░░░░░░░░░░ 23%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3242 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3242 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3242 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3242 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 66.45GB | 1759/3242 | `███████░░░░░░░░ 53%` |
| 5 | `reflect.growslice` | 57.62GB | 2454/3242 | `██████░░░░░░░░░ 46%` |
| 6 | `segmentio/kafka-go.makePartitions` | 57.23GB | 2616/3242 | `██████░░░░░░░░░ 45%` |
| 7 | `experiment/local.topologicalSort` | 51.23GB | 375/3242 | `██████░░░░░░░░░ 40%` |
| 8 | `jackskj/carta.getUniqueId` | 50.82GB | 2470/3242 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 49.34GB | 2234/3242 | `█████░░░░░░░░░░ 39%` |
| 10 | `fmt.(*buffer).writeString` | 44.22GB | 1981/3242 | `█████░░░░░░░░░░ 35%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.3x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
