# Overview: prod
*Last updated: 2026-06-12 01:46 IST*
*Data range: 2026-05-15T16:03 to 2026-06-12T01:45 (3278 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,741 | avg: 14,330 | max: 84,644 | trend: INCREASING (+3.62/hr))
```
▂▁▁▁▁▁▁▁▂▂▂▂▂▃▁▁▁▁▁▁▁▁▂▂▂▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▂▁▁▁▁▁▂▂▂▁▁▁▁▁▁▁▁▁▅▅▆█▆▄▃▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 295.6MB | avg: 236.7MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▂▂▁▁▂▁▁▁▂▃▃▃▂▃▁▂▂▂▁▁▁▁▂▂▃▃▄▃▁▁▁▁▁▁▁▁▁▁▁▁▂▃▃▃▃▁▂▁▁▂▃▂▂▁▁▁▁▁▁▁▁▁▄▄▆█▆▄▃▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,741 | 14,621 | +120 | 14,330 | 84,644 | INCREASING (+3.62/hr) |
| Heap InUse | 295.6MB | 233.6MB | +62.0MB | 236.7MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3311.8MB | 3311.6MB | +0.2MB | 2663.1MB | 6883.9MB | |
| Heap Objects | 1,618,885 | 673,988 | +944897 | 1,017,146 | 17,165,538 | |

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
| 2026-06-12 | 22 | 14,875 | 257.6MB | 353.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `bytes.growSlice` | 5.1MB |
| 6 | `compress/flate.NewWriter` | 3.53MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.01MB |
| 8 | `bufio.NewWriterSize` | 2.54MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `segmentio/kafka-go.makePartitions` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 181.64GB |
| 2 | `reflect.growslice` | 179.69GB |
| 3 | `jackskj/carta.getUniqueId` | 163.75GB |
| 4 | `reflect.unsafe_New` | 144.2GB |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 143.82GB |
| 6 | `fmt.Sprintf` | 134.72GB |
| 7 | `fmt.(*buffer).writeString` | 113.02GB |
| 8 | `carta/value.NewCell` | 102.98GB |
| 9 | `reflect.unsafe_NewArray` | 92.68GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 82.76GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 10.09GB | 10.08GB | 9.95GB | 0B |
| `evaluation.mergeMetadata` | 5.27GB | 5.26GB | 5.19GB | 0B |
| `local.(*Client).EvaluateV2` | 15.36GB | 15.35GB | 15.14GB | 0B |
| `local.topologicalSort` | 2.14GB | 2.13GB | 2.10GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 14.63GB | 14.63GB | 14.42GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 2.13GB | 2.13GB | 2.10GB | 0B |
| `localEvaluation.getMapOfValue` | 14.63GB | 14.63GB | 14.42GB | 0B |
| `utils.ParseFeatureFlag` | 14.66GB | 14.65GB | 14.44GB | 512.56kB |

**Total FF alloc (current snapshot):** 78.91GB  |  **24h avg:** 77.77GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.8MB | 60/3278 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 49.51MB | 89/3278 | `████████████░░░ 84%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2929/3278 | `█████████░░░░░░ 62%` |
| 4 | `runtime.mallocgc` | 31.96MB | 2929/3278 | `████████░░░░░░░ 54%` |
| 5 | `database/sql.convertAssignRows` | 26.83MB | 108/3278 | `██████░░░░░░░░░ 45%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3278 | `████░░░░░░░░░░░ 30%` |
| 7 | `bytes.growSlice` | 15.65MB | 2300/3278 | `███░░░░░░░░░░░░ 26%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3278 | `███░░░░░░░░░░░░ 24%` |
| 9 | `net/http.(*Transport).dialConn` | 13.92MB | 74/3278 | `███░░░░░░░░░░░░ 23%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3278 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3278 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3278 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3278 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 68.0GB | 1795/3278 | `████████░░░░░░░ 54%` |
| 5 | `reflect.growslice` | 59.38GB | 2490/3278 | `███████░░░░░░░░ 47%` |
| 6 | `segmentio/kafka-go.makePartitions` | 58.89GB | 2652/3278 | `███████░░░░░░░░ 47%` |
| 7 | `jackskj/carta.getUniqueId` | 52.44GB | 2506/3278 | `██████░░░░░░░░░ 41%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/3278 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 50.84GB | 2270/3278 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 45.45GB | 2017/3278 | `█████░░░░░░░░░░ 36%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
