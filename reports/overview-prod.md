# Overview: prod
*Last updated: 2026-06-16 07:01 IST*
*Data range: 2026-05-15T16:03 to 2026-06-16T07:01 (4491 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,189 | avg: 14,802 | max: 84,644 | trend: INCREASING (+2.31/hr))
```
▂▁▄▆▂▂▃▁▁▁▄▁▁▂▅▃▁▄▇▂▁█▄▃▂▄▂▁▁▁▃▁▁▁▃▂▂▁▁▁▁▃▃▁▂▁▁▄▄▁▁▁▁▁▂▁▁▁▁▃▂▁▁▁▁▁▁▁▂▁▁▁▂▁▁▁▂▂▂▁▁▁▁▁▁▂▂▁▁▃▅▃▁▁▁▁
```

**Heap InUse** (current: 220.1MB | avg: 245.2MB | max: 3154.1MB | trend: stable (+0.06MB/hr))
```
▂▂▃█▂▂▄▁▁▁▃▂▂▃▄▄▂▄▆▂▃▆▅▂▃▅▃▁▂▂▂▃▁▂▂▂▂▁▁▃▂▃▄▂▂▂▂▄▅▂▂▂▁▂▃▁▁▂▃▃▂▃▁▁▁▃▂▁▂▂▁▂▃▂▂▂▃▂▃▁▂▁▁▁▃▂▂▃▃▅▄▄▂▁▁▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,189 | 14,494 | -305 | 14,802 | 84,644 | INCREASING (+2.31/hr) |
| Heap InUse | 220.1MB | 199.7MB | +20.4MB | 245.2MB | 3154.1MB | stable (+0.06MB/hr) |
| Heap Sys | 2430.5MB | 2430.5MB | +0.0MB | 2520.8MB | 6883.9MB | |
| Heap Objects | 1,197,341 | 872,489 | +324852 | 1,049,735 | 17,165,538 | |

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
| 2026-06-16 | 85 | 15,426 | 263.0MB | 455.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 32.36MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.51MB |
| 7 | `reflect.unsafe_NewArray` | 2.52MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 124.58GB |
| 2 | `reflect.growslice` | 124.54GB |
| 3 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 117.95GB |
| 4 | `jackskj/carta.getUniqueId` | 111.79GB |
| 5 | `reflect.unsafe_New` | 98.33GB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 90.94GB |
| 7 | `fmt.Sprintf` | 88.41GB |
| 8 | `fmt.(*buffer).writeString` | 76.97GB |
| 9 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 74.78GB |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 73.18GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 5.63GB | 5.63GB | 5.48GB | 0B |
| `evaluation.mergeMetadata` | 2.92GB | 2.92GB | 2.84GB | 0B |
| `local.(*Client).EvaluateV2` | 8.67GB | 8.66GB | 8.44GB | 0B |
| `local.topologicalSort` | 1.22GB | 1.22GB | 1.19GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 8.39GB | 8.38GB | 8.17GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.09GB | 1.09GB | 1.06GB | 0B |
| `localEvaluation.getMapOfValue` | 8.39GB | 8.38GB | 8.17GB | 0B |
| `utils.ParseFeatureFlag` | 8.40GB | 8.40GB | 8.18GB | 0B |

**Total FF alloc (current snapshot):** 44.71GB  |  **24h avg:** 43.53GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 41.2MB | 93/4491 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 36.94MB | 127/4491 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 4142/4491 | `█████████████░░ 88%` |
| 4 | `runtime.mallocgc` | 31.37MB | 4142/4491 | `███████████░░░░ 76%` |
| 5 | `database/sql.convertAssignRows` | 21.14MB | 148/4491 | `███████░░░░░░░░ 51%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4491 | `██████░░░░░░░░░ 43%` |
| 7 | `bytes.growSlice` | 15.67MB | 3253/4491 | `█████░░░░░░░░░░ 38%` |
| 8 | `net/http.(*Transport).dialConn` | 13.21MB | 119/4491 | `████░░░░░░░░░░░ 32%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/4491 | `████░░░░░░░░░░░ 28%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4491 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4491 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 75.07GB | 2680/4491 | `█████████░░░░░░ 60%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4491 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4491 | `████████░░░░░░░ 59%` |
| 5 | `reflect.growslice` | 64.08GB | 3703/4491 | `███████░░░░░░░░ 51%` |
| 6 | `segmentio/kafka-go.makePartitions` | 63.89GB | 3865/4491 | `███████░░░░░░░░ 51%` |
| 7 | `jackskj/carta.getUniqueId` | 57.23GB | 3719/4491 | `██████░░░░░░░░░ 45%` |
| 8 | `reflect.unsafe_New` | 53.64GB | 3483/4491 | `██████░░░░░░░░░ 42%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/4491 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 47.91GB | 3037/4491 | `█████░░░░░░░░░░ 38%` |

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
