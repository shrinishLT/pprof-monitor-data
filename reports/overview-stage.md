# Overview: stage
*Last updated: 2026-05-15 21:58 IST*
*Data range: 2026-05-15T16:03 to 2026-05-15T21:58 (6 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,425 | avg: 14,143 | max: 14,425 | trend: INCREASING (+93.31/hr))
```
▁▂▁▁▁█
```

**Heap InUse** (current: 134.6MB | avg: 137.1MB | max: 177.0MB | trend: INCREASING (+5.21MB/hr))
```
▃▅▁█▄▄
```

## Current Status

Goroutines: `████████████████████ 100%`
Heap InUse: `████████░░░░░░░░░░░░ 42%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,425 | 14,089 | +336 | 14,143 | 14,425 | INCREASING (+93.31/hr) |
| Heap InUse | 134.6MB | 139.0MB | -4.4MB | 137.1MB | 177.0MB | INCREASING (+5.21MB/hr) |
| Heap Sys | 315.4MB | 318.0MB | -2.6MB | 317.6MB | 318.0MB | |
| Heap Objects | 529,917 | 797,382 | -267465 | 725,768 | 1,309,284 | |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.16MB |
| 3 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.29MB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 480.0kB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 320.0kB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 160.0kB |
| 7 | `experiment/local.topologicalSort` | 95.88kB |
| 8 | `bufio.NewWriterSize` | 36.0kB |
| 9 | `runtime.mallocgc` | 17.38kB |
| 10 | `bufio.NewReaderSize` | 16.0kB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `experiment/local.(*Client).EvaluateV2` | 240.4MB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 235.86MB |
| 3 | `compress/flate.NewWriter` | 146.81MB |
| 4 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 58.91MB |
| 5 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 6 | `experiment/local.topologicalSort` | 32.76MB |
| 7 | `io.ReadAll` | 22.06MB |
| 8 | `v3/newrelic.newAnalyticsEvents` | 10.63MB |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.16MB |
| 10 | `v3/newrelic.newLogEvents` | 8.93MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 4/6 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.16MB | 4/6 | `███░░░░░░░░░░░░ 25%` |
| 3 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.29MB | 4/6 | `░░░░░░░░░░░░░░░ 6%` |
| 4 | `compress/flate.NewWriter` | 1.69MB | 3/6 | `░░░░░░░░░░░░░░░ 4%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 320.0kB | 1/6 | `███████████████ 100%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 280.0kB | 2/6 | `███████████████ 100%` |
| 7 | `kafka-go/protocol.newPage` | 128.0kB | 1/6 | `███████████████ 100%` |
| 8 | `compress/flate.(*compressor).initDeflate` | 100.0kB | 2/6 | `███████████████ 100%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 100.0kB | 2/6 | `███████████████ 100%` |
| 10 | `experiment/local.topologicalSort` | 95.88kB | 1/6 | `███████████████ 100%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.(*Engine).Evaluate` | 235.86MB | 1/6 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 120.24MB | 2/6 | `███████░░░░░░░░ 50%` |
| 3 | `compress/flate.NewWriter` | 37.97MB | 4/6 | `██░░░░░░░░░░░░░ 16%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 4/6 | `██░░░░░░░░░░░░░ 15%` |
| 5 | `experiment/local.topologicalSort` | 32.76MB | 1/6 | `██░░░░░░░░░░░░░ 13%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 29.47MB | 2/6 | `█░░░░░░░░░░░░░░ 12%` |
| 7 | `io.ReadAll` | 22.06MB | 1/6 | `█░░░░░░░░░░░░░░ 9%` |
| 8 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.16MB | 4/6 | `░░░░░░░░░░░░░░░ 3%` |
| 9 | `v3/newrelic.newAnalyticsEvents` | 5.34MB | 2/6 | `░░░░░░░░░░░░░░░ 2%` |
| 10 | `v3/newrelic.newLogEvents` | 3.02MB | 3/6 | `░░░░░░░░░░░░░░░ 1%` |

## Alerts

No anomalies detected.
