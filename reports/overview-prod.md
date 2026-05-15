# Overview: prod
*Last updated: 2026-05-16 00:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T00:01 (11 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,357 | avg: 14,315 | max: 14,619 | trend: INCREASING (+33.04/hr))
```
▂▂▁▁▃█▆▁▃▄▄
```

**Heap InUse** (current: 210.4MB | avg: 236.8MB | max: 280.1MB | trend: decreasing (-6.17MB/hr))
```
▅▄▄▁▄█▂▆▃▁▁
```

## Current Status

Goroutines: `███████████████████░ 98%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,357 | 14,406 | -49 | 14,315 | 14,619 | INCREASING (+33.04/hr) |
| Heap InUse | 210.4MB | 207.7MB | +2.7MB | 236.8MB | 280.1MB | decreasing (-6.17MB/hr) |
| Heap Sys | 5823.4MB | 5824.3MB | -0.9MB | 5824.8MB | 5825.3MB | |
| Heap Objects | 494,482 | 459,452 | +35030 | 890,077 | 1,322,856 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 1 | 14,357 | 210.4MB | 210.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.16MB |
| 3 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.29MB |
| 4 | `compress/flate.NewWriter` | 1.9MB |
| 5 | `runtime.mallocgc` | 991.34kB |
| 6 | `jasonlvhit/gocron.NewScheduler` | 80.0kB |
| 7 | `bytes.growSlice` | 79.25kB |
| 8 | `v3/newrelic.newLogEvents` | 72.0kB |
| 9 | `segmentio/kafka-go.makePartitions` | 64.88kB |
| 10 | `kafka-go/protocol.newPage` | 64.0kB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 206.45GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.89GB |
| 3 | `reflect.growslice` | 44.18GB |
| 4 | `fmt.(*buffer).writeString` | 31.59GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 14.91GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 14.89GB |
| 7 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 14.06GB |
| 8 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 14.05GB |
| 9 | `compress/flate.NewWriter` | 10.38GB |
| 10 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 9.6GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 9/11 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.16MB | 9/11 | `███░░░░░░░░░░░░ 25%` |
| 3 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.29MB | 9/11 | `░░░░░░░░░░░░░░░ 6%` |
| 4 | `compress/flate.NewWriter` | 2.25MB | 9/11 | `░░░░░░░░░░░░░░░ 6%` |
| 5 | `runtime.mallocgc` | 991.34kB | 9/11 | `███████████████ 100%` |
| 6 | `compress/flate.(*compressor).initDeflate` | 144.0kB | 7/11 | `███████████████ 100%` |
| 7 | `kafka-go/protocol.newPage` | 96.0kB | 2/11 | `███████████████ 100%` |
| 8 | `jasonlvhit/gocron.NewScheduler` | 80.0kB | 9/11 | `███████████████ 100%` |
| 9 | `v3/newrelic.newLogEvents` | 72.0kB | 3/11 | `███████████████ 100%` |
| 10 | `segmentio/kafka-go.makePartitions` | 64.88kB | 1/11 | `███████████████ 100%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 201.72GB | 6/11 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.8GB | 6/11 | `███░░░░░░░░░░░░ 22%` |
| 3 | `reflect.growslice` | 44.11GB | 6/11 | `███░░░░░░░░░░░░ 21%` |
| 4 | `fmt.(*buffer).writeString` | 31.53GB | 6/11 | `██░░░░░░░░░░░░░ 15%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 14.61GB | 6/11 | `█░░░░░░░░░░░░░░ 7%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 14.58GB | 6/11 | `█░░░░░░░░░░░░░░ 7%` |
| 7 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 13.68GB | 6/11 | `█░░░░░░░░░░░░░░ 6%` |
| 8 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 13.68GB | 6/11 | `█░░░░░░░░░░░░░░ 6%` |
| 9 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 9.57GB | 6/11 | `░░░░░░░░░░░░░░░ 4%` |
| 10 | `compress/flate.NewWriter` | 6.79GB | 9/11 | `░░░░░░░░░░░░░░░ 3%` |

## Alerts

No anomalies detected.
