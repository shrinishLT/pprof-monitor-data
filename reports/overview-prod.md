# Overview: prod
*Last updated: 2026-06-10 09:57 IST*
*Data range: 2026-05-15T16:03 to 2026-06-10T09:57 (2801 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,547 | avg: 13,967 | max: 84,644 | trend: INCREASING (+4.01/hr))
```
▆█▇▃▄▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▁
```

**Heap InUse** (current: 312.5MB | avg: 223.9MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▅█▆▄▄▃▂▂▂▁▁▁▁▂▂▁▂▁▁▂▁▃▂▂▂▂▂▁▁▁▁▂▂▂▁▂▁▁▁▁▁▂▂▂▁▁▂▂▁▂▂▂▂▃▁▂▁▁▁▂▁▂▁▁▁▁▁▁▁▁▁▂▂▂▂▁▁▁▁▂▂▂▁▁▁▁▂▁▂▂▂▂▃▂▃▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,547 | 16,761 | -1214 | 13,967 | 84,644 | INCREASING (+4.01/hr) |
| Heap InUse | 312.5MB | 328.4MB | -15.9MB | 223.9MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3343.2MB | 3344.1MB | -0.9MB | 2549.9MB | 6883.9MB | |
| Heap Objects | 1,264,948 | 1,256,064 | +8884 | 975,268 | 17,165,538 | |

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
| 2026-06-10 | 120 | 16,003 | 291.7MB | 1004.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 11.57MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 6 | `bufio.NewWriterSize` | 5.05MB |
| 7 | `bufio.NewReaderSize` | 4.03MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.02MB |
| 9 | `compress/flate.NewWriter` | 2.64MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 126.7GB |
| 2 | `reflect.growslice` | 122.91GB |
| 3 | `jackskj/carta.getUniqueId` | 109.17GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 100.25GB |
| 5 | `reflect.unsafe_New` | 96.91GB |
| 6 | `fmt.Sprintf` | 85.35GB |
| 7 | `fmt.(*buffer).writeString` | 77.87GB |
| 8 | `carta/value.NewCell` | 69.16GB |
| 9 | `reflect.unsafe_NewArray` | 64.78GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 53.56GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 6.25GB | 6.24GB | 6.12GB | 0B |
| `evaluation.mergeMetadata` | 3.28GB | 3.28GB | 3.22GB | 0B |
| `local.(*Client).EvaluateV2` | 9.53GB | 9.52GB | 9.33GB | 0B |
| `local.topologicalSort` | 1.32GB | 1.32GB | 1.30GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 9.12GB | 9.10GB | 8.91GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.29GB | 1.29GB | 1.28GB | 0B |
| `localEvaluation.getMapOfValue` | 9.12GB | 9.10GB | 8.91GB | 0B |
| `utils.ParseFeatureFlag` | 9.13GB | 9.12GB | 8.93GB | 0B |

**Total FF alloc (current snapshot):** 49.03GB  |  **24h avg:** 48.00GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 71.38MB | 48/2801 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 56.12MB | 77/2801 | `███████████░░░░ 78%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2452/2801 | `███████░░░░░░░░ 51%` |
| 4 | `database/sql.convertAssignRows` | 28.64MB | 99/2801 | `██████░░░░░░░░░ 40%` |
| 5 | `runtime.mallocgc` | 28.35MB | 2452/2801 | `█████░░░░░░░░░░ 39%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2801 | `███░░░░░░░░░░░░ 25%` |
| 7 | `bytes.growSlice` | 15.35MB | 1868/2801 | `███░░░░░░░░░░░░ 21%` |
| 8 | `net/http.(*Transport).dialConn` | 14.27MB | 55/2801 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2801 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2801 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2801 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2801 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2801 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2801 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 46.88GB | 1318/2801 | `█████░░░░░░░░░░ 37%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2801 | `█████░░░░░░░░░░ 34%` |
| 7 | `segmentio/kafka-go.makePartitions` | 37.95GB | 2175/2801 | `████░░░░░░░░░░░ 30%` |
| 8 | `reflect.growslice` | 36.47GB | 2013/2801 | `████░░░░░░░░░░░ 29%` |
| 9 | `jackskj/carta.getUniqueId` | 31.7GB | 2029/2801 | `███░░░░░░░░░░░░ 25%` |
| 10 | `reflect.unsafe_New` | 31.31GB | 1793/2801 | `███░░░░░░░░░░░░ 25%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.5x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.1x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.0x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.0x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.5x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.3x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.8x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.5x avg)
