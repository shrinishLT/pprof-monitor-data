# Overview: prod
*Last updated: 2026-06-15 14:46 IST*
*Data range: 2026-05-15T16:03 to 2026-06-15T14:46 (4298 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,548 | avg: 14,759 | max: 84,644 | trend: INCREASING (+2.51/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▃▅▆▇█▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 271.1MB | avg: 243.6MB | max: 3154.1MB | trend: stable (+0.06MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▃▄▄▆▆█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,548 | 15,324 | -776 | 14,759 | 84,644 | INCREASING (+2.51/hr) |
| Heap InUse | 271.1MB | 301.2MB | -30.1MB | 243.6MB | 3154.1MB | stable (+0.06MB/hr) |
| Heap Sys | 2430.4MB | 2429.3MB | +1.1MB | 2525.0MB | 6883.9MB | |
| Heap Objects | 1,435,292 | 1,678,911 | -243619 | 1,045,837 | 17,165,538 | |

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
| 2026-06-15 | 178 | 16,218 | 274.6MB | 1342.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 32.36MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `bufio.NewWriterSize` | 2.52MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `bytes.growSlice` | 2.01MB |
| 8 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 9 | `compress/flate.NewWriter` | 1.76MB |
| 10 | `segmentio/kafka-go.makePartitions` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 109.24GB |
| 2 | `reflect.growslice` | 109.15GB |
| 3 | `segmentio/kafka-go.makePartitions` | 102.38GB |
| 4 | `jackskj/carta.getUniqueId` | 98.71GB |
| 5 | `reflect.unsafe_New` | 86.44GB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 78.32GB |
| 7 | `fmt.Sprintf` | 68.75GB |
| 8 | `fmt.(*buffer).writeString` | 67.2GB |
| 9 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 64.47GB |
| 10 | `carta/value.NewCell` | 62.64GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 4.01GB | 4.00GB | 3.79GB | 0B |
| `evaluation.mergeMetadata` | 2.08GB | 2.07GB | 1.96GB | 0B |
| `local.(*Client).EvaluateV2` | 6.17GB | 6.15GB | 5.82GB | 0B |
| `local.topologicalSort` | 890.95MB | 887.44MB | 841.60MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 6.05GB | 6.03GB | 5.74GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 739.37MB | 737.83MB | 670.47MB | 0B |
| `localEvaluation.getMapOfValue` | 6.05GB | 6.03GB | 5.74GB | 0B |
| `utils.ParseFeatureFlag` | 6.06GB | 6.04GB | 5.75GB | 0B |

**Total FF alloc (current snapshot):** 32.00GB  |  **24h avg:** 30.26GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 43.12MB | 88/4298 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 38.23MB | 122/4298 | `█████████████░░ 88%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3949/4298 | `████████████░░░ 84%` |
| 4 | `runtime.mallocgc` | 31.32MB | 3949/4298 | `██████████░░░░░ 72%` |
| 5 | `database/sql.convertAssignRows` | 21.72MB | 143/4298 | `███████░░░░░░░░ 50%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4298 | `██████░░░░░░░░░ 41%` |
| 7 | `bytes.growSlice` | 15.8MB | 3071/4298 | `█████░░░░░░░░░░ 36%` |
| 8 | `net/http.(*Transport).dialConn` | 13.44MB | 116/4298 | `████░░░░░░░░░░░ 31%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/4298 | `████░░░░░░░░░░░ 27%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4298 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4298 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4298 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4298 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 72.3GB | 2487/4298 | `████████░░░░░░░ 57%` |
| 5 | `reflect.growslice` | 61.42GB | 3510/4298 | `███████░░░░░░░░ 49%` |
| 6 | `segmentio/kafka-go.makePartitions` | 61.28GB | 3672/4298 | `███████░░░░░░░░ 49%` |
| 7 | `jackskj/carta.getUniqueId` | 54.77GB | 3526/4298 | `██████░░░░░░░░░ 43%` |
| 8 | `reflect.unsafe_New` | 51.55GB | 3290/4298 | `██████░░░░░░░░░ 41%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/4298 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 46.45GB | 2844/4298 | `█████░░░░░░░░░░ 37%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.7x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.2x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (3.9x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.3x avg)
