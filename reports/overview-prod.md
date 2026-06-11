# Overview: prod
*Last updated: 2026-06-11 20:02 IST*
*Data range: 2026-05-15T16:03 to 2026-06-11T20:02 (3209 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 19,306 | avg: 14,282 | max: 84,644 | trend: INCREASING (+3.68/hr))
```
▁▁▁▁▁▁▁▂▃▃▃▃▂▁▁▁▁▁▂▁▂▂▂▂▂▃▂▁▁▁▂▁▁▁▁▁▁▁▁▁▃▁▂▂▂▂▂▂▂▁▁▁▁▁▄▂▂▁▁▁▁▂▂▃▂▂▃▄▄▄▂▃▃▂▁▁▂▅▇▆▅▄█▂▃▃▄▁▁▁▂▅▇▆▇▇
```

**Heap InUse** (current: 500.8MB | avg: 235.1MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▂▃▂▃▂▁▁▃▄▃▃▂▄▂▃▁▂▂▄▃▂▃▁▃▂▃▄▃▂▁▄▁▂▃▂▂▁▁▃▁▃▁▃▂▃▂▂▄▂▃▂▁▁▁▆▃▂▂▂▁▂▂▂▄▃▂▄▄▄▄▄▂▃▃▁▂▃▄▇▆▅▄▆▃▄▃▄▂▁▂▂▄▅▆▇█
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 22%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 19,306 | 18,956 | +350 | 14,282 | 84,644 | INCREASING (+3.68/hr) |
| Heap InUse | 500.8MB | 467.8MB | +33.0MB | 235.1MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3326.7MB | 3329.5MB | -2.8MB | 2649.0MB | 6883.9MB | |
| Heap Objects | 2,383,338 | 2,213,849 | +169489 | 1,011,535 | 17,165,538 | |

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
| 2026-06-11 | 241 | 16,211 | 308.5MB | 1403.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `bytes.growSlice` | 41.55MB |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 4 | `bufio.NewReaderSize` | 15.57MB |
| 5 | `bufio.NewWriterSize` | 15.07MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 14.07MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 5.0MB |
| 10 | `compress/flate.NewWriter` | 4.41MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 178.19GB |
| 2 | `segmentio/kafka-go.makePartitions` | 173.82GB |
| 3 | `jackskj/carta.getUniqueId` | 161.62GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 142.88GB |
| 5 | `reflect.unsafe_New` | 142.4GB |
| 6 | `fmt.Sprintf` | 129.34GB |
| 7 | `fmt.(*buffer).writeString` | 112.13GB |
| 8 | `carta/value.NewCell` | 101.73GB |
| 9 | `reflect.unsafe_NewArray` | 88.69GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 81.64GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 9.58GB | 9.57GB | 9.31GB | 0B |
| `evaluation.mergeMetadata` | 5.01GB | 5.00GB | 4.86GB | 0B |
| `local.(*Client).EvaluateV2` | 14.58GB | 14.56GB | 14.18GB | 0B |
| `local.topologicalSort` | 2.02GB | 2.01GB | 1.96GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 13.91GB | 13.89GB | 13.54GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 2.01GB | 2.01GB | 1.94GB | 0B |
| `localEvaluation.getMapOfValue` | 13.91GB | 13.89GB | 13.54GB | 0B |
| `utils.ParseFeatureFlag` | 13.93GB | 13.91GB | 13.56GB | 0B |

**Total FF alloc (current snapshot):** 74.95GB  |  **24h avg:** 72.88GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.8MB | 60/3209 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 50.04MB | 88/3209 | `████████████░░░ 85%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2860/3209 | `█████████░░░░░░ 62%` |
| 4 | `runtime.mallocgc` | 31.51MB | 2860/3209 | `████████░░░░░░░ 53%` |
| 5 | `database/sql.convertAssignRows` | 27.04MB | 107/3209 | `██████░░░░░░░░░ 45%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3209 | `████░░░░░░░░░░░ 30%` |
| 7 | `bytes.growSlice` | 15.61MB | 2235/3209 | `███░░░░░░░░░░░░ 26%` |
| 8 | `net/http.(*Transport).dialConn` | 14.13MB | 71/3209 | `███░░░░░░░░░░░░ 24%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3209 | `███░░░░░░░░░░░░ 24%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3209 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3209 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3209 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3209 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 64.98GB | 1726/3209 | `███████░░░░░░░░ 51%` |
| 5 | `reflect.growslice` | 55.97GB | 2421/3209 | `██████░░░░░░░░░ 44%` |
| 6 | `segmentio/kafka-go.makePartitions` | 55.71GB | 2583/3209 | `██████░░░░░░░░░ 44%` |
| 7 | `experiment/local.topologicalSort` | 51.23GB | 375/3209 | `██████░░░░░░░░░ 40%` |
| 8 | `jackskj/carta.getUniqueId` | 49.32GB | 2437/3209 | `█████░░░░░░░░░░ 39%` |
| 9 | `reflect.unsafe_New` | 47.94GB | 2201/3209 | `█████░░░░░░░░░░ 38%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/3209 | `█████░░░░░░░░░░ 34%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.3x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
