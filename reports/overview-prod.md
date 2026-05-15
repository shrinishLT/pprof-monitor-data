# Overview: prod
*Last updated: 2026-05-15 22:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-15T22:02 (7 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,510 | avg: 14,320 | max: 14,619 | trend: INCREASING (+119.07/hr))
```
▂▂▁▁▃█▆
```

**Heap InUse** (current: 221.5MB | avg: 242.1MB | max: 280.1MB | trend: decreasing (-3.41MB/hr))
```
▅▄▄▁▄█▂
```

## Current Status

Goroutines: `███████████████████░ 99%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,510 | 14,619 | -109 | 14,320 | 14,619 | INCREASING (+119.07/hr) |
| Heap InUse | 221.5MB | 280.1MB | -58.6MB | 242.1MB | 280.1MB | decreasing (-3.41MB/hr) |
| Heap Sys | 5825.2MB | 5825.2MB | +0.0MB | 5825.2MB | 5825.2MB | |
| Heap Objects | 715,817 | 1,322,856 | -607039 | 977,117 | 1,322,856 | |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.16MB |
| 3 | `compress/flate.NewWriter` | 3.16MB |
| 4 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.29MB |
| 5 | `runtime.mallocgc` | 991.34kB |
| 6 | `jasonlvhit/gocron.NewScheduler` | 80.0kB |
| 7 | `compress/flate.(*compressor).initDeflate` | 72.0kB |
| 8 | `bufio.NewReaderSize` | 52.0kB |
| 9 | `bufio.NewWriterSize` | 40.0kB |
| 10 | `compress/flate.(*dictDecoder).init` | 32.0kB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 197.01GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 44.73GB |
| 3 | `reflect.growslice` | 44.1GB |
| 4 | `fmt.(*buffer).writeString` | 31.52GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 14.38GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 14.35GB |
| 7 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 13.33GB |
| 8 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 13.32GB |
| 9 | `compress/flate.NewWriter` | 10.06GB |
| 10 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 9.55GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 5/7 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.16MB | 5/7 | `███░░░░░░░░░░░░ 25%` |
| 3 | `compress/flate.NewWriter` | 2.66MB | 5/7 | `█░░░░░░░░░░░░░░ 7%` |
| 4 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.29MB | 5/7 | `░░░░░░░░░░░░░░░ 6%` |
| 5 | `runtime.mallocgc` | 991.34kB | 5/7 | `███████████████ 100%` |
| 6 | `compress/flate.(*compressor).initDeflate` | 148.8kB | 5/7 | `███████████████ 100%` |
| 7 | `jasonlvhit/gocron.NewScheduler` | 80.0kB | 5/7 | `███████████████ 100%` |
| 8 | `v3/newrelic.newLogEvents` | 72.0kB | 1/7 | `███████████████ 100%` |
| 9 | `regexp.(*bitState).reset` | 64.0kB | 2/7 | `███████████████ 100%` |
| 10 | `v3/newrelic.newAnalyticsEvents` | 64.0kB | 1/7 | `███████████████ 100%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 197.01GB | 2/7 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 44.73GB | 2/7 | `███░░░░░░░░░░░░ 22%` |
| 3 | `reflect.growslice` | 44.09GB | 2/7 | `███░░░░░░░░░░░░ 22%` |
| 4 | `fmt.(*buffer).writeString` | 31.52GB | 2/7 | `██░░░░░░░░░░░░░ 15%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 14.38GB | 2/7 | `█░░░░░░░░░░░░░░ 7%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 14.34GB | 2/7 | `█░░░░░░░░░░░░░░ 7%` |
| 7 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 13.33GB | 2/7 | `█░░░░░░░░░░░░░░ 6%` |
| 8 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 13.32GB | 2/7 | `█░░░░░░░░░░░░░░ 6%` |
| 9 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 9.55GB | 2/7 | `░░░░░░░░░░░░░░░ 4%` |
| 10 | `compress/flate.NewWriter` | 4.02GB | 5/7 | `░░░░░░░░░░░░░░░ 2%` |

## Alerts

No anomalies detected.
