# Overview: prod
*Last updated: 2026-06-09 15:40 IST*
*Data range: 2026-05-15T16:03 to 2026-06-09T15:40 (2582 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,792 | avg: 13,814 | max: 84,644 | trend: INCREASING (+4.35/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▃▆▆▆█▆▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 355.8MB | avg: 218.1MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▃▄▄▄▆▆█▆▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▂▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,792 | 17,057 | -1265 | 13,814 | 84,644 | INCREASING (+4.35/hr) |
| Heap InUse | 355.8MB | 448.9MB | -93.1MB | 218.1MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3343.8MB | 3343.2MB | +0.6MB | 2483.7MB | 6883.9MB | |
| Heap Objects | 1,675,322 | 1,763,371 | -88049 | 956,311 | 17,165,538 | |

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
| 2026-06-09 | 189 | 16,506 | 311.6MB | 1487.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 20.81MB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 20.33MB |
| 5 | `bytes.growSlice` | 16.15MB |
| 6 | `bufio.NewWriterSize` | 10.05MB |
| 7 | `database/sql.convertAssignRows` | 10.0MB |
| 8 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 9 | `bufio.NewReaderSize` | 8.04MB |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 103.92GB |
| 2 | `segmentio/kafka-go.makePartitions` | 101.79GB |
| 3 | `jackskj/carta.getUniqueId` | 92.47GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 90.08GB |
| 5 | `reflect.unsafe_New` | 82.1GB |
| 6 | `fmt.Sprintf` | 67.25GB |
| 7 | `fmt.(*buffer).writeString` | 66.58GB |
| 8 | `carta/value.NewCell` | 58.6GB |
| 9 | `reflect.unsafe_NewArray` | 52.04GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 46.22GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 4.68GB | 4.67GB | 4.46GB | 0B |
| `evaluation.mergeMetadata` | 2.46GB | 2.45GB | 2.34GB | 0B |
| `local.(*Client).EvaluateV2` | 7.15GB | 7.14GB | 6.80GB | 0B |
| `local.topologicalSort` | 1.01GB | 1.00GB | 975.21MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 6.89GB | 6.88GB | 6.57GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 948.79MB | 947.25MB | 882.77MB | 0B |
| `localEvaluation.getMapOfValue` | 6.89GB | 6.88GB | 6.57GB | 0B |
| `utils.ParseFeatureFlag` | 6.90GB | 6.89GB | 6.58GB | 0B |

**Total FF alloc (current snapshot):** 36.91GB  |  **24h avg:** 35.13GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 80.78MB | 42/2582 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 62.08MB | 69/2582 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2233/2582 | `██████░░░░░░░░░ 45%` |
| 4 | `database/sql.convertAssignRows` | 30.58MB | 92/2582 | `█████░░░░░░░░░░ 37%` |
| 5 | `runtime.mallocgc` | 26.19MB | 2233/2582 | `████░░░░░░░░░░░ 32%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2582 | `███░░░░░░░░░░░░ 22%` |
| 7 | `bytes.growSlice` | 15.51MB | 1682/2582 | `██░░░░░░░░░░░░░ 19%` |
| 8 | `net/http.(*Transport).dialConn` | 14.92MB | 51/2582 | `██░░░░░░░░░░░░░ 18%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2582 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `crypto/tls.Client` | 10.64MB | 73/2582 | `█░░░░░░░░░░░░░░ 13%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2582 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2582 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2582 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2582 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2582 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 37.77GB | 1099/2582 | `████░░░░░░░░░░░ 30%` |
| 7 | `segmentio/kafka-go.makePartitions` | 29.41GB | 1956/2582 | `███░░░░░░░░░░░░ 23%` |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2582 | `███░░░░░░░░░░░░ 22%` |
| 9 | `reflect.growslice` | 27.6GB | 1794/2582 | `███░░░░░░░░░░░░ 22%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2582 | `███░░░░░░░░░░░░ 21%` |

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
