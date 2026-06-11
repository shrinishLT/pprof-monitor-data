# Overview: prod
*Last updated: 2026-06-11 16:36 IST*
*Data range: 2026-05-15T16:03 to 2026-06-11T16:35 (3168 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 17,173 | avg: 14,256 | max: 84,644 | trend: INCREASING (+3.72/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▃▄▆▆█▇▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 438.5MB | avg: 233.8MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▃▃▃▅▇▇█▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 20%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 17,173 | 14,510 | +2663 | 14,256 | 84,644 | INCREASING (+3.72/hr) |
| Heap InUse | 438.5MB | 232.3MB | +206.2MB | 233.8MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3339.0MB | 3349.0MB | -10.0MB | 2640.1MB | 6883.9MB | |
| Heap Objects | 2,300,451 | 933,344 | +1367107 | 1,008,240 | 17,165,538 | |

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
| 2026-06-11 | 200 | 16,187 | 304.3MB | 1403.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 19.6MB |
| 4 | `bufio.NewReaderSize` | 12.56MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.55MB |
| 6 | `bufio.NewWriterSize` | 10.05MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 3.5MB |
| 10 | `segmentio/kafka-go.makePartitions` | 3.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 177.63GB |
| 2 | `segmentio/kafka-go.makePartitions` | 169.09GB |
| 3 | `jackskj/carta.getUniqueId` | 160.86GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 142.52GB |
| 5 | `reflect.unsafe_New` | 141.79GB |
| 6 | `fmt.Sprintf` | 124.2GB |
| 7 | `fmt.(*buffer).writeString` | 111.84GB |
| 8 | `carta/value.NewCell` | 101.32GB |
| 9 | `reflect.unsafe_NewArray` | 86.35GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 80.97GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 9.12GB | 9.11GB | 8.87GB | 0B |
| `evaluation.mergeMetadata` | 4.77GB | 4.76GB | 4.63GB | 0B |
| `local.(*Client).EvaluateV2` | 13.88GB | 13.87GB | 13.51GB | 0B |
| `local.topologicalSort` | 1.92GB | 1.92GB | 1.87GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 13.27GB | 13.25GB | 12.92GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.89GB | 1.89GB | 1.83GB | 0B |
| `localEvaluation.getMapOfValue` | 13.27GB | 13.25GB | 12.92GB | 0B |
| `utils.ParseFeatureFlag` | 13.29GB | 13.27GB | 12.94GB | 0B |

**Total FF alloc (current snapshot):** 71.40GB  |  **24h avg:** 69.50GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 59.59MB | 59/3168 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 51.07MB | 86/3168 | `████████████░░░ 85%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2819/3168 | `█████████░░░░░░ 61%` |
| 4 | `runtime.mallocgc` | 31.23MB | 2819/3168 | `███████░░░░░░░░ 52%` |
| 5 | `database/sql.convertAssignRows` | 27.21MB | 106/3168 | `██████░░░░░░░░░ 45%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3168 | `████░░░░░░░░░░░ 30%` |
| 7 | `bytes.growSlice` | 15.6MB | 2194/3168 | `███░░░░░░░░░░░░ 26%` |
| 8 | `net/http.(*Transport).dialConn` | 14.43MB | 69/3168 | `███░░░░░░░░░░░░ 24%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3168 | `███░░░░░░░░░░░░ 23%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3168 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3168 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3168 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3168 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 63.09GB | 1685/3168 | `███████░░░░░░░░ 50%` |
| 5 | `reflect.growslice` | 53.87GB | 2380/3168 | `██████░░░░░░░░░ 43%` |
| 6 | `segmentio/kafka-go.makePartitions` | 53.85GB | 2542/3168 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 51.23GB | 375/3168 | `██████░░░░░░░░░ 40%` |
| 8 | `jackskj/carta.getUniqueId` | 47.4GB | 2396/3168 | `█████░░░░░░░░░░ 37%` |
| 9 | `reflect.unsafe_New` | 46.15GB | 2160/3168 | `█████░░░░░░░░░░ 36%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/3168 | `█████░░░░░░░░░░ 34%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.7x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.3x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
