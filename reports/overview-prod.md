# Overview: prod
*Last updated: 2026-06-04 18:25 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T18:25 (1176 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,617 | avg: 11,242 | max: 84,644 | trend: decreasing (-12.84/hr))
```
▄▆▇█▇▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 201.7MB | avg: 170.8MB | max: 2823.8MB | trend: stable (-0.15MB/hr))
```
▅▇█▇▆▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▂▂▂▂▁▁▁▂▂▂▁▁▁▁▂▁▁▁▁▃▁▂▂▁▂▂▂▂▂▁▂▂▁▁▁▁▁▂▁▁▁▁▂▂▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,617 | 15,211 | -594 | 11,242 | 84,644 | decreasing (-12.84/hr) |
| Heap InUse | 201.7MB | 222.9MB | -21.2MB | 170.8MB | 2823.8MB | stable (-0.15MB/hr) |
| Heap Sys | 965.0MB | 965.3MB | -0.3MB | 2632.4MB | 6883.9MB | |
| Heap Objects | 974,492 | 1,042,878 | -68386 | 737,735 | 14,090,816 | |

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
| 2026-06-04 | 222 | 16,801 | 274.4MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 5.59MB |
| 6 | `bytes.growSlice` | 3.52MB |
| 7 | `segmentio/kafka-go.makePartitions` | 3.01MB |
| 8 | `crypto/tls.Client` | 3.0MB |
| 9 | `database/sql.convertAssignRows` | 2.5MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 2.64GB |
| 2 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 2.29GB |
| 3 | `segmentio/kafka-go.makePartitions` | 1.89GB |
| 4 | `fmt.Sprintf` | 1.76GB |
| 5 | `jackskj/carta.getUniqueId` | 1.09GB |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 1.05GB |
| 7 | `reflect.unsafe_NewArray` | 983.45MB |
| 8 | `strconv.appendQuotedWith` | 904.81MB |
| 9 | `fmt.Sprint` | 887.01MB |
| 10 | `database/sql.convertAssignRows` | 883.08MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 176.64MB | 171.59MB | 357.60MB | 0B |
| `evaluation.mergeMetadata` | 97.52MB | 94.52MB | 185.09MB | 0B |
| `local.(*Client).EvaluateV2` | 280.26MB | 271.52MB | 551.66MB | 0B |
| `local.topologicalSort` | 44.05MB | 43.04MB | 78.72MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 250.82MB | 244.62MB | 512.46MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 58.15MB | 55.11MB | 88.97MB | 0B |
| `localEvaluation.getMapOfValue` | 250.82MB | 244.62MB | 512.46MB | 0B |
| `utils.ParseFeatureFlag` | 250.82MB | 244.62MB | 512.46MB | 0B |

**Total FF alloc (current snapshot):** 1.38GB  |  **24h avg:** 2.73GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 64.9MB | 40/1176 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 58.21MB | 24/1176 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 827/1176 | `████████░░░░░░░ 56%` |
| 4 | `database/sql.convertAssignRows` | 31.63MB | 51/1176 | `███████░░░░░░░░ 48%` |
| 5 | `runtime.mallocgc` | 19.78MB | 827/1176 | `████░░░░░░░░░░░ 30%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1176 | `████░░░░░░░░░░░ 27%` |
| 7 | `bytes.growSlice` | 15.41MB | 613/1176 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1176 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1176 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1176 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1176 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1176 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1176 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1176 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1176 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 39.56GB | 799/1176 | `████░░░░░░░░░░░ 31%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1176 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 17.87GB | 723/1176 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `fmt.Sprintf` | 11.86GB | 418/1176 | `█░░░░░░░░░░░░░░ 9%` |
| 10 | `segmentio/kafka-go.makePartitions` | 10.67GB | 560/1176 | `█░░░░░░░░░░░░░░ 8%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (11.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.5x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.5x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.8x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.5x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.9x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.1x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.9x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.4x avg)
