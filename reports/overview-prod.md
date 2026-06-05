# Overview: prod
*Last updated: 2026-06-05 07:10 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T07:10 (1329 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,249 | avg: 11,704 | max: 84,644 | trend: decreasing (-5.23/hr))
```
▂▃█▄▁▁▁▁▂▁▂▁▁▁▁▁▁▂▆▃▁▁▁▁▁▁▁▁▂▃▂▃▃▃▂▂▁▁▄▂▁▂▃▁▁▁▃▁▂▁▁▁▂▄▃▄▆▅▁▁▁▁▁▁▂▂▁▆▂▁▁▁▂▂▂▁▁▂▃▂▃▃▂▂▂▂▂▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 135.2MB | avg: 180.0MB | max: 3154.1MB | trend: stable (-0.03MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 1%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,249 | 14,418 | -169 | 11,704 | 84,644 | decreasing (-5.23/hr) |
| Heap InUse | 135.2MB | 157.4MB | -22.2MB | 180.0MB | 3154.1MB | stable (-0.03MB/hr) |
| Heap Sys | 1026.8MB | 1027.5MB | -0.7MB | 2705.2MB | 6883.9MB | |
| Heap Objects | 686,965 | 904,877 | -217912 | 800,474 | 17,165,538 | |

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
| 2026-06-05 | 87 | 14,898 | 261.4MB | 3154.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 10.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `compress/flate.NewWriter` | 5.29MB |
| 6 | `segmentio/kafka-go.makePartitions` | 5.01MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.unsafe_NewArray` | 2.01MB |
| 9 | `bufio.NewReaderSize` | 2.01MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 1.6MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 2.17GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 871.25MB |
| 3 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 516.45MB |
| 4 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 425.45MB |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 348.01MB |
| 6 | `segmentio/kafka-go.makePartitions` | 330.27MB |
| 7 | `database/sql.convertAssignRows` | 267.51MB |
| 8 | `reflect.unsafe_NewArray` | 151.21MB |
| 9 | `jackskj/carta.getUniqueId` | 95.02MB |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 92.59MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 28.87MB | 22.26MB | 173.70MB | 0B |
| `evaluation.mergeMetadata` | 16.00MB | 14.00MB | 87.96MB | 0B |
| `local.(*Client).EvaluateV2` | 40.24MB | 31.54MB | 262.64MB | 0B |
| `local.topologicalSort` | 5.06MB | 4.55MB | 38.33MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 34.59MB | 25.42MB | 259.97MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 8.71MB | 8.17MB | 27.36MB | 0B |
| `localEvaluation.getMapOfValue` | 34.59MB | 25.42MB | 259.97MB | 0B |
| `utils.ParseFeatureFlag` | 34.59MB | 25.42MB | 260.75MB | 0B |

**Total FF alloc (current snapshot):** 202.66MB  |  **24h avg:** 1.34GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 94.56MB | 31/1329 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 76.85MB | 51/1329 | `████████████░░░ 81%` |
| 3 | `database/sql.convertAssignRows` | 40.34MB | 63/1329 | `██████░░░░░░░░░ 42%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 980/1329 | `█████░░░░░░░░░░ 38%` |
| 5 | `runtime.mallocgc` | 18.2MB | 980/1329 | `██░░░░░░░░░░░░░ 19%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1329 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `bytes.growSlice` | 14.33MB | 749/1329 | `██░░░░░░░░░░░░░ 15%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1329 | `█░░░░░░░░░░░░░░ 13%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1329 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1329 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1329 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1329 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1329 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1329 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1329 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 35.23GB | 951/1329 | `████░░░░░░░░░░░ 28%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1329 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 15.64GB | 874/1329 | `█░░░░░░░░░░░░░░ 12%` |
| 9 | `fmt.Sprintf` | 9.77GB | 543/1329 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.58GB | 187/1329 | `█░░░░░░░░░░░░░░ 7%` |

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
- Goroutine spike to 25,220 at 2026-05-20T02:02 (2.2x avg)
