# Overview: prod
*Last updated: 2026-06-15 13:21 IST*
*Data range: 2026-05-15T16:03 to 2026-06-15T13:20 (4281 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,425 | avg: 14,758 | max: 84,644 | trend: INCREASING (+2.53/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▃▅▆▇█▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 198.1MB | avg: 243.5MB | max: 3154.1MB | trend: stable (+0.06MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▃▄▄▆▆█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,425 | 14,968 | -543 | 14,758 | 84,644 | INCREASING (+2.53/hr) |
| Heap InUse | 198.1MB | 262.5MB | -64.4MB | 243.5MB | 3154.1MB | stable (+0.06MB/hr) |
| Heap Sys | 2400.2MB | 2399.8MB | +0.4MB | 2525.5MB | 6883.9MB | |
| Heap Objects | 697,076 | 1,000,267 | -303191 | 1,045,645 | 17,165,538 | |

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
| 2026-06-15 | 161 | 16,338 | 276.2MB | 1342.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 32.36MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `bytes.growSlice` | 4.03MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `bufio.NewWriterSize` | 2.02MB |
| 8 | `reflect.mapassign_faststr0` | 2.0MB |
| 9 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 10 | `segmentio/kafka-go.makePartitions` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 109.06GB |
| 2 | `reflect.growslice` | 108.22GB |
| 3 | `segmentio/kafka-go.makePartitions` | 100.43GB |
| 4 | `jackskj/carta.getUniqueId` | 97.77GB |
| 5 | `reflect.unsafe_New` | 85.74GB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 76.84GB |
| 7 | `fmt.Sprintf` | 67.71GB |
| 8 | `fmt.(*buffer).writeString` | 66.67GB |
| 9 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 63.14GB |
| 10 | `carta/value.NewCell` | 62.1GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 3.84GB | 3.83GB | 3.65GB | 0B |
| `evaluation.mergeMetadata` | 1.99GB | 1.98GB | 1.89GB | 0B |
| `local.(*Client).EvaluateV2` | 5.89GB | 5.88GB | 5.62GB | 0B |
| `local.topologicalSort` | 850.48MB | 849.46MB | 813.05MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 5.81GB | 5.80GB | 5.55GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 679.43MB | 676.36MB | 638.42MB | 0B |
| `localEvaluation.getMapOfValue` | 5.81GB | 5.80GB | 5.55GB | 0B |
| `utils.ParseFeatureFlag` | 5.82GB | 5.81GB | 5.56GB | 0B |

**Total FF alloc (current snapshot):** 30.65GB  |  **24h avg:** 29.22GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 42.64MB | 87/4281 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 37.69MB | 121/4281 | `█████████████░░ 88%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3932/4281 | `████████████░░░ 85%` |
| 4 | `runtime.mallocgc` | 31.32MB | 3932/4281 | `███████████░░░░ 73%` |
| 5 | `database/sql.convertAssignRows` | 21.35MB | 142/4281 | `███████░░░░░░░░ 50%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4281 | `██████░░░░░░░░░ 42%` |
| 7 | `bytes.growSlice` | 15.84MB | 3055/4281 | `█████░░░░░░░░░░ 37%` |
| 8 | `net/http.(*Transport).dialConn` | 13.44MB | 116/4281 | `████░░░░░░░░░░░ 31%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/4281 | `████░░░░░░░░░░░ 27%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4281 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4281 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4281 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4281 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 72.05GB | 2470/4281 | `████████░░░░░░░ 57%` |
| 5 | `reflect.growslice` | 61.19GB | 3493/4281 | `███████░░░░░░░░ 48%` |
| 6 | `segmentio/kafka-go.makePartitions` | 61.09GB | 3655/4281 | `███████░░░░░░░░ 48%` |
| 7 | `jackskj/carta.getUniqueId` | 54.56GB | 3509/4281 | `██████░░░░░░░░░ 43%` |
| 8 | `reflect.unsafe_New` | 51.37GB | 3273/4281 | `██████░░░░░░░░░ 41%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/4281 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 46.32GB | 2827/4281 | `█████░░░░░░░░░░ 37%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.7x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.2x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (3.9x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.3x avg)
