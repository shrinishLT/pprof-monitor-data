# Overview: prod
*Last updated: 2026-05-16 01:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T01:03 (15 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,208 | avg: 14,445 | max: 15,942 | trend: INCREASING (+89.18/hr))
```
▁▁▁▁▁▂▂▁▁▂▁▃▁█▁
```

**Heap InUse** (current: 152.0MB | avg: 218.1MB | max: 280.1MB | trend: decreasing (-14.08MB/hr))
```
▆▆▆▄▆█▅▇▅▄▄▅▁▂▂
```

## Current Status

Goroutines: `█████████████████░░░ 89%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,208 | 15,942 | -1734 | 14,445 | 15,942 | INCREASING (+89.18/hr) |
| Heap InUse | 152.0MB | 167.2MB | -15.2MB | 218.1MB | 280.1MB | decreasing (-14.08MB/hr) |
| Heap Sys | 1391.0MB | 1453.3MB | -62.3MB | 4655.4MB | 5825.3MB | |
| Heap Objects | 552,073 | 387,576 | +164497 | 825,890 | 1,322,856 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 5 | 14,714 | 175.3MB | 222.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 21.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 5.61MB |
| 6 | `reflect.mapassign_faststr0` | 3.0MB |
| 7 | `database/sql.convertAssignRows` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `bytes.growSlice` | 2.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 20.13GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 12.23GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 12.18GB |
| 4 | `experiment/local.topologicalSort` | 8.12GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 6.34GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 3.77GB |
| 7 | `fmt.Sprintf` | 2.99GB |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 2.48GB |
| 9 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 1.77GB |
| 10 | `internal/evaluation.coerceString` | 1.27GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 13/15 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.19MB | 13/15 | `███░░░░░░░░░░░░ 25%` |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB | 4/15 | `██░░░░░░░░░░░░░ 16%` |
| 4 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 5.61MB | 1/15 | `██░░░░░░░░░░░░░ 15%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 5.53MB | 1/15 | `██░░░░░░░░░░░░░ 15%` |
| 6 | `runtime.mallocgc` | 4.84MB | 13/15 | `█░░░░░░░░░░░░░░ 13%` |
| 7 | `bytes.growSlice` | 3.45MB | 6/15 | `█░░░░░░░░░░░░░░ 9%` |
| 8 | `reflect.mapassign_faststr0` | 3.0MB | 1/15 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `aes/gcm.NewGCMForTLS13` | 2.5MB | 2/15 | `█░░░░░░░░░░░░░░ 6%` |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB | 4/15 | `█░░░░░░░░░░░░░░ 6%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 122.02GB | 10/15 | `███████████████ 100%` |
| 2 | `reflect.growslice` | 44.11GB | 6/15 | `█████░░░░░░░░░░ 36%` |
| 3 | `fmt.(*buffer).writeString` | 31.53GB | 6/15 | `███░░░░░░░░░░░░ 25%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 30.92GB | 9/15 | `███░░░░░░░░░░░░ 25%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 10.23GB | 10/15 | `█░░░░░░░░░░░░░░ 8%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 10.22GB | 10/15 | `█░░░░░░░░░░░░░░ 8%` |
| 7 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 9.31GB | 9/15 | `█░░░░░░░░░░░░░░ 7%` |
| 8 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 9.28GB | 9/15 | `█░░░░░░░░░░░░░░ 7%` |
| 9 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 8.46GB | 7/15 | `█░░░░░░░░░░░░░░ 6%` |
| 10 | `compress/flate.NewWriter` | 6.79GB | 9/15 | `░░░░░░░░░░░░░░░ 5%` |

## Alerts

No anomalies detected.
