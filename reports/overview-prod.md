# Overview: prod
*Last updated: 2026-06-04 02:55 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T02:55 (990 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,200 | avg: 10,149 | max: 84,644 | trend: decreasing (-37.37/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▄▁▅▅▅▅▅▅▄▅▅▅▅▄▄▄▄▄▅▅▅▅▅▅▄█▆▄▅▄▅▅▅▅▅▅▅▅▄▅▅▅▅▅
```

**Heap InUse** (current: 2823.8MB | avg: 151.7MB | max: 2823.8MB | trend: decreasing (-0.54MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `████████░░░░░░░░░░░░ 41%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,200 | 15,019 | +181 | 10,149 | 84,644 | decreasing (-37.37/hr) |
| Heap InUse | 2823.8MB | 219.9MB | +2603.9MB | 151.7MB | 2823.8MB | decreasing (-0.54MB/hr) |
| Heap Sys | 4526.8MB | 860.2MB | +3666.6MB | 2544.3MB | 6883.9MB | |
| Heap Objects | 14,090,816 | 1,136,037 | +12954779 | 650,978 | 14,090,816 | |

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
| 2026-06-04 | 36 | 15,451 | 285.3MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 549.71MB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 370.31MB |
| 3 | `database/sql.convertAssignRows` | 297.01MB |
| 4 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 63.18MB |
| 5 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 6 | `dotlapse-event-service/project.FilterProjectsByTags` | 19.84MB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB |
| 8 | `runtime.mallocgc` | 14.13MB |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 9.5MB |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 6.19GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 2.98GB |
| 3 | `fmt.Sprintf` | 2.79GB |
| 4 | `reflect.growslice` | 2.55GB |
| 5 | `jackskj/carta.getUniqueId` | 2.49GB |
| 6 | `reflect.unsafe_New` | 2.16GB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.03GB |
| 8 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 1.61GB |
| 9 | `fmt.(*buffer).writeString` | 1.56GB |
| 10 | `carta/value.NewCell` | 1.55GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 91.53MB | 85.87MB | 69.49MB | 0B |
| `evaluation.mergeMetadata` | 44.01MB | 42.01MB | 35.56MB | 0B |
| `local.(*Client).EvaluateV2` | 146.77MB | 136.42MB | 106.49MB | 513.31kB |
| `local.topologicalSort` | 25.84MB | 23.82MB | 18.28MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 139.21MB | 128.85MB | 95.58MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 15.77MB | 15.27MB | 18.31MB | 513.31kB |
| `localEvaluation.getMapOfValue` | 139.21MB | 128.85MB | 95.58MB | 0B |
| `utils.ParseFeatureFlag` | 139.21MB | 128.85MB | 95.78MB | 0B |

**Total FF alloc (current snapshot):** 741.55MB  |  **24h avg:** 535.05MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 67.61MB | 27/990 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 62.95MB | 17/990 | `█████████████░░ 93%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 641/990 | `████████░░░░░░░ 54%` |
| 4 | `database/sql.convertAssignRows` | 33.77MB | 35/990 | `███████░░░░░░░░ 49%` |
| 5 | `runtime.mallocgc` | 21.66MB | 641/990 | `████░░░░░░░░░░░ 32%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/990 | `███░░░░░░░░░░░░ 26%` |
| 7 | `bytes.growSlice` | 13.29MB | 448/990 | `██░░░░░░░░░░░░░ 19%` |
| 8 | `net/http.(*Transport).dialConn` | 11.31MB | 8/990 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 11.12MB | 17/990 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/990 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/990 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/990 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/990 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/990 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 45.1GB | 618/990 | `█████░░░░░░░░░░ 35%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/990 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/990 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 20.43GB | 561/990 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `fmt.Sprintf` | 14.51GB | 308/990 | `█░░░░░░░░░░░░░░ 11%` |
| 10 | `segmentio/kafka-go.makePartitions` | 12.88GB | 423/990 | `█░░░░░░░░░░░░░░ 10%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (12.5x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (8.3x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.9x avg)
- Goroutine spike to 20,552 at 2026-05-16T03:31 (2.0x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (3.2x avg)
- Heap spike to 391.4MB at 2026-05-17T10:03 (2.6x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.8x avg)
- Heap spike to 404.6MB at 2026-05-18T06:03 (2.7x avg)
- Goroutine spike to 21,569 at 2026-05-18T10:01 (2.1x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (3.2x avg)
