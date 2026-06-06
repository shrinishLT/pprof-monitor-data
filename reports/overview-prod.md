# Overview: prod
*Last updated: 2026-06-06 18:41 IST*
*Data range: 2026-05-15T16:03 to 2026-06-06T18:41 (1754 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,202 | avg: 12,833 | max: 84,644 | trend: INCREASING (+3.46/hr))
```
▁▄▁▁▅▃▂▃▁▁▁▁▁▁▁▁▁▂▂▄▂▄▅▄▁▅▄▂▃▃▂▂▁▁▁▁▁▁▁▃▅▄▃▄▄▂█▂▁▅▂▁▂▂▃▁▁▂▁▁▁▁▁▁▂▁▁▁▁▁▁▂▁▁▁▁▂▁▁▃▁▂▂▁▁▁▁▁▃▂▂▃▁▁▁▁
```

**Heap InUse** (current: 162.0MB | avg: 193.6MB | max: 3154.1MB | trend: stable (+0.05MB/hr))
```
▂▃▄▃▅▅▅▄▄▅▃▅▄▄▃▂▅▃▅▅▄▄▄▄▃▅▄▅▃▆▁▂▁█▁▂▁▁▁▁▂▂▃▄▂▃▃▂▂▃▂▂▁▃▂▁▁▃▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▂▃▁▁▁▁▁▁▂▁▁▂▁▁▂▂▂▁▁▂▁▁▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,202 | 14,203 | -1 | 12,833 | 84,644 | INCREASING (+3.46/hr) |
| Heap InUse | 162.0MB | 148.6MB | +13.4MB | 193.6MB | 3154.1MB | stable (+0.05MB/hr) |
| Heap Sys | 852.6MB | 852.6MB | +0.0MB | 2373.8MB | 6883.9MB | |
| Heap Objects | 1,201,340 | 896,698 | +304642 | 861,491 | 17,165,538 | |

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
| 2026-06-06 | 225 | 16,299 | 242.2MB | 1932.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.58MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `compress/flate.NewWriter` | 6.17MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.51MB |
| 7 | `reflect.mapassign_faststr0` | 3.0MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `compress/flate.(*compressor).initDeflate` | 2.14MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 7.47GB |
| 2 | `reflect.unsafe_NewArray` | 3.75GB |
| 3 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 3.36GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 2.96GB |
| 5 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 2.75GB |
| 6 | `reflect.MakeSlice` | 2.12GB |
| 7 | `reflect.growslice` | 1.94GB |
| 8 | `jackskj/carta.getUniqueId` | 1.83GB |
| 9 | `reflect.unsafe_New` | 1.56GB |
| 10 | `fmt.Sprintf` | 1.47GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 279.04MB | 274.98MB | 186.14MB | 0B |
| `evaluation.mergeMetadata` | 146.04MB | 144.54MB | 94.57MB | 0B |
| `local.(*Client).EvaluateV2` | 413.14MB | 407.47MB | 276.97MB | 0B |
| `local.topologicalSort` | 52.63MB | 52.63MB | 36.97MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 407.45MB | 401.78MB | 274.70MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 42.95MB | 42.95MB | 26.91MB | 0B |
| `localEvaluation.getMapOfValue` | 407.45MB | 401.78MB | 274.70MB | 0B |
| `utils.ParseFeatureFlag` | 407.95MB | 402.29MB | 274.72MB | 0B |

**Total FF alloc (current snapshot):** 2.11GB  |  **24h avg:** 1.41GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 88.01MB | 36/1754 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 69.13MB | 59/1754 | `███████████░░░░ 78%` |
| 3 | `database/sql.convertAssignRows` | 36.75MB | 73/1754 | `██████░░░░░░░░░ 41%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1405/1754 | `██████░░░░░░░░░ 41%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1754 | `███░░░░░░░░░░░░ 20%` |
| 6 | `runtime.mallocgc` | 17.22MB | 1405/1754 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `bytes.growSlice` | 15.18MB | 1083/1754 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `net/http.(*Transport).dialConn` | 12.61MB | 32/1754 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1754 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1754 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1754 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1754 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1754 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1754 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1754 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 29.33GB | 1168/1754 | `███░░░░░░░░░░░░ 23%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1754 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.23GB | 969/1754 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 12.86GB | 401/1754 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `fmt.Sprintf` | 12.67GB | 883/1754 | `█░░░░░░░░░░░░░░ 10%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.6x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.2x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.5x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.4x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.1x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.1x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.9x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.6x avg)
