# Overview: prod
*Last updated: 2026-06-05 05:00 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T05:00 (1303 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,341 | avg: 11,643 | max: 84,644 | trend: decreasing (-6.12/hr))
```
▁▁▁▁▃▅█▇▅▆▂▂▂▁▁▁▁▁▁▂▁▁▁▁▁▁▁▂▄▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▄▂▁▁▁▁▁▁▁▁▂▂▁▂▂▂▁▁▁▁▂▁▁▁▂▁▁▁▂▁▁▁▁▁▂▂▂▂▃▃▁▁▁▁▁▁▁▁▁▄▂▁
```

**Heap InUse** (current: 160.1MB | avg: 177.9MB | max: 3154.1MB | trend: stable (-0.05MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,341 | 15,309 | -968 | 11,643 | 84,644 | decreasing (-6.12/hr) |
| Heap InUse | 160.1MB | 253.0MB | -92.9MB | 177.9MB | 3154.1MB | stable (-0.05MB/hr) |
| Heap Sys | 4531.2MB | 4529.2MB | +2.0MB | 2680.1MB | 6883.9MB | |
| Heap Objects | 807,589 | 1,398,745 | -591156 | 784,581 | 17,165,538 | |

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
| 2026-06-05 | 61 | 14,964 | 252.4MB | 3154.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 7.51MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `bufio.NewReaderSize` | 3.04MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `bufio.NewWriterSize` | 2.01MB |
| 9 | `segmentio/kafka-go.makePartitions` | 2.01MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 14.4GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 5.7GB |
| 3 | `segmentio/kafka-go.makePartitions` | 3.44GB |
| 4 | `go-sql-driver/mysql.(*binaryRows).readRow` | 1.97GB |
| 5 | `reflect.unsafe_NewArray` | 1.8GB |
| 6 | `database/sql.convertAssignRows` | 1.75GB |
| 7 | `fmt.Sprintf` | 1.64GB |
| 8 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 1.58GB |
| 9 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 1.31GB |
| 10 | `reflect.MakeSlice` | 990.02MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 187.01MB | 180.98MB | 144.09MB | 0B |
| `evaluation.mergeMetadata` | 95.02MB | 91.52MB | 72.89MB | 0B |
| `local.(*Client).EvaluateV2` | 278.01MB | 270.92MB | 211.54MB | 0B |
| `local.topologicalSort` | 38.93MB | 38.93MB | 30.72MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 276.51MB | 268.92MB | 200.93MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 27.56MB | 27.56MB | 27.71MB | 0B |
| `localEvaluation.getMapOfValue` | 276.51MB | 268.92MB | 200.93MB | 0B |
| `utils.ParseFeatureFlag` | 277.51MB | 269.92MB | 201.32MB | 0B |

**Total FF alloc (current snapshot):** 1.42GB  |  **24h avg:** 1.06GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 76.66MB | 28/1303 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 74.54MB | 45/1303 | `██████████████░ 97%` |
| 3 | `database/sql.convertAssignRows` | 36.87MB | 57/1303 | `███████░░░░░░░░ 48%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 954/1303 | `███████░░░░░░░░ 47%` |
| 5 | `runtime.mallocgc` | 18.48MB | 954/1303 | `███░░░░░░░░░░░░ 24%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1303 | `███░░░░░░░░░░░░ 23%` |
| 7 | `bytes.growSlice` | 14.6MB | 727/1303 | `██░░░░░░░░░░░░░ 19%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1303 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1303 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1303 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1303 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1303 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1303 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1303 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1303 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 35.41GB | 926/1303 | `████░░░░░░░░░░░ 28%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1303 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 15.77GB | 849/1303 | `█░░░░░░░░░░░░░░ 12%` |
| 9 | `fmt.Sprintf` | 9.91GB | 534/1303 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.77GB | 175/1303 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.7x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.3x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.7x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.4x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.8x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.7x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.3x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.4x avg)
- Goroutine spike to 25,220 at 2026-05-20T02:02 (2.2x avg)
