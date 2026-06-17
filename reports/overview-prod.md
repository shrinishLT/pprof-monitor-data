# Overview: prod
*Last updated: 2026-06-17 08:51 IST*
*Data range: 2026-05-15T16:03 to 2026-06-17T08:51 (4799 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,216 | avg: 14,885 | max: 84,644 | trend: INCREASING (+2.08/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▄█▅▅▂▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 148.4MB | avg: 244.6MB | max: 3154.1MB | trend: stable (+0.05MB/hr))
```
▁▁▁▁▂▁▁▁▁▁▂▁▂▃▁▂▁▁▁▁▂▁▂▄▂▁▁▁▁▁▁▁▁▁▂▁▁▁▁▂▂▄█▅▅▅▂▁▂▂▁▂▂▂▁▂▂▂▁▁▁▁▂▂▂▃▃▂▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▂▁▂▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,216 | 14,258 | -42 | 14,885 | 84,644 | INCREASING (+2.08/hr) |
| Heap InUse | 148.4MB | 180.3MB | -31.9MB | 244.6MB | 3154.1MB | stable (+0.05MB/hr) |
| Heap Sys | 1058.9MB | 1058.8MB | +0.1MB | 2433.2MB | 6883.9MB | |
| Heap Objects | 537,588 | 723,251 | -185663 | 1,050,662 | 17,165,538 | |

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
| 2026-06-16 | 286 | 16,159 | 253.2MB | 1286.4MB |
| 2026-06-17 | 107 | 15,393 | 213.6MB | 638.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 17.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 5 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 3.95MB |
| 6 | `database/sql.convertAssignRows` | 3.0MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.85MB |
| 8 | `bytes.growSlice` | 2.81MB |
| 9 | `bufio.NewReaderSize` | 2.52MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 29.42GB |
| 2 | `reflect.growslice` | 22.18GB |
| 3 | `fmt.Sprintf` | 20.53GB |
| 4 | `jackskj/carta.getUniqueId` | 19.98GB |
| 5 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 17.93GB |
| 6 | `reflect.unsafe_New` | 17.66GB |
| 7 | `reflect.unsafe_NewArray` | 15.25GB |
| 8 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 14.7GB |
| 9 | `fmt.(*buffer).writeString` | 13.3GB |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 13.19GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.82GB | 1.82GB | 1.71GB | 0B |
| `evaluation.mergeMetadata` | 961.23MB | 958.73MB | 902.41MB | 0B |
| `local.(*Client).EvaluateV2` | 2.79GB | 2.78GB | 2.62GB | 0B |
| `local.topologicalSort` | 391.12MB | 389.11MB | 366.21MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.70GB | 2.69GB | 2.52GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 371.77MB | 369.70MB | 358.97MB | 0B |
| `localEvaluation.getMapOfValue` | 2.70GB | 2.69GB | 2.52GB | 0B |
| `utils.ParseFeatureFlag` | 2.71GB | 2.70GB | 2.53GB | 0B |

**Total FF alloc (current snapshot):** 14.41GB  |  **24h avg:** 13.49GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 37.87MB | 103/4799 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 4450/4799 | `██████████████░ 96%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 34.96MB | 136/4799 | `█████████████░░ 92%` |
| 4 | `runtime.mallocgc` | 30.34MB | 4450/4799 | `████████████░░░ 80%` |
| 5 | `database/sql.convertAssignRows` | 19.94MB | 160/4799 | `███████░░░░░░░░ 52%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4799 | `███████░░░░░░░░ 47%` |
| 7 | `bytes.growSlice` | 15.54MB | 3527/4799 | `██████░░░░░░░░░ 41%` |
| 8 | `net/http.(*Transport).dialConn` | 13.18MB | 129/4799 | `█████░░░░░░░░░░ 34%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/4799 | `████░░░░░░░░░░░ 31%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4799 | `████░░░░░░░░░░░ 27%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4799 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 75.85GB | 2734/4799 | `█████████░░░░░░ 60%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4799 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4799 | `████████░░░░░░░ 59%` |
| 5 | `segmentio/kafka-go.makePartitions` | 61.64GB | 4173/4799 | `███████░░░░░░░░ 49%` |
| 6 | `reflect.growslice` | 61.39GB | 4011/4799 | `███████░░░░░░░░ 49%` |
| 7 | `jackskj/carta.getUniqueId` | 54.89GB | 4027/4799 | `██████░░░░░░░░░ 43%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/4799 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 51.17GB | 3791/4799 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 46.94GB | 3202/4799 | `█████░░░░░░░░░░ 37%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.7x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.7x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.2x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (3.9x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.5x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.3x avg)
