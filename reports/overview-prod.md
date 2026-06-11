# Overview: prod
*Last updated: 2026-06-12 01:06 IST*
*Data range: 2026-05-15T16:03 to 2026-06-12T01:06 (3270 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,736 | avg: 14,328 | max: 84,644 | trend: INCREASING (+3.64/hr))
```
▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▂▂▂▂▂▃▁▁▁▁▁▁▁▁▂▂▂▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▂▁▁▁▁▁▂▂▂▁▁▁▁▁▁▁▁▁▅▅▆█▆▄▃▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁
```

**Heap InUse** (current: 291.5MB | avg: 236.7MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▁▁▂▁▁▂▂▂▂▂▁▁▂▁▁▁▂▃▃▃▂▃▁▂▂▂▁▁▁▁▂▂▃▃▄▃▁▁▁▁▁▁▁▁▁▁▁▁▂▃▃▃▃▁▂▁▁▂▃▂▂▁▁▁▁▁▁▁▁▁▄▄▆█▆▄▃▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,736 | 16,209 | -1473 | 14,328 | 84,644 | INCREASING (+3.64/hr) |
| Heap InUse | 291.5MB | 353.3MB | -61.8MB | 236.7MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3307.7MB | 3306.1MB | +1.6MB | 2661.5MB | 6883.9MB | |
| Heap Objects | 1,446,595 | 1,336,005 | +110590 | 1,016,862 | 17,165,538 | |

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
| 2026-06-12 | 14 | 14,885 | 250.8MB | 353.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 5.03MB |
| 6 | `compress/flate.NewWriter` | 4.41MB |
| 7 | `bytes.growSlice` | 4.37MB |
| 8 | `bufio.NewWriterSize` | 4.04MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.52MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 180.74GB |
| 2 | `reflect.growslice` | 179.44GB |
| 3 | `jackskj/carta.getUniqueId` | 163.48GB |
| 4 | `reflect.unsafe_New` | 143.97GB |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 143.79GB |
| 6 | `fmt.Sprintf` | 134.29GB |
| 7 | `fmt.(*buffer).writeString` | 112.9GB |
| 8 | `carta/value.NewCell` | 102.82GB |
| 9 | `reflect.unsafe_NewArray` | 92.21GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 82.6GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 10.03GB | 10.03GB | 9.89GB | 0B |
| `evaluation.mergeMetadata` | 5.24GB | 5.24GB | 5.16GB | 0B |
| `local.(*Client).EvaluateV2` | 15.27GB | 15.26GB | 15.05GB | 0B |
| `local.topologicalSort` | 2.12GB | 2.12GB | 2.09GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 14.55GB | 14.54GB | 14.34GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 2.12GB | 2.12GB | 2.09GB | 0B |
| `localEvaluation.getMapOfValue` | 14.55GB | 14.54GB | 14.34GB | 0B |
| `utils.ParseFeatureFlag` | 14.57GB | 14.56GB | 14.36GB | 0B |

**Total FF alloc (current snapshot):** 78.45GB  |  **24h avg:** 77.33GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.8MB | 60/3270 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 49.51MB | 89/3270 | `████████████░░░ 84%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2921/3270 | `█████████░░░░░░ 62%` |
| 4 | `runtime.mallocgc` | 31.91MB | 2921/3270 | `████████░░░░░░░ 54%` |
| 5 | `database/sql.convertAssignRows` | 26.83MB | 108/3270 | `██████░░░░░░░░░ 45%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3270 | `████░░░░░░░░░░░ 30%` |
| 7 | `bytes.growSlice` | 15.68MB | 2292/3270 | `████░░░░░░░░░░░ 26%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3270 | `███░░░░░░░░░░░░ 24%` |
| 9 | `net/http.(*Transport).dialConn` | 13.92MB | 74/3270 | `███░░░░░░░░░░░░ 23%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3270 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3270 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3270 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3270 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 67.66GB | 1787/3270 | `████████░░░░░░░ 54%` |
| 5 | `reflect.growslice` | 58.99GB | 2482/3270 | `███████░░░░░░░░ 47%` |
| 6 | `segmentio/kafka-go.makePartitions` | 58.52GB | 2644/3270 | `███████░░░░░░░░ 46%` |
| 7 | `jackskj/carta.getUniqueId` | 52.09GB | 2498/3270 | `██████░░░░░░░░░ 41%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/3270 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 50.51GB | 2262/3270 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 45.18GB | 2009/3270 | `█████░░░░░░░░░░ 36%` |

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
