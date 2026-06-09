# Overview: prod
*Last updated: 2026-06-10 00:30 IST*
*Data range: 2026-05-15T16:03 to 2026-06-10T00:30 (2688 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,336 | avg: 13,879 | max: 84,644 | trend: INCREASING (+4.14/hr))
```
▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▁▁▁▁▁▁▂▁▁▁▂▂▃▁▂▆▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▃▂▁▁▇▃▁▅▃▂▁▅▄▁▃▂▁█▅▁▂▂▂▁▁▁▁▄▁▁▁▁▁
```

**Heap InUse** (current: 278.0MB | avg: 221.0MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▂▁▂▁▁▁▂▂▂▂▂▂▁▂▁▁▁▂▁▁▂▁▂▂▂▁▂▃▃▂▃▂▃▂▃▂▂▁▂▂▃▃▄▃▃▇▃▂▁▁▁▁▁▁▂▂▁▁▁▁▁▃▄▄▂▂▂▇▃▁▅▄▂▁▆▅▁▃▄▁█▅▁▁▂▃▁▁▁▁▄▂▁▁▂▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,336 | 14,160 | +1176 | 13,879 | 84,644 | INCREASING (+4.14/hr) |
| Heap InUse | 278.0MB | 255.8MB | +22.2MB | 221.0MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3330.1MB | 3330.0MB | +0.1MB | 2517.4MB | 6883.9MB | |
| Heap Objects | 1,206,093 | 1,519,193 | -313100 | 964,420 | 17,165,538 | |

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
| 2026-06-10 | 7 | 15,051 | 266.5MB | 390.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 8.54MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 6 | `bufio.NewReaderSize` | 5.05MB |
| 7 | `bufio.NewWriterSize` | 5.03MB |
| 8 | `segmentio/kafka-go.makePartitions` | 3.54MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.01MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 113.82GB |
| 2 | `reflect.growslice` | 105.16GB |
| 3 | `jackskj/carta.getUniqueId` | 94.14GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 90.26GB |
| 5 | `reflect.unsafe_New` | 83.38GB |
| 6 | `fmt.Sprintf` | 76.38GB |
| 7 | `fmt.(*buffer).writeString` | 67.46GB |
| 8 | `carta/value.NewCell` | 59.45GB |
| 9 | `reflect.unsafe_NewArray` | 58.17GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 47.17GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 5.68GB | 5.67GB | 5.52GB | 0B |
| `evaluation.mergeMetadata` | 2.99GB | 2.98GB | 2.90GB | 0B |
| `local.(*Client).EvaluateV2` | 8.67GB | 8.66GB | 8.43GB | 0B |
| `local.topologicalSort` | 1.21GB | 1.21GB | 1.17GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 8.26GB | 8.25GB | 8.03GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.21GB | 1.21GB | 1.18GB | 0B |
| `localEvaluation.getMapOfValue` | 8.26GB | 8.25GB | 8.03GB | 0B |
| `utils.ParseFeatureFlag` | 8.27GB | 8.26GB | 8.04GB | 0B |

**Total FF alloc (current snapshot):** 44.55GB  |  **24h avg:** 43.31GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 79.04MB | 43/2688 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 59.71MB | 72/2688 | `███████████░░░░ 75%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2339/2688 | `██████░░░░░░░░░ 46%` |
| 4 | `database/sql.convertAssignRows` | 29.99MB | 94/2688 | `█████░░░░░░░░░░ 37%` |
| 5 | `runtime.mallocgc` | 27.29MB | 2339/2688 | `█████░░░░░░░░░░ 34%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2688 | `███░░░░░░░░░░░░ 22%` |
| 7 | `bytes.growSlice` | 15.34MB | 1781/2688 | `██░░░░░░░░░░░░░ 19%` |
| 8 | `net/http.(*Transport).dialConn` | 14.48MB | 53/2688 | `██░░░░░░░░░░░░░ 18%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2688 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2688 | `██░░░░░░░░░░░░░ 13%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2688 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2688 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2688 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2688 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2688 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 42.38GB | 1205/2688 | `█████░░░░░░░░░░ 33%` |
| 7 | `segmentio/kafka-go.makePartitions` | 33.44GB | 2062/2688 | `████░░░░░░░░░░░ 26%` |
| 8 | `reflect.growslice` | 31.9GB | 1900/2688 | `███░░░░░░░░░░░░ 25%` |
| 9 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2688 | `███░░░░░░░░░░░░ 22%` |
| 10 | `jackskj/carta.getUniqueId` | 27.6GB | 1916/2688 | `███░░░░░░░░░░░░ 22%` |

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
