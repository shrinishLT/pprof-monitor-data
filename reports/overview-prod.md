# Overview: prod
*Last updated: 2026-05-15 23:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-15T23:31 (10 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,406 | avg: 14,311 | max: 14,619 | trend: INCREASING (+38.51/hr))
```
▂▂▁▁▃█▆▁▃▄
```

**Heap InUse** (current: 207.7MB | avg: 239.5MB | max: 280.1MB | trend: decreasing (-4.70MB/hr))
```
▅▄▄▁▄█▂▆▃▁
```

## Current Status

Goroutines: `███████████████████░ 98%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,406 | 14,291 | +115 | 14,311 | 14,619 | INCREASING (+38.51/hr) |
| Heap InUse | 207.7MB | 230.3MB | -22.6MB | 239.5MB | 280.1MB | decreasing (-4.70MB/hr) |
| Heap Sys | 5824.3MB | 5823.2MB | +1.1MB | 5824.9MB | 5825.3MB | |
| Heap Objects | 459,452 | 781,077 | -321625 | 929,636 | 1,322,856 | |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.16MB |
| 3 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.29MB |
| 4 | `compress/flate.NewWriter` | 1.27MB |
| 5 | `runtime.mallocgc` | 991.34kB |
| 6 | `compress/flate.(*compressor).initDeflate` | 200.0kB |
| 7 | `jasonlvhit/gocron.NewScheduler` | 80.0kB |
| 8 | `bufio.NewReaderSize` | 44.0kB |
| 9 | `bufio.NewWriterSize` | 44.0kB |
| 10 | `experiment/local.(*Client).EvaluateV2` | 40.0kB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 206.42GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.88GB |
| 3 | `reflect.growslice` | 44.11GB |
| 4 | `fmt.(*buffer).writeString` | 31.53GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 14.81GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 14.79GB |
| 7 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 14.06GB |
| 8 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 14.05GB |
| 9 | `compress/flate.NewWriter` | 10.28GB |
| 10 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 9.58GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 8/10 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.16MB | 8/10 | `███░░░░░░░░░░░░ 25%` |
| 3 | `compress/flate.NewWriter` | 2.29MB | 8/10 | `░░░░░░░░░░░░░░░ 6%` |
| 4 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.29MB | 8/10 | `░░░░░░░░░░░░░░░ 6%` |
| 5 | `runtime.mallocgc` | 991.34kB | 8/10 | `███████████████ 100%` |
| 6 | `compress/flate.(*compressor).initDeflate` | 144.0kB | 7/10 | `███████████████ 100%` |
| 7 | `kafka-go/protocol.newPage` | 128.0kB | 1/10 | `███████████████ 100%` |
| 8 | `jasonlvhit/gocron.NewScheduler` | 80.0kB | 8/10 | `███████████████ 100%` |
| 9 | `v3/newrelic.newLogEvents` | 72.0kB | 2/10 | `███████████████ 100%` |
| 10 | `regexp.(*bitState).reset` | 64.0kB | 2/10 | `███████████████ 100%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 200.77GB | 5/10 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.59GB | 5/10 | `███░░░░░░░░░░░░ 22%` |
| 3 | `reflect.growslice` | 44.1GB | 5/10 | `███░░░░░░░░░░░░ 21%` |
| 4 | `fmt.(*buffer).writeString` | 31.52GB | 5/10 | `██░░░░░░░░░░░░░ 15%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 14.55GB | 5/10 | `█░░░░░░░░░░░░░░ 7%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 14.52GB | 5/10 | `█░░░░░░░░░░░░░░ 7%` |
| 7 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 13.61GB | 5/10 | `█░░░░░░░░░░░░░░ 6%` |
| 8 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 13.6GB | 5/10 | `█░░░░░░░░░░░░░░ 6%` |
| 9 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 9.57GB | 5/10 | `░░░░░░░░░░░░░░░ 4%` |
| 10 | `compress/flate.NewWriter` | 6.34GB | 8/10 | `░░░░░░░░░░░░░░░ 3%` |

## Alerts

No anomalies detected.
