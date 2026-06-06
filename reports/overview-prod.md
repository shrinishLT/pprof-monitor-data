# Overview: prod
*Last updated: 2026-06-07 05:02 IST*
*Data range: 2026-05-15T16:03 to 2026-06-07T05:02 (1878 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,478 | avg: 12,925 | max: 84,644 | trend: INCREASING (+3.36/hr))
```
▃▁▁▃▂▁▂▂▂▁▁▁▂▁▃▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▂▁▁▁█▇▅▁▂▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▄▄▃▂▂▂▃▄▁▁▁▁▁▁▁▁▁▃
```

**Heap InUse** (current: 138.5MB | avg: 190.7MB | max: 3154.1MB | trend: stable (+0.03MB/hr))
```
▄▃▁▃▄▁▄▁▃▂▁▃▅▄▄▃▂▅▃▄▃▁▃▁▅▃▃▃▂▄▄▂▁▄▂▁▄▄▅▃▂▄▃▂▅▃▁▁▅▄▄▆▃▄▃▄▅▁▆█▃▅▂▁▃▁▁▁▃▄▄▄▄▄▂▂▃▃▄▃▂▂▅▃▃▄▄▂▁▃▄▁▁▁▄▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,478 | 14,106 | +372 | 12,925 | 84,644 | INCREASING (+3.36/hr) |
| Heap InUse | 138.5MB | 172.6MB | -34.1MB | 190.7MB | 3154.1MB | stable (+0.03MB/hr) |
| Heap Sys | 854.0MB | 854.5MB | -0.5MB | 2273.4MB | 6883.9MB | |
| Heap Objects | 686,839 | 1,278,003 | -591164 | 861,226 | 17,165,538 | |

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
| 2026-06-07 | 61 | 14,236 | 151.1MB | 233.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.58MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `reflect.growslice` | 5.09MB |
| 6 | `bytes.growSlice` | 4.02MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `reflect.unsafe_New` | 2.0MB |
| 10 | `segmentio/kafka-go.makePartitions` | 1.53MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 21.64GB |
| 2 | `reflect.unsafe_NewArray` | 11.05GB |
| 3 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 8.54GB |
| 4 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 7.0GB |
| 5 | `reflect.MakeSlice` | 6.23GB |
| 6 | `reflect.growslice` | 5.1GB |
| 7 | `jackskj/carta.getUniqueId` | 4.45GB |
| 8 | `reflect.unsafe_New` | 4.21GB |
| 9 | `dotlapse-event-service/project.ApplyPagination` | 4.19GB |
| 10 | `fmt.Sprintf` | 3.47GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 538.75MB | 536.25MB | 486.96MB | 0B |
| `evaluation.mergeMetadata` | 283.57MB | 281.57MB | 253.90MB | 0B |
| `local.(*Client).EvaluateV2` | 824.35MB | 820.80MB | 743.68MB | 0B |
| `local.topologicalSort` | 115.38MB | 115.38MB | 103.12MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 831.63MB | 827.04MB | 748.05MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 74.10MB | 74.10MB | 69.20MB | 0B |
| `localEvaluation.getMapOfValue` | 831.63MB | 827.04MB | 748.05MB | 0B |
| `utils.ParseFeatureFlag` | 833.63MB | 829.04MB | 750.05MB | 0B |

**Total FF alloc (current snapshot):** 4.23GB  |  **24h avg:** 3.81GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 85.72MB | 37/1878 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 66.16MB | 62/1878 | `███████████░░░░ 77%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1529/1878 | `██████░░░░░░░░░ 42%` |
| 4 | `database/sql.convertAssignRows` | 34.56MB | 78/1878 | `██████░░░░░░░░░ 40%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1878 | `███░░░░░░░░░░░░ 20%` |
| 6 | `runtime.mallocgc` | 16.77MB | 1529/1878 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `bytes.growSlice` | 14.76MB | 1122/1878 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `net/http.(*Transport).dialConn` | 12.61MB | 32/1878 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1878 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1878 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1878 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1878 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1878 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1878 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1878 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1878 | `███░░░░░░░░░░░░ 22%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 26.85GB | 1292/1878 | `███░░░░░░░░░░░░ 21%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.23GB | 969/1878 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 12.86GB | 401/1878 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 12.52GB | 301/1878 | `█░░░░░░░░░░░░░░ 10%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.5x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.5x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.2x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.6x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.5x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.5x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.1x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.1x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (5.0x avg)
