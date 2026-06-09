# Overview: prod
*Last updated: 2026-06-09 17:30 IST*
*Data range: 2026-05-15T16:03 to 2026-06-09T17:30 (2604 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,250 | avg: 13,822 | max: 84,644 | trend: INCREASING (+4.28/hr))
```
▁▁▁▁▁▁▁▂▃▄▃▆▆▆█▆▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 264.9MB | avg: 218.6MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▁▁▁▁▁▂▂▂▃▄▄▄▆▆█▆▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,250 | 14,511 | -261 | 13,822 | 84,644 | INCREASING (+4.28/hr) |
| Heap InUse | 264.9MB | 296.6MB | -31.7MB | 218.6MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3346.5MB | 3346.5MB | +0.0MB | 2491.0MB | 6883.9MB | |
| Heap Objects | 1,333,788 | 1,571,546 | -237758 | 957,282 | 17,165,538 | |

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
| 2026-06-09 | 211 | 16,332 | 306.9MB | 1487.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `bytes.growSlice` | 3.63MB |
| 6 | `compress/flate.NewWriter` | 3.53MB |
| 7 | `segmentio/kafka-go.makePartitions` | 3.01MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `bufio.NewWriterSize` | 2.02MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 104.28GB |
| 2 | `segmentio/kafka-go.makePartitions` | 104.26GB |
| 3 | `jackskj/carta.getUniqueId` | 92.89GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 90.12GB |
| 5 | `reflect.unsafe_New` | 82.42GB |
| 6 | `fmt.Sprintf` | 68.76GB |
| 7 | `fmt.(*buffer).writeString` | 66.86GB |
| 8 | `carta/value.NewCell` | 58.82GB |
| 9 | `reflect.unsafe_NewArray` | 53.33GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 46.34GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 4.93GB | 4.92GB | 4.68GB | 0B |
| `evaluation.mergeMetadata` | 2.58GB | 2.58GB | 2.45GB | 0B |
| `local.(*Client).EvaluateV2` | 7.54GB | 7.52GB | 7.15GB | 0B |
| `local.topologicalSort` | 1.06GB | 1.05GB | 1.00GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 7.22GB | 7.21GB | 6.88GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.01GB | 1.01GB | 951.57MB | 0B |
| `localEvaluation.getMapOfValue` | 7.22GB | 7.21GB | 6.88GB | 0B |
| `utils.ParseFeatureFlag` | 7.23GB | 7.22GB | 6.89GB | 0B |

**Total FF alloc (current snapshot):** 38.78GB  |  **24h avg:** 36.85GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 80.78MB | 42/2604 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 62.08MB | 69/2604 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2255/2604 | `██████░░░░░░░░░ 45%` |
| 4 | `database/sql.convertAssignRows` | 30.29MB | 93/2604 | `█████░░░░░░░░░░ 37%` |
| 5 | `runtime.mallocgc` | 26.42MB | 2255/2604 | `████░░░░░░░░░░░ 32%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2604 | `███░░░░░░░░░░░░ 22%` |
| 7 | `bytes.growSlice` | 15.4MB | 1703/2604 | `██░░░░░░░░░░░░░ 19%` |
| 8 | `net/http.(*Transport).dialConn` | 14.92MB | 51/2604 | `██░░░░░░░░░░░░░ 18%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2604 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `crypto/tls.Client` | 10.64MB | 73/2604 | `█░░░░░░░░░░░░░░ 13%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2604 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2604 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2604 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2604 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2604 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 38.8GB | 1121/2604 | `████░░░░░░░░░░░ 31%` |
| 7 | `segmentio/kafka-go.makePartitions` | 30.23GB | 1978/2604 | `███░░░░░░░░░░░░ 24%` |
| 8 | `reflect.growslice` | 28.52GB | 1816/2604 | `███░░░░░░░░░░░░ 22%` |
| 9 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2604 | `███░░░░░░░░░░░░ 22%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2604 | `███░░░░░░░░░░░░ 21%` |

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
