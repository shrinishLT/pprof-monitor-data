# Overview: prod
*Last updated: 2026-06-13 21:20 IST*
*Data range: 2026-05-15T16:03 to 2026-06-13T21:20 (3801 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,482 | avg: 14,598 | max: 84,644 | trend: INCREASING (+3.05/hr))
```
▃▁▂▂▄▂▁▁▂▂▁▁▃▃▂▁▂▂▅▃▂▇▁▁▂▁▂▁▂▁▁▃▃▁▁▁▁▁▇▁▁▁▁▁▂▁▁▁▃▁▃▁▁▃▄▁▄▃▂▅█▁▁▁▄▁▁▁▂▁▁▁▄▄▁▁▁▁▁▃▂▁▁▁▁▄▂▂▁▁▁▁▁▁▁▃
```

**Heap InUse** (current: 257.3MB | avg: 240.3MB | max: 3154.1MB | trend: stable (+0.08MB/hr))
```
▂▂▃▂▄▃▅▂▅▆▄▃▅▂▁▄▅▄▅▆▂▇▅▂▂▅▄▆▄▂▄▄▇▂▃▄▆▁▄▁▆▂▃▅▄▁▃▁▄▅▇▂▃▂▆▃▃▄▂▄▄▃▂▃▃▂▄▂▆▆▁▅█▃▁▂▅▅▁▅▃▄▂▂▃▄▂▆▅▅▁▁▆▁▃▆
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,482 | 14,080 | +402 | 14,598 | 84,644 | INCREASING (+3.05/hr) |
| Heap InUse | 257.3MB | 205.2MB | +52.1MB | 240.3MB | 3154.1MB | stable (+0.08MB/hr) |
| Heap Sys | 2273.3MB | 2273.8MB | -0.5MB | 2547.1MB | 6883.9MB | |
| Heap Objects | 1,191,198 | 1,194,109 | -2911 | 1,036,392 | 17,165,538 | |

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
| 2026-06-13 | 257 | 16,313 | 263.7MB | 1566.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 30.86MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.54MB |
| 6 | `bytes.growSlice` | 3.53MB |
| 7 | `compress/flate.NewWriter` | 3.53MB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 3.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 45.55GB |
| 2 | `reflect.growslice` | 40.0GB |
| 3 | `jackskj/carta.getUniqueId` | 35.9GB |
| 4 | `reflect.unsafe_New` | 32.12GB |
| 5 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 31.71GB |
| 6 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 26.1GB |
| 7 | `fmt.Sprintf` | 25.33GB |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 24.29GB |
| 9 | `fmt.(*buffer).writeString` | 23.49GB |
| 10 | `reflect.unsafe_NewArray` | 23.35GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.99GB | 1.99GB | 1.94GB | 0B |
| `evaluation.mergeMetadata` | 1.03GB | 1.03GB | 1.00GB | 0B |
| `local.(*Client).EvaluateV2` | 3.07GB | 3.06GB | 2.98GB | 0B |
| `local.topologicalSort` | 438.02MB | 438.02MB | 424.40MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.98GB | 2.98GB | 2.90GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 383.84MB | 383.84MB | 376.24MB | 0B |
| `localEvaluation.getMapOfValue` | 2.98GB | 2.98GB | 2.90GB | 0B |
| `utils.ParseFeatureFlag` | 2.99GB | 2.99GB | 2.90GB | 0B |

**Total FF alloc (current snapshot):** 15.84GB  |  **24h avg:** 15.40GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 48.23MB | 75/3801 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 42.62MB | 105/3801 | `█████████████░░ 88%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3452/3801 | `███████████░░░░ 75%` |
| 4 | `runtime.mallocgc` | 31.24MB | 3452/3801 | `█████████░░░░░░ 64%` |
| 5 | `database/sql.convertAssignRows` | 23.7MB | 125/3801 | `███████░░░░░░░░ 49%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3801 | `█████░░░░░░░░░░ 37%` |
| 7 | `bytes.growSlice` | 15.79MB | 2712/3801 | `████░░░░░░░░░░░ 32%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 13.5MB | 5/3801 | `████░░░░░░░░░░░ 27%` |
| 9 | `net/http.(*Transport).dialConn` | 13.43MB | 99/3801 | `████░░░░░░░░░░░ 27%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3801 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3801 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3801 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3801 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 70.87GB | 2004/3801 | `████████░░░░░░░ 56%` |
| 5 | `reflect.growslice` | 59.37GB | 3013/3801 | `███████░░░░░░░░ 47%` |
| 6 | `segmentio/kafka-go.makePartitions` | 59.27GB | 3175/3801 | `███████░░░░░░░░ 47%` |
| 7 | `jackskj/carta.getUniqueId` | 52.69GB | 3029/3801 | `██████░░░░░░░░░ 42%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/3801 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 50.24GB | 2793/3801 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 46.33GB | 2375/3801 | `█████░░░░░░░░░░ 37%` |

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
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.3x avg)
