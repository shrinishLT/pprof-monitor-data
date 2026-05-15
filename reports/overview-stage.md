# Overview: stage
*Last updated: 2026-05-15 22:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-15T22:31 (8 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,250 | avg: 14,186 | max: 14,425 | trend: INCREASING (+85.57/hr))
```
▁▂▁▁▁█▇▄
```

**Heap InUse** (current: 141.4MB | avg: 135.5MB | max: 177.0MB | trend: INCREASING (+0.82MB/hr))
```
▃▅▁█▄▄▃▄
```

## Current Status

Goroutines: `███████████████████░ 98%`
Heap InUse: `████████░░░░░░░░░░░░ 44%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,250 | 14,385 | -135 | 14,186 | 14,425 | INCREASING (+85.57/hr) |
| Heap InUse | 141.4MB | 119.7MB | +21.7MB | 135.5MB | 177.0MB | INCREASING (+0.82MB/hr) |
| Heap Sys | 312.3MB | 315.2MB | -2.9MB | 316.6MB | 318.0MB | |
| Heap Objects | 762,611 | 400,048 | +362563 | 689,659 | 1,309,284 | |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.16MB |
| 3 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.29MB |
| 4 | `compress/flate.NewWriter` | 1.27MB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 480.0kB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 378.62kB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 200.0kB |
| 8 | `kafka-go/protocol.newPage` | 128.0kB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 112.0kB |
| 10 | `experiment/local.topologicalSort` | 58.0kB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.(*Engine).Evaluate` | 370.13MB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 368.4MB |
| 3 | `compress/flate.NewWriter` | 208.83MB |
| 4 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 91.2MB |
| 5 | `experiment/local.topologicalSort` | 50.05MB |
| 6 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 7 | `io.ReadAll` | 30.9MB |
| 8 | `v3/newrelic.newAnalyticsEvents` | 15.27MB |
| 9 | `v3/newrelic.newLogEvents` | 11.81MB |
| 10 | `segmentio/kafka-go.makeLayout` | 10.29MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 6/8 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.16MB | 6/8 | `███░░░░░░░░░░░░ 25%` |
| 3 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.29MB | 6/8 | `░░░░░░░░░░░░░░░ 6%` |
| 4 | `compress/flate.NewWriter` | 1.39MB | 5/8 | `░░░░░░░░░░░░░░░ 3%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 293.33kB | 3/8 | `███████████████ 100%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 274.65kB | 4/8 | `███████████████ 100%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 120.0kB | 4/8 | `███████████████ 100%` |
| 8 | `kafka-go/protocol.newPage` | 106.67kB | 3/8 | `███████████████ 100%` |
| 9 | `compress/flate.(*compressor).initDeflate` | 90.67kB | 3/8 | `███████████████ 100%` |
| 10 | `v3/newrelic.newAnalyticsEvents` | 80.0kB | 2/8 | `███████████████ 100%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.(*Engine).Evaluate` | 296.82MB | 3/8 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 224.49MB | 4/8 | `███████████░░░░ 75%` |
| 3 | `compress/flate.NewWriter` | 86.91MB | 6/8 | `████░░░░░░░░░░░ 29%` |
| 4 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 55.28MB | 4/8 | `██░░░░░░░░░░░░░ 18%` |
| 5 | `experiment/local.topologicalSort` | 40.51MB | 3/8 | `██░░░░░░░░░░░░░ 13%` |
| 6 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 6/8 | `█░░░░░░░░░░░░░░ 12%` |
| 7 | `io.ReadAll` | 25.01MB | 3/8 | `█░░░░░░░░░░░░░░ 8%` |
| 8 | `v3/newrelic.newAnalyticsEvents` | 9.36MB | 4/8 | `░░░░░░░░░░░░░░░ 3%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.16MB | 5/8 | `░░░░░░░░░░░░░░░ 3%` |
| 10 | `v3/newrelic.newLogEvents` | 6.0MB | 5/8 | `░░░░░░░░░░░░░░░ 2%` |

## Alerts

No anomalies detected.
