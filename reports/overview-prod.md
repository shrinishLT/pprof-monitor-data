# Overview: prod
*Last updated: 2026-06-14 20:26 IST*
*Data range: 2026-05-15T16:03 to 2026-06-14T20:25 (4078 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,146 | avg: 14,700 | max: 84,644 | trend: INCREASING (+2.74/hr))
```
▅▆▆█▆▅▂▂▁▂▁▄▁▁▂▁▁▁▁▁▁▁▂▁▁▂▁▁▁▃▂▁▁▂▃▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▂▂▁▁▁▁▃▃▂▃▁▁▁▂▁▁▁▁▃▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁
```

**Heap InUse** (current: 197.7MB | avg: 242.5MB | max: 3154.1MB | trend: stable (+0.07MB/hr))
```
▄▄▅█▆▄▃▄▅▂▄▆▃▂▃▂▃▂▁▂▃▁▂▃▁▃▄▄▂▄▄▄▂▃▄▃▃▃▄▂▄▃▂▃▄▁▃▅▂▄▄▆▂▁▃▃▁▄▄▃▃▄▃▃▃▄▂▄▂▃▂▃▂▂▂▂▂▁▁▃▄▄▁▃▂▂▃▁▂▃▁▃▂▁▄▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,146 | 14,172 | -26 | 14,700 | 84,644 | INCREASING (+2.74/hr) |
| Heap InUse | 197.7MB | 250.4MB | -52.7MB | 242.5MB | 3154.1MB | stable (+0.07MB/hr) |
| Heap Sys | 2409.1MB | 2409.1MB | +0.0MB | 2531.6MB | 6883.9MB | |
| Heap Objects | 871,283 | 1,461,549 | -590266 | 1,041,974 | 17,165,538 | |

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
| 2026-06-14 | 246 | 16,123 | 273.4MB | 1419.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 32.36MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.01MB |
| 7 | `reflect.mapassign_faststr0` | 2.0MB |
| 8 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 9 | `reflect.unsafe_NewArray` | 1.51MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 1.07MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 90.27GB |
| 2 | `reflect.growslice` | 78.29GB |
| 3 | `segmentio/kafka-go.makePartitions` | 77.34GB |
| 4 | `jackskj/carta.getUniqueId` | 71.93GB |
| 5 | `reflect.unsafe_New` | 62.44GB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 57.73GB |
| 7 | `fmt.Sprintf` | 54.66GB |
| 8 | `fmt.(*buffer).writeString` | 48.83GB |
| 9 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 47.49GB |
| 10 | `carta/value.NewCell` | 45.25GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 2.94GB | 2.93GB | 2.87GB | 0B |
| `evaluation.mergeMetadata` | 1.50GB | 1.50GB | 1.47GB | 0B |
| `local.(*Client).EvaluateV2` | 4.53GB | 4.52GB | 4.41GB | 0B |
| `local.topologicalSort` | 661.79MB | 661.29MB | 645.83MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 4.46GB | 4.46GB | 4.36GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 522.80MB | 521.74MB | 504.32MB | 0B |
| `localEvaluation.getMapOfValue` | 4.46GB | 4.46GB | 4.36GB | 0B |
| `utils.ParseFeatureFlag` | 4.47GB | 4.47GB | 4.37GB | 0B |

**Total FF alloc (current snapshot):** 23.51GB  |  **24h avg:** 22.96GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 44.35MB | 83/4078 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 40.38MB | 112/4078 | `█████████████░░ 91%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3729/4078 | `████████████░░░ 82%` |
| 4 | `runtime.mallocgc` | 31.26MB | 3729/4078 | `██████████░░░░░ 70%` |
| 5 | `database/sql.convertAssignRows` | 22.56MB | 133/4078 | `███████░░░░░░░░ 50%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4078 | `██████░░░░░░░░░ 40%` |
| 7 | `bytes.growSlice` | 15.82MB | 2928/4078 | `█████░░░░░░░░░░ 35%` |
| 8 | `net/http.(*Transport).dialConn` | 13.32MB | 108/4078 | `████░░░░░░░░░░░ 30%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/4078 | `████░░░░░░░░░░░ 26%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4078 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4078 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4078 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4078 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 69.92GB | 2267/4078 | `████████░░░░░░░ 55%` |
| 5 | `reflect.growslice` | 59.56GB | 3290/4078 | `███████░░░░░░░░ 47%` |
| 6 | `segmentio/kafka-go.makePartitions` | 59.45GB | 3452/4078 | `███████░░░░░░░░ 47%` |
| 7 | `jackskj/carta.getUniqueId` | 53.03GB | 3306/4078 | `██████░░░░░░░░░ 42%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/4078 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 50.16GB | 3070/4078 | `██████░░░░░░░░░ 40%` |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 45.9GB | 1498/4078 | `█████░░░░░░░░░░ 36%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.8x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.2x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.3x avg)
