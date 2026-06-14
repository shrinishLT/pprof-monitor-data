# Overview: prod
*Last updated: 2026-06-14 06:45 IST*
*Data range: 2026-05-15T16:03 to 2026-06-14T06:45 (3914 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,123 | avg: 14,633 | max: 84,644 | trend: INCREASING (+2.89/hr))
```
▆▅▆▆▆▅▇▆▇▅▅▃▃▄▄▅▄▄▆▆▆▄▇▅▅▅▆▅▆▆▆▇▆▇▅▇▆▇▇▇▅▇▆▅▆▅▅▅▅▅▇▆▅▇▄▅▅▇▆▅▆▅▇▅█▅▄▄▃▅▄▄▄▄▇▅▄▃▅▄▅▂▁▁▁▁▁▂▂▂▃▇▂▃▁▁
```

**Heap InUse** (current: 164.2MB | avg: 241.3MB | max: 3154.1MB | trend: stable (+0.07MB/hr))
```
▂▃▂▃▄▂▃▂▃▃▂▂▂▂▂▄▂▂▂▂▃▂▄▃▂▄▃▂▂▄▂▃▃▄▄▃▃▃▃▃▃▃▄▂▂▂▃▂▂▃▄▃▂▃▃▂▂▄▂▂▂▄▃▃▃▃█▃▂▂▂▃▂▃▂▄▃▂▃▂▂▁▁▁▁▁▁▂▂▁▃▄▂▃▂▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,123 | 14,257 | -134 | 14,633 | 84,644 | INCREASING (+2.89/hr) |
| Heap InUse | 164.2MB | 224.0MB | -59.8MB | 241.3MB | 3154.1MB | stable (+0.07MB/hr) |
| Heap Sys | 2297.7MB | 2297.5MB | +0.2MB | 2539.8MB | 6883.9MB | |
| Heap Objects | 597,991 | 1,345,773 | -747782 | 1,036,557 | 17,165,538 | |

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
| 2026-06-11 | 288 | 16,393 | 314.0MB | 1403.5MB |
| 2026-06-12 | 288 | 16,142 | 260.8MB | 1418.7MB |
| 2026-06-13 | 288 | 16,274 | 264.7MB | 1566.3MB |
| 2026-06-14 | 82 | 15,765 | 278.2MB | 547.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 30.86MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.01MB |
| 8 | `reflect.unsafe_NewArray` | 2.0MB |
| 9 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 10 | `bytes.growSlice` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 59.17GB |
| 2 | `segmentio/kafka-go.makePartitions` | 58.57GB |
| 3 | `jackskj/carta.getUniqueId` | 54.3GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 53.82GB |
| 5 | `reflect.unsafe_New` | 47.29GB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 44.69GB |
| 7 | `fmt.Sprintf` | 44.67GB |
| 8 | `fmt.(*buffer).writeString` | 37.14GB |
| 9 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 36.76GB |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 35.55GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 2.44GB | 2.44GB | 2.36GB | 0B |
| `evaluation.mergeMetadata` | 1.25GB | 1.25GB | 1.21GB | 0B |
| `local.(*Client).EvaluateV2` | 3.74GB | 3.74GB | 3.62GB | 0B |
| `local.topologicalSort` | 545.36MB | 545.36MB | 529.00MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 3.68GB | 3.68GB | 3.55GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 439.65MB | 439.65MB | 429.36MB | 0B |
| `localEvaluation.getMapOfValue` | 3.68GB | 3.68GB | 3.55GB | 0B |
| `utils.ParseFeatureFlag` | 3.69GB | 3.69GB | 3.56GB | 0B |

**Total FF alloc (current snapshot):** 19.43GB  |  **24h avg:** 18.80GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 46.72MB | 78/3914 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 41.56MB | 108/3914 | `█████████████░░ 88%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3565/3914 | `███████████░░░░ 78%` |
| 4 | `runtime.mallocgc` | 31.23MB | 3565/3914 | `██████████░░░░░ 66%` |
| 5 | `database/sql.convertAssignRows` | 23.23MB | 128/3914 | `███████░░░░░░░░ 49%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3914 | `█████░░░░░░░░░░ 38%` |
| 7 | `bytes.growSlice` | 15.73MB | 2817/3914 | `█████░░░░░░░░░░ 33%` |
| 8 | `net/http.(*Transport).dialConn` | 13.13MB | 102/3914 | `████░░░░░░░░░░░ 28%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/3914 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3914 | `███░░░░░░░░░░░░ 22%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3914 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3914 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3914 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 69.38GB | 2103/3914 | `████████░░░░░░░ 55%` |
| 5 | `segmentio/kafka-go.makePartitions` | 59.02GB | 3288/3914 | `███████░░░░░░░░ 47%` |
| 6 | `reflect.growslice` | 58.9GB | 3126/3914 | `███████░░░░░░░░ 47%` |
| 7 | `jackskj/carta.getUniqueId` | 52.34GB | 3142/3914 | `██████░░░░░░░░░ 41%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/3914 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 49.75GB | 2906/3914 | `█████░░░░░░░░░░ 39%` |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 45.9GB | 1498/3914 | `█████░░░░░░░░░░ 36%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.8x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.3x avg)
