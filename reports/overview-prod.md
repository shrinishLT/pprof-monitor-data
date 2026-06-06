# Overview: prod
*Last updated: 2026-06-07 04:15 IST*
*Data range: 2026-05-15T16:03 to 2026-06-07T04:15 (1869 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,142 | avg: 12,919 | max: 84,644 | trend: INCREASING (+3.37/hr))
```
▁▃▁▁▁▁▁▁▂▃▁▁▃▂▁▂▂▂▁▁▁▂▁▃▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▂▁▁▁█▇▅▁▂▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▄▄▃▂▂▂▃▄▁
```

**Heap InUse** (current: 175.5MB | avg: 191.0MB | max: 3154.1MB | trend: stable (+0.03MB/hr))
```
▁▃▁▂▂▅▂▂▄▄▃▁▃▄▁▄▁▃▂▁▃▅▄▄▃▂▅▃▄▃▁▃▁▅▃▃▃▂▄▄▂▁▄▂▁▄▄▅▃▂▄▃▂▅▃▁▁▅▄▄▆▃▄▃▄▅▁▆█▃▅▂▁▃▁▁▁▃▄▄▄▄▄▂▂▃▃▄▃▂▂▅▃▃▄▄
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,142 | 14,552 | -410 | 12,919 | 84,644 | INCREASING (+3.37/hr) |
| Heap InUse | 175.5MB | 177.2MB | -1.7MB | 191.0MB | 3154.1MB | stable (+0.03MB/hr) |
| Heap Sys | 854.5MB | 853.2MB | +1.3MB | 2280.3MB | 6883.9MB | |
| Heap Objects | 1,236,011 | 1,059,627 | +176384 | 861,863 | 17,165,538 | |

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
| 2026-06-07 | 52 | 14,252 | 154.2MB | 233.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.58MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `bytes.growSlice` | 2.51MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.51MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `reflect.unsafe_NewArray` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 20.56GB |
| 2 | `reflect.unsafe_NewArray` | 10.51GB |
| 3 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 8.54GB |
| 4 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 7.0GB |
| 5 | `reflect.MakeSlice` | 5.91GB |
| 6 | `reflect.growslice` | 4.65GB |
| 7 | `jackskj/carta.getUniqueId` | 4.15GB |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 4.14GB |
| 9 | `reflect.unsafe_New` | 3.89GB |
| 10 | `fmt.Sprintf` | 3.43GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 520.11MB | 518.10MB | 468.52MB | 0B |
| `evaluation.mergeMetadata` | 271.57MB | 269.57MB | 244.23MB | 0B |
| `local.(*Client).EvaluateV2` | 796.37MB | 791.31MB | 713.95MB | 0B |
| `local.topologicalSort` | 111.83MB | 110.32MB | 98.66MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 802.62MB | 797.56MB | 717.81MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 72.55MB | 72.55MB | 67.03MB | 0B |
| `localEvaluation.getMapOfValue` | 802.62MB | 797.56MB | 717.81MB | 0B |
| `utils.ParseFeatureFlag` | 804.62MB | 799.56MB | 719.76MB | 0B |

**Total FF alloc (current snapshot):** 4.08GB  |  **24h avg:** 3.66GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 85.72MB | 37/1869 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 66.16MB | 62/1869 | `███████████░░░░ 77%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1520/1869 | `██████░░░░░░░░░ 42%` |
| 4 | `database/sql.convertAssignRows` | 34.56MB | 78/1869 | `██████░░░░░░░░░ 40%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1869 | `███░░░░░░░░░░░░ 20%` |
| 6 | `runtime.mallocgc` | 16.8MB | 1520/1869 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `bytes.growSlice` | 14.77MB | 1121/1869 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `net/http.(*Transport).dialConn` | 12.61MB | 32/1869 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1869 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1869 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1869 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1869 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1869 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1869 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1869 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1869 | `███░░░░░░░░░░░░ 22%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 27.01GB | 1283/1869 | `███░░░░░░░░░░░░ 21%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.23GB | 969/1869 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 12.86GB | 401/1869 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 12.52GB | 301/1869 | `█░░░░░░░░░░░░░░ 10%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.6x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.5x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.2x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.6x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.5x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.5x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.1x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.1x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (5.0x avg)
