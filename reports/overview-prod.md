# Overview: prod
*Last updated: 2026-06-12 13:37 IST*
*Data range: 2026-05-15T16:03 to 2026-06-12T13:37 (3420 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,395 | avg: 14,432 | max: 84,644 | trend: INCREASING (+3.54/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▄▆▆▆█▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 148.4MB | avg: 239.5MB | max: 3154.1MB | trend: stable (+0.10MB/hr))
```
▁▁▁▁▁▁▁▂▁▂▂▁▁▁▁▁▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▁▁▂▂▂▃▄▄▃▄▇▅█▇▆▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,395 | 16,161 | -1766 | 14,432 | 84,644 | INCREASING (+3.54/hr) |
| Heap InUse | 148.4MB | 220.7MB | -72.3MB | 239.5MB | 3154.1MB | stable (+0.10MB/hr) |
| Heap Sys | 401.8MB | 400.9MB | +0.9MB | 2672.1MB | 6883.9MB | |
| Heap Objects | 580,948 | 747,037 | -166089 | 1,027,889 | 17,165,538 | |

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
| 2026-06-12 | 164 | 16,541 | 297.8MB | 1418.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 4 | `runtime.mallocgc` | 8.01MB |
| 5 | `bytes.growSlice` | 3.01MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.01MB |
| 7 | `compress/flate.NewWriter` | 2.64MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `bufio.NewWriterSize` | 2.02MB |
| 10 | `bufio.NewReaderSize` | 2.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 3.9GB |
| 2 | `jackskj/carta.getUniqueId` | 3.64GB |
| 3 | `reflect.unsafe_New` | 3.12GB |
| 4 | `segmentio/kafka-go.makePartitions` | 2.22GB |
| 5 | `carta/value.NewCell` | 2.21GB |
| 6 | `fmt.(*buffer).writeString` | 2.16GB |
| 7 | `fmt.Sprintf` | 2.12GB |
| 8 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 1.44GB |
| 9 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 1.4GB |
| 10 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 1.23GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 167.60MB | 162.51MB | 6.02GB | 0B |
| `evaluation.mergeMetadata` | 93.02MB | 90.52MB | 3.14GB | 0B |
| `local.(*Client).EvaluateV2` | 247.85MB | 238.12MB | 9.17GB | 0B |
| `local.topologicalSort` | 32.40MB | 29.87MB | 1.28GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 227.93MB | 220.72MB | 8.77GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 38.38MB | 34.83MB | 1.24GB | 0B |
| `localEvaluation.getMapOfValue` | 227.93MB | 220.72MB | 8.77GB | 0B |
| `utils.ParseFeatureFlag` | 228.43MB | 221.22MB | 8.79GB | 0B |

**Total FF alloc (current snapshot):** 1.23GB  |  **24h avg:** 47.19GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 54.78MB | 65/3420 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 47.6MB | 93/3420 | `█████████████░░ 86%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3071/3420 | `██████████░░░░░ 66%` |
| 4 | `runtime.mallocgc` | 32.52MB | 3071/3420 | `████████░░░░░░░ 59%` |
| 5 | `database/sql.convertAssignRows` | 25.59MB | 114/3420 | `███████░░░░░░░░ 46%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3420 | `████░░░░░░░░░░░ 32%` |
| 7 | `bytes.growSlice` | 15.87MB | 2414/3420 | `████░░░░░░░░░░░ 28%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3420 | `███░░░░░░░░░░░░ 25%` |
| 9 | `net/http.(*Transport).dialConn` | 14.04MB | 81/3420 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3420 | `██░░░░░░░░░░░░░ 19%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3420 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3420 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3420 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 72.99GB | 1922/3420 | `████████░░░░░░░ 58%` |
| 5 | `reflect.growslice` | 64.96GB | 2632/3420 | `███████░░░░░░░░ 51%` |
| 6 | `segmentio/kafka-go.makePartitions` | 64.08GB | 2794/3420 | `███████░░░░░░░░ 51%` |
| 7 | `jackskj/carta.getUniqueId` | 57.53GB | 2648/3420 | `██████░░░░░░░░░ 46%` |
| 8 | `reflect.unsafe_New` | 55.5GB | 2412/3420 | `██████░░░░░░░░░ 44%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/3420 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 49.34GB | 2151/3420 | `█████░░░░░░░░░░ 39%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
