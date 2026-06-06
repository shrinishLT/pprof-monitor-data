# Overview: prod
*Last updated: 2026-06-06 22:30 IST*
*Data range: 2026-05-15T16:03 to 2026-06-06T22:30 (1800 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,081 | avg: 12,869 | max: 84,644 | trend: INCREASING (+3.43/hr))
```
█▂▁▅▂▁▂▂▃▁▁▂▁▁▁▁▁▁▂▁▁▁▁▂▁▂▁▁▁▁▂▁▁▃▁▂▂▁▁▁▁▁▃▂▂▃▁▁▁▁▁▁▁▁▃▂▁▁▂▁▂▁▁▁▁▁▂▁▁▁▂▁▁▁▁▁▁▂▂▁▁▂▁▁▂▁▁▁▁▁▂▁▂▁▁▁
```

**Heap InUse** (current: 178.2MB | avg: 192.4MB | max: 3154.1MB | trend: stable (+0.04MB/hr))
```
▇▅▅█▄▄▃▆▄▂▃▅▂▁▃▃▁▃▂▃▃▂▁▄▁▂▅▅▆▃▂▁▁▂▂▄▂▁▃▃▂▄▄▄▃▃▃▃▃▄▂▂▂▃▄▃▄▁▄▃▆▅▃▃▃▂▄▁▄▁▃▁▂▂▅▁▂▄▄▃▁▃▄▁▄▁▃▂▁▃▅▄▅▃▂▅
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,081 | 14,082 | -1 | 12,869 | 84,644 | INCREASING (+3.43/hr) |
| Heap InUse | 178.2MB | 124.8MB | +53.4MB | 192.4MB | 3154.1MB | stable (+0.04MB/hr) |
| Heap Sys | 853.6MB | 853.6MB | +0.0MB | 2334.9MB | 6883.9MB | |
| Heap Objects | 1,369,341 | 654,677 | +714664 | 860,606 | 17,165,538 | |

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
| 2026-06-06 | 271 | 15,949 | 226.2MB | 1932.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.58MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.57MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `reflect.mapassign_faststr0` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 12.66GB |
| 2 | `reflect.unsafe_NewArray` | 6.43GB |
| 3 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 5.5GB |
| 4 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 4.5GB |
| 5 | `reflect.MakeSlice` | 3.61GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 3.41GB |
| 7 | `reflect.growslice` | 2.16GB |
| 8 | `fmt.Sprintf` | 2.0GB |
| 9 | `jackskj/carta.getUniqueId` | 1.99GB |
| 10 | `reflect.unsafe_New` | 1.76GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 393.59MB | 393.05MB | 335.20MB | 0B |
| `evaluation.mergeMetadata` | 206.55MB | 206.55MB | 174.16MB | 0B |
| `local.(*Client).EvaluateV2` | 591.73MB | 590.14MB | 501.26MB | 0B |
| `local.topologicalSort` | 79.96MB | 79.45MB | 66.38MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 590.30MB | 588.71MB | 497.29MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 58.74MB | 58.74MB | 51.56MB | 0B |
| `localEvaluation.getMapOfValue` | 590.30MB | 588.71MB | 497.29MB | 0B |
| `utils.ParseFeatureFlag` | 591.30MB | 589.71MB | 498.23MB | 0B |

**Total FF alloc (current snapshot):** 3.03GB  |  **24h avg:** 2.56GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 88.01MB | 36/1800 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 67.18MB | 61/1800 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1451/1800 | `██████░░░░░░░░░ 41%` |
| 4 | `database/sql.convertAssignRows` | 35.4MB | 76/1800 | `██████░░░░░░░░░ 40%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1800 | `███░░░░░░░░░░░░ 20%` |
| 6 | `runtime.mallocgc` | 17.05MB | 1451/1800 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `bytes.growSlice` | 14.93MB | 1105/1800 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `net/http.(*Transport).dialConn` | 12.61MB | 32/1800 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1800 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1800 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1800 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1800 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1800 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1800 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1800 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 28.33GB | 1214/1800 | `███░░░░░░░░░░░░ 22%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1800 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.23GB | 969/1800 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 12.86GB | 401/1800 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 12.52GB | 301/1800 | `█░░░░░░░░░░░░░░ 10%` |

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
