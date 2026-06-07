# Overview: prod
*Last updated: 2026-06-07 23:15 IST*
*Data range: 2026-05-15T16:03 to 2026-06-07T23:15 (2097 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,182 | avg: 13,224 | max: 84,644 | trend: INCREASING (+3.91/hr))
```
▂▃▂▂▃▂▆█▄▆▁▁▁▁▃▂▁▁▁▁▁▂▁▁▁▂▁▁▁▁▁▁▁▃▁▁▁▂▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▂▁▁▂▂▂▁▂▁▂▄▂▂▂▂▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▂▁▁
```

**Heap InUse** (current: 295.3MB | avg: 197.6MB | max: 3154.1MB | trend: stable (+0.05MB/hr))
```
▂█▅▅▄▂▅▅▆▄▁▃▂▅▅▃▄▁▅▂▅▁▁▃▃▃▄▁▂▃▃▃▄▂▁▃▁▂▁▂▃▃▃▁▁▄▅▄▁▅▂▁▅▄▂▂▁▁▄▄▁▄▂▂▂▂▂▃▄▆▅▂▃▅▂▅▂▂▂▂▃▄▄▃▃▃▄▄▄▄▁▂▂▂▂▆
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,182 | 14,168 | +14 | 13,224 | 84,644 | INCREASING (+3.91/hr) |
| Heap InUse | 295.3MB | 199.3MB | +96.0MB | 197.6MB | 3154.1MB | stable (+0.05MB/hr) |
| Heap Sys | 3221.1MB | 3221.2MB | -0.1MB | 2299.3MB | 6883.9MB | |
| Heap Objects | 946,545 | 729,238 | +217307 | 890,410 | 17,165,538 | |

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
| 2026-06-07 | 280 | 15,454 | 233.6MB | 1942.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 49.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 7.49MB |
| 6 | `bytes.growSlice` | 3.02MB |
| 7 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 2.85MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `database/sql.convertAssignRows` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 46.47GB |
| 2 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 40.04GB |
| 3 | `reflect.growslice` | 34.44GB |
| 4 | `jackskj/carta.getUniqueId` | 29.58GB |
| 5 | `reflect.unsafe_New` | 26.6GB |
| 6 | `reflect.unsafe_NewArray` | 23.75GB |
| 7 | `fmt.(*buffer).writeString` | 21.37GB |
| 8 | `carta/value.NewCell` | 19.02GB |
| 9 | `fmt.Sprintf` | 17.01GB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 16.38GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.27GB | 1.27GB | 1.21GB | 0B |
| `evaluation.mergeMetadata` | 669.16MB | 667.66MB | 638.74MB | 0B |
| `local.(*Client).EvaluateV2` | 1.92GB | 1.92GB | 1.83GB | 0B |
| `local.topologicalSort` | 258.64MB | 257.64MB | 247.03MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.91GB | 1.91GB | 1.82GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 212.63MB | 211.61MB | 196.74MB | 0B |
| `localEvaluation.getMapOfValue` | 1.91GB | 1.91GB | 1.82GB | 0B |
| `utils.ParseFeatureFlag` | 1.92GB | 1.91GB | 1.83GB | 0B |

**Total FF alloc (current snapshot):** 10.05GB  |  **24h avg:** 9.57GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 85.72MB | 37/2097 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 64.17MB | 64/2097 | `███████████░░░░ 74%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1748/2097 | `██████░░░░░░░░░ 42%` |
| 4 | `database/sql.convertAssignRows` | 32.64MB | 83/2097 | `█████░░░░░░░░░░ 38%` |
| 5 | `runtime.mallocgc` | 19.52MB | 1748/2097 | `███░░░░░░░░░░░░ 22%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2097 | `███░░░░░░░░░░░░ 20%` |
| 7 | `bytes.growSlice` | 14.82MB | 1275/2097 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `net/http.(*Transport).dialConn` | 13.47MB | 37/2097 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2097 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 10.48MB | 38/2097 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2097 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2097 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2097 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2097 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2097 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2097 | `███░░░░░░░░░░░░ 22%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2097 | `███░░░░░░░░░░░░ 21%` |
| 8 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 18.55GB | 614/2097 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `segmentio/kafka-go.makePartitions` | 14.66GB | 1471/2097 | `█░░░░░░░░░░░░░░ 11%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 14.23GB | 969/2097 | `█░░░░░░░░░░░░░░ 11%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.6x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.4x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.1x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.4x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.3x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.0x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.0x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.8x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.5x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (3.1x avg)
