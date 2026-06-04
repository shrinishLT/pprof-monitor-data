# Overview: prod
*Last updated: 2026-06-04 21:05 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T21:05 (1208 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,563 | avg: 11,359 | max: 84,644 | trend: decreasing (-10.71/hr))
```
▃▃▂▁▄▅▅▄▁▁▂▃▄▃▃▂▁▂▃▅▆▄▅▅▆▄▃▂▄▅▂▂▁▂▃▂▁▁▃▅▄▄▅█▃▁▂▃▂▂▁▁▁▁▁▂▂▂▁▁▁▂▁▁▁▁▂▂▁▁▁▁▁▁▁▁▃▂▃▂▃▂▂▂▄▄▅▄▂▂▃▁▂▁▁▁
```

**Heap InUse** (current: 145.1MB | avg: 172.4MB | max: 2823.8MB | trend: stable (-0.13MB/hr))
```
▃▃▂▁▂▃▃▄▁▂▁▂▃▂▂▂▂█▂▃▄▂▃▄▅▄▃▂▃▄▂▂▁▁▃▃▁▁▂▂▃▃▅▄▃▁▂▃▁▁▁▁▁▁▁▂▂▁▁▁▁▁▂▁▁▁▂▁▁▁▂▁▁▁▁▁▂▂▂▂▂▁▁▂▃▃▄▂▂▂▂▂▁▂▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,563 | 14,546 | +17 | 11,359 | 84,644 | decreasing (-10.71/hr) |
| Heap InUse | 145.1MB | 169.0MB | -23.9MB | 172.4MB | 2823.8MB | stable (-0.13MB/hr) |
| Heap Sys | 3854.3MB | 3854.4MB | -0.1MB | 2650.5MB | 6883.9MB | |
| Heap Objects | 422,072 | 621,493 | -199421 | 745,838 | 14,090,816 | |

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
| 2026-06-04 | 254 | 16,659 | 268.9MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `bufio.NewReaderSize` | 4.55MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.53MB |
| 8 | `bytes.growSlice` | 2.51MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 15.08GB |
| 2 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 11.56GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 5.98GB |
| 4 | `fmt.Sprintf` | 5.64GB |
| 5 | `segmentio/kafka-go.makePartitions` | 5.5GB |
| 6 | `database/sql.convertAssignRows` | 4.24GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 4.06GB |
| 8 | `jackskj/carta.getUniqueId` | 3.29GB |
| 9 | `reflect.unsafe_NewArray` | 2.85GB |
| 10 | `strconv.appendQuotedWith` | 2.8GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 480.09MB | 472.41MB | 261.48MB | 0B |
| `evaluation.mergeMetadata` | 243.56MB | 239.56MB | 135.79MB | 0B |
| `local.(*Client).EvaluateV2` | 759.62MB | 747.26MB | 408.58MB | 0B |
| `local.topologicalSort` | 103.20MB | 102.18MB | 58.88MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 671.99MB | 661.17MB | 364.56MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 154.83MB | 152.77MB | 82.89MB | 0B |
| `localEvaluation.getMapOfValue` | 671.99MB | 661.17MB | 364.56MB | 0B |
| `utils.ParseFeatureFlag` | 672.49MB | 661.67MB | 364.58MB | 0B |

**Total FF alloc (current snapshot):** 3.67GB  |  **24h avg:** 1.99GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 64.9MB | 40/1208 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 58.21MB | 24/1208 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 859/1208 | `████████░░░░░░░ 56%` |
| 4 | `database/sql.convertAssignRows` | 31.07MB | 52/1208 | `███████░░░░░░░░ 47%` |
| 5 | `runtime.mallocgc` | 19.46MB | 859/1208 | `████░░░░░░░░░░░ 29%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1208 | `████░░░░░░░░░░░ 27%` |
| 7 | `bytes.growSlice` | 15.25MB | 645/1208 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1208 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1208 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1208 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1208 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1208 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1208 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1208 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1208 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 38.35GB | 831/1208 | `████░░░░░░░░░░░ 30%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1208 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 17.27GB | 754/1208 | `██░░░░░░░░░░░░░ 13%` |
| 9 | `fmt.Sprintf` | 11.25GB | 450/1208 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `segmentio/kafka-go.makePartitions` | 10.3GB | 592/1208 | `█░░░░░░░░░░░░░░ 8%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (11.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.5x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.5x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.8x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.5x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.9x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.0x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.8x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.4x avg)
