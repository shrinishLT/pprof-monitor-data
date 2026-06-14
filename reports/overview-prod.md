# Overview: prod
*Last updated: 2026-06-15 01:40 IST*
*Data range: 2026-05-15T16:03 to 2026-06-15T01:40 (4141 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,317 | avg: 14,694 | max: 84,644 | trend: INCREASING (+2.60/hr))
```
▇▁▁▁▄▂▂▂▃█▃▁▁▂▁▃▁▁▁▁▃▂▁▁▁▁▁▁▄▂▁▁▁▂▂▂▂▁▃▂▂▁▁▁▇▂▂▂▁▁▁▁▄▁▁▆▁▁▁▁▁▁▁▂▂▃▁▆▁▁▂▁▁▂▁▅▁▁▁▃▁▁▁▁▁▁▁▃▁▁▁▁▄▁▃▂
```

**Heap InUse** (current: 259.5MB | avg: 242.1MB | max: 3154.1MB | trend: stable (+0.06MB/hr))
```
▄▃▅▃▅▂▃▂▃▃▃▃▃▃▁▁▄▅▄▁▃▃▂▄▁▂▃▁▄▃▁▄▂▂▆▃▂▃█▂▄▃▁▁▇▅▃▂▁▃▅▂▃▁▃▄▃▅▅▁▄▁▃▄▂▂▃▄▃▁▃▂▂▄▂▅▂▃▄▃▁▄▂▄▂▅▁▄▂▄▄▁▅▄▁▅
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,317 | 14,431 | -114 | 14,694 | 84,644 | INCREASING (+2.60/hr) |
| Heap InUse | 259.5MB | 178.8MB | +80.7MB | 242.1MB | 3154.1MB | stable (+0.06MB/hr) |
| Heap Sys | 2410.7MB | 2411.3MB | -0.6MB | 2529.7MB | 6883.9MB | |
| Heap Objects | 1,653,464 | 416,251 | +1237213 | 1,041,161 | 17,165,538 | |

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
| 2026-06-15 | 21 | 14,250 | 216.4MB | 268.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 32.36MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `compress/flate.NewWriter` | 5.29MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.06MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.01MB |
| 9 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 10 | `bufio.NewWriterSize` | 1.52MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 90.29GB |
| 2 | `segmentio/kafka-go.makePartitions` | 84.49GB |
| 3 | `reflect.growslice` | 78.66GB |
| 4 | `jackskj/carta.getUniqueId` | 72.16GB |
| 5 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 64.94GB |
| 6 | `reflect.unsafe_New` | 62.73GB |
| 7 | `fmt.Sprintf` | 55.45GB |
| 8 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 53.4GB |
| 9 | `fmt.(*buffer).writeString` | 48.95GB |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 47.31GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 3.14GB | 3.14GB | 3.07GB | 0B |
| `evaluation.mergeMetadata` | 1.61GB | 1.61GB | 1.57GB | 0B |
| `local.(*Client).EvaluateV2` | 4.83GB | 4.83GB | 4.72GB | 0B |
| `local.topologicalSort` | 705.80MB | 705.80MB | 689.75MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 4.73GB | 4.72GB | 4.62GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 585.31MB | 585.31MB | 570.87MB | 0B |
| `localEvaluation.getMapOfValue` | 4.73GB | 4.72GB | 4.62GB | 0B |
| `utils.ParseFeatureFlag` | 4.74GB | 4.73GB | 4.63GB | 0B |

**Total FF alloc (current snapshot):** 25.03GB  |  **24h avg:** 24.45GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 43.86MB | 84/4141 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 39.42MB | 115/4141 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3792/4141 | `████████████░░░ 83%` |
| 4 | `runtime.mallocgc` | 31.28MB | 3792/4141 | `██████████░░░░░ 71%` |
| 5 | `database/sql.convertAssignRows` | 22.4MB | 134/4141 | `███████░░░░░░░░ 51%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4141 | `██████░░░░░░░░░ 41%` |
| 7 | `bytes.growSlice` | 15.7MB | 2958/4141 | `█████░░░░░░░░░░ 35%` |
| 8 | `net/http.(*Transport).dialConn` | 13.32MB | 108/4141 | `████░░░░░░░░░░░ 30%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/4141 | `████░░░░░░░░░░░ 26%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4141 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4141 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4141 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4141 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 70.47GB | 2330/4141 | `████████░░░░░░░ 56%` |
| 5 | `reflect.growslice` | 59.91GB | 3353/4141 | `███████░░░░░░░░ 47%` |
| 6 | `segmentio/kafka-go.makePartitions` | 59.84GB | 3515/4141 | `███████░░░░░░░░ 47%` |
| 7 | `jackskj/carta.getUniqueId` | 53.38GB | 3369/4141 | `██████░░░░░░░░░ 42%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/4141 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 50.41GB | 3133/4141 | `██████░░░░░░░░░ 40%` |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 45.9GB | 1498/4141 | `█████░░░░░░░░░░ 36%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.8x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.3x avg)
