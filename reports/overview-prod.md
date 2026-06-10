# Overview: prod
*Last updated: 2026-06-10 07:25 IST*
*Data range: 2026-05-15T16:03 to 2026-06-10T07:25 (2771 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,203 | avg: 13,959 | max: 84,644 | trend: INCREASING (+4.11/hr))
```
▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▅█▇▅▂▁▁▄▃▃▄▄▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 242.4MB | avg: 223.6MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▅█▆▅▃▁▁▄▃▃▄▄▃▃▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,203 | 14,224 | -21 | 13,959 | 84,644 | INCREASING (+4.11/hr) |
| Heap InUse | 242.4MB | 216.9MB | +25.5MB | 223.6MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3341.2MB | 3341.2MB | +0.0MB | 2541.3MB | 6883.9MB | |
| Heap Objects | 1,044,740 | 826,165 | +218575 | 974,257 | 17,165,538 | |

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
| 2026-06-10 | 90 | 16,429 | 304.9MB | 1004.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `bytes.growSlice` | 4.82MB |
| 6 | `compress/flate.NewWriter` | 4.41MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `encoding/json.(*decodeState).literalStore` | 2.04MB |
| 9 | `bufio.NewWriterSize` | 2.02MB |
| 10 | `segmentio/kafka-go.makePartitions` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 123.26GB |
| 2 | `reflect.growslice` | 119.56GB |
| 3 | `jackskj/carta.getUniqueId` | 105.89GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 98.69GB |
| 5 | `reflect.unsafe_New` | 94.08GB |
| 6 | `fmt.Sprintf` | 83.2GB |
| 7 | `fmt.(*buffer).writeString` | 76.07GB |
| 8 | `carta/value.NewCell` | 67.15GB |
| 9 | `reflect.unsafe_NewArray` | 63.02GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 51.84GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 6.09GB | 6.08GB | 5.98GB | 0B |
| `evaluation.mergeMetadata` | 3.20GB | 3.20GB | 3.15GB | 0B |
| `local.(*Client).EvaluateV2` | 9.28GB | 9.27GB | 9.12GB | 0B |
| `local.topologicalSort` | 1.29GB | 1.29GB | 1.27GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 8.86GB | 8.85GB | 8.69GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.28GB | 1.28GB | 1.27GB | 0B |
| `localEvaluation.getMapOfValue` | 8.86GB | 8.85GB | 8.69GB | 0B |
| `utils.ParseFeatureFlag` | 8.87GB | 8.86GB | 8.70GB | 0B |

**Total FF alloc (current snapshot):** 47.72GB  |  **24h avg:** 46.86GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 72.79MB | 47/2771 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 56.76MB | 76/2771 | `███████████░░░░ 77%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2422/2771 | `███████░░░░░░░░ 50%` |
| 4 | `database/sql.convertAssignRows` | 28.88MB | 98/2771 | `█████░░░░░░░░░░ 39%` |
| 5 | `runtime.mallocgc` | 28.08MB | 2422/2771 | `█████░░░░░░░░░░ 38%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2771 | `███░░░░░░░░░░░░ 24%` |
| 7 | `bytes.growSlice` | 15.45MB | 1848/2771 | `███░░░░░░░░░░░░ 21%` |
| 8 | `net/http.(*Transport).dialConn` | 14.27MB | 55/2771 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2771 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2771 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2771 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2771 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2771 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2771 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 45.67GB | 1288/2771 | `█████░░░░░░░░░░ 36%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2771 | `█████░░░░░░░░░░ 34%` |
| 7 | `segmentio/kafka-go.makePartitions` | 36.74GB | 2145/2771 | `████░░░░░░░░░░░ 29%` |
| 8 | `reflect.growslice` | 35.2GB | 1983/2771 | `████░░░░░░░░░░░ 28%` |
| 9 | `jackskj/carta.getUniqueId` | 30.57GB | 1999/2771 | `███░░░░░░░░░░░░ 24%` |
| 10 | `reflect.unsafe_New` | 30.23GB | 1763/2771 | `███░░░░░░░░░░░░ 24%` |

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
