# Overview: prod
*Last updated: 2026-05-15 21:53 IST*
*Data range: 2026-05-15T16:03 to 2026-05-15T21:52 (5 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,322 | avg: 14,222 | max: 14,322 | trend: INCREASING (+2.20/hr))
```
▅▄▁▁█
```

**Heap InUse** (current: 237.9MB | avg: 238.6MB | max: 256.1MB | trend: decreasing (-15.90MB/hr))
```
█▆▆▁▅
```

## Current Status

Goroutines: `████████████████████ 100%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,322 | 14,136 | +186 | 14,222 | 14,322 | INCREASING (+2.20/hr) |
| Heap InUse | 237.9MB | 204.6MB | +33.3MB | 238.6MB | 256.1MB | decreasing (-15.90MB/hr) |
| Heap Sys | 5825.2MB | 5825.2MB | +0.0MB | 5825.2MB | 5825.2MB | |
| Heap Objects | 927,574 | 562,503 | +365071 | 960,230 | 1,131,046 | |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.16MB |
| 3 | `compress/flate.NewWriter` | 2.53MB |
| 4 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.29MB |
| 5 | `runtime.mallocgc` | 991.34kB |
| 6 | `compress/flate.(*compressor).initDeflate` | 336.0kB |
| 7 | `jasonlvhit/gocron.NewScheduler` | 80.0kB |
| 8 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 56.0kB |
| 9 | `bufio.NewReaderSize` | 48.0kB |
| 10 | `bufio.NewWriterSize` | 48.0kB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.16MB |
| 3 | `compress/flate.NewWriter` | 2.53MB |
| 4 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.29MB |
| 5 | `runtime.mallocgc` | 991.34kB |
| 6 | `compress/flate.(*compressor).initDeflate` | 336.0kB |
| 7 | `jasonlvhit/gocron.NewScheduler` | 80.0kB |
| 8 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 56.0kB |
| 9 | `bufio.NewReaderSize` | 48.0kB |
| 10 | `bufio.NewWriterSize` | 48.0kB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3/5 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.16MB | 3/5 | `███░░░░░░░░░░░░ 25%` |
| 3 | `compress/flate.NewWriter` | 2.95MB | 3/5 | `█░░░░░░░░░░░░░░ 8%` |
| 4 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.29MB | 3/5 | `░░░░░░░░░░░░░░░ 6%` |
| 5 | `runtime.mallocgc` | 991.34kB | 3/5 | `███████████████ 100%` |
| 6 | `compress/flate.(*compressor).initDeflate` | 202.67kB | 3/5 | `███████████████ 100%` |
| 7 | `jasonlvhit/gocron.NewScheduler` | 80.0kB | 3/5 | `███████████████ 100%` |
| 8 | `v3/newrelic.newLogEvents` | 72.0kB | 1/5 | `███████████████ 100%` |
| 9 | `regexp.(*bitState).reset` | 64.0kB | 1/5 | `███████████████ 100%` |
| 10 | `v3/newrelic.newAnalyticsEvents` | 64.0kB | 1/5 | `███████████████ 100%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3/5 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.16MB | 3/5 | `███░░░░░░░░░░░░ 25%` |
| 3 | `compress/flate.NewWriter` | 2.95MB | 3/5 | `█░░░░░░░░░░░░░░ 8%` |
| 4 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.29MB | 3/5 | `░░░░░░░░░░░░░░░ 6%` |
| 5 | `runtime.mallocgc` | 991.34kB | 3/5 | `███████████████ 100%` |
| 6 | `compress/flate.(*compressor).initDeflate` | 202.67kB | 3/5 | `███████████████ 100%` |
| 7 | `jasonlvhit/gocron.NewScheduler` | 80.0kB | 3/5 | `███████████████ 100%` |
| 8 | `v3/newrelic.newLogEvents` | 72.0kB | 1/5 | `███████████████ 100%` |
| 9 | `regexp.(*bitState).reset` | 64.0kB | 1/5 | `███████████████ 100%` |
| 10 | `v3/newrelic.newAnalyticsEvents` | 64.0kB | 1/5 | `███████████████ 100%` |

## Alerts

No anomalies detected.
