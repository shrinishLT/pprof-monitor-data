# Overview: prod
*Last updated: 2026-06-09 16:56 IST*
*Data range: 2026-05-15T16:03 to 2026-06-09T16:56 (2597 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,236 | avg: 13,820 | max: 84,644 | trend: INCREASING (+4.30/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▃▆▆▆█▆▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 236.8MB | avg: 218.4MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▃▄▄▄▆▆█▆▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,236 | 15,529 | -1293 | 13,820 | 84,644 | INCREASING (+4.30/hr) |
| Heap InUse | 236.8MB | 253.3MB | -16.5MB | 218.4MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3346.2MB | 3345.9MB | +0.3MB | 2488.7MB | 6883.9MB | |
| Heap Objects | 1,129,400 | 702,684 | +426716 | 956,435 | 17,165,538 | |

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
| 2026-06-09 | 204 | 16,390 | 308.1MB | 1487.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.01MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `bufio.NewWriterSize` | 2.02MB |
| 9 | `bufio.NewReaderSize` | 2.02MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 104.13GB |
| 2 | `segmentio/kafka-go.makePartitions` | 103.47GB |
| 3 | `jackskj/carta.getUniqueId` | 92.74GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 90.12GB |
| 5 | `reflect.unsafe_New` | 82.31GB |
| 6 | `fmt.Sprintf` | 68.5GB |
| 7 | `fmt.(*buffer).writeString` | 66.75GB |
| 8 | `carta/value.NewCell` | 58.73GB |
| 9 | `reflect.unsafe_NewArray` | 52.92GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 46.32GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 4.86GB | 4.85GB | 4.61GB | 0B |
| `evaluation.mergeMetadata` | 2.55GB | 2.54GB | 2.42GB | 0B |
| `local.(*Client).EvaluateV2` | 7.44GB | 7.42GB | 7.03GB | 0B |
| `local.topologicalSort` | 1.04GB | 1.04GB | 1010.41MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 7.13GB | 7.12GB | 6.78GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1016.23MB | 1011.11MB | 928.83MB | 0B |
| `localEvaluation.getMapOfValue` | 7.13GB | 7.12GB | 6.78GB | 0B |
| `utils.ParseFeatureFlag` | 7.14GB | 7.13GB | 6.79GB | 0B |

**Total FF alloc (current snapshot):** 38.28GB  |  **24h avg:** 36.29GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 80.78MB | 42/2597 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 62.08MB | 69/2597 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2248/2597 | `██████░░░░░░░░░ 45%` |
| 4 | `database/sql.convertAssignRows` | 30.58MB | 92/2597 | `█████░░░░░░░░░░ 37%` |
| 5 | `runtime.mallocgc` | 26.35MB | 2248/2597 | `████░░░░░░░░░░░ 32%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2597 | `███░░░░░░░░░░░░ 22%` |
| 7 | `bytes.growSlice` | 15.44MB | 1696/2597 | `██░░░░░░░░░░░░░ 19%` |
| 8 | `net/http.(*Transport).dialConn` | 14.92MB | 51/2597 | `██░░░░░░░░░░░░░ 18%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2597 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `crypto/tls.Client` | 10.64MB | 73/2597 | `█░░░░░░░░░░░░░░ 13%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2597 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2597 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2597 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2597 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2597 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 38.47GB | 1114/2597 | `████░░░░░░░░░░░ 30%` |
| 7 | `segmentio/kafka-go.makePartitions` | 29.97GB | 1971/2597 | `███░░░░░░░░░░░░ 23%` |
| 8 | `reflect.growslice` | 28.23GB | 1809/2597 | `███░░░░░░░░░░░░ 22%` |
| 9 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2597 | `███░░░░░░░░░░░░ 22%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2597 | `███░░░░░░░░░░░░ 21%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.7x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.1x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.1x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.0x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.6x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.4x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.8x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.6x avg)
