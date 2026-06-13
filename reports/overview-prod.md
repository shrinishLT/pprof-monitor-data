# Overview: prod
*Last updated: 2026-06-13 09:15 IST*
*Data range: 2026-05-15T16:03 to 2026-06-13T09:15 (3656 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,117 | avg: 14,533 | max: 84,644 | trend: INCREASING (+3.21/hr))
```
▄▃▄▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▄▄▃▂▂▂▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 167.6MB | avg: 239.4MB | max: 3154.1MB | trend: stable (+0.08MB/hr))
```
▃▃▃▄▂▂▁▁▁▁▁▁▂▁▁▁▁▁▁▁█▃▄▄▂▃▂▁▁▁▁▁▁▁▁▂▃▁▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,117 | 14,569 | -452 | 14,533 | 84,644 | INCREASING (+3.21/hr) |
| Heap InUse | 167.6MB | 215.3MB | -47.7MB | 239.4MB | 3154.1MB | stable (+0.08MB/hr) |
| Heap Sys | 1432.0MB | 1430.8MB | +1.2MB | 2565.4MB | 6883.9MB | |
| Heap Objects | 830,279 | 1,070,161 | -239882 | 1,030,777 | 17,165,538 | |

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
| 2026-06-13 | 112 | 16,403 | 265.8MB | 1133.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 23.22MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 8 | `segmentio/kafka-go.makePartitions` | 1.51MB |
| 9 | `reflect.unsafe_NewArray` | 1.5MB |
| 10 | `encoding/json.(*decodeState).objectInterface` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 29.14GB |
| 2 | `reflect.growslice` | 23.87GB |
| 3 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 21.97GB |
| 4 | `jackskj/carta.getUniqueId` | 21.26GB |
| 5 | `reflect.unsafe_New` | 19.1GB |
| 6 | `fmt.Sprintf` | 19.05GB |
| 7 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 18.07GB |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 16.5GB |
| 9 | `reflect.unsafe_NewArray` | 14.86GB |
| 10 | `fmt.(*buffer).writeString` | 13.99GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.57GB | 1.57GB | 1.49GB | 0B |
| `evaluation.mergeMetadata` | 826.20MB | 824.20MB | 784.93MB | 0B |
| `local.(*Client).EvaluateV2` | 2.42GB | 2.41GB | 2.30GB | 0B |
| `local.topologicalSort` | 348.33MB | 348.33MB | 332.09MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.32GB | 2.31GB | 2.19GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 333.90MB | 333.90MB | 327.21MB | 0B |
| `localEvaluation.getMapOfValue` | 2.32GB | 2.31GB | 2.19GB | 0B |
| `utils.ParseFeatureFlag` | 2.32GB | 2.32GB | 2.20GB | 0B |

**Total FF alloc (current snapshot):** 12.43GB  |  **24h avg:** 11.79GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 49.43MB | 73/3656 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 44.97MB | 99/3656 | `█████████████░░ 90%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3307/3656 | `███████████░░░░ 74%` |
| 4 | `runtime.mallocgc` | 31.3MB | 3307/3656 | `█████████░░░░░░ 63%` |
| 5 | `database/sql.convertAssignRows` | 24.02MB | 123/3656 | `███████░░░░░░░░ 48%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3656 | `█████░░░░░░░░░░ 36%` |
| 7 | `bytes.growSlice` | 15.71MB | 2619/3656 | `████░░░░░░░░░░░ 31%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3656 | `████░░░░░░░░░░░ 28%` |
| 9 | `net/http.(*Transport).dialConn` | 13.41MB | 90/3656 | `████░░░░░░░░░░░ 27%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3656 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3656 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3656 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3656 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 72.96GB | 1923/3656 | `████████░░░░░░░ 58%` |
| 5 | `reflect.growslice` | 60.49GB | 2868/3656 | `███████░░░░░░░░ 48%` |
| 6 | `segmentio/kafka-go.makePartitions` | 60.31GB | 3030/3656 | `███████░░░░░░░░ 48%` |
| 7 | `jackskj/carta.getUniqueId` | 53.66GB | 2884/3656 | `██████░░░░░░░░░ 42%` |
| 8 | `reflect.unsafe_New` | 51.35GB | 2648/3656 | `██████░░░░░░░░░ 41%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/3656 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 47.91GB | 2230/3656 | `█████░░░░░░░░░░ 38%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.8x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
