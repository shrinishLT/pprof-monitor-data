# Overview: prod
*Last updated: 2026-05-15 22:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-15T22:31 (8 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,175 | avg: 14,302 | max: 14,619 | trend: INCREASING (+55.19/hr))
```
▂▂▁▁▃█▆▁
```

**Heap InUse** (current: 262.0MB | avg: 244.6MB | max: 280.1MB | trend: INCREASING (+1.04MB/hr))
```
▅▄▄▁▄█▂▆
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,175 | 14,510 | -335 | 14,302 | 14,619 | INCREASING (+55.19/hr) |
| Heap InUse | 262.0MB | 221.5MB | +40.5MB | 244.6MB | 280.1MB | INCREASING (+1.04MB/hr) |
| Heap Sys | 5825.3MB | 5825.2MB | +0.1MB | 5825.2MB | 5825.3MB | |
| Heap Objects | 1,216,013 | 715,817 | +500196 | 1,006,979 | 1,322,856 | |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.16MB |
| 3 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.29MB |
| 4 | `compress/flate.NewWriter` | 1.27MB |
| 5 | `runtime.mallocgc` | 991.34kB |
| 6 | `jasonlvhit/gocron.NewScheduler` | 80.0kB |
| 7 | `v3/newrelic.newAnalyticsEvents` | 48.0kB |
| 8 | `bufio.NewReaderSize` | 44.0kB |
| 9 | `bufio.NewWriterSize` | 36.0kB |
| 10 | `bytes.growSlice` | 32.5kB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 201.69GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.8GB |
| 3 | `reflect.growslice` | 44.1GB |
| 4 | `fmt.(*buffer).writeString` | 31.52GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 14.44GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 14.42GB |
| 7 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 13.66GB |
| 8 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 13.66GB |
| 9 | `compress/flate.NewWriter` | 10.12GB |
| 10 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 9.57GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 6/8 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.16MB | 6/8 | `███░░░░░░░░░░░░ 25%` |
| 3 | `compress/flate.NewWriter` | 2.43MB | 6/8 | `░░░░░░░░░░░░░░░ 6%` |
| 4 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.29MB | 6/8 | `░░░░░░░░░░░░░░░ 6%` |
| 5 | `runtime.mallocgc` | 991.34kB | 6/8 | `███████████████ 100%` |
| 6 | `compress/flate.(*compressor).initDeflate` | 148.8kB | 5/8 | `███████████████ 100%` |
| 7 | `jasonlvhit/gocron.NewScheduler` | 80.0kB | 6/8 | `███████████████ 100%` |
| 8 | `v3/newrelic.newLogEvents` | 72.0kB | 1/8 | `███████████████ 100%` |
| 9 | `regexp.(*bitState).reset` | 64.0kB | 2/8 | `███████████████ 100%` |
| 10 | `v3/newrelic.newAnalyticsEvents` | 56.0kB | 2/8 | `███████████████ 100%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 198.57GB | 3/8 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.09GB | 3/8 | `███░░░░░░░░░░░░ 22%` |
| 3 | `reflect.growslice` | 44.1GB | 3/8 | `███░░░░░░░░░░░░ 22%` |
| 4 | `fmt.(*buffer).writeString` | 31.52GB | 3/8 | `██░░░░░░░░░░░░░ 15%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 14.4GB | 3/8 | `█░░░░░░░░░░░░░░ 7%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 14.37GB | 3/8 | `█░░░░░░░░░░░░░░ 7%` |
| 7 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 13.44GB | 3/8 | `█░░░░░░░░░░░░░░ 6%` |
| 8 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 13.43GB | 3/8 | `█░░░░░░░░░░░░░░ 6%` |
| 9 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 9.56GB | 3/8 | `░░░░░░░░░░░░░░░ 4%` |
| 10 | `compress/flate.NewWriter` | 5.04GB | 6/8 | `░░░░░░░░░░░░░░░ 2%` |

## Alerts

No anomalies detected.
