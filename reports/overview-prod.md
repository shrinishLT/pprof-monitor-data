# Overview: prod
*Last updated: 2026-05-16 00:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T00:31 (13 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,252 | avg: 14,349 | max: 14,810 | trend: INCREASING (+42.96/hr))
```
▂▂▁▁▂▆▄▁▂▃▃█▂
```

**Heap InUse** (current: 124.1MB | avg: 227.1MB | max: 280.1MB | trend: decreasing (-11.94MB/hr))
```
▆▆▆▄▆█▅▇▅▄▄▅▁
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,252 | 14,810 | -558 | 14,349 | 14,810 | INCREASING (+42.96/hr) |
| Heap InUse | 124.1MB | 222.7MB | -98.6MB | 227.1MB | 280.1MB | decreasing (-11.94MB/hr) |
| Heap Sys | 1457.8MB | 1456.2MB | +1.6MB | 5152.8MB | 5825.3MB | |
| Heap Objects | 509,215 | 1,148,633 | -639418 | 880,669 | 1,322,856 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 3 | 14,473 | 185.7MB | 222.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.08MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `bytes.growSlice` | 3.02MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 1.5MB |
| 10 | `reflect.unsafe_NewArray` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 2.45GB |
| 2 | `internal/evaluation.mergeMetadata` | 1.2GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 1.14GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 744.33MB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 718.34MB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 587.38MB |
| 7 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 487.65MB |
| 8 | `experiment/local.topologicalSort` | 484.54MB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 397.01MB |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 392.52MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 11/13 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.18MB | 11/13 | `███░░░░░░░░░░░░ 25%` |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB | 2/13 | `██░░░░░░░░░░░░░ 16%` |
| 4 | `runtime.mallocgc` | 2.81MB | 11/13 | `█░░░░░░░░░░░░░░ 7%` |
| 5 | `aes/gcm.NewGCMForTLS13` | 2.5MB | 1/13 | `█░░░░░░░░░░░░░░ 6%` |
| 6 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB | 2/13 | `█░░░░░░░░░░░░░░ 6%` |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.29MB | 10/13 | `░░░░░░░░░░░░░░░ 6%` |
| 8 | `compress/flate.NewWriter` | 2.29MB | 10/13 | `░░░░░░░░░░░░░░░ 6%` |
| 9 | `bytes.growSlice` | 2.29MB | 4/13 | `░░░░░░░░░░░░░░░ 6%` |
| 10 | `segmentio/kafka-go.makePartitions` | 1.53MB | 2/13 | `░░░░░░░░░░░░░░░ 4%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 151.9GB | 8/13 | `███████████████ 100%` |
| 2 | `reflect.growslice` | 44.11GB | 6/13 | `████░░░░░░░░░░░ 29%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 34.64GB | 8/13 | `███░░░░░░░░░░░░ 22%` |
| 4 | `fmt.(*buffer).writeString` | 31.53GB | 6/13 | `███░░░░░░░░░░░░ 20%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 11.12GB | 8/13 | `█░░░░░░░░░░░░░░ 7%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 11.11GB | 8/13 | `█░░░░░░░░░░░░░░ 7%` |
| 7 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 10.41GB | 8/13 | `█░░░░░░░░░░░░░░ 6%` |
| 8 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 10.38GB | 8/13 | `█░░░░░░░░░░░░░░ 6%` |
| 9 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 9.57GB | 6/13 | `░░░░░░░░░░░░░░░ 6%` |
| 10 | `compress/flate.NewWriter` | 6.79GB | 9/13 | `░░░░░░░░░░░░░░░ 4%` |

## Alerts

No anomalies detected.
