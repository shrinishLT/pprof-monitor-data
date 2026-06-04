# Overview: prod
*Last updated: 2026-06-04 21:15 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T21:15 (1210 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,326 | avg: 11,365 | max: 84,644 | trend: decreasing (-10.60/hr))
```
▂▁▄▅▅▄▁▁▂▃▄▃▃▂▁▂▃▅▆▄▅▅▆▄▃▂▄▅▂▂▁▂▃▂▁▁▃▅▄▄▅█▃▁▂▃▂▂▁▁▁▁▁▂▂▂▁▁▁▂▁▁▁▁▂▂▁▁▁▁▁▁▁▁▃▂▃▂▃▂▂▂▄▄▅▄▂▂▃▁▂▁▁▁▁▁
```

**Heap InUse** (current: 199.0MB | avg: 172.4MB | max: 2823.8MB | trend: stable (-0.12MB/hr))
```
▂▁▂▃▃▄▁▂▁▂▃▂▂▂▂█▂▃▄▂▃▄▅▄▃▂▃▄▂▂▁▁▃▃▁▁▂▂▃▃▅▄▃▁▂▃▁▁▁▁▁▁▁▂▂▁▁▁▁▁▂▁▁▁▂▁▁▁▂▁▁▁▁▁▂▂▂▂▂▁▁▂▃▃▄▂▂▂▂▂▁▂▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,326 | 14,543 | -217 | 11,365 | 84,644 | decreasing (-10.60/hr) |
| Heap InUse | 199.0MB | 208.8MB | -9.8MB | 172.4MB | 2823.8MB | stable (-0.12MB/hr) |
| Heap Sys | 3854.5MB | 3854.3MB | +0.2MB | 2652.4MB | 6883.9MB | |
| Heap Objects | 1,218,677 | 1,199,665 | +19012 | 746,604 | 14,090,816 | |

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
| 2026-06-04 | 256 | 16,642 | 268.4MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 8 | `kafka-go/protocol.newPage` | 1.6MB |
| 9 | `bufio.NewReaderSize` | 1.53MB |
| 10 | `bytes.growSlice` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 15.08GB |
| 2 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 11.66GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 5.98GB |
| 4 | `fmt.Sprintf` | 5.77GB |
| 5 | `segmentio/kafka-go.makePartitions` | 5.72GB |
| 6 | `database/sql.convertAssignRows` | 4.26GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 4.09GB |
| 8 | `jackskj/carta.getUniqueId` | 3.31GB |
| 9 | `reflect.unsafe_NewArray` | 2.96GB |
| 10 | `strconv.appendQuotedWith` | 2.86GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 496.86MB | 489.24MB | 280.40MB | 0B |
| `evaluation.mergeMetadata` | 252.06MB | 248.06MB | 145.32MB | 0B |
| `local.(*Client).EvaluateV2` | 785.74MB | 772.40MB | 438.56MB | 0B |
| `local.topologicalSort` | 107.25MB | 104.71MB | 62.90MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 693.60MB | 683.31MB | 390.75MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 161.90MB | 157.83MB | 89.14MB | 0B |
| `localEvaluation.getMapOfValue` | 693.60MB | 683.31MB | 390.75MB | 0B |
| `utils.ParseFeatureFlag` | 694.10MB | 683.81MB | 390.79MB | 0B |

**Total FF alloc (current snapshot):** 3.79GB  |  **24h avg:** 2.14GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 64.9MB | 40/1210 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 58.21MB | 24/1210 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 861/1210 | `████████░░░░░░░ 56%` |
| 4 | `database/sql.convertAssignRows` | 31.07MB | 52/1210 | `███████░░░░░░░░ 47%` |
| 5 | `runtime.mallocgc` | 19.44MB | 861/1210 | `████░░░░░░░░░░░ 29%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1210 | `████░░░░░░░░░░░ 27%` |
| 7 | `bytes.growSlice` | 15.21MB | 647/1210 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1210 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1210 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1210 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1210 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1210 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1210 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1210 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1210 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 38.3GB | 833/1210 | `████░░░░░░░░░░░ 30%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1210 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 17.24GB | 756/1210 | `██░░░░░░░░░░░░░ 13%` |
| 9 | `fmt.Sprintf` | 11.23GB | 452/1210 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `segmentio/kafka-go.makePartitions` | 10.29GB | 594/1210 | `█░░░░░░░░░░░░░░ 8%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (11.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.4x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.5x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.8x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.5x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.9x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.0x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.8x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.4x avg)
