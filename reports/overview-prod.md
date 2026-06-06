# Overview: prod
*Last updated: 2026-06-07 01:15 IST*
*Data range: 2026-05-15T16:03 to 2026-06-07T01:15 (1833 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,099 | avg: 12,891 | max: 84,644 | trend: INCREASING (+3.39/hr))
```
▆▃▅▄▂▃▃▁▁▇▄▄█▂▁▂▂▂▂▂▂▇▃▁▂▅▃▄▁▁▁▂▃▅▂▁▁▆▁▂▁▂▂▂▃▄▁▂▄▃▂▃▂▃▁▁▁▃▁▅▁▁▁▁▁▁▁▁▁▃▁▄▁▁▁▁▁▁▁▁▁▁▁▄▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 161.9MB | avg: 191.7MB | max: 3154.1MB | trend: stable (+0.04MB/hr))
```
▃▃▅▃▁▄▄▂▅▅▆▄▃▄▄▄▅▃▃▂▄▆▄▅▁▅▄█▆▄▄▄▃▆▂▆▁▅▁▃▃▇▂▃▅▅▄▁▄▆▁▆▂▄▃▁▃▇▆▆▄▂▆▃▆▄▂▅▁▇▄▅▄▂▅▅▃▁▆▃▁▆▅▇▄▂▆▄▂▆▄▂▁▇▅▅
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,099 | 14,087 | +12 | 12,891 | 84,644 | INCREASING (+3.39/hr) |
| Heap InUse | 161.9MB | 166.7MB | -4.8MB | 191.7MB | 3154.1MB | stable (+0.04MB/hr) |
| Heap Sys | 853.7MB | 853.8MB | -0.1MB | 2308.3MB | 6883.9MB | |
| Heap Objects | 1,088,456 | 1,217,692 | -129236 | 862,217 | 17,165,538 | |

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
| 2026-06-07 | 16 | 14,110 | 152.6MB | 189.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.58MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `aws/endpoints.init` | 2.0MB |
| 8 | `reflect.unsafe_NewArray` | 1.52MB |
| 9 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 1.5MB |
| 10 | `segmentio/kafka-go.makePartitions` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 16.43GB |
| 2 | `reflect.unsafe_NewArray` | 8.4GB |
| 3 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 6.63GB |
| 4 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 5.42GB |
| 5 | `reflect.MakeSlice` | 4.7GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 3.71GB |
| 7 | `reflect.growslice` | 2.24GB |
| 8 | `fmt.Sprintf` | 2.14GB |
| 9 | `segmentio/kafka-go.makeLayout` | 2.08GB |
| 10 | `jackskj/carta.getUniqueId` | 2.0GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 441.96MB | 439.92MB | 405.26MB | 0B |
| `evaluation.mergeMetadata` | 232.06MB | 231.06MB | 212.09MB | 0B |
| `local.(*Client).EvaluateV2` | 670.76MB | 667.67MB | 610.26MB | 0B |
| `local.topologicalSort` | 92.62MB | 92.62MB | 82.78MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 674.94MB | 671.86MB | 610.74MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 62.80MB | 62.80MB | 59.39MB | 0B |
| `localEvaluation.getMapOfValue` | 674.94MB | 671.86MB | 610.74MB | 0B |
| `utils.ParseFeatureFlag` | 676.94MB | 673.86MB | 612.16MB | 0B |

**Total FF alloc (current snapshot):** 3.44GB  |  **24h avg:** 3.13GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 88.01MB | 36/1833 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 67.18MB | 61/1833 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1484/1833 | `██████░░░░░░░░░ 41%` |
| 4 | `database/sql.convertAssignRows` | 34.98MB | 77/1833 | `█████░░░░░░░░░░ 39%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1833 | `███░░░░░░░░░░░░ 20%` |
| 6 | `runtime.mallocgc` | 16.92MB | 1484/1833 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `bytes.growSlice` | 14.9MB | 1108/1833 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `net/http.(*Transport).dialConn` | 12.61MB | 32/1833 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1833 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1833 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1833 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1833 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1833 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1833 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1833 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1833 | `███░░░░░░░░░░░░ 22%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 27.68GB | 1247/1833 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.23GB | 969/1833 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 12.86GB | 401/1833 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 12.52GB | 301/1833 | `█░░░░░░░░░░░░░░ 10%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.6x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.2x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.6x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.5x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.4x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.1x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.1x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (5.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.6x avg)
