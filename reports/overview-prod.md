# Overview: prod
*Last updated: 2026-06-17 12:31 IST*
*Data range: 2026-05-15T16:03 to 2026-06-17T12:31 (4843 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,735 | avg: 14,941 | max: 84,644 | trend: INCREASING (+2.16/hr))
```
▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▄▃▅▆▆█▇▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 241.5MB | avg: 245.8MB | max: 3154.1MB | trend: stable (+0.05MB/hr))
```
▃▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▂▃▄▅▄▄▆█▇▇▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,735 | 15,026 | +709 | 14,941 | 84,644 | INCREASING (+2.16/hr) |
| Heap InUse | 241.5MB | 228.1MB | +13.4MB | 245.8MB | 3154.1MB | stable (+0.05MB/hr) |
| Heap Sys | 1884.4MB | 1884.0MB | +0.4MB | 2424.6MB | 6883.9MB | |
| Heap Objects | 673,920 | 914,312 | -240392 | 1,054,505 | 17,165,538 | |

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
| 2026-06-16 | 286 | 16,159 | 253.2MB | 1286.4MB |
| 2026-06-17 | 151 | 17,038 | 259.7MB | 1186.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 30.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 8.07MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 5.53MB |
| 6 | `compress/flate.NewWriter` | 5.29MB |
| 7 | `bufio.NewReaderSize` | 5.02MB |
| 8 | `bufio.NewWriterSize` | 4.02MB |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.85MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 35.81GB |
| 2 | `segmentio/kafka-go.makePartitions` | 34.46GB |
| 3 | `jackskj/carta.getUniqueId` | 32.88GB |
| 4 | `reflect.unsafe_New` | 28.88GB |
| 5 | `fmt.Sprintf` | 25.57GB |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 22.67GB |
| 7 | `fmt.(*buffer).writeString` | 21.83GB |
| 8 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 20.74GB |
| 9 | `carta/value.NewCell` | 20.38GB |
| 10 | `reflect.unsafe_NewArray` | 17.81GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 2.11GB | 2.10GB | 1.95GB | 0B |
| `evaluation.mergeMetadata` | 1.09GB | 1.09GB | 1.01GB | 0B |
| `local.(*Client).EvaluateV2` | 3.23GB | 3.21GB | 2.99GB | 0B |
| `local.topologicalSort` | 453.39MB | 449.87MB | 417.63MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 3.15GB | 3.14GB | 2.90GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 402.05MB | 402.05MB | 385.34MB | 0B |
| `localEvaluation.getMapOfValue` | 3.15GB | 3.14GB | 2.90GB | 0B |
| `utils.ParseFeatureFlag` | 3.16GB | 3.14GB | 2.90GB | 0B |

**Total FF alloc (current snapshot):** 16.73GB  |  **24h avg:** 15.43GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 37.87MB | 103/4843 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 4494/4843 | `██████████████░ 96%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 34.73MB | 137/4843 | `█████████████░░ 91%` |
| 4 | `runtime.mallocgc` | 30.28MB | 4494/4843 | `███████████░░░░ 79%` |
| 5 | `database/sql.convertAssignRows` | 19.85MB | 161/4843 | `███████░░░░░░░░ 52%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4843 | `███████░░░░░░░░ 47%` |
| 7 | `bytes.growSlice` | 15.84MB | 3566/4843 | `██████░░░░░░░░░ 41%` |
| 8 | `net/http.(*Transport).dialConn` | 13.27MB | 138/4843 | `█████░░░░░░░░░░ 35%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 10.86MB | 7/4843 | `████░░░░░░░░░░░ 28%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4843 | `████░░░░░░░░░░░ 27%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4843 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 75.34GB | 2760/4843 | `█████████░░░░░░ 60%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4843 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4843 | `████████░░░░░░░ 59%` |
| 5 | `segmentio/kafka-go.makePartitions` | 61.33GB | 4217/4843 | `███████░░░░░░░░ 49%` |
| 6 | `reflect.growslice` | 61.05GB | 4055/4843 | `███████░░░░░░░░ 48%` |
| 7 | `jackskj/carta.getUniqueId` | 54.6GB | 4071/4843 | `██████░░░░░░░░░ 43%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/4843 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 50.87GB | 3835/4843 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 46.55GB | 3246/4843 | `█████░░░░░░░░░░ 37%` |

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
