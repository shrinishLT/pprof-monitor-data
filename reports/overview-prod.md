# Overview: prod
*Last updated: 2026-06-17 23:16 IST*
*Data range: 2026-05-15T16:03 to 2026-06-17T23:16 (4972 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,446 | avg: 14,975 | max: 84,644 | trend: INCREASING (+2.08/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▂▂▁▂▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▅▆▃▄▂▂▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 179.6MB | avg: 246.6MB | max: 3154.1MB | trend: stable (+0.05MB/hr))
```
▁▁▂▁▂▁▁▂▁▁▁▁▁▁▁▁▁▂▂▂▃▂▂▂▂▁▂▁▁▃▃▂▃▃▃▁▂▁▁▁▁▁▁▂▁▂▄▃▂▂▂▁▁▂▁▁▁▂▁▂▂▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▂▁█▇▆▅▅▂▃▂▁▂▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,446 | 14,512 | -66 | 14,975 | 84,644 | INCREASING (+2.08/hr) |
| Heap InUse | 179.6MB | 182.8MB | -3.2MB | 246.6MB | 3154.1MB | stable (+0.05MB/hr) |
| Heap Sys | 2218.4MB | 2218.4MB | +0.0MB | 2418.0MB | 6883.9MB | |
| Heap Objects | 508,611 | 428,976 | +79635 | 1,056,197 | 17,165,538 | |

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
| 2026-06-17 | 280 | 16,674 | 268.5MB | 1186.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 30.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 5 | `bufio.NewReaderSize` | 3.53MB |
| 6 | `bytes.growSlice` | 3.52MB |
| 7 | `segmentio/kafka-go.makePartitions` | 3.51MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.85MB |
| 9 | `compress/flate.NewWriter` | 2.64MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 49.14GB |
| 2 | `reflect.growslice` | 42.13GB |
| 3 | `jackskj/carta.getUniqueId` | 40.03GB |
| 4 | `fmt.Sprintf` | 37.62GB |
| 5 | `reflect.unsafe_New` | 34.81GB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 30.3GB |
| 7 | `fmt.(*buffer).writeString` | 26.22GB |
| 8 | `reflect.unsafe_NewArray` | 25.34GB |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 25.02GB |
| 10 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 24.94GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 3.44GB | 3.43GB | 3.24GB | 0B |
| `evaluation.mergeMetadata` | 1.78GB | 1.77GB | 1.67GB | 0B |
| `local.(*Client).EvaluateV2` | 5.22GB | 5.20GB | 4.91GB | 0B |
| `local.topologicalSort` | 744.61MB | 741.55MB | 694.39MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 4.97GB | 4.96GB | 4.68GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 754.90MB | 752.89MB | 714.66MB | 0B |
| `localEvaluation.getMapOfValue` | 4.97GB | 4.96GB | 4.68GB | 0B |
| `utils.ParseFeatureFlag` | 4.98GB | 4.97GB | 4.69GB | 0B |

**Total FF alloc (current snapshot):** 26.82GB  |  **24h avg:** 25.26GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 37.25MB | 105/4972 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 4623/4972 | `██████████████░ 98%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 34.39MB | 140/4972 | `█████████████░░ 92%` |
| 4 | `runtime.mallocgc` | 30.29MB | 4623/4972 | `████████████░░░ 81%` |
| 5 | `database/sql.convertAssignRows` | 19.66MB | 164/4972 | `███████░░░░░░░░ 52%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4972 | `███████░░░░░░░░ 48%` |
| 7 | `bytes.growSlice` | 15.82MB | 3690/4972 | `██████░░░░░░░░░ 42%` |
| 8 | `net/http.(*Transport).dialConn` | 13.19MB | 140/4972 | `█████░░░░░░░░░░ 35%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4972 | `████░░░░░░░░░░░ 28%` |
| 10 | `crypto/tls.Client` | 10.36MB | 169/4972 | `████░░░░░░░░░░░ 27%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4972 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4972 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4972 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 73.06GB | 2889/4972 | `████████░░░░░░░ 58%` |
| 5 | `segmentio/kafka-go.makePartitions` | 60.75GB | 4346/4972 | `███████░░░░░░░░ 48%` |
| 6 | `reflect.growslice` | 60.42GB | 4184/4972 | `███████░░░░░░░░ 48%` |
| 7 | `jackskj/carta.getUniqueId` | 54.09GB | 4200/4972 | `██████░░░░░░░░░ 43%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/4972 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 50.29GB | 3964/4972 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 45.73GB | 3375/4972 | `█████░░░░░░░░░░ 36%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.7x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.7x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.7x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.2x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (3.9x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.2x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.5x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.3x avg)
