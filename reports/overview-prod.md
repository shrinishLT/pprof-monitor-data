# Overview: prod
*Last updated: 2026-06-11 04:46 IST*
*Data range: 2026-05-15T16:03 to 2026-06-11T04:45 (3026 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,002 | avg: 14,140 | max: 84,644 | trend: INCREASING (+3.79/hr))
```
▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▅█▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▄▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▂▁
```

**Heap InUse** (current: 296.2MB | avg: 229.8MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▁▂▄▂▃▂▄▃▂▁▁▁▁▂▃▂▁▁▂▃▂▁▁▂▃▃▂▁▁▅█▆▂▃▂▃▁▂▂▂▂▁▂▁▁▂▂▂▂▂▃▂▂▂▂▂▂▁▁▁▁▃▃▃▂▁▁▁▂▂▁▁▂▁▂▂▃▂▅▃▂▂▂▂▂▁▁▂▃▁▂▁▂▂▂▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,002 | 15,660 | -658 | 14,140 | 84,644 | INCREASING (+3.79/hr) |
| Heap InUse | 296.2MB | 267.7MB | +28.5MB | 229.8MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3344.3MB | 3343.7MB | +0.6MB | 2608.0MB | 6883.9MB | |
| Heap Objects | 984,406 | 864,067 | +120339 | 992,769 | 17,165,538 | |

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
| 2026-06-11 | 58 | 14,895 | 268.4MB | 428.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 12.74MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 6 | `bufio.NewWriterSize` | 4.53MB |
| 7 | `fmt.(*buffer).writeString` | 3.51MB |
| 8 | `bufio.NewReaderSize` | 3.04MB |
| 9 | `segmentio/kafka-go.makePartitions` | 3.02MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 152.72GB |
| 2 | `reflect.growslice` | 145.64GB |
| 3 | `jackskj/carta.getUniqueId` | 132.06GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 117.31GB |
| 5 | `reflect.unsafe_New` | 116.55GB |
| 6 | `fmt.Sprintf` | 107.21GB |
| 7 | `fmt.(*buffer).writeString` | 91.6GB |
| 8 | `carta/value.NewCell` | 83.16GB |
| 9 | `reflect.unsafe_NewArray` | 78.05GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 65.88GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 8.04GB | 8.04GB | 7.90GB | 0B |
| `evaluation.mergeMetadata` | 4.21GB | 4.21GB | 4.14GB | 0B |
| `local.(*Client).EvaluateV2` | 12.26GB | 12.25GB | 12.05GB | 0B |
| `local.topologicalSort` | 1.69GB | 1.69GB | 1.67GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 11.69GB | 11.68GB | 11.47GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.69GB | 1.69GB | 1.67GB | 0B |
| `localEvaluation.getMapOfValue` | 11.69GB | 11.68GB | 11.47GB | 0B |
| `utils.ParseFeatureFlag` | 11.71GB | 11.70GB | 11.49GB | 0B |

**Total FF alloc (current snapshot):** 62.98GB  |  **24h avg:** 61.87GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.39MB | 56/3026 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 52.2MB | 84/3026 | `████████████░░░ 83%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2677/3026 | `████████░░░░░░░ 58%` |
| 4 | `runtime.mallocgc` | 30.21MB | 2677/3026 | `███████░░░░░░░░ 48%` |
| 5 | `database/sql.convertAssignRows` | 27.21MB | 106/3026 | `██████░░░░░░░░░ 43%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3026 | `████░░░░░░░░░░░ 28%` |
| 7 | `bytes.growSlice` | 15.38MB | 2075/3026 | `███░░░░░░░░░░░░ 24%` |
| 8 | `net/http.(*Transport).dialConn` | 14.4MB | 61/3026 | `███░░░░░░░░░░░░ 23%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3026 | `███░░░░░░░░░░░░ 22%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3026 | `██░░░░░░░░░░░░░ 16%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3026 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3026 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3026 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 56.45GB | 1543/3026 | `██████░░░░░░░░░ 45%` |
| 5 | `experiment/local.topologicalSort` | 51.23GB | 375/3026 | `██████░░░░░░░░░ 40%` |
| 6 | `segmentio/kafka-go.makePartitions` | 47.51GB | 2400/3026 | `█████░░░░░░░░░░ 37%` |
| 7 | `reflect.growslice` | 46.69GB | 2238/3026 | `█████░░░░░░░░░░ 37%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/3026 | `█████░░░░░░░░░░ 34%` |
| 9 | `jackskj/carta.getUniqueId` | 40.88GB | 2254/3026 | `████░░░░░░░░░░░ 32%` |
| 10 | `reflect.unsafe_New` | 40.03GB | 2018/3026 | `████░░░░░░░░░░░ 32%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.2x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.7x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.4x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
