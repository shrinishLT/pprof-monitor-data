# Overview: prod
*Last updated: 2026-06-05 09:40 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T09:40 (1359 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,014 | avg: 11,771 | max: 84,644 | trend: decreasing (-4.31/hr))
```
▂▃▃▃▂▂▁▁▄▂▁▂▃▁▁▁▃▁▂▁▁▂▂▄▃▄▆▆▁▁▁▁▁▁▂▂▁▇▃▁▁▁▂▂▂▁▁▂▃▂▃▃▂▂▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▄▄▁▁▂▁▁▃▁▁▁▂▂▂▁▃▂
```

**Heap InUse** (current: 178.0MB | avg: 179.8MB | max: 3154.1MB | trend: stable (-0.03MB/hr))
```
▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,014 | 15,655 | -641 | 11,771 | 84,644 | decreasing (-4.31/hr) |
| Heap InUse | 178.0MB | 232.0MB | -54.0MB | 179.8MB | 3154.1MB | stable (-0.03MB/hr) |
| Heap Sys | 4421.3MB | 4420.6MB | +0.7MB | 2690.4MB | 6883.9MB | |
| Heap Objects | 837,135 | 1,112,010 | -274875 | 801,781 | 17,165,538 | |

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
| 2026-06-05 | 117 | 14,856 | 238.7MB | 3154.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 9.1MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 6 | `bufio.NewReaderSize` | 3.51MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.01MB |
| 8 | `compress/flate.NewWriter` | 2.64MB |
| 9 | `segmentio/kafka-go.makePartitions` | 2.54MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 8.18GB |
| 2 | `segmentio/kafka-go.makePartitions` | 3.7GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 3.26GB |
| 4 | `jackskj/carta.getUniqueId` | 2.56GB |
| 5 | `reflect.growslice` | 2.42GB |
| 6 | `reflect.unsafe_New` | 2.14GB |
| 7 | `fmt.Sprintf` | 2.08GB |
| 8 | `reflect.unsafe_NewArray` | 1.83GB |
| 9 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 1.59GB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 1.53GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 199.20MB | 194.52MB | 154.25MB | 0B |
| `evaluation.mergeMetadata` | 101.03MB | 99.03MB | 78.01MB | 0B |
| `local.(*Client).EvaluateV2` | 296.84MB | 289.58MB | 231.96MB | 0B |
| `local.topologicalSort` | 40.45MB | 39.43MB | 33.65MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 309.07MB | 301.75MB | 234.87MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 18.01MB | 16.51MB | 20.82MB | 0B |
| `localEvaluation.getMapOfValue` | 309.07MB | 301.75MB | 234.87MB | 0B |
| `utils.ParseFeatureFlag` | 309.07MB | 301.75MB | 235.16MB | 0B |

**Total FF alloc (current snapshot):** 1.55GB  |  **24h avg:** 1.19GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 94.56MB | 31/1359 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 76.85MB | 51/1359 | `████████████░░░ 81%` |
| 3 | `database/sql.convertAssignRows` | 40.34MB | 63/1359 | `██████░░░░░░░░░ 42%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1010/1359 | `█████░░░░░░░░░░ 38%` |
| 5 | `runtime.mallocgc` | 18.01MB | 1010/1359 | `██░░░░░░░░░░░░░ 19%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1359 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `bytes.growSlice` | 14.08MB | 773/1359 | `██░░░░░░░░░░░░░ 14%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1359 | `█░░░░░░░░░░░░░░ 13%` |
| 9 | `fmt.Sprint` | 12.05MB | 2/1359 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `net/http.(*Transport).dialConn` | 11.71MB | 17/1359 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1359 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1359 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1359 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1359 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1359 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 34.27GB | 981/1359 | `████░░░░░░░░░░░ 27%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1359 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 15.18GB | 904/1359 | `█░░░░░░░░░░░░░░ 12%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.58GB | 187/1359 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `fmt.Sprintf` | 9.52GB | 559/1359 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.5x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.2x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.7x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.4x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.7x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.7x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.7x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.3x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.4x avg)
- Goroutine spike to 25,220 at 2026-05-20T02:02 (2.1x avg)
