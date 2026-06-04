# Overview: prod
*Last updated: 2026-06-04 07:00 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T07:00 (1039 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,265 | avg: 10,397 | max: 84,644 | trend: decreasing (-29.60/hr))
```
▁▁▁▄▁▅▅▅▅▅▅▄▅▅▅▅▄▄▄▄▄▅▅▅▅▅▅▄█▆▄▅▄▅▅▅▅▅▅▅▅▄▅▅▅▅▅▄▄▅▄▅▆▅▅▅▅▅▅▅▅▅▅▅▆▅▆▇▅▅▄▅▆▅▅▅▅▅▅▅▅▄▄▄▅▅▅▅▅▅▅▅▄▄▄▄
```

**Heap InUse** (current: 122.2MB | avg: 155.6MB | max: 2823.8MB | trend: stable (-0.42MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 1%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,265 | 14,105 | +160 | 10,397 | 84,644 | decreasing (-29.60/hr) |
| Heap InUse | 122.2MB | 169.6MB | -47.4MB | 155.6MB | 2823.8MB | stable (-0.42MB/hr) |
| Heap Sys | 2735.2MB | 2735.1MB | +0.1MB | 2547.2MB | 6883.9MB | |
| Heap Objects | 378,468 | 1,168,372 | -789904 | 667,992 | 14,090,816 | |

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
| 2026-06-04 | 85 | 15,431 | 255.8MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.6MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `compress/flate.NewWriter` | 6.17MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `compress/flate.(*compressor).initDeflate` | 1.6MB |
| 10 | `bytes.growSlice` | 1.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 36.25GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.31GB |
| 3 | `reflect.growslice` | 6.16GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 6.02GB |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 5.2GB |
| 6 | `jackskj/carta.getUniqueId` | 4.9GB |
| 7 | `reflect.unsafe_New` | 4.52GB |
| 8 | `database/sql.convertAssignRows` | 4.2GB |
| 9 | `fmt.(*buffer).writeString` | 3.63GB |
| 10 | `carta/value.NewCell` | 3.18GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 97.21MB | 92.71MB | 76.61MB | 0B |
| `evaluation.mergeMetadata` | 56.01MB | 52.01MB | 41.24MB | 0B |
| `local.(*Client).EvaluateV2` | 148.45MB | 139.87MB | 115.42MB | 0B |
| `local.topologicalSort` | 20.22MB | 18.70MB | 16.67MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 148.36MB | 139.26MB | 113.89MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 16.95MB | 16.95MB | 10.87MB | 0B |
| `localEvaluation.getMapOfValue` | 148.36MB | 139.26MB | 113.89MB | 0B |
| `utils.ParseFeatureFlag` | 148.86MB | 139.76MB | 113.91MB | 0B |

**Total FF alloc (current snapshot):** 784.44MB  |  **24h avg:** 602.49MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 65.73MB | 34/1039 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 59.47MB | 20/1039 | `█████████████░░ 90%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 690/1039 | `████████░░░░░░░ 55%` |
| 4 | `database/sql.convertAssignRows` | 33.13MB | 42/1039 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 21.05MB | 690/1039 | `████░░░░░░░░░░░ 32%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1039 | `████░░░░░░░░░░░ 27%` |
| 7 | `bytes.growSlice` | 13.19MB | 493/1039 | `███░░░░░░░░░░░░ 20%` |
| 8 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1039 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `net/http.(*Transport).dialConn` | 10.5MB | 9/1039 | `██░░░░░░░░░░░░░ 15%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.76MB | 22/1039 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1039 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1039 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1039 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1039 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1039 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 42.78GB | 663/1039 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1039 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.61GB | 594/1039 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `fmt.Sprintf` | 13.22GB | 347/1039 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `segmentio/kafka-go.makePartitions` | 12.47GB | 441/1039 | `█░░░░░░░░░░░░░░ 9%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (12.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (8.1x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.8x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (3.1x avg)
- Heap spike to 391.4MB at 2026-05-17T10:03 (2.5x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.7x avg)
- Heap spike to 404.6MB at 2026-05-18T06:03 (2.6x avg)
- Goroutine spike to 21,569 at 2026-05-18T10:01 (2.1x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (3.2x avg)
- Heap spike to 408.3MB at 2026-05-18T16:02 (2.6x avg)
