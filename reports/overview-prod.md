# Overview: prod
*Last updated: 2026-06-06 16:05 IST*
*Data range: 2026-05-15T16:03 to 2026-06-06T16:05 (1723 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,451 | avg: 12,807 | max: 84,644 | trend: INCREASING (+3.46/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▄▇█▇▄▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 140.0MB | avg: 194.4MB | max: 3154.1MB | trend: stable (+0.06MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▄▆▇█▄▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,451 | 14,089 | +362 | 12,807 | 84,644 | INCREASING (+3.46/hr) |
| Heap InUse | 140.0MB | 149.1MB | -9.1MB | 194.4MB | 3154.1MB | stable (+0.06MB/hr) |
| Heap Sys | 852.2MB | 852.4MB | -0.2MB | 2401.2MB | 6883.9MB | |
| Heap Objects | 669,603 | 994,121 | -324518 | 863,091 | 17,165,538 | |

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
| 2026-06-06 | 194 | 16,620 | 257.4MB | 1932.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.58MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `compress/flate.NewWriter` | 5.29MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.51MB |
| 7 | `reflect.mapassign_faststr0` | 2.5MB |
| 8 | `encoding/json.(*decodeState).literalStore` | 2.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `bufio.NewReaderSize` | 2.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 3.85GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 2.65GB |
| 3 | `reflect.unsafe_NewArray` | 1.95GB |
| 4 | `reflect.growslice` | 1.79GB |
| 5 | `jackskj/carta.getUniqueId` | 1.72GB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 1.69GB |
| 7 | `reflect.unsafe_New` | 1.42GB |
| 8 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 1.38GB |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 1.15GB |
| 10 | `fmt.(*buffer).writeString` | 1.13GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 151.82MB | 147.81MB | 536.11MB | 0B |
| `evaluation.mergeMetadata` | 74.52MB | 71.52MB | 276.33MB | 0B |
| `local.(*Client).EvaluateV2` | 228.30MB | 223.25MB | 814.07MB | 0B |
| `local.topologicalSort` | 33.39MB | 32.89MB | 113.26MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 232.95MB | 227.38MB | 793.72MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 17.83MB | 17.83MB | 95.98MB | 0B |
| `localEvaluation.getMapOfValue` | 232.95MB | 227.38MB | 793.72MB | 0B |
| `utils.ParseFeatureFlag` | 232.95MB | 227.38MB | 794.94MB | 0B |

**Total FF alloc (current snapshot):** 1.18GB  |  **24h avg:** 4.12GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 90.47MB | 35/1723 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 71.33MB | 57/1723 | `███████████░░░░ 78%` |
| 3 | `database/sql.convertAssignRows` | 38.18MB | 70/1723 | `██████░░░░░░░░░ 42%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1374/1723 | `██████░░░░░░░░░ 40%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1723 | `██░░░░░░░░░░░░░ 19%` |
| 6 | `runtime.mallocgc` | 17.35MB | 1374/1723 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `bytes.growSlice` | 15.33MB | 1069/1723 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `net/http.(*Transport).dialConn` | 12.61MB | 32/1723 | `██░░░░░░░░░░░░░ 13%` |
| 9 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1723 | `██░░░░░░░░░░░░░ 13%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1723 | `█░░░░░░░░░░░░░░ 11%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1723 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1723 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1723 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1723 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1723 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 30.05GB | 1137/1723 | `███░░░░░░░░░░░░ 24%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1723 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44GB | 954/1723 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 12.86GB | 401/1723 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `fmt.Sprintf` | 12.8GB | 873/1723 | `█░░░░░░░░░░░░░░ 10%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.6x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.2x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.4x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.4x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.1x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.0x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.9x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.6x avg)
