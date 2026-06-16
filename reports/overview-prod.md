# Overview: prod
*Last updated: 2026-06-16 22:11 IST*
*Data range: 2026-05-15T16:03 to 2026-06-16T22:11 (4671 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,832 | avg: 14,868 | max: 84,644 | trend: INCREASING (+2.21/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▃▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▃▁▁▁▁▁▁▂▂▁▁▂▁▁▁▂▂▁▁▁▁▂▆█▅▂▂▃▅▄▃▁▂▂▂▁▁▃▃▁▂▁▁▁▁▁▁▁
```

**Heap InUse** (current: 175.9MB | avg: 245.3MB | max: 3154.1MB | trend: stable (+0.05MB/hr))
```
▁▁▁▁▂▂▁▁▁▂▁▂▁▁▁▁▃▂▃▂▂▂▁▁▁▂▂▁▁▁▁▂▂▂▂▂▂▂▁▁▂▁▁▂▁▂▂▂▄▂▂▁▁▁▁▂▂▂▂▂▁▁▂▂▂▁▁▂▂▃█▇▆▄▃▄▅▄▄▂▃▂▃▂▂▄▄▂▂▁▂▁▂▂▂▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,832 | 14,475 | +357 | 14,868 | 84,644 | INCREASING (+2.21/hr) |
| Heap InUse | 175.9MB | 190.7MB | -14.8MB | 245.3MB | 3154.1MB | stable (+0.05MB/hr) |
| Heap Sys | 1000.5MB | 1000.5MB | +0.0MB | 2471.9MB | 6883.9MB | |
| Heap Objects | 689,125 | 1,126,212 | -437087 | 1,052,334 | 17,165,538 | |

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
| 2026-06-16 | 265 | 16,171 | 253.8MB | 1286.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 5.67MB |
| 5 | `compress/flate.NewWriter` | 5.29MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 7 | `bufio.NewReaderSize` | 3.51MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.85MB |
| 9 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 2.14MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 14.76GB |
| 2 | `fmt.Sprintf` | 11.16GB |
| 3 | `jackskj/carta.getUniqueId` | 7.97GB |
| 4 | `reflect.unsafe_NewArray` | 7.72GB |
| 5 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 7.72GB |
| 6 | `reflect.growslice` | 7.48GB |
| 7 | `reflect.unsafe_New` | 6.55GB |
| 8 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 6.33GB |
| 9 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 6.27GB |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 5.73GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.17GB | 1.17GB | 989.80MB | 0B |
| `evaluation.mergeMetadata` | 614.15MB | 612.15MB | 507.90MB | 0B |
| `local.(*Client).EvaluateV2` | 1.79GB | 1.78GB | 1.47GB | 0B |
| `local.topologicalSort` | 243.46MB | 241.94MB | 200.11MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.68GB | 1.67GB | 1.38GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 286.57MB | 286.57MB | 243.42MB | 0B |
| `localEvaluation.getMapOfValue` | 1.68GB | 1.67GB | 1.38GB | 0B |
| `utils.ParseFeatureFlag` | 1.68GB | 1.67GB | 1.38GB | 0B |

**Total FF alloc (current snapshot):** 9.11GB  |  **24h avg:** 7.50GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 38.54MB | 101/4671 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 4322/4671 | `██████████████░ 95%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 35.6MB | 133/4671 | `█████████████░░ 92%` |
| 4 | `runtime.mallocgc` | 30.78MB | 4322/4671 | `███████████░░░░ 79%` |
| 5 | `database/sql.convertAssignRows` | 20.35MB | 156/4671 | `███████░░░░░░░░ 52%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4671 | `███████░░░░░░░░ 46%` |
| 7 | `bytes.growSlice` | 15.69MB | 3421/4671 | `██████░░░░░░░░░ 40%` |
| 8 | `net/http.(*Transport).dialConn` | 13.25MB | 128/4671 | `█████░░░░░░░░░░ 34%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/4671 | `████░░░░░░░░░░░ 30%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4671 | `████░░░░░░░░░░░ 27%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4671 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 75.85GB | 2734/4671 | `█████████░░░░░░ 60%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4671 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4671 | `████████░░░░░░░ 59%` |
| 5 | `reflect.growslice` | 62.98GB | 3883/4671 | `███████░░░░░░░░ 50%` |
| 6 | `segmentio/kafka-go.makePartitions` | 62.89GB | 4045/4671 | `███████░░░░░░░░ 50%` |
| 7 | `jackskj/carta.getUniqueId` | 56.28GB | 3899/4671 | `██████░░░░░░░░░ 45%` |
| 8 | `reflect.unsafe_New` | 52.58GB | 3663/4671 | `██████░░░░░░░░░ 42%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/4671 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 47.4GB | 3159/4671 | `█████░░░░░░░░░░ 37%` |

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
