# Overview: prod
*Last updated: 2026-06-17 21:11 IST*
*Data range: 2026-05-15T16:03 to 2026-06-17T21:11 (4947 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,343 | avg: 14,957 | max: 84,644 | trend: INCREASING (+2.06/hr))
```
▁▂▂▂▂▂▇▃▃▂▁▄▃▂▂▁▂▃▂▂▂▂▂▂▂▁▁▄▂▂▁▁▁▁▂▂▁▁▁▁▂▂▁▃▄▅▄▃▃▃▂▁▂▂▆▅▄▅▅▅▂▂▁▁▁▁▁▁▁▁▅█▄▂▃▂▁▁▂▁▂▂▂▁▃▁▁▂▃▁▁▁▁▁▁▁
```

**Heap InUse** (current: 209.0MB | avg: 246.3MB | max: 3154.1MB | trend: stable (+0.05MB/hr))
```
▂▃▂▃▂▃█▄▃▂▂▃▂▂▂▂▄▃▃▂▂▂▁▂▂▂▁▃▂▃▁▂▄▁▁▂▁▁▂▁▂▂▃▃▃▅▃▂▃▃▂▃▁▂▅▅▄▄▅▅▂▃▁▁▁▁▁▁▂▁▃▆▄▃▂▃▁▁▂▁▂▂▂▁▃▂▁▂▄▂▂▁▂▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,343 | 14,537 | -194 | 14,957 | 84,644 | INCREASING (+2.06/hr) |
| Heap InUse | 209.0MB | 196.0MB | +13.0MB | 246.3MB | 3154.1MB | stable (+0.05MB/hr) |
| Heap Sys | 2229.8MB | 2229.2MB | +0.6MB | 2419.1MB | 6883.9MB | |
| Heap Objects | 994,692 | 665,250 | +329442 | 1,055,412 | 17,165,538 | |

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
| 2026-06-16 | 286 | 16,159 | 253.2MB | 1286.4MB |
| 2026-06-17 | 255 | 16,490 | 263.2MB | 1186.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 30.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `segmentio/kafka-go.makePartitions` | 4.51MB |
| 5 | `bytes.growSlice` | 4.02MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.85MB |
| 8 | `compress/flate.NewWriter` | 2.64MB |
| 9 | `bufio.NewReaderSize` | 2.54MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 46.26GB |
| 2 | `reflect.growslice` | 41.37GB |
| 3 | `jackskj/carta.getUniqueId` | 39.0GB |
| 4 | `fmt.Sprintf` | 35.92GB |
| 5 | `reflect.unsafe_New` | 33.94GB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 28.06GB |
| 7 | `fmt.(*buffer).writeString` | 25.71GB |
| 8 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 24.69GB |
| 9 | `carta/value.NewCell` | 23.9GB |
| 10 | `reflect.unsafe_NewArray` | 23.86GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 3.25GB | 3.24GB | 2.97GB | 0B |
| `evaluation.mergeMetadata` | 1.67GB | 1.67GB | 1.52GB | 0B |
| `local.(*Client).EvaluateV2` | 4.92GB | 4.91GB | 4.51GB | 0B |
| `local.topologicalSort` | 694.95MB | 693.93MB | 632.31MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 4.68GB | 4.67GB | 4.31GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 721.66MB | 721.66MB | 641.66MB | 0B |
| `localEvaluation.getMapOfValue` | 4.68GB | 4.67GB | 4.31GB | 0B |
| `utils.ParseFeatureFlag` | 4.69GB | 4.68GB | 4.32GB | 0B |

**Total FF alloc (current snapshot):** 25.27GB  |  **24h avg:** 23.17GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 37.25MB | 105/4947 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 4598/4947 | `██████████████░ 98%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 34.39MB | 140/4947 | `█████████████░░ 92%` |
| 4 | `runtime.mallocgc` | 30.29MB | 4598/4947 | `████████████░░░ 81%` |
| 5 | `database/sql.convertAssignRows` | 19.66MB | 164/4947 | `███████░░░░░░░░ 52%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4947 | `███████░░░░░░░░ 48%` |
| 7 | `bytes.growSlice` | 15.75MB | 3665/4947 | `██████░░░░░░░░░ 42%` |
| 8 | `net/http.(*Transport).dialConn` | 13.27MB | 138/4947 | `█████░░░░░░░░░░ 35%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 10.86MB | 7/4947 | `████░░░░░░░░░░░ 29%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4947 | `████░░░░░░░░░░░ 28%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4947 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4947 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4947 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 73.48GB | 2864/4947 | `████████░░░░░░░ 58%` |
| 5 | `segmentio/kafka-go.makePartitions` | 60.83GB | 4321/4947 | `███████░░░░░░░░ 48%` |
| 6 | `reflect.growslice` | 60.53GB | 4159/4947 | `███████░░░░░░░░ 48%` |
| 7 | `jackskj/carta.getUniqueId` | 54.17GB | 4175/4947 | `██████░░░░░░░░░ 43%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/4947 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 50.39GB | 3939/4947 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 45.87GB | 3350/4947 | `█████░░░░░░░░░░ 36%` |

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
