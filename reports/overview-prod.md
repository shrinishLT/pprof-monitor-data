# Overview: prod
*Last updated: 2026-06-09 22:45 IST*
*Data range: 2026-05-15T16:03 to 2026-06-09T22:45 (2667 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 20,382 | avg: 13,863 | max: 84,644 | trend: INCREASING (+4.16/hr))
```
▂▂▂▁▁▁▂▁▂▃▂▁▁▁▁▁▁▁▂▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▁▁▁▁▁▁▂▁▁▁▂▂▃▁▂▆▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▃▂▁▁█▃▁▅▃▂▁▅
```

**Heap InUse** (current: 498.5MB | avg: 220.4MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▂▄▂▂▂▂▄▂▂▅▃▂▂▂▂▁▁▁▃▂▁▂▁▂▂▁▁▂▂▂▂▂▂▁▂▁▁▁▂▁▁▂▁▂▂▂▁▂▃▃▂▃▂▃▂▃▂▂▁▂▂▃▃▄▃▃▇▃▂▁▁▁▁▁▁▂▂▁▁▂▁▁▃▅▄▂▂▂█▃▁▅▄▂▁▆
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 24%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 20,382 | 14,860 | +5522 | 13,863 | 84,644 | INCREASING (+4.16/hr) |
| Heap InUse | 498.5MB | 216.8MB | +281.7MB | 220.4MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3326.2MB | 3330.5MB | -4.3MB | 2511.0MB | 6883.9MB | |
| Heap Objects | 2,402,722 | 525,649 | +1877073 | 962,653 | 17,165,538 | |

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
| 2026-06-09 | 274 | 16,146 | 304.1MB | 1487.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 35.18MB |
| 4 | `bufio.NewWriterSize` | 15.59MB |
| 5 | `bufio.NewReaderSize` | 14.07MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.56MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 9 | `net/http.(*Transport).queueForIdleConn` | 7.01MB |
| 10 | `aes/gcm.NewGCMForTLS13` | 7.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 111.41GB |
| 2 | `reflect.growslice` | 105.04GB |
| 3 | `jackskj/carta.getUniqueId` | 93.94GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 90.25GB |
| 5 | `reflect.unsafe_New` | 83.22GB |
| 6 | `fmt.Sprintf` | 74.39GB |
| 7 | `fmt.(*buffer).writeString` | 67.42GB |
| 8 | `carta/value.NewCell` | 59.36GB |
| 9 | `reflect.unsafe_NewArray` | 56.98GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 47.12GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 5.55GB | 5.54GB | 5.34GB | 0B |
| `evaluation.mergeMetadata` | 2.91GB | 2.91GB | 2.81GB | 0B |
| `local.(*Client).EvaluateV2` | 8.47GB | 8.46GB | 8.16GB | 0B |
| `local.topologicalSort` | 1.18GB | 1.18GB | 1.14GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 8.06GB | 8.05GB | 7.76GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.19GB | 1.19GB | 1.14GB | 0B |
| `localEvaluation.getMapOfValue` | 8.06GB | 8.05GB | 7.76GB | 0B |
| `utils.ParseFeatureFlag` | 8.07GB | 8.06GB | 7.77GB | 0B |

**Total FF alloc (current snapshot):** 43.49GB  |  **24h avg:** 41.88GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 79.04MB | 43/2667 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 61.25MB | 70/2667 | `███████████░░░░ 77%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2318/2667 | `██████░░░░░░░░░ 46%` |
| 4 | `database/sql.convertAssignRows` | 29.99MB | 94/2667 | `█████░░░░░░░░░░ 37%` |
| 5 | `runtime.mallocgc` | 27.08MB | 2318/2667 | `█████░░░░░░░░░░ 34%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2667 | `███░░░░░░░░░░░░ 22%` |
| 7 | `bytes.growSlice` | 15.33MB | 1764/2667 | `██░░░░░░░░░░░░░ 19%` |
| 8 | `net/http.(*Transport).dialConn` | 14.48MB | 53/2667 | `██░░░░░░░░░░░░░ 18%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2667 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `crypto/tls.Client` | 10.64MB | 73/2667 | `██░░░░░░░░░░░░░ 13%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2667 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2667 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2667 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2667 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2667 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 41.53GB | 1184/2667 | `████░░░░░░░░░░░ 33%` |
| 7 | `segmentio/kafka-go.makePartitions` | 32.63GB | 2041/2667 | `███░░░░░░░░░░░░ 26%` |
| 8 | `reflect.growslice` | 31.08GB | 1879/2667 | `███░░░░░░░░░░░░ 24%` |
| 9 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2667 | `███░░░░░░░░░░░░ 22%` |
| 10 | `jackskj/carta.getUniqueId` | 26.86GB | 1895/2667 | `███░░░░░░░░░░░░ 21%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.6x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.1x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.0x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.0x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.6x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.3x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.8x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.6x avg)
