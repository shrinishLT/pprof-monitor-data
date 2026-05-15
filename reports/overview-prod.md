# Overview: prod
*Last updated: 2026-05-15 21:58 IST*
*Data range: 2026-05-15T16:03 to 2026-05-15T21:58 (6 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,619 | avg: 14,288 | max: 14,619 | trend: INCREASING (+114.57/hr))
```
▂▂▁▁▃█
```

**Heap InUse** (current: 280.1MB | avg: 245.5MB | max: 280.1MB | trend: INCREASING (+2.77MB/hr))
```
▅▄▄▁▄█
```

## Current Status

Goroutines: `████████████████████ 100%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,619 | 14,322 | +297 | 14,288 | 14,619 | INCREASING (+114.57/hr) |
| Heap InUse | 280.1MB | 237.9MB | +42.2MB | 245.5MB | 280.1MB | INCREASING (+2.77MB/hr) |
| Heap Sys | 5825.2MB | 5825.2MB | +0.0MB | 5825.2MB | 5825.2MB | |
| Heap Objects | 1,322,856 | 927,574 | +395282 | 1,020,668 | 1,322,856 | |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.16MB |
| 3 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.29MB |
| 4 | `compress/flate.NewWriter` | 1.27MB |
| 5 | `runtime.mallocgc` | 991.34kB |
| 6 | `jasonlvhit/gocron.NewScheduler` | 80.0kB |
| 7 | `regexp.(*bitState).reset` | 64.0kB |
| 8 | `compress/flate.(*compressor).initDeflate` | 64.0kB |
| 9 | `fmt.(*buffer).writeString` | 56.0kB |
| 10 | `bufio.NewReaderSize` | 56.0kB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 197.01GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 44.73GB |
| 3 | `reflect.growslice` | 44.09GB |
| 4 | `fmt.(*buffer).writeString` | 31.52GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 14.37GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 14.34GB |
| 7 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 13.33GB |
| 8 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 13.32GB |
| 9 | `compress/flate.NewWriter` | 10.05GB |
| 10 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 9.55GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 4/6 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.16MB | 4/6 | `███░░░░░░░░░░░░ 25%` |
| 3 | `compress/flate.NewWriter` | 2.53MB | 4/6 | `█░░░░░░░░░░░░░░ 6%` |
| 4 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.29MB | 4/6 | `░░░░░░░░░░░░░░░ 6%` |
| 5 | `runtime.mallocgc` | 991.34kB | 4/6 | `███████████████ 100%` |
| 6 | `compress/flate.(*compressor).initDeflate` | 168.0kB | 4/6 | `███████████████ 100%` |
| 7 | `jasonlvhit/gocron.NewScheduler` | 80.0kB | 4/6 | `███████████████ 100%` |
| 8 | `v3/newrelic.newLogEvents` | 72.0kB | 1/6 | `███████████████ 100%` |
| 9 | `regexp.(*bitState).reset` | 64.0kB | 2/6 | `███████████████ 100%` |
| 10 | `v3/newrelic.newAnalyticsEvents` | 64.0kB | 1/6 | `███████████████ 100%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 197.01GB | 1/6 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 44.73GB | 1/6 | `███░░░░░░░░░░░░ 22%` |
| 3 | `reflect.growslice` | 44.09GB | 1/6 | `███░░░░░░░░░░░░ 22%` |
| 4 | `fmt.(*buffer).writeString` | 31.52GB | 1/6 | `██░░░░░░░░░░░░░ 15%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 14.37GB | 1/6 | `█░░░░░░░░░░░░░░ 7%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 14.34GB | 1/6 | `█░░░░░░░░░░░░░░ 7%` |
| 7 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 13.33GB | 1/6 | `█░░░░░░░░░░░░░░ 6%` |
| 8 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 13.32GB | 1/6 | `█░░░░░░░░░░░░░░ 6%` |
| 9 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 9.55GB | 1/6 | `░░░░░░░░░░░░░░░ 4%` |
| 10 | `compress/flate.NewWriter` | 2.51GB | 4/6 | `░░░░░░░░░░░░░░░ 1%` |

## Alerts

No anomalies detected.
