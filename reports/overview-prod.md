# Overview: prod
*Last updated: 2026-06-16 15:16 IST*
*Data range: 2026-05-15T16:03 to 2026-06-16T15:16 (4589 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,362 | avg: 14,856 | max: 84,644 | trend: INCREASING (+2.30/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▃▄▃▄▄▅▆█▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 140.0MB | avg: 245.8MB | max: 3154.1MB | trend: stable (+0.06MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▅▃▄▅▅▇█▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,362 | 14,489 | -127 | 14,856 | 84,644 | INCREASING (+2.30/hr) |
| Heap InUse | 140.0MB | 183.1MB | -43.1MB | 245.8MB | 3154.1MB | stable (+0.06MB/hr) |
| Heap Sys | 848.4MB | 848.0MB | +0.4MB | 2498.4MB | 6883.9MB | |
| Heap Objects | 602,478 | 821,278 | -218800 | 1,053,289 | 17,165,538 | |

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
| 2026-06-12 | 288 | 16,142 | 260.8MB | 1418.7MB |
| 2026-06-13 | 288 | 16,274 | 264.7MB | 1566.3MB |
| 2026-06-14 | 288 | 15,854 | 265.3MB | 1419.6MB |
| 2026-06-15 | 286 | 16,144 | 281.9MB | 1342.8MB |
| 2026-06-16 | 183 | 16,443 | 269.4MB | 1286.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 10.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 7.2MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.85MB |
| 7 | `compress/flate.NewWriter` | 2.64MB |
| 8 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 9 | `reflect.mapassign_faststr0` | 2.0MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 1.07MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 5.95GB |
| 2 | `jackskj/carta.getUniqueId` | 5.63GB |
| 3 | `segmentio/kafka-go.makePartitions` | 5.28GB |
| 4 | `reflect.unsafe_New` | 4.84GB |
| 5 | `fmt.Sprintf` | 3.94GB |
| 6 | `fmt.(*buffer).writeString` | 3.52GB |
| 7 | `carta/value.NewCell` | 3.44GB |
| 8 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 3.42GB |
| 9 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 2.81GB |
| 10 | `reflect.unsafe_NewArray` | 2.76GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 371.58MB | 366.05MB | 304.22MB | 0B |
| `evaluation.mergeMetadata` | 190.55MB | 187.05MB | 158.22MB | 0B |
| `local.(*Client).EvaluateV2` | 579.66MB | 572.01MB | 467.32MB | 0B |
| `local.topologicalSort` | 79.88MB | 79.38MB | 64.27MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 556.75MB | 549.12MB | 453.69MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 83.30MB | 82.76MB | 62.94MB | 0B |
| `localEvaluation.getMapOfValue` | 556.75MB | 549.12MB | 453.69MB | 0B |
| `utils.ParseFeatureFlag` | 558.25MB | 550.62MB | 454.55MB | 0B |

**Total FF alloc (current snapshot):** 2.91GB  |  **24h avg:** 2.36GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 39.44MB | 98/4589 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 4240/4589 | `█████████████░░ 92%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 36.19MB | 130/4589 | `█████████████░░ 91%` |
| 4 | `runtime.mallocgc` | 31.14MB | 4240/4589 | `███████████░░░░ 78%` |
| 5 | `database/sql.convertAssignRows` | 20.6MB | 153/4589 | `███████░░░░░░░░ 52%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4589 | `██████░░░░░░░░░ 45%` |
| 7 | `bytes.growSlice` | 15.81MB | 3340/4589 | `██████░░░░░░░░░ 40%` |
| 8 | `net/http.(*Transport).dialConn` | 13.25MB | 128/4589 | `█████░░░░░░░░░░ 33%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/4589 | `████░░░░░░░░░░░ 30%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4589 | `████░░░░░░░░░░░ 26%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4589 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 75.85GB | 2734/4589 | `█████████░░░░░░ 60%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4589 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4589 | `████████░░░░░░░ 59%` |
| 5 | `reflect.growslice` | 64.2GB | 3801/4589 | `███████░░░░░░░░ 51%` |
| 6 | `segmentio/kafka-go.makePartitions` | 63.98GB | 3963/4589 | `███████░░░░░░░░ 51%` |
| 7 | `jackskj/carta.getUniqueId` | 57.34GB | 3817/4589 | `██████░░░░░░░░░ 45%` |
| 8 | `reflect.unsafe_New` | 53.65GB | 3581/4589 | `██████░░░░░░░░░ 42%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/4589 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 47.73GB | 3135/4589 | `█████░░░░░░░░░░ 38%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.7x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.7x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.7x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.2x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (3.9x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.5x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.3x avg)
