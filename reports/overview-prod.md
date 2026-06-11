# Overview: prod
*Last updated: 2026-06-12 04:06 IST*
*Data range: 2026-05-15T16:03 to 2026-06-12T04:06 (3306 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,446 | avg: 14,336 | max: 84,644 | trend: INCREASING (+3.55/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▂▁▁▁▁▁▂▂▂▁▁▁▁▁▁▁▁▁▅▅▆█▆▄▃▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 341.2MB | avg: 236.9MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▂▃▃▃▃▁▂▁▁▂▃▂▃▁▁▁▁▂▁▁▁▁▄▄▆█▆▄▃▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▂▁▁▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,446 | 15,099 | +347 | 14,336 | 84,644 | INCREASING (+3.55/hr) |
| Heap InUse | 341.2MB | 230.0MB | +111.2MB | 236.9MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3342.2MB | 3343.2MB | -1.0MB | 2668.7MB | 6883.9MB | |
| Heap Objects | 1,843,973 | 495,796 | +1348177 | 1,016,973 | 17,165,538 | |

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
| 2026-06-12 | 50 | 14,964 | 259.1MB | 361.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 10.56MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 6 | `bufio.NewReaderSize` | 6.55MB |
| 7 | `compress/flate.NewWriter` | 4.41MB |
| 8 | `bufio.NewWriterSize` | 4.04MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.01MB |
| 10 | `segmentio/kafka-go.makePartitions` | 3.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 184.89GB |
| 2 | `reflect.growslice` | 182.09GB |
| 3 | `jackskj/carta.getUniqueId` | 165.9GB |
| 4 | `reflect.unsafe_New` | 146.18GB |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 144.89GB |
| 6 | `fmt.Sprintf` | 137.01GB |
| 7 | `fmt.(*buffer).writeString` | 114.24GB |
| 8 | `carta/value.NewCell` | 104.43GB |
| 9 | `reflect.unsafe_NewArray` | 94.3GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 84.29GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 10.25GB | 10.25GB | 10.11GB | 0B |
| `evaluation.mergeMetadata` | 5.35GB | 5.35GB | 5.28GB | 0B |
| `local.(*Client).EvaluateV2` | 15.61GB | 15.60GB | 15.40GB | 0B |
| `local.topologicalSort` | 2.17GB | 2.17GB | 2.14GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 14.88GB | 14.87GB | 14.67GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 2.16GB | 2.16GB | 2.13GB | 0B |
| `localEvaluation.getMapOfValue` | 14.88GB | 14.87GB | 14.67GB | 0B |
| `utils.ParseFeatureFlag` | 14.91GB | 14.90GB | 14.69GB | 0B |

**Total FF alloc (current snapshot):** 80.21GB  |  **24h avg:** 79.09GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 57.92MB | 61/3306 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 49.07MB | 90/3306 | `████████████░░░ 84%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2957/3306 | `█████████░░░░░░ 63%` |
| 4 | `runtime.mallocgc` | 32.13MB | 2957/3306 | `████████░░░░░░░ 55%` |
| 5 | `database/sql.convertAssignRows` | 26.19MB | 111/3306 | `██████░░░░░░░░░ 45%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3306 | `████░░░░░░░░░░░ 31%` |
| 7 | `bytes.growSlice` | 15.58MB | 2323/3306 | `████░░░░░░░░░░░ 26%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3306 | `███░░░░░░░░░░░░ 24%` |
| 9 | `net/http.(*Transport).dialConn` | 13.92MB | 74/3306 | `███░░░░░░░░░░░░ 24%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3306 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3306 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3306 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3306 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 69.18GB | 1823/3306 | `████████░░░░░░░ 55%` |
| 5 | `reflect.growslice` | 60.74GB | 2518/3306 | `███████░░░░░░░░ 48%` |
| 6 | `segmentio/kafka-go.makePartitions` | 60.19GB | 2680/3306 | `███████░░░░░░░░ 48%` |
| 7 | `jackskj/carta.getUniqueId` | 53.69GB | 2534/3306 | `██████░░░░░░░░░ 42%` |
| 8 | `reflect.unsafe_New` | 51.99GB | 2298/3306 | `██████░░░░░░░░░ 41%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/3306 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 46.39GB | 2045/3306 | `█████░░░░░░░░░░ 37%` |

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
