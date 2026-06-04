# Overview: prod
*Last updated: 2026-06-05 02:30 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T02:30 (1273 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,829 | avg: 11,563 | max: 84,644 | trend: decreasing (-7.33/hr))
```
▁▂▂▁▁▁▁▁▁▁▁▃▂▃▂▃▂▂▂▃▄▅▄▂▂▃▁▂▁▁▁▁▁▁▃▅█▇▅▆▂▂▂▁▁▁▁▁▁▂▁▁▁▁▁▁▁▂▄▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▄▂▁▁▁▁▁▁▁▁▂▂▁▂▂▂▁▁▁▁▂▁
```

**Heap InUse** (current: 548.8MB | avg: 177.3MB | max: 3154.1MB | trend: stable (-0.06MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,829 | 16,024 | -1195 | 11,563 | 84,644 | decreasing (-7.33/hr) |
| Heap InUse | 548.8MB | 283.4MB | +265.4MB | 177.3MB | 3154.1MB | stable (-0.06MB/hr) |
| Heap Sys | 1000.1MB | 4656.3MB | -3656.2MB | 2676.1MB | 6883.9MB | |
| Heap Objects | 4,734,113 | 1,735,420 | +2998693 | 778,767 | 17,165,538 | |

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
| 2026-06-05 | 31 | 14,887 | 300.4MB | 3154.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 128.71MB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 82.07MB |
| 3 | `database/sql.convertAssignRows` | 74.0MB |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 5 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 12.12MB |
| 6 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 7 | `dotlapse-event-service/project.FilterProjectsByTags` | 6.61MB |
| 8 | `runtime.mallocgc` | 6.51MB |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 10 | `bytes.growSlice` | 4.02MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 1.33GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 632.1MB |
| 3 | `reflect.growslice` | 267.92MB |
| 4 | `go-sql-driver/mysql.(*binaryRows).readRow` | 233.51MB |
| 5 | `jackskj/carta.getUniqueId` | 225.03MB |
| 6 | `reflect.unsafe_New` | 221.1MB |
| 7 | `database/sql.convertAssignRows` | 185.51MB |
| 8 | `fmt.(*buffer).writeString` | 165.6MB |
| 9 | `carta/value.NewCell` | 161.01MB |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 60.62MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 7.13MB | 273.63MB | 185.70MB | 0B |
| `evaluation.mergeMetadata` | 4.00MB | 137.03MB | 95.58MB | 0B |
| `local.(*Client).EvaluateV2` | 8.19MB | 399.09MB | 271.49MB | 0B |
| `local.topologicalSort` | 525.43kB | 59.21MB | 38.86MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 6.68MB | 376.74MB | 246.91MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 2.02MB | 53.65MB | 45.61MB | 0B |
| `localEvaluation.getMapOfValue` | 6.68MB | 376.74MB | 246.91MB | 0B |
| `utils.ParseFeatureFlag` | 6.68MB | 376.74MB | 246.96MB | 0B |

**Total FF alloc (current snapshot):** 41.91MB  |  **24h avg:** 1.35GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 79.36MB | 27/1273 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 76.91MB | 43/1273 | `██████████████░ 96%` |
| 3 | `database/sql.convertAssignRows` | 37.77MB | 55/1273 | `███████░░░░░░░░ 47%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 924/1273 | `██████░░░░░░░░░ 46%` |
| 5 | `runtime.mallocgc` | 18.85MB | 924/1273 | `███░░░░░░░░░░░░ 23%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1273 | `███░░░░░░░░░░░░ 22%` |
| 7 | `bytes.growSlice` | 14.84MB | 701/1273 | `██░░░░░░░░░░░░░ 18%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1273 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1273 | `██░░░░░░░░░░░░░ 15%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1273 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1273 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1273 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1273 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1273 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1273 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 36.33GB | 896/1273 | `████░░░░░░░░░░░ 28%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1273 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 16.23GB | 819/1273 | `█░░░░░░░░░░░░░░ 12%` |
| 9 | `fmt.Sprintf` | 10.33GB | 510/1273 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.77GB | 175/1273 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.7x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.3x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.7x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.4x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.8x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.8x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.0x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.7x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.3x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.4x avg)
