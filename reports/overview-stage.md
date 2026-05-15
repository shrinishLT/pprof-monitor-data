# Overview: stage
*Last updated: 2026-05-15 22:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-15T22:02 (7 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,385 | avg: 14,177 | max: 14,425 | trend: INCREASING (+110.21/hr))
```
▁▂▁▁▁█▇
```

**Heap InUse** (current: 119.7MB | avg: 134.6MB | max: 177.0MB | trend: stable (-0.47MB/hr))
```
▃▅▁█▄▄▃
```

## Current Status

Goroutines: `███████████████████░ 99%`
Heap InUse: `███████░░░░░░░░░░░░░ 37%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,385 | 14,425 | -40 | 14,177 | 14,425 | INCREASING (+110.21/hr) |
| Heap InUse | 119.7MB | 134.6MB | -14.9MB | 134.6MB | 177.0MB | stable (-0.47MB/hr) |
| Heap Sys | 315.2MB | 315.4MB | -0.2MB | 317.2MB | 318.0MB | |
| Heap Objects | 400,048 | 529,917 | -129869 | 679,237 | 1,309,284 | |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.16MB |
| 3 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.29MB |
| 4 | `compress/flate.NewWriter` | 648.0kB |
| 5 | `experiment/local.(*Client).EvaluateV2` | 160.0kB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 80.02kB |
| 7 | `internal/evaluation.(*Engine).Evaluate` | 80.0kB |
| 8 | `compress/flate.(*compressor).initDeflate` | 72.0kB |
| 9 | `v3/newrelic.newLogEvents` | 72.0kB |
| 10 | `kafka-go/protocol.newPage` | 64.0kB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `experiment/local.(*Client).EvaluateV2` | 289.08MB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 284.46MB |
| 3 | `compress/flate.NewWriter` | 160.73MB |
| 4 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 70.97MB |
| 5 | `experiment/local.topologicalSort` | 38.72MB |
| 6 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 7 | `io.ReadAll` | 22.06MB |
| 8 | `v3/newrelic.newAnalyticsEvents` | 11.51MB |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.16MB |
| 10 | `v3/newrelic.newLogEvents` | 9.14MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 5/7 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.16MB | 5/7 | `███░░░░░░░░░░░░ 25%` |
| 3 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.29MB | 5/7 | `░░░░░░░░░░░░░░░ 6%` |
| 4 | `compress/flate.NewWriter` | 1.43MB | 4/7 | `░░░░░░░░░░░░░░░ 3%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 240.0kB | 3/7 | `███████████████ 100%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 200.0kB | 2/7 | `███████████████ 100%` |
| 7 | `kafka-go/protocol.newPage` | 96.0kB | 2/7 | `███████████████ 100%` |
| 8 | `experiment/local.topologicalSort` | 95.88kB | 1/7 | `███████████████ 100%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 93.34kB | 3/7 | `███████████████ 100%` |
| 10 | `compress/flate.(*compressor).initDeflate` | 90.67kB | 3/7 | `███████████████ 100%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.(*Engine).Evaluate` | 260.16MB | 2/7 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 176.52MB | 3/7 | `██████████░░░░░ 67%` |
| 3 | `compress/flate.NewWriter` | 62.52MB | 5/7 | `███░░░░░░░░░░░░ 24%` |
| 4 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.31MB | 3/7 | `██░░░░░░░░░░░░░ 16%` |
| 5 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 5/7 | `██░░░░░░░░░░░░░ 14%` |
| 6 | `experiment/local.topologicalSort` | 35.74MB | 2/7 | `██░░░░░░░░░░░░░ 13%` |
| 7 | `io.ReadAll` | 22.06MB | 2/7 | `█░░░░░░░░░░░░░░ 8%` |
| 8 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.16MB | 5/7 | `░░░░░░░░░░░░░░░ 3%` |
| 9 | `v3/newrelic.newAnalyticsEvents` | 7.4MB | 3/7 | `░░░░░░░░░░░░░░░ 2%` |
| 10 | `v3/newrelic.newLogEvents` | 4.55MB | 4/7 | `░░░░░░░░░░░░░░░ 1%` |

## Alerts

No anomalies detected.
