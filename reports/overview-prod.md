# Overview: prod
*Last updated: 2026-06-04 23:40 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T23:40 (1239 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,289 | avg: 11,472 | max: 84,644 | trend: decreasing (-8.86/hr))
```
▂▁▂▃▂▁▁▃▄▄▄▄▇▃▁▂▃▂▂▁▁▁▁▁▂▂▂▁▁▁▂▁▁▁▁▂▂▁▁▁▁▁▁▁▁▃▂▃▂▃▂▂▂▃▄▅▄▂▂▃▁▂▁▁▁▁▁▁▃▅█▇▅▆▁▂▂▁▁▁▁▁▁▂▁▁▁▁▁▁▁▂▄▂▁▁
```

**Heap InUse** (current: 187.5MB | avg: 174.3MB | max: 2823.8MB | trend: stable (-0.10MB/hr))
```
▂▁▁▃▃▁▁▂▂▃▃▅▄▃▁▂▃▁▁▁▁▁▁▁▂▂▁▁▁▁▁▂▁▁▁▂▁▁▁▂▁▁▁▁▁▂▂▂▂▂▁▁▂▃▃▄▂▂▂▂▂▁▂▁▁▁▁▁▂▃▄▄▃▄▂▁▁▂▁▂▂▁▁▂▁▁█▁▁▁▁▁▃▂▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,289 | 14,529 | -240 | 11,472 | 84,644 | decreasing (-8.86/hr) |
| Heap InUse | 187.5MB | 210.8MB | -23.3MB | 174.3MB | 2823.8MB | stable (-0.10MB/hr) |
| Heap Sys | 798.9MB | 797.6MB | +1.3MB | 2655.8MB | 6883.9MB | |
| Heap Objects | 1,245,721 | 1,267,015 | -21294 | 756,756 | 14,090,816 | |

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
| 2026-06-04 | 285 | 16,574 | 266.5MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `reflect.unsafe_NewArray` | 3.02MB |
| 6 | `bytes.growSlice` | 3.02MB |
| 7 | `compress/flate.NewWriter` | 2.64MB |
| 8 | `bufio.NewReaderSize` | 2.52MB |
| 9 | `segmentio/kafka-go.makePartitions` | 2.51MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 2.19GB |
| 2 | `segmentio/kafka-go.makePartitions` | 896.31MB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 894.77MB |
| 4 | `fmt.Sprintf` | 609.17MB |
| 5 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 524.77MB |
| 6 | `reflect.unsafe_NewArray` | 477.03MB |
| 7 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 435.26MB |
| 8 | `go-sql-driver/mysql.(*binaryRows).readRow` | 393.51MB |
| 9 | `database/sql.convertAssignRows` | 324.52MB |
| 10 | `jackskj/carta.getUniqueId` | 322.56MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 75.54MB | 70.50MB | 402.86MB | 0B |
| `evaluation.mergeMetadata` | 43.01MB | 39.51MB | 207.33MB | 0B |
| `local.(*Client).EvaluateV2` | 102.89MB | 95.28MB | 628.95MB | 0B |
| `local.topologicalSort` | 14.63MB | 13.12MB | 86.28MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 90.05MB | 82.97MB | 554.40MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 18.47MB | 16.93MB | 130.30MB | 0B |
| `localEvaluation.getMapOfValue` | 90.05MB | 82.97MB | 554.40MB | 0B |
| `utils.ParseFeatureFlag` | 90.05MB | 82.97MB | 554.64MB | 0B |

**Total FF alloc (current snapshot):** 524.70MB  |  **24h avg:** 3.05GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 65.38MB | 41/1239 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 58.62MB | 25/1239 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 890/1239 | `████████░░░░░░░ 56%` |
| 4 | `database/sql.convertAssignRows` | 31.49MB | 53/1239 | `███████░░░░░░░░ 48%` |
| 5 | `runtime.mallocgc` | 19.16MB | 890/1239 | `████░░░░░░░░░░░ 29%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1239 | `████░░░░░░░░░░░ 27%` |
| 7 | `bytes.growSlice` | 15.17MB | 674/1239 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1239 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1239 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1239 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1239 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1239 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1239 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1239 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1239 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 37.36GB | 862/1239 | `████░░░░░░░░░░░ 29%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1239 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 16.76GB | 785/1239 | `██░░░░░░░░░░░░░ 13%` |
| 9 | `fmt.Sprintf` | 10.93GB | 477/1239 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `segmentio/kafka-go.makePartitions` | 10.02GB | 623/1239 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.4x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.7x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.4x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.8x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.8x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.0x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.8x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.3x avg)
- Heap spike to 439.8MB at 2026-05-19T17:02 (2.5x avg)
