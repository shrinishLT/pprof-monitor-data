# Overview: prod
*Last updated: 2026-06-05 02:25 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T02:25 (1272 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,024 | avg: 11,561 | max: 84,644 | trend: decreasing (-7.37/hr))
```
▁▁▂▂▁▁▁▁▁▁▁▁▃▂▃▂▃▂▂▂▃▄▅▄▂▂▃▁▂▁▁▁▁▁▁▃▅█▇▅▆▂▂▂▁▁▁▁▁▁▂▁▁▁▁▁▁▁▂▄▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▄▂▁▁▁▁▁▁▁▁▂▂▁▂▂▂▁▁▁▁▂
```

**Heap InUse** (current: 283.4MB | avg: 177.1MB | max: 3154.1MB | trend: stable (-0.07MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,024 | 14,713 | +1311 | 11,561 | 84,644 | decreasing (-7.37/hr) |
| Heap InUse | 283.4MB | 183.7MB | +99.7MB | 177.1MB | 3154.1MB | stable (-0.07MB/hr) |
| Heap Sys | 4656.3MB | 4656.0MB | +0.3MB | 2677.4MB | 6883.9MB | |
| Heap Objects | 1,735,420 | 1,031,286 | +704134 | 775,658 | 17,165,538 | |

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
| 2026-06-05 | 30 | 14,889 | 292.1MB | 3154.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 14.58MB |
| 3 | `runtime.mallocgc` | 11.01MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 6.03MB |
| 6 | `bufio.NewReaderSize` | 5.54MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 8 | `bufio.NewWriterSize` | 3.51MB |
| 9 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 10 | `compress/flate.NewWriter` | 2.64MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 16.55GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 6.58GB |
| 3 | `segmentio/kafka-go.makePartitions` | 4.58GB |
| 4 | `fmt.Sprintf` | 2.99GB |
| 5 | `reflect.growslice` | 2.79GB |
| 6 | `jackskj/carta.getUniqueId` | 2.75GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.68GB |
| 8 | `reflect.unsafe_New` | 2.41GB |
| 9 | `reflect.unsafe_NewArray` | 2.4GB |
| 10 | `database/sql.convertAssignRows` | 2.16GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 273.63MB | 266.11MB | 198.30MB | 0B |
| `evaluation.mergeMetadata` | 137.03MB | 132.53MB | 102.08MB | 0B |
| `local.(*Client).EvaluateV2` | 399.09MB | 390.03MB | 291.22MB | 0B |
| `local.topologicalSort` | 59.21MB | 58.71MB | 41.55MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 376.74MB | 368.67MB | 264.26MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 53.65MB | 52.65MB | 49.76MB | 0B |
| `localEvaluation.getMapOfValue` | 376.74MB | 368.67MB | 264.26MB | 0B |
| `utils.ParseFeatureFlag` | 376.74MB | 368.67MB | 264.31MB | 0B |

**Total FF alloc (current snapshot):** 2.00GB  |  **24h avg:** 1.44GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 79.25MB | 26/1272 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 75.68MB | 42/1272 | `██████████████░ 95%` |
| 3 | `database/sql.convertAssignRows` | 37.1MB | 54/1272 | `███████░░░░░░░░ 46%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 923/1272 | `██████░░░░░░░░░ 46%` |
| 5 | `runtime.mallocgc` | 18.86MB | 923/1272 | `███░░░░░░░░░░░░ 23%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1272 | `███░░░░░░░░░░░░ 22%` |
| 7 | `bytes.growSlice` | 14.85MB | 700/1272 | `██░░░░░░░░░░░░░ 18%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1272 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1272 | `██░░░░░░░░░░░░░ 15%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1272 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1272 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1272 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1272 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1272 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1272 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 36.37GB | 895/1272 | `████░░░░░░░░░░░ 29%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1272 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 16.25GB | 818/1272 | `█░░░░░░░░░░░░░░ 12%` |
| 9 | `fmt.Sprintf` | 10.33GB | 510/1272 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.77GB | 175/1272 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.7x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.3x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.7x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.4x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.8x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.8x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.0x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.7x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.3x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.4x avg)
