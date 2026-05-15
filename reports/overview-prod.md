# Overview: prod
*Last updated: 2026-05-16 00:29 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T00:29 (12 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,810 | avg: 14,357 | max: 14,810 | trend: INCREASING (+63.45/hr))
```
▂▂▁▁▂▆▄▁▂▃▃█
```

**Heap InUse** (current: 222.7MB | avg: 235.6MB | max: 280.1MB | trend: decreasing (-5.83MB/hr))
```
▅▄▄▁▄█▂▆▃▁▁▂
```

## Current Status

Goroutines: `████████████████████ 100%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,810 | 14,357 | +453 | 14,357 | 14,810 | INCREASING (+63.45/hr) |
| Heap InUse | 222.7MB | 210.4MB | +12.3MB | 235.6MB | 280.1MB | decreasing (-5.83MB/hr) |
| Heap Sys | 1456.2MB | 5823.4MB | -4367.2MB | 5460.7MB | 5825.3MB | |
| Heap Objects | 1,148,633 | 494,482 | +654151 | 911,623 | 1,322,856 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 2 | 14,584 | 216.6MB | 222.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.08MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 6.03MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 6 | `bufio.NewWriterSize` | 3.01MB |
| 7 | `compress/flate.(*compressor).initDeflate` | 2.66MB |
| 8 | `compress/flate.NewWriter` | 2.64MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 2.5MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 2.45GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 1.14GB |
| 3 | `internal/evaluation.mergeMetadata` | 1.08GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 679.89MB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 648.06MB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 587.38MB |
| 7 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 487.65MB |
| 8 | `experiment/local.topologicalSort` | 433.44MB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 397.01MB |
| 10 | `database/sql.convertAssignRows` | 364.02MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 10/12 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.17MB | 10/12 | `███░░░░░░░░░░░░ 25%` |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB | 1/12 | `██░░░░░░░░░░░░░ 16%` |
| 4 | `aes/gcm.NewGCMForTLS13` | 2.5MB | 1/12 | `█░░░░░░░░░░░░░░ 6%` |
| 5 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB | 1/12 | `█░░░░░░░░░░░░░░ 6%` |
| 6 | `compress/flate.NewWriter` | 2.29MB | 10/12 | `░░░░░░░░░░░░░░░ 6%` |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.29MB | 9/12 | `░░░░░░░░░░░░░░░ 6%` |
| 8 | `bytes.growSlice` | 2.05MB | 3/12 | `░░░░░░░░░░░░░░░ 5%` |
| 9 | `runtime.mallocgc` | 1.98MB | 10/12 | `░░░░░░░░░░░░░░░ 5%` |
| 10 | `bufio.NewWriterSize` | 476.32kB | 7/12 | `███████████████ 100%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 173.25GB | 7/12 | `███████████████ 100%` |
| 2 | `reflect.growslice` | 44.11GB | 6/12 | `███░░░░░░░░░░░░ 25%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 39.42GB | 7/12 | `███░░░░░░░░░░░░ 22%` |
| 4 | `fmt.(*buffer).writeString` | 31.53GB | 6/12 | `██░░░░░░░░░░░░░ 18%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 12.61GB | 7/12 | `█░░░░░░░░░░░░░░ 7%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 12.59GB | 7/12 | `█░░░░░░░░░░░░░░ 7%` |
| 7 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 11.81GB | 7/12 | `█░░░░░░░░░░░░░░ 6%` |
| 8 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 11.79GB | 7/12 | `█░░░░░░░░░░░░░░ 6%` |
| 9 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 9.57GB | 6/12 | `░░░░░░░░░░░░░░░ 5%` |
| 10 | `compress/flate.NewWriter` | 6.79GB | 9/12 | `░░░░░░░░░░░░░░░ 3%` |

## Alerts

No anomalies detected.
