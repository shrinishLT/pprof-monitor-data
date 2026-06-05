# Overview: prod
*Last updated: 2026-06-05 11:50 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T11:50 (1385 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,307 | avg: 12,023 | max: 84,644 | trend: decreasing (-1.93/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▅▃▄▆▆█▆▅▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 146.0MB | avg: 184.8MB | max: 3154.1MB | trend: stable (+0.01MB/hr))
```
▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▃▃▄▄▅▄▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,307 | 14,585 | -278 | 12,023 | 84,644 | decreasing (-1.93/hr) |
| Heap InUse | 146.0MB | 158.2MB | -12.2MB | 184.8MB | 3154.1MB | stable (+0.01MB/hr) |
| Heap Sys | 841.4MB | 841.8MB | -0.4MB | 2703.7MB | 6883.9MB | |
| Heap Objects | 787,737 | 805,109 | -17372 | 820,528 | 17,165,538 | |

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
| 2026-06-05 | 143 | 16,740 | 276.7MB | 3154.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 9.58MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `compress/flate.NewWriter` | 5.29MB |
| 6 | `reflect.unsafe_NewArray` | 2.51MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `compress/flate.(*compressor).initDeflate` | 2.13MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 1.67GB |
| 2 | `reflect.growslice` | 1.27GB |
| 3 | `jackskj/carta.getUniqueId` | 1.08GB |
| 4 | `reflect.unsafe_New` | 887.9MB |
| 5 | `fmt.(*buffer).writeString` | 878.34MB |
| 6 | `carta/value.NewCell` | 683.55MB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 670.4MB |
| 8 | `segmentio/kafka-go.makePartitions` | 621.58MB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 413.01MB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 357.99MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 41.91MB | 39.91MB | 174.94MB | 0B |
| `evaluation.mergeMetadata` | 20.00MB | 18.50MB | 89.47MB | 0B |
| `local.(*Client).EvaluateV2` | 69.82MB | 63.71MB | 261.05MB | 0B |
| `local.topologicalSort` | 10.60MB | 8.57MB | 35.03MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 72.92MB | 65.78MB | 272.96MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 3.56MB | 3.56MB | 15.47MB | 0B |
| `localEvaluation.getMapOfValue` | 72.92MB | 65.78MB | 272.96MB | 0B |
| `utils.ParseFeatureFlag` | 72.92MB | 65.78MB | 272.96MB | 0B |

**Total FF alloc (current snapshot):** 364.66MB  |  **24h avg:** 1.36GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 94.56MB | 31/1385 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 76.85MB | 51/1385 | `████████████░░░ 81%` |
| 3 | `database/sql.convertAssignRows` | 39.77MB | 64/1385 | `██████░░░░░░░░░ 42%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1036/1385 | `█████░░░░░░░░░░ 38%` |
| 5 | `runtime.mallocgc` | 18.05MB | 1036/1385 | `██░░░░░░░░░░░░░ 19%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1385 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `bytes.growSlice` | 15.46MB | 798/1385 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1385 | `█░░░░░░░░░░░░░░ 13%` |
| 9 | `net/http.(*Transport).dialConn` | 12.06MB | 24/1385 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1385 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1385 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1385 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1385 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1385 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1385 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 33.55GB | 1007/1385 | `████░░░░░░░░░░░ 26%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1385 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.96GB | 919/1385 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.49GB | 203/1385 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `fmt.Sprintf` | 9.32GB | 579/1385 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.0x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.6x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.3x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.7x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.6x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.6x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.2x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.3x avg)
- Goroutine spike to 25,220 at 2026-05-20T02:02 (2.1x avg)
