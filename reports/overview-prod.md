# Overview: prod
*Last updated: 2026-06-04 17:26 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T17:26 (1164 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,515 | avg: 11,203 | max: 84,644 | trend: decreasing (-13.64/hr))
```
▁▁▁▁▁▁▁▁▂▃▄▂▄▆▇█▇▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 147.5MB | avg: 170.6MB | max: 2823.8MB | trend: stable (-0.16MB/hr))
```
▁▁▁▁▁▁▁▂▂▃▃▃▅▇█▇▆▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▂▂▂▂▁▁▁▂▂▂▁▁▁▁▂▁▁▁▁▃▁▂▂▁▂▂▂▂▂▁▂▂▁▁▁▁▁▂▁▁▁▁▂▂▂▂▂▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,515 | 14,887 | -372 | 11,203 | 84,644 | decreasing (-13.64/hr) |
| Heap InUse | 147.5MB | 207.5MB | -60.0MB | 170.6MB | 2823.8MB | stable (-0.16MB/hr) |
| Heap Sys | 965.1MB | 964.3MB | +0.8MB | 2649.6MB | 6883.9MB | |
| Heap Objects | 634,572 | 1,053,299 | -418727 | 736,933 | 14,090,816 | |

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
| 2026-06-04 | 210 | 16,902 | 279.2MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `bytes.growSlice` | 3.02MB |
| 6 | `bufio.NewWriterSize` | 3.01MB |
| 7 | `compress/flate.NewWriter` | 2.64MB |
| 8 | `bufio.NewReaderSize` | 2.52MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `reflect.growslice` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 2.61GB |
| 2 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 1.08GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 1.03GB |
| 4 | `fmt.Sprintf` | 781.05MB |
| 5 | `segmentio/kafka-go.makePartitions` | 633.49MB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 601.65MB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 587.51MB |
| 8 | `database/sql.convertAssignRows` | 567.04MB |
| 9 | `jackskj/carta.getUniqueId` | 497.62MB |
| 10 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 486.97MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 63.01MB | 53.86MB | 397.45MB | 0B |
| `evaluation.mergeMetadata` | 35.51MB | 30.51MB | 205.74MB | 0B |
| `local.(*Client).EvaluateV2` | 91.89MB | 80.20MB | 611.75MB | 0B |
| `local.topologicalSort` | 13.67MB | 13.16MB | 86.30MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 88.93MB | 79.76MB | 569.94MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 17.29MB | 13.73MB | 96.41MB | 0B |
| `localEvaluation.getMapOfValue` | 88.93MB | 79.76MB | 569.94MB | 0B |
| `utils.ParseFeatureFlag` | 88.93MB | 79.76MB | 569.94MB | 0B |

**Total FF alloc (current snapshot):** 488.15MB  |  **24h avg:** 3.03GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 64.9MB | 40/1164 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 58.21MB | 24/1164 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 815/1164 | `████████░░░░░░░ 56%` |
| 4 | `database/sql.convertAssignRows` | 32.21MB | 50/1164 | `███████░░░░░░░░ 49%` |
| 5 | `runtime.mallocgc` | 19.91MB | 815/1164 | `████░░░░░░░░░░░ 30%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1164 | `████░░░░░░░░░░░ 27%` |
| 7 | `bytes.growSlice` | 15.57MB | 601/1164 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1164 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1164 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1164 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1164 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1164 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1164 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1164 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1164 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 40.12GB | 787/1164 | `████░░░░░░░░░░░ 31%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1164 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 18.15GB | 711/1164 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `fmt.Sprintf` | 12.17GB | 406/1164 | `█░░░░░░░░░░░░░░ 9%` |
| 10 | `segmentio/kafka-go.makePartitions` | 10.88GB | 548/1164 | `█░░░░░░░░░░░░░░ 8%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (11.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.6x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.5x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.8x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.5x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.9x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.1x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.9x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.4x avg)
