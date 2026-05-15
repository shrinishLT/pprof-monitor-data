# Overview: stage
*Last updated: 2026-05-15 21:53 IST*
*Data range: 2026-05-15T16:03 to 2026-05-15T21:53 (5 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,089 | avg: 14,086 | max: 14,131 | trend: decreasing (-6.00/hr))
```
▁█▁▁▃
```

**Heap InUse** (current: 139.0MB | avg: 137.6MB | max: 177.0MB | trend: INCREASING (+10.60MB/hr))
```
▃▅▁█▄
```

## Current Status

Goroutines: `███████████████████░ 99%`
Heap InUse: `████████░░░░░░░░░░░░ 43%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,089 | 14,071 | +18 | 14,086 | 14,131 | decreasing (-6.00/hr) |
| Heap InUse | 139.0MB | 177.0MB | -38.0MB | 137.6MB | 177.0MB | INCREASING (+10.60MB/hr) |
| Heap Sys | 318.0MB | 318.0MB | +0.0MB | 318.0MB | 318.0MB | |
| Heap Objects | 797,382 | 1,309,284 | -511902 | 764,939 | 1,309,284 | |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.16MB |
| 3 | `compress/flate.NewWriter` | 2.53MB |
| 4 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.29MB |
| 5 | `compress/flate.(*compressor).initDeflate` | 128.0kB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 80.0kB |
| 7 | `net/http.init.func16` | 64.0kB |
| 8 | `reflect.unsafe_NewArray` | 54.12kB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 40.0kB |
| 10 | `runtime.mallocgc` | 17.38kB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.16MB |
| 3 | `compress/flate.NewWriter` | 2.53MB |
| 4 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.29MB |
| 5 | `compress/flate.(*compressor).initDeflate` | 128.0kB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 80.0kB |
| 7 | `net/http.init.func16` | 64.0kB |
| 8 | `reflect.unsafe_NewArray` | 54.12kB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 40.0kB |
| 10 | `runtime.mallocgc` | 17.38kB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3/5 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.16MB | 3/5 | `███░░░░░░░░░░░░ 25%` |
| 3 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.29MB | 3/5 | `░░░░░░░░░░░░░░░ 6%` |
| 4 | `compress/flate.NewWriter` | 1.69MB | 3/5 | `░░░░░░░░░░░░░░░ 4%` |
| 5 | `kafka-go/protocol.newPage` | 128.0kB | 1/5 | `███████████████ 100%` |
| 6 | `compress/flate.(*compressor).initDeflate` | 100.0kB | 2/5 | `███████████████ 100%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 80.0kB | 1/5 | `███████████████ 100%` |
| 8 | `v3/newrelic.newLogEvents` | 72.0kB | 2/5 | `███████████████ 100%` |
| 9 | `reflect.unsafe_NewArray` | 54.12kB | 1/5 | `███████████████ 100%` |
| 10 | `v3/newrelic.newAnalyticsEvents` | 48.0kB | 1/5 | `███████████████ 100%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3/5 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.16MB | 3/5 | `███░░░░░░░░░░░░ 25%` |
| 3 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.29MB | 3/5 | `░░░░░░░░░░░░░░░ 6%` |
| 4 | `compress/flate.NewWriter` | 1.69MB | 3/5 | `░░░░░░░░░░░░░░░ 4%` |
| 5 | `kafka-go/protocol.newPage` | 128.0kB | 1/5 | `███████████████ 100%` |
| 6 | `compress/flate.(*compressor).initDeflate` | 100.0kB | 2/5 | `███████████████ 100%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 80.0kB | 1/5 | `███████████████ 100%` |
| 8 | `v3/newrelic.newLogEvents` | 72.0kB | 2/5 | `███████████████ 100%` |
| 9 | `reflect.unsafe_NewArray` | 54.12kB | 1/5 | `███████████████ 100%` |
| 10 | `v3/newrelic.newAnalyticsEvents` | 48.0kB | 1/5 | `███████████████ 100%` |

## Alerts

No anomalies detected.
