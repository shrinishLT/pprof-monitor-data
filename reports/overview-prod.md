# Overview: prod
*Last updated: 2026-06-13 21:31 IST*
*Data range: 2026-05-15T16:03 to 2026-06-13T21:30 (3803 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,261 | avg: 14,598 | max: 84,644 | trend: INCREASING (+3.04/hr))
```
▂▂▄▂▁▁▂▂▁▁▃▃▂▁▂▂▅▃▂▇▁▁▂▁▂▁▂▁▁▃▃▁▁▁▁▁▇▁▁▁▁▁▂▁▁▁▃▁▃▁▁▃▄▁▄▃▂▅█▁▁▁▄▁▁▁▂▁▁▁▄▄▁▁▁▁▁▃▂▁▁▁▁▄▂▂▁▁▁▁▁▁▁▃▂▂
```

**Heap InUse** (current: 203.8MB | avg: 240.2MB | max: 3154.1MB | trend: stable (+0.08MB/hr))
```
▃▂▄▃▅▂▅▆▄▃▅▂▁▄▅▄▅▆▂▇▅▂▂▅▄▆▄▂▄▄▇▂▃▄▆▁▄▁▆▂▃▅▄▁▃▁▄▅▇▂▃▂▆▃▃▄▂▄▄▃▂▃▃▂▄▂▆▆▁▅█▃▁▂▅▅▁▅▃▄▂▂▃▄▂▆▅▅▁▁▆▁▃▆▃▃
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,261 | 14,383 | -122 | 14,598 | 84,644 | INCREASING (+3.04/hr) |
| Heap InUse | 203.8MB | 200.3MB | +3.5MB | 240.2MB | 3154.1MB | stable (+0.08MB/hr) |
| Heap Sys | 2273.2MB | 2273.8MB | -0.6MB | 2546.9MB | 6883.9MB | |
| Heap Objects | 972,526 | 884,135 | +88391 | 1,036,335 | 17,165,538 | |

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
| 2026-06-13 | 259 | 16,298 | 263.3MB | 1566.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 30.86MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 9 | `reflect.unsafe_NewArray` | 1.01MB |
| 10 | `encoding/json.(*decodeState).objectInterface` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 45.75GB |
| 2 | `reflect.growslice` | 40.0GB |
| 3 | `jackskj/carta.getUniqueId` | 35.9GB |
| 4 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 33.1GB |
| 5 | `reflect.unsafe_New` | 32.12GB |
| 6 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 27.24GB |
| 7 | `fmt.Sprintf` | 25.37GB |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 24.43GB |
| 9 | `fmt.(*buffer).writeString` | 23.49GB |
| 10 | `reflect.unsafe_NewArray` | 23.45GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 2.00GB | 2.00GB | 1.94GB | 0B |
| `evaluation.mergeMetadata` | 1.03GB | 1.03GB | 1.00GB | 0B |
| `local.(*Client).EvaluateV2` | 3.07GB | 3.07GB | 2.99GB | 0B |
| `local.topologicalSort` | 438.54MB | 438.54MB | 425.56MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.99GB | 2.99GB | 2.90GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 384.34MB | 384.34MB | 377.02MB | 0B |
| `localEvaluation.getMapOfValue` | 2.99GB | 2.99GB | 2.90GB | 0B |
| `utils.ParseFeatureFlag` | 2.99GB | 2.99GB | 2.91GB | 0B |

**Total FF alloc (current snapshot):** 15.86GB  |  **24h avg:** 15.44GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 48.23MB | 75/3803 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 42.62MB | 105/3803 | `█████████████░░ 88%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3454/3803 | `███████████░░░░ 75%` |
| 4 | `runtime.mallocgc` | 31.24MB | 3454/3803 | `█████████░░░░░░ 64%` |
| 5 | `database/sql.convertAssignRows` | 23.7MB | 125/3803 | `███████░░░░░░░░ 49%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3803 | `█████░░░░░░░░░░ 37%` |
| 7 | `bytes.growSlice` | 15.79MB | 2713/3803 | `████░░░░░░░░░░░ 32%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 13.5MB | 5/3803 | `████░░░░░░░░░░░ 27%` |
| 9 | `net/http.(*Transport).dialConn` | 13.43MB | 99/3803 | `████░░░░░░░░░░░ 27%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3803 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3803 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3803 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3803 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 70.87GB | 2004/3803 | `████████░░░░░░░ 56%` |
| 5 | `reflect.growslice` | 59.36GB | 3015/3803 | `███████░░░░░░░░ 47%` |
| 6 | `segmentio/kafka-go.makePartitions` | 59.26GB | 3177/3803 | `███████░░░░░░░░ 47%` |
| 7 | `jackskj/carta.getUniqueId` | 52.68GB | 3031/3803 | `██████░░░░░░░░░ 42%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/3803 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 50.23GB | 2795/3803 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 46.31GB | 2377/3803 | `█████░░░░░░░░░░ 37%` |

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
