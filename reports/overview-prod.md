# Overview: prod
*Last updated: 2026-06-13 15:56 IST*
*Data range: 2026-05-15T16:03 to 2026-06-13T15:55 (3736 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,105 | avg: 14,604 | max: 84,644 | trend: INCREASING (+3.23/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▃▄▂▄▆▇▇█▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 217.8MB | avg: 240.8MB | max: 3154.1MB | trend: stable (+0.08MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▂▄▆▆▅█▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,105 | 14,081 | +24 | 14,604 | 84,644 | INCREASING (+3.23/hr) |
| Heap InUse | 217.8MB | 181.0MB | +36.8MB | 240.8MB | 3154.1MB | stable (+0.08MB/hr) |
| Heap Sys | 2268.5MB | 2268.5MB | +0.0MB | 2551.9MB | 6883.9MB | |
| Heap Objects | 1,235,208 | 792,103 | +443105 | 1,037,103 | 17,165,538 | |

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
| 2026-06-13 | 192 | 17,003 | 282.0MB | 1566.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 30.86MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `compress/flate.NewWriter` | 5.29MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 8 | `segmentio/kafka-go.makePartitions` | 1.5MB |
| 9 | `bufio.NewWriterSize` | 1.03MB |
| 10 | `aws/endpoints.init` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 39.82GB |
| 2 | `segmentio/kafka-go.makePartitions` | 38.21GB |
| 3 | `jackskj/carta.getUniqueId` | 35.83GB |
| 4 | `reflect.unsafe_New` | 31.98GB |
| 5 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 25.2GB |
| 6 | `fmt.Sprintf` | 24.57GB |
| 7 | `fmt.(*buffer).writeString` | 23.44GB |
| 8 | `carta/value.NewCell` | 23.19GB |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 21.88GB |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 21.07GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.84GB | 1.84GB | 1.76GB | 0B |
| `evaluation.mergeMetadata` | 977.74MB | 977.24MB | 938.58MB | 0B |
| `local.(*Client).EvaluateV2` | 2.83GB | 2.83GB | 2.71GB | 0B |
| `local.topologicalSort` | 405.59MB | 404.58MB | 388.34MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.74GB | 2.74GB | 2.62GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 360.94MB | 360.94MB | 351.69MB | 0B |
| `localEvaluation.getMapOfValue` | 2.74GB | 2.74GB | 2.62GB | 0B |
| `utils.ParseFeatureFlag` | 2.75GB | 2.75GB | 2.63GB | 0B |

**Total FF alloc (current snapshot):** 14.61GB  |  **24h avg:** 13.99GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 48.84MB | 74/3736 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 44.19MB | 101/3736 | `█████████████░░ 90%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3387/3736 | `███████████░░░░ 75%` |
| 4 | `runtime.mallocgc` | 31.25MB | 3387/3736 | `█████████░░░░░░ 63%` |
| 5 | `database/sql.convertAssignRows` | 23.7MB | 125/3736 | `███████░░░░░░░░ 48%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3736 | `█████░░░░░░░░░░ 36%` |
| 7 | `bytes.growSlice` | 15.96MB | 2676/3736 | `████░░░░░░░░░░░ 32%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 13.5MB | 5/3736 | `████░░░░░░░░░░░ 27%` |
| 9 | `net/http.(*Transport).dialConn` | 13.43MB | 99/3736 | `████░░░░░░░░░░░ 27%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3736 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3736 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3736 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3736 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 71.29GB | 1987/3736 | `████████░░░░░░░ 57%` |
| 5 | `reflect.growslice` | 59.8GB | 2948/3736 | `███████░░░░░░░░ 47%` |
| 6 | `segmentio/kafka-go.makePartitions` | 59.63GB | 3110/3736 | `███████░░░░░░░░ 47%` |
| 7 | `jackskj/carta.getUniqueId` | 53.06GB | 2964/3736 | `██████░░░░░░░░░ 42%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/3736 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 50.68GB | 2728/3736 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 46.97GB | 2310/3736 | `█████░░░░░░░░░░ 37%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.8x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.3x avg)
