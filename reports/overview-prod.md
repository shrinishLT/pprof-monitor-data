# Overview: prod
*Last updated: 2026-06-16 08:36 IST*
*Data range: 2026-05-15T16:03 to 2026-06-16T08:35 (4509 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,319 | avg: 14,801 | max: 84,644 | trend: INCREASING (+2.28/hr))
```
▇▂▁█▄▃▂▄▂▁▁▁▃▁▁▁▃▂▂▁▁▁▁▃▃▁▁▁▁▄▄▁▁▁▁▁▂▁▁▁▁▃▂▁▁▁▁▁▁▁▂▁▁▁▂▁▁▁▂▂▂▁▁▁▁▁▁▂▂▁▁▃▅▃▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 228.2MB | avg: 245.1MB | max: 3154.1MB | trend: stable (+0.06MB/hr))
```
▇▃▃█▆▃▃▆▄▁▂▂▃▃▁▃▃▃▃▁▁▃▃▄▄▃▃▂▃▄▆▃▃▂▁▂▄▂▁▃▃▄▂▃▁▁▁▄▂▂▂▂▁▂▃▃▂▃▃▃▄▁▂▂▁▂▄▂▃▃▄▆▅▅▃▁▁▂▂▁▁▂▂▁▂▂▂▁▂▃▁▂▃▁▃▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,319 | 14,234 | +85 | 14,801 | 84,644 | INCREASING (+2.28/hr) |
| Heap InUse | 228.2MB | 256.7MB | -28.5MB | 245.1MB | 3154.1MB | stable (+0.06MB/hr) |
| Heap Sys | 2431.5MB | 2431.6MB | -0.1MB | 2520.4MB | 6883.9MB | |
| Heap Objects | 1,228,367 | 1,565,232 | -336865 | 1,049,708 | 17,165,538 | |

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
| 2026-06-16 | 103 | 15,271 | 256.1MB | 455.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 32.36MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `bytes.growSlice` | 4.6MB |
| 6 | `compress/flate.NewWriter` | 3.53MB |
| 7 | `bufio.NewWriterSize` | 2.54MB |
| 8 | `reflect.unsafe_NewArray` | 2.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 126.67GB |
| 2 | `reflect.growslice` | 125.03GB |
| 3 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 118.01GB |
| 4 | `jackskj/carta.getUniqueId` | 112.37GB |
| 5 | `reflect.unsafe_New` | 98.76GB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 92.51GB |
| 7 | `fmt.Sprintf` | 88.98GB |
| 8 | `fmt.(*buffer).writeString` | 77.22GB |
| 9 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 76.08GB |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 74.19GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 5.76GB | 5.75GB | 5.60GB | 0B |
| `evaluation.mergeMetadata` | 2.99GB | 2.98GB | 2.90GB | 0B |
| `local.(*Client).EvaluateV2` | 8.85GB | 8.83GB | 8.61GB | 0B |
| `local.topologicalSort` | 1.25GB | 1.25GB | 1.22GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 8.57GB | 8.56GB | 8.34GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.11GB | 1.10GB | 1.08GB | 0B |
| `localEvaluation.getMapOfValue` | 8.57GB | 8.56GB | 8.34GB | 0B |
| `utils.ParseFeatureFlag` | 8.58GB | 8.57GB | 8.35GB | 0B |

**Total FF alloc (current snapshot):** 45.68GB  |  **24h avg:** 44.43GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 40.82MB | 94/4509 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 36.68MB | 128/4509 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 4160/4509 | `█████████████░░ 89%` |
| 4 | `runtime.mallocgc` | 31.37MB | 4160/4509 | `███████████░░░░ 76%` |
| 5 | `database/sql.convertAssignRows` | 21.02MB | 149/4509 | `███████░░░░░░░░ 51%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4509 | `██████░░░░░░░░░ 44%` |
| 7 | `bytes.growSlice` | 15.63MB | 3265/4509 | `█████░░░░░░░░░░ 38%` |
| 8 | `net/http.(*Transport).dialConn` | 13.21MB | 119/4509 | `████░░░░░░░░░░░ 32%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/4509 | `████░░░░░░░░░░░ 29%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4509 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4509 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 75.36GB | 2698/4509 | `█████████░░░░░░ 60%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4509 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4509 | `████████░░░░░░░ 59%` |
| 5 | `reflect.growslice` | 64.37GB | 3721/4509 | `███████░░░░░░░░ 51%` |
| 6 | `segmentio/kafka-go.makePartitions` | 64.18GB | 3883/4509 | `███████░░░░░░░░ 51%` |
| 7 | `jackskj/carta.getUniqueId` | 57.49GB | 3737/4509 | `██████░░░░░░░░░ 45%` |
| 8 | `reflect.unsafe_New` | 53.87GB | 3501/4509 | `██████░░░░░░░░░ 43%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/4509 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 48.08GB | 3055/4509 | `█████░░░░░░░░░░ 38%` |

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
