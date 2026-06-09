# Overview: prod
*Last updated: 2026-06-10 01:10 IST*
*Data range: 2026-05-15T16:03 to 2026-06-10T01:10 (2696 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 19,088 | avg: 13,882 | max: 84,644 | trend: INCREASING (+4.12/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▁▁▁▁▁▁▂▁▁▁▂▂▃▁▂▆▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▃▂▁▁▇▃▁▅▃▂▁▅▄▁▃▂▁█▅▁▂▂▂▁▁▁▁▄▁▁▁▁▁▁▁▁▁▁▁▁▄
```

**Heap InUse** (current: 364.8MB | avg: 221.1MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▂▂▂▂▁▂▁▁▁▂▁▁▂▁▂▂▂▁▂▃▃▂▃▂▃▂▃▂▂▁▂▂▃▃▄▃▃▇▃▂▁▁▁▁▁▁▂▂▁▁▁▁▁▃▄▄▂▂▂▇▃▁▅▄▂▁▆▅▁▃▄▁█▅▁▁▂▃▁▁▁▁▄▂▁▁▂▂▁▁▁▂▁▁▂▄
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 22%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 19,088 | 14,243 | +4845 | 13,882 | 84,644 | INCREASING (+4.12/hr) |
| Heap InUse | 364.8MB | 286.1MB | +78.7MB | 221.1MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3330.7MB | 3330.8MB | -0.1MB | 2519.8MB | 6883.9MB | |
| Heap Objects | 1,928,864 | 1,761,473 | +167391 | 965,173 | 17,165,538 | |

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
| 2026-06-10 | 15 | 14,996 | 259.6MB | 390.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 18.64MB |
| 4 | `bufio.NewWriterSize` | 12.06MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 10.55MB |
| 6 | `bufio.NewReaderSize` | 10.05MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 9 | `compress/flate.NewWriter` | 5.29MB |
| 10 | `crypto/tls.Client` | 3.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 114.75GB |
| 2 | `reflect.growslice` | 105.22GB |
| 3 | `jackskj/carta.getUniqueId` | 94.2GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 90.27GB |
| 5 | `reflect.unsafe_New` | 83.44GB |
| 6 | `fmt.Sprintf` | 76.55GB |
| 7 | `fmt.(*buffer).writeString` | 67.5GB |
| 8 | `carta/value.NewCell` | 59.5GB |
| 9 | `reflect.unsafe_NewArray` | 58.63GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 47.18GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 5.73GB | 5.72GB | 5.58GB | 0B |
| `evaluation.mergeMetadata` | 3.02GB | 3.01GB | 2.93GB | 0B |
| `local.(*Client).EvaluateV2` | 8.74GB | 8.73GB | 8.52GB | 0B |
| `local.topologicalSort` | 1.22GB | 1.22GB | 1.19GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 8.32GB | 8.31GB | 8.11GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.22GB | 1.22GB | 1.19GB | 0B |
| `localEvaluation.getMapOfValue` | 8.32GB | 8.31GB | 8.11GB | 0B |
| `utils.ParseFeatureFlag` | 8.33GB | 8.33GB | 8.12GB | 0B |

**Total FF alloc (current snapshot):** 44.89GB  |  **24h avg:** 43.76GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 79.04MB | 43/2696 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 59.71MB | 72/2696 | `███████████░░░░ 75%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2347/2696 | `██████░░░░░░░░░ 46%` |
| 4 | `database/sql.convertAssignRows` | 29.99MB | 94/2696 | `█████░░░░░░░░░░ 37%` |
| 5 | `runtime.mallocgc` | 27.37MB | 2347/2696 | `█████░░░░░░░░░░ 34%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2696 | `███░░░░░░░░░░░░ 22%` |
| 7 | `bytes.growSlice` | 15.32MB | 1786/2696 | `██░░░░░░░░░░░░░ 19%` |
| 8 | `net/http.(*Transport).dialConn` | 14.48MB | 53/2696 | `██░░░░░░░░░░░░░ 18%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2696 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2696 | `██░░░░░░░░░░░░░ 13%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2696 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2696 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2696 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2696 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2696 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 42.7GB | 1213/2696 | `█████░░░░░░░░░░ 34%` |
| 7 | `segmentio/kafka-go.makePartitions` | 33.75GB | 2070/2696 | `████░░░░░░░░░░░ 26%` |
| 8 | `reflect.growslice` | 32.2GB | 1908/2696 | `███░░░░░░░░░░░░ 25%` |
| 9 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2696 | `███░░░░░░░░░░░░ 22%` |
| 10 | `jackskj/carta.getUniqueId` | 27.88GB | 1924/2696 | `███░░░░░░░░░░░░ 22%` |

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
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.5x avg)
