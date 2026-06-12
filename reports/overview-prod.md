# Overview: prod
*Last updated: 2026-06-12 14:45 IST*
*Data range: 2026-05-15T16:03 to 2026-06-12T14:45 (3434 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,698 | avg: 14,433 | max: 84,644 | trend: INCREASING (+3.50/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▄▆▆▆█▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 191.0MB | avg: 239.3MB | max: 3154.1MB | trend: stable (+0.10MB/hr))
```
▁▁▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▁▁▂▂▂▃▄▄▃▄▇▅█▇▆▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,698 | 14,783 | -85 | 14,433 | 84,644 | INCREASING (+3.50/hr) |
| Heap InUse | 191.0MB | 220.8MB | -29.8MB | 239.3MB | 3154.1MB | stable (+0.10MB/hr) |
| Heap Sys | 614.1MB | 614.1MB | +0.0MB | 2663.7MB | 6883.9MB | |
| Heap Objects | 1,039,110 | 1,286,866 | -247756 | 1,027,280 | 17,165,538 | |

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
| 2026-06-12 | 178 | 16,398 | 288.8MB | 1418.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 4 | `runtime.mallocgc` | 8.01MB |
| 5 | `bytes.growSlice` | 6.68MB |
| 6 | `compress/flate.NewWriter` | 3.53MB |
| 7 | `segmentio/kafka-go.makePartitions` | 3.01MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 10 | `bufio.NewWriterSize` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 4.04GB |
| 2 | `segmentio/kafka-go.makePartitions` | 3.86GB |
| 3 | `jackskj/carta.getUniqueId` | 3.81GB |
| 4 | `reflect.unsafe_New` | 3.29GB |
| 5 | `fmt.Sprintf` | 3.07GB |
| 6 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 2.44GB |
| 7 | `carta/value.NewCell` | 2.31GB |
| 8 | `fmt.(*buffer).writeString` | 2.31GB |
| 9 | `reflect.unsafe_NewArray` | 1.98GB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 1.93GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 259.90MB | 251.72MB | 2.99GB | 0B |
| `evaluation.mergeMetadata` | 137.03MB | 133.53MB | 1.56GB | 0B |
| `local.(*Client).EvaluateV2` | 396.00MB | 383.66MB | 4.55GB | 0B |
| `local.topologicalSort` | 54.66MB | 53.65MB | 649.93MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 366.35MB | 353.99MB | 4.35GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 58.89MB | 57.89MB | 631.51MB | 0B |
| `localEvaluation.getMapOfValue` | 366.35MB | 353.99MB | 4.35GB | 0B |
| `utils.ParseFeatureFlag` | 367.35MB | 354.49MB | 4.36GB | 512.02kB |

**Total FF alloc (current snapshot):** 1.96GB  |  **24h avg:** 23.41GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 54.78MB | 65/3434 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 47.6MB | 93/3434 | `█████████████░░ 86%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3085/3434 | `██████████░░░░░ 66%` |
| 4 | `runtime.mallocgc` | 32.41MB | 3085/3434 | `████████░░░░░░░ 59%` |
| 5 | `database/sql.convertAssignRows` | 25.45MB | 115/3434 | `██████░░░░░░░░░ 46%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3434 | `████░░░░░░░░░░░ 32%` |
| 7 | `bytes.growSlice` | 15.82MB | 2427/3434 | `████░░░░░░░░░░░ 28%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3434 | `███░░░░░░░░░░░░ 25%` |
| 9 | `net/http.(*Transport).dialConn` | 14.04MB | 81/3434 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3434 | `██░░░░░░░░░░░░░ 19%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3434 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3434 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3434 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 72.99GB | 1922/3434 | `████████░░░░░░░ 58%` |
| 5 | `reflect.growslice` | 64.63GB | 2646/3434 | `███████░░░░░░░░ 51%` |
| 6 | `segmentio/kafka-go.makePartitions` | 63.77GB | 2808/3434 | `███████░░░░░░░░ 50%` |
| 7 | `jackskj/carta.getUniqueId` | 57.25GB | 2662/3434 | `██████░░░░░░░░░ 45%` |
| 8 | `reflect.unsafe_New` | 55.2GB | 2426/3434 | `██████░░░░░░░░░ 44%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/3434 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 49.03GB | 2165/3434 | `█████░░░░░░░░░░ 39%` |

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
