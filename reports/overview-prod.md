# Overview: prod
*Last updated: 2026-06-12 20:17 IST*
*Data range: 2026-05-15T16:03 to 2026-06-12T20:17 (3500 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,418 | avg: 14,446 | max: 84,644 | trend: INCREASING (+3.35/hr))
```
▁▁▁▁▂▅▄▄▃▂▂▃▄▂▄▁▁▁▁▁▁▂▁▁▁▄▂▃▂▁▂▂▂▅▆▄▄▃▂▂▃▃▃▄▂▃▁▂▂▁▁▃▂▁▁▁▁▁▁▁▁▂▂▁▃▁▁▁▁▃▂▁▁▁▂▂▂▁▂▂▂▂▂▁▁▁▁▂▅▄█▇▅▄▂▁
```

**Heap InUse** (current: 144.5MB | avg: 238.4MB | max: 3154.1MB | trend: stable (+0.09MB/hr))
```
▁▂▁▁▄▄▃▅▅▂▂▃▅▄▄▂▂▂▂▁▃▃▂▅▂▃▂▃▄▃▃▂▄▆▅▅▃▃▃▃▅▃▃▄▃▄▄▃▃▄▃▃▃▂▃▂▄▂▁▂▃▂▄▂▃▁▃▂▂▃▃▂▁▂▂▄▂▃▄▂▄▂▂▂▁▂▁▂▄▅▇█▄▆▃▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,418 | 15,160 | -742 | 14,446 | 84,644 | INCREASING (+3.35/hr) |
| Heap InUse | 144.5MB | 177.2MB | -32.7MB | 238.4MB | 3154.1MB | stable (+0.09MB/hr) |
| Heap Sys | 687.2MB | 687.2MB | +0.0MB | 2626.3MB | 6883.9MB | |
| Heap Objects | 425,537 | 618,760 | -193223 | 1,023,416 | 17,165,538 | |

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
| 2026-06-07 | 288 | 15,421 | 234.3MB | 1942.9MB |
| 2026-06-08 | 288 | 16,327 | 305.6MB | 2130.6MB |
| 2026-06-09 | 288 | 16,163 | 304.7MB | 1487.7MB |
| 2026-06-10 | 287 | 16,453 | 305.9MB | 1442.9MB |
| 2026-06-11 | 288 | 16,393 | 314.0MB | 1403.5MB |
| 2026-06-12 | 244 | 16,055 | 263.0MB | 1418.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 9.6MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 8.55MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.51MB |
| 8 | `jackskj/carta.getUniqueId` | 2.5MB |
| 9 | `reflect.growslice` | 2.42MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 11.38GB |
| 2 | `fmt.Sprintf` | 8.26GB |
| 3 | `reflect.unsafe_NewArray` | 5.81GB |
| 4 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 5.38GB |
| 5 | `jackskj/carta.getUniqueId` | 5.37GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 5.18GB |
| 7 | `reflect.growslice` | 5.18GB |
| 8 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 4.98GB |
| 9 | `reflect.unsafe_New` | 4.45GB |
| 10 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 4.17GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 839.83MB | 825.14MB | 630.60MB | 0B |
| `evaluation.mergeMetadata` | 435.11MB | 426.61MB | 327.21MB | 0B |
| `local.(*Client).EvaluateV2` | 1.27GB | 1.25GB | 976.57MB | 0B |
| `local.topologicalSort` | 186.38MB | 184.86MB | 141.52MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.16GB | 1.14GB | 900.99MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 214.76MB | 211.13MB | 152.82MB | 0B |
| `localEvaluation.getMapOfValue` | 1.16GB | 1.14GB | 900.99MB | 0B |
| `utils.ParseFeatureFlag` | 1.17GB | 1.15GB | 904.61MB | 0B |

**Total FF alloc (current snapshot):** 6.40GB  |  **24h avg:** 4.82GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 52.6MB | 68/3500 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 47.12MB | 94/3500 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3151/3500 | `██████████░░░░░ 69%` |
| 4 | `runtime.mallocgc` | 31.9MB | 3151/3500 | `█████████░░░░░░ 60%` |
| 5 | `database/sql.convertAssignRows` | 24.89MB | 118/3500 | `███████░░░░░░░░ 47%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3500 | `█████░░░░░░░░░░ 34%` |
| 7 | `bytes.growSlice` | 15.64MB | 2490/3500 | `████░░░░░░░░░░░ 29%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3500 | `████░░░░░░░░░░░ 26%` |
| 9 | `net/http.(*Transport).dialConn` | 13.9MB | 82/3500 | `███░░░░░░░░░░░░ 26%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3500 | `███░░░░░░░░░░░░ 20%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3500 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3500 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3500 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 72.99GB | 1922/3500 | `████████░░░░░░░ 58%` |
| 5 | `reflect.growslice` | 63.18GB | 2712/3500 | `███████░░░░░░░░ 50%` |
| 6 | `segmentio/kafka-go.makePartitions` | 62.49GB | 2874/3500 | `███████░░░░░░░░ 49%` |
| 7 | `jackskj/carta.getUniqueId` | 55.98GB | 2728/3500 | `██████░░░░░░░░░ 44%` |
| 8 | `reflect.unsafe_New` | 53.85GB | 2492/3500 | `██████░░░░░░░░░ 43%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/3500 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 48.65GB | 2183/3500 | `█████░░░░░░░░░░ 38%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
