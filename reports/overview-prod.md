# Overview: prod
*Last updated: 2026-06-04 00:45 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T00:45 (964 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,437 | avg: 9,998 | max: 84,644 | trend: decreasing (-42.39/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▆▁█▇▆▇▇▆▆▆▆▇▆▆▆▆▆▆
```

**Heap InUse** (current: 147.4MB | avg: 147.0MB | max: 1896.6MB | trend: decreasing (-0.64MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▇▆▅▅▆▄▄▆▄█▆▃▃▃▅▄
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,437 | 14,353 | +84 | 9,998 | 84,644 | decreasing (-42.39/hr) |
| Heap InUse | 147.4MB | 183.8MB | -36.4MB | 147.0MB | 1896.6MB | decreasing (-0.64MB/hr) |
| Heap Sys | 2427.0MB | 2427.4MB | -0.4MB | 2579.4MB | 6883.9MB | |
| Heap Objects | 542,847 | 1,177,324 | -634477 | 629,242 | 8,100,802 | |

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
| 2026-06-04 | 10 | 14,768 | 180.1MB | 318.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `bufio.NewWriterSize` | 3.03MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.53MB |
| 7 | `bytes.growSlice` | 2.51MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `reflect.unsafe_NewArray` | 2.0MB |
| 10 | `compress/flate.NewWriter` | 1.76MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 3.6GB |
| 2 | `segmentio/kafka-go.makePartitions` | 1.51GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 1.41GB |
| 4 | `fmt.Sprintf` | 1.07GB |
| 5 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 977.63MB |
| 6 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 826.45MB |
| 7 | `reflect.unsafe_NewArray` | 803.94MB |
| 8 | `go-sql-driver/mysql.(*binaryRows).readRow` | 644.51MB |
| 9 | `database/sql.convertAssignRows` | 542.53MB |
| 10 | `strconv.appendQuotedWith` | 522.61MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 93.92MB | 86.30MB | 81.46MB | 0B |
| `evaluation.mergeMetadata` | 50.01MB | 46.01MB | 42.01MB | 0B |
| `local.(*Client).EvaluateV2` | 139.25MB | 127.48MB | 122.19MB | 0B |
| `local.topologicalSort` | 23.81MB | 21.81MB | 20.37MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 124.97MB | 113.74MB | 104.95MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 26.04MB | 24.48MB | 26.63MB | 0B |
| `localEvaluation.getMapOfValue` | 124.97MB | 113.74MB | 104.95MB | 0B |
| `utils.ParseFeatureFlag` | 125.47MB | 114.24MB | 105.34MB | 0B |

**Total FF alloc (current snapshot):** 708.43MB  |  **24h avg:** 607.91MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 49.06MB | 26/964 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 43.74MB | 16/964 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 615/964 | `███████████░░░░ 74%` |
| 4 | `database/sql.convertAssignRows` | 26.65MB | 33/964 | `████████░░░░░░░ 54%` |
| 5 | `runtime.mallocgc` | 22.02MB | 615/964 | `██████░░░░░░░░░ 44%` |
| 6 | `bytes.growSlice` | 13.34MB | 424/964 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*Transport).dialConn` | 11.31MB | 8/964 | `███░░░░░░░░░░░░ 23%` |
| 8 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/964 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 9.68MB | 3/964 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.2MB | 608/964 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/964 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/964 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/964 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/964 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 46.97GB | 592/964 | `█████░░░░░░░░░░ 37%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/964 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/964 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 21.0GB | 545/964 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `fmt.Sprintf` | 15.71GB | 282/964 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `segmentio/kafka-go.makePartitions` | 13.61GB | 398/964 | `█░░░░░░░░░░░░░░ 10%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (12.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (8.5x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (3.0x avg)
- Goroutine spike to 20,552 at 2026-05-16T03:31 (2.1x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (3.3x avg)
- Heap spike to 391.4MB at 2026-05-17T10:03 (2.7x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.8x avg)
- Heap spike to 404.6MB at 2026-05-18T06:03 (2.8x avg)
- Heap spike to 373.5MB at 2026-05-18T10:01 (2.5x avg)
- Goroutine spike to 21,569 at 2026-05-18T10:01 (2.2x avg)
