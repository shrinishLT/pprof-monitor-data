# Overview: prod
*Last updated: 2026-06-04 06:40 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T06:40 (1035 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,538 | avg: 10,382 | max: 84,644 | trend: decreasing (-30.11/hr))
```
▁▁▁▁▁▁▁▄▁▅▅▅▅▅▅▄▅▅▅▅▄▄▄▄▄▅▅▅▅▅▅▄█▆▄▅▄▅▅▅▅▅▅▅▅▄▅▅▅▅▅▄▄▅▄▅▆▅▅▅▅▅▅▅▅▅▅▅▆▅▆▇▅▅▄▅▆▅▅▅▅▅▅▅▅▄▄▄▅▅▅▅▅▅▅▅
```

**Heap InUse** (current: 391.1MB | avg: 155.6MB | max: 2823.8MB | trend: stable (-0.43MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,538 | 14,485 | +53 | 10,382 | 84,644 | decreasing (-30.11/hr) |
| Heap InUse | 391.1MB | 178.2MB | +212.9MB | 155.6MB | 2823.8MB | stable (-0.43MB/hr) |
| Heap Sys | 2734.8MB | 2250.8MB | +484.0MB | 2546.4MB | 6883.9MB | |
| Heap Objects | 2,110,596 | 841,430 | +1269166 | 667,207 | 14,090,816 | |

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
| 2026-06-04 | 81 | 15,491 | 260.7MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 42.26MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `database/sql.convertAssignRows` | 28.5MB |
| 4 | `runtime.mallocgc` | 12.6MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 7 | `dotlapse-event-service/project.FilterProjectsByTags` | 3.05MB |
| 8 | `bytes.growSlice` | 3.02MB |
| 9 | `segmentio/kafka-go.makePartitions` | 3.01MB |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 3.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 35.98GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.29GB |
| 3 | `reflect.growslice` | 6.13GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 6.02GB |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 5.18GB |
| 6 | `jackskj/carta.getUniqueId` | 4.88GB |
| 7 | `reflect.unsafe_New` | 4.51GB |
| 8 | `database/sql.convertAssignRows` | 4.19GB |
| 9 | `fmt.(*buffer).writeString` | 3.62GB |
| 10 | `carta/value.NewCell` | 3.17GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 82.60MB | 79.08MB | 76.40MB | 0B |
| `evaluation.mergeMetadata` | 45.01MB | 42.51MB | 40.53MB | 0B |
| `local.(*Client).EvaluateV2` | 123.51MB | 112.23MB | 115.76MB | 0B |
| `local.topologicalSort` | 16.68MB | 13.64MB | 17.21MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 122.40MB | 111.61MB | 113.69MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 15.90MB | 14.89MB | 10.73MB | 0B |
| `localEvaluation.getMapOfValue` | 122.40MB | 111.61MB | 113.69MB | 0B |
| `utils.ParseFeatureFlag` | 122.40MB | 111.61MB | 113.69MB | 0B |

**Total FF alloc (current snapshot):** 650.91MB  |  **24h avg:** 601.69MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 65.73MB | 34/1035 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 59.47MB | 20/1035 | `█████████████░░ 90%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 686/1035 | `████████░░░░░░░ 55%` |
| 4 | `database/sql.convertAssignRows` | 33.13MB | 42/1035 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 21.1MB | 686/1035 | `████░░░░░░░░░░░ 32%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1035 | `████░░░░░░░░░░░ 27%` |
| 7 | `bytes.growSlice` | 13.23MB | 491/1035 | `███░░░░░░░░░░░░ 20%` |
| 8 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1035 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `net/http.(*Transport).dialConn` | 10.5MB | 9/1035 | `██░░░░░░░░░░░░░ 15%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.76MB | 22/1035 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1035 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1035 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1035 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1035 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1035 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 42.82GB | 659/1035 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1035 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.64GB | 590/1035 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `fmt.Sprintf` | 13.22GB | 347/1035 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `segmentio/kafka-go.makePartitions` | 12.47GB | 441/1035 | `█░░░░░░░░░░░░░░ 9%` |

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
