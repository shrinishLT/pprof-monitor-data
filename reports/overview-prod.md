# Overview: prod
*Last updated: 2026-06-11 00:41 IST*
*Data range: 2026-05-15T16:03 to 2026-06-11T00:40 (2977 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,333 | avg: 14,127 | max: 84,644 | trend: INCREASING (+3.93/hr))
```
▁▁▁▃▁▁▁▁▁▁▁▁▂▂▁▁▂▂▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▃▁▂▂▂▂▂▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▅█▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 258.0MB | avg: 229.2MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▁▂▃▃▂▁▁▂▁▂▁▁▂▃▁▂▃▄▃▂▃▃▂▂▁▂▂▃▃▂▃▃▂▁▂▃▂▃▂▁▄▂▂▃▃▃▄▃▁▁▂▄▂▃▂▄▃▂▁▁▁▁▂▃▂▁▁▂▃▂▁▁▂▃▃▂▁▁▅█▆▂▃▂▃▁▂▂▂▂▁▂▁▁▂▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,333 | 14,580 | -247 | 14,127 | 84,644 | INCREASING (+3.93/hr) |
| Heap InUse | 258.0MB | 294.0MB | -36.0MB | 229.2MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3327.3MB | 3326.5MB | +0.8MB | 2596.0MB | 6883.9MB | |
| Heap Objects | 988,487 | 1,600,284 | -611797 | 990,375 | 17,165,538 | |

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
| 2026-06-11 | 9 | 14,614 | 262.8MB | 294.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 8.36MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 4.13MB |
| 7 | `compress/flate.NewWriter` | 3.53MB |
| 8 | `reflect.mapassign_faststr0` | 3.0MB |
| 9 | `database/sql.convertAssignRows` | 3.0MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 147.15GB |
| 2 | `reflect.growslice` | 139.77GB |
| 3 | `jackskj/carta.getUniqueId` | 125.87GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 113.17GB |
| 5 | `reflect.unsafe_New` | 111.23GB |
| 6 | `fmt.Sprintf` | 101.2GB |
| 7 | `fmt.(*buffer).writeString` | 87.77GB |
| 8 | `carta/value.NewCell` | 79.49GB |
| 9 | `reflect.unsafe_NewArray` | 75.17GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 60.63GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 7.75GB | 7.74GB | 7.58GB | 0B |
| `evaluation.mergeMetadata` | 4.06GB | 4.05GB | 3.97GB | 0B |
| `local.(*Client).EvaluateV2` | 11.82GB | 11.80GB | 11.55GB | 0B |
| `local.topologicalSort` | 1.64GB | 1.64GB | 1.60GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 11.23GB | 11.22GB | 10.99GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.66GB | 1.65GB | 1.62GB | 0B |
| `localEvaluation.getMapOfValue` | 11.23GB | 11.22GB | 10.99GB | 0B |
| `utils.ParseFeatureFlag` | 11.25GB | 11.24GB | 11.00GB | 0B |

**Total FF alloc (current snapshot):** 60.63GB  |  **24h avg:** 59.30GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 63.44MB | 55/2977 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 53.32MB | 82/2977 | `████████████░░░ 84%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2628/2977 | `████████░░░░░░░ 57%` |
| 4 | `runtime.mallocgc` | 29.84MB | 2628/2977 | `███████░░░░░░░░ 47%` |
| 5 | `database/sql.convertAssignRows` | 27.65MB | 104/2977 | `██████░░░░░░░░░ 43%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2977 | `████░░░░░░░░░░░ 28%` |
| 7 | `bytes.growSlice` | 15.55MB | 2031/2977 | `███░░░░░░░░░░░░ 24%` |
| 8 | `net/http.(*Transport).dialConn` | 14.56MB | 60/2977 | `███░░░░░░░░░░░░ 22%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2977 | `███░░░░░░░░░░░░ 22%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2977 | `██░░░░░░░░░░░░░ 16%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2977 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2977 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2977 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 54.56GB | 1494/2977 | `██████░░░░░░░░░ 43%` |
| 5 | `experiment/local.topologicalSort` | 51.23GB | 375/2977 | `██████░░░░░░░░░ 40%` |
| 6 | `segmentio/kafka-go.makePartitions` | 45.37GB | 2351/2977 | `█████░░░░░░░░░░ 36%` |
| 7 | `reflect.growslice` | 44.55GB | 2189/2977 | `█████░░░░░░░░░░ 35%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2977 | `█████░░░░░░░░░░ 34%` |
| 9 | `jackskj/carta.getUniqueId` | 38.94GB | 2205/2977 | `████░░░░░░░░░░░ 31%` |
| 10 | `reflect.unsafe_New` | 38.2GB | 1969/2977 | `████░░░░░░░░░░░ 30%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.2x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.7x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.4x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
