# Overview: prod
*Last updated: 2026-06-09 02:35 IST*
*Data range: 2026-05-15T16:03 to 2026-06-09T02:35 (2425 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,406 | avg: 13,621 | max: 84,644 | trend: INCREASING (+4.23/hr))
```
▁▁▁▁▁▁▁▃▂▁▂▂▆▃▄▂▂▅▃▂▄▂▂▂▁▁▂▁▂▂▂▁▁▁▁▂▁▁▂▄▂▁▁▁▁▁▁▁▁▂▁▁▁▂▁▁▁▁▁▂▁▁▂▁▁▂▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▅█▄▄▂▁▁▁▁▁
```

**Heap InUse** (current: 265.0MB | avg: 211.7MB | max: 3154.1MB | trend: stable (+0.10MB/hr))
```
▃▃▂▂▂▂▄▄▄▂▄▃▇▄▅▃▃▇▆▃▆▄▃▅▄▄▂▂▃▄▂▁▂▂▂▃▂▃▃▆▅▁▂▃▃▃▁▃▂▂▂▃▂▄▃▁▁▁▃▄▂▄▂▂▃▂▃▁▂▁▂▄▄▃▃▂▂▃▃▁▃▃▄▂▄▁▇█▄▄▅▄▄▂▂▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,406 | 14,350 | +56 | 13,621 | 84,644 | INCREASING (+4.23/hr) |
| Heap InUse | 265.0MB | 236.0MB | +29.0MB | 211.7MB | 3154.1MB | stable (+0.10MB/hr) |
| Heap Sys | 3330.8MB | 3330.7MB | +0.1MB | 2429.4MB | 6883.9MB | |
| Heap Objects | 1,293,859 | 1,028,500 | +265359 | 934,839 | 17,165,538 | |

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
| 2026-06-09 | 32 | 15,113 | 281.8MB | 447.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 5.25MB |
| 6 | `bytes.growSlice` | 4.53MB |
| 7 | `database/sql.convertAssignRows` | 3.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `bufio.NewWriterSize` | 2.04MB |
| 10 | `segmentio/kafka-go.makePartitions` | 2.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 83.85GB |
| 2 | `reflect.growslice` | 74.16GB |
| 3 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 69.22GB |
| 4 | `jackskj/carta.getUniqueId` | 66.38GB |
| 5 | `reflect.unsafe_New` | 58.84GB |
| 6 | `fmt.Sprintf` | 52.62GB |
| 7 | `fmt.(*buffer).writeString` | 47.45GB |
| 8 | `reflect.unsafe_NewArray` | 42.88GB |
| 9 | `carta/value.NewCell` | 41.98GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 37.29GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 3.65GB | 3.65GB | 3.50GB | 0B |
| `evaluation.mergeMetadata` | 1.90GB | 1.90GB | 1.82GB | 0B |
| `local.(*Client).EvaluateV2` | 5.54GB | 5.53GB | 5.33GB | 0B |
| `local.topologicalSort` | 780.79MB | 778.25MB | 750.54MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 5.32GB | 5.31GB | 5.09GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 751.04MB | 751.04MB | 738.36MB | 0B |
| `localEvaluation.getMapOfValue` | 5.32GB | 5.31GB | 5.09GB | 0B |
| `utils.ParseFeatureFlag` | 5.33GB | 5.32GB | 5.10GB | 0B |

**Total FF alloc (current snapshot):** 28.55GB  |  **24h avg:** 27.39GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 83.74MB | 40/2425 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 63.86MB | 66/2425 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2076/2425 | `██████░░░░░░░░░ 43%` |
| 4 | `database/sql.convertAssignRows` | 31.02MB | 90/2425 | `█████░░░░░░░░░░ 37%` |
| 5 | `runtime.mallocgc` | 24.35MB | 2076/2425 | `████░░░░░░░░░░░ 29%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2425 | `███░░░░░░░░░░░░ 21%` |
| 7 | `bytes.growSlice` | 15.16MB | 1546/2425 | `██░░░░░░░░░░░░░ 18%` |
| 8 | `net/http.(*Transport).dialConn` | 14.36MB | 47/2425 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2425 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `crypto/tls.Client` | 10.66MB | 64/2425 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2425 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2425 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2425 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2425 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2425 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 30.71GB | 942/2425 | `███░░░░░░░░░░░░ 24%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2425 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2425 | `███░░░░░░░░░░░░ 21%` |
| 9 | `segmentio/kafka-go.makePartitions` | 23.87GB | 1799/2425 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `reflect.growslice` | 21.63GB | 1637/2425 | `██░░░░░░░░░░░░░ 17%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.2x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.1x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.2x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.1x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.7x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.5x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.5x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.9x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.7x avg)
