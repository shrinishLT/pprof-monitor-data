# Overview: prod
*Last updated: 2026-05-15 23:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-15T23:02 (9 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,291 | avg: 14,301 | max: 14,619 | trend: INCREASING (+37.17/hr))
```
▂▂▁▁▃█▆▁▃
```

**Heap InUse** (current: 230.3MB | avg: 243.0MB | max: 280.1MB | trend: decreasing (-1.17MB/hr))
```
▅▄▄▁▄█▂▆▃
```

## Current Status

Goroutines: `███████████████████░ 97%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,291 | 14,175 | +116 | 14,301 | 14,619 | INCREASING (+37.17/hr) |
| Heap InUse | 230.3MB | 262.0MB | -31.7MB | 243.0MB | 280.1MB | decreasing (-1.17MB/hr) |
| Heap Sys | 5823.2MB | 5825.3MB | -2.1MB | 5825.0MB | 5825.3MB | |
| Heap Objects | 781,077 | 1,216,013 | -434936 | 981,879 | 1,322,856 | |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.16MB |
| 3 | `compress/flate.NewWriter` | 2.53MB |
| 4 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.29MB |
| 5 | `runtime.mallocgc` | 991.34kB |
| 6 | `kafka-go/protocol.newPage` | 128.0kB |
| 7 | `jasonlvhit/gocron.NewScheduler` | 80.0kB |
| 8 | `v3/newrelic.newLogEvents` | 72.0kB |
| 9 | `compress/flate.(*compressor).initDeflate` | 64.0kB |
| 10 | `bufio.NewWriterSize` | 44.0kB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 201.72GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.8GB |
| 3 | `reflect.growslice` | 44.1GB |
| 4 | `fmt.(*buffer).writeString` | 31.52GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 14.73GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 14.71GB |
| 7 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 13.66GB |
| 8 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 13.66GB |
| 9 | `compress/flate.NewWriter` | 10.21GB |
| 10 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 9.58GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 7/9 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.16MB | 7/9 | `███░░░░░░░░░░░░ 25%` |
| 3 | `compress/flate.NewWriter` | 2.44MB | 7/9 | `░░░░░░░░░░░░░░░ 6%` |
| 4 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.29MB | 7/9 | `░░░░░░░░░░░░░░░ 6%` |
| 5 | `runtime.mallocgc` | 991.34kB | 7/9 | `███████████████ 100%` |
| 6 | `compress/flate.(*compressor).initDeflate` | 134.67kB | 6/9 | `███████████████ 100%` |
| 7 | `kafka-go/protocol.newPage` | 128.0kB | 1/9 | `███████████████ 100%` |
| 8 | `jasonlvhit/gocron.NewScheduler` | 80.0kB | 7/9 | `███████████████ 100%` |
| 9 | `v3/newrelic.newLogEvents` | 72.0kB | 2/9 | `███████████████ 100%` |
| 10 | `regexp.(*bitState).reset` | 64.0kB | 2/9 | `███████████████ 100%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 199.36GB | 4/9 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.27GB | 4/9 | `███░░░░░░░░░░░░ 22%` |
| 3 | `reflect.growslice` | 44.1GB | 4/9 | `███░░░░░░░░░░░░ 22%` |
| 4 | `fmt.(*buffer).writeString` | 31.52GB | 4/9 | `██░░░░░░░░░░░░░ 15%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 14.48GB | 4/9 | `█░░░░░░░░░░░░░░ 7%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 14.46GB | 4/9 | `█░░░░░░░░░░░░░░ 7%` |
| 7 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 13.5GB | 4/9 | `█░░░░░░░░░░░░░░ 6%` |
| 8 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 13.49GB | 4/9 | `█░░░░░░░░░░░░░░ 6%` |
| 9 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 9.56GB | 4/9 | `░░░░░░░░░░░░░░░ 4%` |
| 10 | `compress/flate.NewWriter` | 5.78GB | 7/9 | `░░░░░░░░░░░░░░░ 2%` |

## Alerts

No anomalies detected.
