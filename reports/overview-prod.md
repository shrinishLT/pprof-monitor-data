# Overview: prod
*Last updated: 2026-06-13 08:06 IST*
*Data range: 2026-05-15T16:03 to 2026-06-13T08:06 (3642 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,829 | avg: 14,532 | max: 84,644 | trend: INCREASING (+3.24/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▃▃▃▄▃▄▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▄▄▃▂▂▂▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 219.1MB | avg: 239.4MB | max: 3154.1MB | trend: stable (+0.09MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▃▄▄▃▃▃▄▂▂▁▁▁▁▁▁▂▁▁▁▁▁▁▁█▃▄▄▂▃▂▁▁▁▁▁▁▁▁▂▃▁▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,829 | 14,465 | +364 | 14,532 | 84,644 | INCREASING (+3.24/hr) |
| Heap InUse | 219.1MB | 196.0MB | +23.1MB | 239.4MB | 3154.1MB | stable (+0.09MB/hr) |
| Heap Sys | 1423.4MB | 1424.5MB | -1.1MB | 2569.8MB | 6883.9MB | |
| Heap Objects | 1,162,290 | 847,555 | +314735 | 1,030,249 | 17,165,538 | |

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
| 2026-06-13 | 98 | 16,639 | 271.6MB | 1133.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 23.22MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `bytes.growSlice` | 5.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 5.01MB |
| 7 | `compress/flate.NewWriter` | 3.53MB |
| 8 | `bufio.NewWriterSize` | 2.51MB |
| 9 | `reflect.mapassign_faststr0` | 2.5MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 27.56GB |
| 2 | `reflect.growslice` | 23.49GB |
| 3 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 20.9GB |
| 4 | `jackskj/carta.getUniqueId` | 20.86GB |
| 5 | `reflect.unsafe_New` | 18.76GB |
| 6 | `fmt.Sprintf` | 18.57GB |
| 7 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 17.2GB |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 16.09GB |
| 9 | `reflect.unsafe_NewArray` | 14.08GB |
| 10 | `fmt.(*buffer).writeString` | 13.81GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.54GB | 1.53GB | 1.44GB | 0B |
| `evaluation.mergeMetadata` | 807.70MB | 804.69MB | 756.87MB | 0B |
| `local.(*Client).EvaluateV2` | 2.36GB | 2.36GB | 2.22GB | 0B |
| `local.topologicalSort` | 340.24MB | 340.24MB | 320.48MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.26GB | 2.25GB | 2.11GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 331.40MB | 331.40MB | 321.18MB | 0B |
| `localEvaluation.getMapOfValue` | 2.26GB | 2.25GB | 2.11GB | 0B |
| `utils.ParseFeatureFlag` | 2.26GB | 2.26GB | 2.11GB | 0B |

**Total FF alloc (current snapshot):** 12.12GB  |  **24h avg:** 11.36GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 50.02MB | 72/3642 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.39MB | 98/3642 | `█████████████░░ 90%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3293/3642 | `██████████░░░░░ 73%` |
| 4 | `runtime.mallocgc` | 31.33MB | 3293/3642 | `█████████░░░░░░ 62%` |
| 5 | `database/sql.convertAssignRows` | 24.18MB | 122/3642 | `███████░░░░░░░░ 48%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3642 | `█████░░░░░░░░░░ 35%` |
| 7 | `bytes.growSlice` | 15.76MB | 2607/3642 | `████░░░░░░░░░░░ 31%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3642 | `████░░░░░░░░░░░ 28%` |
| 9 | `net/http.(*Transport).dialConn` | 13.41MB | 90/3642 | `████░░░░░░░░░░░ 26%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3642 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3642 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3642 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3642 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 72.96GB | 1923/3642 | `████████░░░░░░░ 58%` |
| 5 | `reflect.growslice` | 60.67GB | 2854/3642 | `███████░░░░░░░░ 48%` |
| 6 | `segmentio/kafka-go.makePartitions` | 60.46GB | 3016/3642 | `███████░░░░░░░░ 48%` |
| 7 | `jackskj/carta.getUniqueId` | 53.82GB | 2870/3642 | `██████░░░░░░░░░ 43%` |
| 8 | `reflect.unsafe_New` | 51.52GB | 2634/3642 | `██████░░░░░░░░░ 41%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/3642 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 48.13GB | 2216/3642 | `█████░░░░░░░░░░ 38%` |

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
