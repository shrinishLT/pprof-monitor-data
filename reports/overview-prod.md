# Overview: prod
*Last updated: 2026-06-16 14:01 IST*
*Data range: 2026-05-15T16:03 to 2026-06-16T14:00 (4574 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,393 | avg: 14,857 | max: 84,644 | trend: INCREASING (+2.32/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▃▄▃▄▄▅▆█▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 123.9MB | avg: 246.0MB | max: 3154.1MB | trend: stable (+0.06MB/hr))
```
▁▂▁▁▁▂▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▅▃▄▅▅▇█▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 1%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,393 | 15,679 | -1286 | 14,857 | 84,644 | INCREASING (+2.32/hr) |
| Heap InUse | 123.9MB | 216.0MB | -92.1MB | 246.0MB | 3154.1MB | stable (+0.06MB/hr) |
| Heap Sys | 463.3MB | 462.4MB | +0.9MB | 2504.3MB | 6883.9MB | |
| Heap Objects | 397,041 | 842,291 | -445250 | 1,054,018 | 17,165,538 | |

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
| 2026-06-14 | 288 | 15,854 | 265.3MB | 1419.6MB |
| 2026-06-15 | 286 | 16,144 | 281.9MB | 1342.8MB |
| 2026-06-16 | 168 | 16,603 | 277.9MB | 1286.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 10.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 7.49MB |
| 5 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 7.49MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.85MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.53MB |
| 9 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 10 | `database/sql.convertAssignRows` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 5.58GB |
| 2 | `jackskj/carta.getUniqueId` | 5.16GB |
| 3 | `reflect.unsafe_New` | 4.53GB |
| 4 | `segmentio/kafka-go.makePartitions` | 3.57GB |
| 5 | `fmt.(*buffer).writeString` | 3.34GB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 3.33GB |
| 7 | `fmt.Sprintf` | 3.2GB |
| 8 | `carta/value.NewCell` | 3.19GB |
| 9 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 2.75GB |
| 10 | `reflect.unsafe_NewArray` | 1.85GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 237.93MB | 232.84MB | 2.06GB | 0B |
| `evaluation.mergeMetadata` | 126.03MB | 123.53MB | 1.07GB | 0B |
| `local.(*Client).EvaluateV2` | 362.51MB | 354.33MB | 3.16GB | 0B |
| `local.topologicalSort` | 49.03MB | 47.50MB | 455.36MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 349.35MB | 341.67MB | 3.07GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 54.64MB | 54.14MB | 400.51MB | 0B |
| `localEvaluation.getMapOfValue` | 349.35MB | 341.67MB | 3.07GB | 0B |
| `utils.ParseFeatureFlag` | 350.35MB | 342.67MB | 3.07GB | 0B |

**Total FF alloc (current snapshot):** 1.84GB  |  **24h avg:** 16.33GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 39.82MB | 97/4574 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 4225/4574 | `█████████████░░ 91%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 36.19MB | 130/4574 | `█████████████░░ 90%` |
| 4 | `runtime.mallocgc` | 31.22MB | 4225/4574 | `███████████░░░░ 78%` |
| 5 | `database/sql.convertAssignRows` | 20.6MB | 153/4574 | `███████░░░░░░░░ 51%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4574 | `██████░░░░░░░░░ 45%` |
| 7 | `bytes.growSlice` | 15.85MB | 3325/4574 | `█████░░░░░░░░░░ 39%` |
| 8 | `net/http.(*Transport).dialConn` | 13.25MB | 128/4574 | `████░░░░░░░░░░░ 33%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/4574 | `████░░░░░░░░░░░ 29%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4574 | `███░░░░░░░░░░░░ 26%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4574 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 75.85GB | 2734/4574 | `█████████░░░░░░ 60%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4574 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4574 | `████████░░░░░░░ 59%` |
| 5 | `reflect.growslice` | 64.43GB | 3786/4574 | `███████░░░░░░░░ 51%` |
| 6 | `segmentio/kafka-go.makePartitions` | 64.21GB | 3948/4574 | `███████░░░░░░░░ 51%` |
| 7 | `jackskj/carta.getUniqueId` | 57.55GB | 3802/4574 | `██████░░░░░░░░░ 46%` |
| 8 | `reflect.unsafe_New` | 53.86GB | 3566/4574 | `██████░░░░░░░░░ 43%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/4574 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 47.95GB | 3120/4574 | `█████░░░░░░░░░░ 38%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.7x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.7x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.7x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.2x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (3.9x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.5x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.3x avg)
