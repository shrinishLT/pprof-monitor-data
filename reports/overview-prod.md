# Overview: prod
*Last updated: 2026-06-05 09:15 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T09:15 (1354 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,862 | avg: 11,759 | max: 84,644 | trend: decreasing (-4.47/hr))
```
▁▁▁▂▃▂▃▃▃▂▂▁▁▄▂▁▂▃▁▁▁▃▁▂▁▁▂▂▄▃▄▆▆▁▁▁▁▁▁▂▂▁▇▃▁▁▁▂▂▂▁▁▂▃▂▃▃▂▂▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▄▄▁▁▂▁▁▃▁▁▁▂
```

**Heap InUse** (current: 155.4MB | avg: 179.8MB | max: 3154.1MB | trend: stable (-0.03MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,862 | 14,574 | +288 | 11,759 | 84,644 | decreasing (-4.47/hr) |
| Heap InUse | 155.4MB | 162.0MB | -6.6MB | 179.8MB | 3154.1MB | stable (-0.03MB/hr) |
| Heap Sys | 4421.1MB | 4420.9MB | +0.2MB | 2684.0MB | 6883.9MB | |
| Heap Objects | 513,871 | 829,802 | -315931 | 802,060 | 17,165,538 | |

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
| 2026-06-05 | 112 | 14,849 | 241.4MB | 3154.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 7.04MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 6 | `bufio.NewReaderSize` | 2.51MB |
| 7 | `bufio.NewWriterSize` | 2.51MB |
| 8 | `reflect.mapassign_faststr0` | 2.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `segmentio/kafka-go.makePartitions` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 8.14GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 3.24GB |
| 3 | `segmentio/kafka-go.makePartitions` | 3.15GB |
| 4 | `reflect.unsafe_NewArray` | 1.56GB |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 1.33GB |
| 6 | `jackskj/carta.getUniqueId` | 1.3GB |
| 7 | `reflect.growslice` | 1.21GB |
| 8 | `reflect.unsafe_New` | 1.07GB |
| 9 | `database/sql.convertAssignRows` | 1.03GB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 1.02GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 170.64MB | 164.58MB | 157.53MB | 0B |
| `evaluation.mergeMetadata` | 86.52MB | 83.02MB | 79.64MB | 0B |
| `local.(*Client).EvaluateV2` | 253.21MB | 246.13MB | 237.07MB | 0B |
| `local.topologicalSort` | 35.37MB | 34.86MB | 34.55MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 263.36MB | 256.28MB | 239.01MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 14.43MB | 14.43MB | 22.18MB | 0B |
| `localEvaluation.getMapOfValue` | 263.36MB | 256.28MB | 239.01MB | 0B |
| `utils.ParseFeatureFlag` | 263.36MB | 256.28MB | 239.41MB | 0B |

**Total FF alloc (current snapshot):** 1.32GB  |  **24h avg:** 1.22GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 94.56MB | 31/1354 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 76.85MB | 51/1354 | `████████████░░░ 81%` |
| 3 | `database/sql.convertAssignRows` | 40.34MB | 63/1354 | `██████░░░░░░░░░ 42%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1005/1354 | `█████░░░░░░░░░░ 38%` |
| 5 | `runtime.mallocgc` | 18.03MB | 1005/1354 | `██░░░░░░░░░░░░░ 19%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1354 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `bytes.growSlice` | 14.12MB | 768/1354 | `██░░░░░░░░░░░░░ 14%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1354 | `█░░░░░░░░░░░░░░ 13%` |
| 9 | `fmt.Sprint` | 12.05MB | 2/1354 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `net/http.(*Transport).dialConn` | 11.71MB | 17/1354 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1354 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1354 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1354 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1354 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1354 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 34.4GB | 976/1354 | `████░░░░░░░░░░░ 27%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1354 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 15.24GB | 899/1354 | `█░░░░░░░░░░░░░░ 12%` |
| 9 | `fmt.Sprintf` | 9.59GB | 554/1354 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.58GB | 187/1354 | `█░░░░░░░░░░░░░░ 7%` |

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
