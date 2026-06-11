# Overview: prod
*Last updated: 2026-06-11 10:02 IST*
*Data range: 2026-05-15T16:03 to 2026-06-11T10:01 (3089 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 17,686 | avg: 14,154 | max: 84,644 | trend: INCREASING (+3.62/hr))
```
▂▂▁▁▁▁▁▂▁▁▁▁▁▂▃█▂▁▁▂▂▁▁▁▄▂▁▁▂▁▂▃▂▂▁▁▂▁▂▃▄▃▂▂▁▁▁▁▁▂▄▂▃▂▂▁▁▁▂▂▁▁▁▁▁▁▁▁▁▃▃▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▃▂▂▂▃▆
```

**Heap InUse** (current: 400.3MB | avg: 230.6MB | max: 3154.1MB | trend: stable (+0.10MB/hr))
```
▄▃▂▂▁▃▃▂▁▃▁▃▃▄▃█▄▃▃▂▃▃▂▂▃▄▂▄▂▃▃▃▄▅▂▃▂▃▄▄▇▃▅▄▁▂▃▂▂▂▄▄▃▅▄▃▂▁▁▃▂▁▃▃▁▃▂▁▁▄▂▄▂▃▃▃▃▂▃▂▂▂▄▁▂▁▃▃▃▃▂▄▂▃▅▇
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 20%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 17,686 | 15,758 | +1928 | 14,154 | 84,644 | INCREASING (+3.62/hr) |
| Heap InUse | 400.3MB | 329.9MB | +70.4MB | 230.6MB | 3154.1MB | stable (+0.10MB/hr) |
| Heap Sys | 3341.5MB | 3344.1MB | -2.6MB | 2623.0MB | 6883.9MB | |
| Heap Objects | 2,242,460 | 1,549,102 | +693358 | 996,575 | 17,165,538 | |

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
| 2026-06-11 | 121 | 14,864 | 267.8MB | 428.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 15.58MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.05MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `bufio.NewWriterSize` | 8.57MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 8 | `bufio.NewReaderSize` | 7.54MB |
| 9 | `reflect.growslice` | 4.58MB |
| 10 | `aes/gcm.NewGCMForTLS13` | 3.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 163.07GB |
| 2 | `segmentio/kafka-go.makePartitions` | 160.06GB |
| 3 | `jackskj/carta.getUniqueId` | 147.21GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 130.36GB |
| 5 | `reflect.unsafe_New` | 129.78GB |
| 6 | `fmt.Sprintf` | 116.84GB |
| 7 | `fmt.(*buffer).writeString` | 102.93GB |
| 8 | `carta/value.NewCell` | 92.69GB |
| 9 | `reflect.unsafe_NewArray` | 81.72GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 76.4GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 8.38GB | 8.37GB | 8.25GB | 0B |
| `evaluation.mergeMetadata` | 4.38GB | 4.38GB | 4.31GB | 0B |
| `local.(*Client).EvaluateV2` | 12.76GB | 12.75GB | 12.57GB | 0B |
| `local.topologicalSort` | 1.76GB | 1.76GB | 1.73GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 12.20GB | 12.19GB | 12.00GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.73GB | 1.73GB | 1.72GB | 0B |
| `localEvaluation.getMapOfValue` | 12.20GB | 12.19GB | 12.00GB | 0B |
| `utils.ParseFeatureFlag` | 12.22GB | 12.21GB | 12.02GB | 0B |

**Total FF alloc (current snapshot):** 65.63GB  |  **24h avg:** 64.59GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 59.59MB | 59/3089 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 51.07MB | 86/3089 | `████████████░░░ 85%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2740/3089 | `█████████░░░░░░ 61%` |
| 4 | `runtime.mallocgc` | 30.68MB | 2740/3089 | `███████░░░░░░░░ 51%` |
| 5 | `database/sql.convertAssignRows` | 27.21MB | 106/3089 | `██████░░░░░░░░░ 45%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3089 | `████░░░░░░░░░░░ 30%` |
| 7 | `bytes.growSlice` | 15.22MB | 2121/3089 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*Transport).dialConn` | 14.4MB | 61/3089 | `███░░░░░░░░░░░░ 24%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3089 | `███░░░░░░░░░░░░ 23%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3089 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3089 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3089 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3089 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 59.25GB | 1606/3089 | `███████░░░░░░░░ 47%` |
| 5 | `experiment/local.topologicalSort` | 51.23GB | 375/3089 | `██████░░░░░░░░░ 40%` |
| 6 | `segmentio/kafka-go.makePartitions` | 50.29GB | 2463/3089 | `██████░░░░░░░░░ 40%` |
| 7 | `reflect.growslice` | 49.74GB | 2301/3089 | `█████░░░░░░░░░░ 39%` |
| 8 | `jackskj/carta.getUniqueId` | 43.64GB | 2317/3089 | `█████░░░░░░░░░░ 34%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/3089 | `█████░░░░░░░░░░ 34%` |
| 10 | `reflect.unsafe_New` | 42.62GB | 2081/3089 | `█████░░░░░░░░░░ 34%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.2x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.7x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.4x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
