# Overview: prod
*Last updated: 2026-06-05 14:20 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T14:20 (1415 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,028 | avg: 12,091 | max: 84,644 | trend: decreasing (-1.25/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▅▃▄▆▆█▆▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 215.0MB | avg: 185.2MB | max: 3154.1MB | trend: stable (+0.02MB/hr))
```
▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▅▄▄▅▆▆█▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,028 | 15,265 | -237 | 12,091 | 84,644 | decreasing (-1.25/hr) |
| Heap InUse | 215.0MB | 176.5MB | +38.5MB | 185.2MB | 3154.1MB | stable (+0.02MB/hr) |
| Heap Sys | 1055.2MB | 1055.0MB | +0.2MB | 2665.2MB | 6883.9MB | |
| Heap Objects | 1,177,281 | 655,393 | +521888 | 823,423 | 17,165,538 | |

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
| 2026-06-05 | 173 | 16,478 | 264.0MB | 3154.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 10.64MB |
| 3 | `runtime.mallocgc` | 10.58MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 6 | `compress/flate.NewWriter` | 4.41MB |
| 7 | `bufio.NewReaderSize` | 3.03MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.51MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `bufio.NewWriterSize` | 2.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 5.56GB |
| 2 | `jackskj/carta.getUniqueId` | 4.99GB |
| 3 | `reflect.unsafe_New` | 4.44GB |
| 4 | `segmentio/kafka-go.makePartitions` | 4.01GB |
| 5 | `fmt.(*buffer).writeString` | 3.55GB |
| 6 | `fmt.Sprintf` | 3.22GB |
| 7 | `carta/value.NewCell` | 3.21GB |
| 8 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 3.14GB |
| 9 | `dotlapse-event-service/project.ApplyPagination` | 2.83GB |
| 10 | `reflect.unsafe_NewArray` | 2.09GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 266.92MB | 263.86MB | 164.78MB | 0B |
| `evaluation.mergeMetadata` | 135.53MB | 134.03MB | 82.78MB | 0B |
| `local.(*Client).EvaluateV2` | 425.56MB | 420.43MB | 255.56MB | 0B |
| `local.topologicalSort` | 66.22MB | 65.21MB | 35.97MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 403.53MB | 398.44MB | 255.36MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 59.99MB | 58.45MB | 25.19MB | 0B |
| `localEvaluation.getMapOfValue` | 403.53MB | 398.44MB | 255.36MB | 0B |
| `utils.ParseFeatureFlag` | 404.03MB | 398.94MB | 255.48MB | 0B |

**Total FF alloc (current snapshot):** 2.11GB  |  **24h avg:** 1.30GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 98.34MB | 32/1415 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 76.97MB | 52/1415 | `███████████░░░░ 78%` |
| 3 | `database/sql.convertAssignRows` | 40.41MB | 65/1415 | `██████░░░░░░░░░ 41%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1066/1415 | `█████░░░░░░░░░░ 37%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1415 | `██░░░░░░░░░░░░░ 18%` |
| 6 | `runtime.mallocgc` | 17.83MB | 1066/1415 | `██░░░░░░░░░░░░░ 18%` |
| 7 | `bytes.growSlice` | 15.26MB | 825/1415 | `██░░░░░░░░░░░░░ 15%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1415 | `█░░░░░░░░░░░░░░ 12%` |
| 9 | `net/http.(*Transport).dialConn` | 12.06MB | 24/1415 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1415 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1415 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1415 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1415 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1415 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1415 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 32.64GB | 1037/1415 | `███░░░░░░░░░░░░ 26%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1415 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.82GB | 928/1415 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.49GB | 203/1415 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `fmt.Sprintf` | 9.09GB | 599/1415 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.0x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.6x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.3x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.7x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.6x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.6x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.2x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.2x avg)
- Goroutine spike to 25,220 at 2026-05-20T02:02 (2.1x avg)
