# Overview: prod
*Last updated: 2026-06-11 12:51 IST*
*Data range: 2026-05-15T16:03 to 2026-06-11T12:51 (3123 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,936 | avg: 14,244 | max: 84,644 | trend: INCREASING (+3.84/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▃▄▆▆█▇▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 326.1MB | avg: 233.1MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▃▃▃▅▇▇█▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,936 | 16,151 | -215 | 14,244 | 84,644 | INCREASING (+3.84/hr) |
| Heap InUse | 326.1MB | 368.9MB | -42.8MB | 233.1MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3313.6MB | 3313.4MB | +0.2MB | 2630.2MB | 6883.9MB | |
| Heap Objects | 1,119,246 | 1,563,244 | -443998 | 1,005,971 | 17,165,538 | |

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
| 2026-06-11 | 155 | 16,522 | 310.7MB | 1403.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 13.74MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 6 | `bufio.NewWriterSize` | 7.57MB |
| 7 | `bufio.NewReaderSize` | 5.54MB |
| 8 | `segmentio/kafka-go.makePartitions` | 4.53MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.52MB |
| 10 | `jackskj/carta.getUniqueId` | 3.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 174.28GB |
| 2 | `segmentio/kafka-go.makePartitions` | 163.92GB |
| 3 | `jackskj/carta.getUniqueId` | 157.57GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 141.74GB |
| 5 | `reflect.unsafe_New` | 138.96GB |
| 6 | `fmt.Sprintf` | 120.8GB |
| 7 | `fmt.(*buffer).writeString` | 109.95GB |
| 8 | `carta/value.NewCell` | 99.33GB |
| 9 | `reflect.unsafe_NewArray` | 83.72GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 79.62GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 8.64GB | 8.63GB | 8.46GB | 0B |
| `evaluation.mergeMetadata` | 4.51GB | 4.51GB | 4.42GB | 0B |
| `local.(*Client).EvaluateV2` | 13.17GB | 13.15GB | 12.89GB | 0B |
| `local.topologicalSort` | 1.83GB | 1.83GB | 1.78GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 12.60GB | 12.58GB | 12.33GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.78GB | 1.78GB | 1.74GB | 0B |
| `localEvaluation.getMapOfValue` | 12.60GB | 12.58GB | 12.33GB | 0B |
| `utils.ParseFeatureFlag` | 12.62GB | 12.60GB | 12.35GB | 0B |

**Total FF alloc (current snapshot):** 67.76GB  |  **24h avg:** 66.29GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 59.59MB | 59/3123 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 51.07MB | 86/3123 | `████████████░░░ 85%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2774/3123 | `█████████░░░░░░ 61%` |
| 4 | `runtime.mallocgc` | 30.92MB | 2774/3123 | `███████░░░░░░░░ 51%` |
| 5 | `database/sql.convertAssignRows` | 27.21MB | 106/3123 | `██████░░░░░░░░░ 45%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3123 | `████░░░░░░░░░░░ 30%` |
| 7 | `bytes.growSlice` | 15.73MB | 2149/3123 | `███░░░░░░░░░░░░ 26%` |
| 8 | `net/http.(*Transport).dialConn` | 14.43MB | 69/3123 | `███░░░░░░░░░░░░ 24%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3123 | `███░░░░░░░░░░░░ 23%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3123 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3123 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3123 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3123 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 60.91GB | 1640/3123 | `███████░░░░░░░░ 48%` |
| 5 | `segmentio/kafka-go.makePartitions` | 51.81GB | 2497/3123 | `██████░░░░░░░░░ 41%` |
| 6 | `reflect.growslice` | 51.5GB | 2335/3123 | `██████░░░░░░░░░ 41%` |
| 7 | `experiment/local.topologicalSort` | 51.23GB | 375/3123 | `██████░░░░░░░░░ 40%` |
| 8 | `jackskj/carta.getUniqueId` | 45.25GB | 2351/3123 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.unsafe_New` | 44.13GB | 2115/3123 | `█████░░░░░░░░░░ 35%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/3123 | `█████░░░░░░░░░░ 34%` |

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
