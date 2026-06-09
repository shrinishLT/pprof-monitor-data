# Overview: prod
*Last updated: 2026-06-09 16:14 IST*
*Data range: 2026-05-15T16:03 to 2026-06-09T16:14 (2588 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,443 | avg: 13,817 | max: 84,644 | trend: INCREASING (+4.33/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▃▆▆▆█▆▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 236.7MB | avg: 218.3MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▃▄▄▄▆▆█▆▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,443 | 15,109 | -666 | 13,817 | 84,644 | INCREASING (+4.33/hr) |
| Heap InUse | 236.7MB | 251.8MB | -15.1MB | 218.3MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3345.6MB | 3345.4MB | +0.2MB | 2485.7MB | 6883.9MB | |
| Heap Objects | 862,687 | 784,021 | +78666 | 956,000 | 17,165,538 | |

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
| 2026-06-09 | 195 | 16,460 | 310.0MB | 1487.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `bytes.growSlice` | 2.3MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.03MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `bufio.NewReaderSize` | 1.52MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 103.95GB |
| 2 | `segmentio/kafka-go.makePartitions` | 102.49GB |
| 3 | `jackskj/carta.getUniqueId` | 92.54GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 90.08GB |
| 5 | `reflect.unsafe_New` | 82.14GB |
| 6 | `fmt.Sprintf` | 67.9GB |
| 7 | `fmt.(*buffer).writeString` | 66.61GB |
| 8 | `carta/value.NewCell` | 58.63GB |
| 9 | `reflect.unsafe_NewArray` | 52.42GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 46.26GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 4.77GB | 4.74GB | 4.51GB | 0B |
| `evaluation.mergeMetadata` | 2.50GB | 2.49GB | 2.37GB | 0B |
| `local.(*Client).EvaluateV2` | 7.29GB | 7.25GB | 6.89GB | 0B |
| `local.topologicalSort` | 1.03GB | 1.02GB | 988.99MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 7.00GB | 6.97GB | 6.65GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 982.54MB | 972.36MB | 900.03MB | 0B |
| `localEvaluation.getMapOfValue` | 7.00GB | 6.97GB | 6.65GB | 0B |
| `utils.ParseFeatureFlag` | 7.01GB | 6.99GB | 6.66GB | 0B |

**Total FF alloc (current snapshot):** 37.55GB  |  **24h avg:** 35.58GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 80.78MB | 42/2588 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 62.08MB | 69/2588 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2239/2588 | `██████░░░░░░░░░ 45%` |
| 4 | `database/sql.convertAssignRows` | 30.58MB | 92/2588 | `█████░░░░░░░░░░ 37%` |
| 5 | `runtime.mallocgc` | 26.25MB | 2239/2588 | `████░░░░░░░░░░░ 32%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2588 | `███░░░░░░░░░░░░ 22%` |
| 7 | `bytes.growSlice` | 15.48MB | 1688/2588 | `██░░░░░░░░░░░░░ 19%` |
| 8 | `net/http.(*Transport).dialConn` | 14.92MB | 51/2588 | `██░░░░░░░░░░░░░ 18%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2588 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `crypto/tls.Client` | 10.64MB | 73/2588 | `█░░░░░░░░░░░░░░ 13%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2588 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2588 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2588 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2588 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2588 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 38.05GB | 1105/2588 | `████░░░░░░░░░░░ 30%` |
| 7 | `segmentio/kafka-go.makePartitions` | 29.63GB | 1962/2588 | `███░░░░░░░░░░░░ 23%` |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2588 | `███░░░░░░░░░░░░ 22%` |
| 9 | `reflect.growslice` | 27.85GB | 1800/2588 | `███░░░░░░░░░░░░ 22%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2588 | `███░░░░░░░░░░░░ 21%` |

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
