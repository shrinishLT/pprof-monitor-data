# Overview: prod
*Last updated: 2026-06-04 06:20 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T06:20 (1031 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,675 | avg: 10,366 | max: 84,644 | trend: decreasing (-30.66/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▄▁▅▅▅▅▅▅▄▅▅▅▅▄▄▄▄▄▅▅▅▅▅▅▄█▆▄▅▄▅▅▅▅▅▅▅▅▄▅▅▅▅▅▄▄▅▄▅▆▅▅▅▅▅▅▅▅▅▅▅▆▅▆▇▅▅▄▅▆▅▅▅▅▅▅▅▅▄▄▄▅▅▅▅
```

**Heap InUse** (current: 361.5MB | avg: 155.2MB | max: 2823.8MB | trend: stable (-0.44MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,675 | 15,569 | -894 | 10,366 | 84,644 | decreasing (-30.66/hr) |
| Heap InUse | 361.5MB | 207.4MB | +154.1MB | 155.2MB | 2823.8MB | stable (-0.44MB/hr) |
| Heap Sys | 2250.3MB | 2250.6MB | -0.3MB | 2547.1MB | 6883.9MB | |
| Heap Objects | 2,008,096 | 809,383 | +1198713 | 664,949 | 14,090,816 | |

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
| 2026-06-04 | 77 | 15,535 | 260.3MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 82.24MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `database/sql.convertAssignRows` | 21.0MB |
| 4 | `runtime.mallocgc` | 12.6MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `bytes.growSlice` | 5.53MB |
| 7 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 5.05MB |
| 8 | `segmentio/kafka-go.makePartitions` | 4.51MB |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 10 | `compress/flate.NewWriter` | 3.53MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 19.61GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 7.79GB |
| 3 | `reflect.growslice` | 6.11GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 6.02GB |
| 5 | `jackskj/carta.getUniqueId` | 4.86GB |
| 6 | `reflect.unsafe_New` | 4.48GB |
| 7 | `fmt.(*buffer).writeString` | 3.61GB |
| 8 | `go-sql-driver/mysql.(*binaryRows).readRow` | 3.21GB |
| 9 | `carta/value.NewCell` | 3.16GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 2.81GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 56.72MB | 51.14MB | 76.27MB | 0B |
| `evaluation.mergeMetadata` | 32.51MB | 30.01MB | 40.24MB | 0B |
| `local.(*Client).EvaluateV2` | 82.20MB | 74.01MB | 116.43MB | 0B |
| `local.topologicalSort` | 8.08MB | 7.08MB | 17.84MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 82.64MB | 73.44MB | 113.81MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 11.81MB | 11.81MB | 10.61MB | 0B |
| `localEvaluation.getMapOfValue` | 82.64MB | 73.44MB | 113.81MB | 0B |
| `utils.ParseFeatureFlag` | 82.64MB | 73.44MB | 113.81MB | 0B |

**Total FF alloc (current snapshot):** 439.23MB  |  **24h avg:** 602.81MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 68.01MB | 31/1031 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 60.16MB | 18/1031 | `█████████████░░ 88%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 682/1031 | `████████░░░░░░░ 53%` |
| 4 | `database/sql.convertAssignRows` | 33.54MB | 39/1031 | `███████░░░░░░░░ 49%` |
| 5 | `runtime.mallocgc` | 21.15MB | 682/1031 | `████░░░░░░░░░░░ 31%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1031 | `███░░░░░░░░░░░░ 26%` |
| 7 | `bytes.growSlice` | 13.31MB | 487/1031 | `██░░░░░░░░░░░░░ 19%` |
| 8 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1031 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `net/http.(*Transport).dialConn` | 10.5MB | 9/1031 | `██░░░░░░░░░░░░░ 15%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 10.44MB | 20/1031 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1031 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1031 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1031 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1031 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1031 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 42.89GB | 655/1031 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1031 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.69GB | 586/1031 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `fmt.Sprintf` | 13.22GB | 347/1031 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `segmentio/kafka-go.makePartitions` | 12.47GB | 441/1031 | `█░░░░░░░░░░░░░░ 9%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (12.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (8.2x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.8x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (3.1x avg)
- Heap spike to 391.4MB at 2026-05-17T10:03 (2.5x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.7x avg)
- Heap spike to 404.6MB at 2026-05-18T06:03 (2.6x avg)
- Goroutine spike to 21,569 at 2026-05-18T10:01 (2.1x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (3.2x avg)
- Heap spike to 408.3MB at 2026-05-18T16:02 (2.6x avg)
