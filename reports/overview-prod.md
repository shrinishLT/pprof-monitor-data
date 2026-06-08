# Overview: prod
*Last updated: 2026-06-08 22:50 IST*
*Data range: 2026-05-15T16:03 to 2026-06-08T22:50 (2380 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,719 | avg: 13,595 | max: 84,644 | trend: INCREASING (+4.34/hr))
```
▅▃▄▄▃▂▃▃▄▃▂▄▃▄▅▃▂▁▁▄▆▅▄▅█▃▁▁▄▃▃▃▂▁▁▁▁▁▆▂▂▂▂▁▂▁▁▁▁▁▁▁▃▂▁▂▂▆▃▄▂▂▆▃▂▄▂▂▂▁▁▁▁▂▂▂▁▁▁▁▂▁▁▂▅▂▁▁▁▁▁▁▁▁▂▁
```

**Heap InUse** (current: 251.0MB | avg: 210.5MB | max: 3154.1MB | trend: stable (+0.10MB/hr))
```
▂▂▂▂▂▁▁▂▂▂▁█▁▂▂▂▁▁▁▂▃▃▂▂▂▄▁▁▂▁▁▂▁▁▁▁▁▁▃▂▁▁▁▂▁▁▁▁▁▁▁▁▂▂▁▂▁▃▂▂▁▁▃▂▁▂▂▁▂▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,719 | 15,357 | -638 | 13,595 | 84,644 | INCREASING (+4.34/hr) |
| Heap InUse | 251.0MB | 245.9MB | +5.1MB | 210.5MB | 3154.1MB | stable (+0.10MB/hr) |
| Heap Sys | 3340.2MB | 3340.3MB | -0.1MB | 2412.1MB | 6883.9MB | |
| Heap Objects | 1,124,056 | 521,145 | +602911 | 930,893 | 17,165,538 | |

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
| 2026-06-08 | 275 | 16,404 | 307.8MB | 2130.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `compress/flate.NewWriter` | 6.17MB |
| 6 | `segmentio/kafka-go.makePartitions` | 4.51MB |
| 7 | `bytes.growSlice` | 4.02MB |
| 8 | `bufio.NewWriterSize` | 3.03MB |
| 9 | `bufio.NewReaderSize` | 2.51MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 78.71GB |
| 2 | `reflect.growslice` | 66.14GB |
| 3 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 60.19GB |
| 4 | `jackskj/carta.getUniqueId` | 57.62GB |
| 5 | `reflect.unsafe_New` | 51.74GB |
| 6 | `fmt.Sprintf` | 41.98GB |
| 7 | `fmt.(*buffer).writeString` | 41.13GB |
| 8 | `reflect.unsafe_NewArray` | 40.22GB |
| 9 | `carta/value.NewCell` | 37.02GB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 25.54GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 3.36GB | 3.36GB | 3.15GB | 0B |
| `evaluation.mergeMetadata` | 1.75GB | 1.75GB | 1.64GB | 0B |
| `local.(*Client).EvaluateV2` | 5.12GB | 5.11GB | 4.79GB | 0B |
| `local.topologicalSort` | 726.59MB | 724.05MB | 678.82MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 4.89GB | 4.88GB | 4.59GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 720.82MB | 720.82MB | 669.35MB | 0B |
| `localEvaluation.getMapOfValue` | 4.89GB | 4.88GB | 4.59GB | 0B |
| `utils.ParseFeatureFlag` | 4.89GB | 4.89GB | 4.59GB | 0B |

**Total FF alloc (current snapshot):** 26.32GB  |  **24h avg:** 24.67GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 85.75MB | 39/2380 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 63.86MB | 66/2380 | `███████████░░░░ 74%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2031/2380 | `██████░░░░░░░░░ 42%` |
| 4 | `database/sql.convertAssignRows` | 31.33MB | 89/2380 | `█████░░░░░░░░░░ 36%` |
| 5 | `runtime.mallocgc` | 23.77MB | 2031/2380 | `████░░░░░░░░░░░ 27%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2380 | `███░░░░░░░░░░░░ 20%` |
| 7 | `bytes.growSlice` | 15.3MB | 1507/2380 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `net/http.(*Transport).dialConn` | 14.36MB | 47/2380 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2380 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `crypto/tls.Client` | 10.66MB | 64/2380 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2380 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2380 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2380 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2380 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2380 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 29.14GB | 897/2380 | `███░░░░░░░░░░░░ 23%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2380 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2380 | `███░░░░░░░░░░░░ 21%` |
| 9 | `segmentio/kafka-go.makePartitions` | 22.4GB | 1754/2380 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `reflect.growslice` | 20.32GB | 1592/2380 | `██░░░░░░░░░░░░░ 16%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.2x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.1x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.2x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.1x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.7x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.6x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.5x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (3.0x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.8x avg)
