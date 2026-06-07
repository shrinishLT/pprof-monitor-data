# Overview: prod
*Last updated: 2026-06-07 19:45 IST*
*Data range: 2026-05-15T16:03 to 2026-06-07T19:45 (2055 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,140 | avg: 13,204 | max: 84,644 | trend: INCREASING (+4.04/hr))
```
▃▃▃▃▃▅▅▅▇█▇▂▁▁▂▂▁▃▂▃▁▁▂▁▁▁▁▂▁▁▁▁▁▂▁▁▁▂▂▁▂▂▁▁▁▁▂▁▃▄▂▃▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 259.5MB | avg: 196.9MB | max: 3154.1MB | trend: stable (+0.05MB/hr))
```
▄▄▅▆▅▆▇▅▆▆▆▃▃▃▃▂▅▇▅▄▃▃▂▆▅▃▂▅▅▂▄▂▂▅▂▂▄▃▄▂▃▆▂█▅▅▄▂▅▅▆▄▁▃▂▅▅▃▄▁▅▂▅▁▁▃▃▃▄▁▂▃▃▃▄▂▁▃▁▂▁▂▃▃▃▁▁▄▅▄▁▅▂▁▅▄
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,140 | 14,087 | +53 | 13,204 | 84,644 | INCREASING (+4.04/hr) |
| Heap InUse | 259.5MB | 273.4MB | -13.9MB | 196.9MB | 3154.1MB | stable (+0.05MB/hr) |
| Heap Sys | 3220.8MB | 3220.8MB | +0.0MB | 2280.5MB | 6883.9MB | |
| Heap Objects | 1,264,233 | 1,894,200 | -629967 | 886,020 | 17,165,538 | |

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
| 2026-06-07 | 238 | 15,672 | 234.0MB | 1942.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 49.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `aws/endpoints.init` | 2.0MB |
| 8 | `compress/flate.(*compressor).initDeflate` | 1.6MB |
| 9 | `segmentio/kafka-go.makePartitions` | 1.53MB |
| 10 | `bytes.growSlice` | 1.07MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 41.69GB |
| 2 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 40.03GB |
| 3 | `reflect.growslice` | 34.27GB |
| 4 | `jackskj/carta.getUniqueId` | 29.49GB |
| 5 | `reflect.unsafe_New` | 26.46GB |
| 6 | `fmt.(*buffer).writeString` | 21.34GB |
| 7 | `reflect.unsafe_NewArray` | 21.29GB |
| 8 | `carta/value.NewCell` | 18.93GB |
| 9 | `fmt.Sprintf` | 16.48GB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 14.67GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.15GB | 1.15GB | 1.09GB | 0B |
| `evaluation.mergeMetadata` | 611.15MB | 611.15MB | 576.19MB | 0B |
| `local.(*Client).EvaluateV2` | 1.75GB | 1.75GB | 1.66GB | 0B |
| `local.topologicalSort` | 237.87MB | 237.36MB | 227.63MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.75GB | 1.75GB | 1.67GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 177.93MB | 176.88MB | 159.05MB | 0B |
| `localEvaluation.getMapOfValue` | 1.75GB | 1.75GB | 1.67GB | 0B |
| `utils.ParseFeatureFlag` | 1.76GB | 1.75GB | 1.68GB | 0B |

**Total FF alloc (current snapshot):** 9.17GB  |  **24h avg:** 8.72GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 85.72MB | 37/2055 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 66.16MB | 62/2055 | `███████████░░░░ 77%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1706/2055 | `██████░░░░░░░░░ 42%` |
| 4 | `database/sql.convertAssignRows` | 33.78MB | 80/2055 | `█████░░░░░░░░░░ 39%` |
| 5 | `runtime.mallocgc` | 18.78MB | 1706/2055 | `███░░░░░░░░░░░░ 21%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2055 | `███░░░░░░░░░░░░ 20%` |
| 7 | `bytes.growSlice` | 15.0MB | 1256/2055 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `net/http.(*Transport).dialConn` | 13.47MB | 37/2055 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2055 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 10.48MB | 38/2055 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2055 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2055 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2055 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2055 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2055 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2055 | `███░░░░░░░░░░░░ 22%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2055 | `███░░░░░░░░░░░░ 21%` |
| 8 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 16.97GB | 572/2055 | `██░░░░░░░░░░░░░ 13%` |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 14.23GB | 969/2055 | `█░░░░░░░░░░░░░░ 11%` |
| 10 | `segmentio/kafka-go.makePartitions` | 13.8GB | 1429/2055 | `█░░░░░░░░░░░░░░ 11%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.6x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.4x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.1x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.4x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.4x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.0x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.0x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.9x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.5x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (3.2x avg)
