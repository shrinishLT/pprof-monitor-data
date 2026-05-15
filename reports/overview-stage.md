# Overview: stage
*Last updated: 2026-05-15 23:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-15T23:31 (10 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,169 | avg: 14,174 | max: 14,425 | trend: INCREASING (+32.45/hr))
```
▁▂▁▁▁█▇▄▁▂
```

**Heap InUse** (current: 181.5MB | avg: 142.7MB | max: 181.5MB | trend: INCREASING (+7.71MB/hr))
```
▃▅▁▇▄▄▂▄▆█
```

## Current Status

Goroutines: `███████████████████░ 98%`
Heap InUse: `███████████░░░░░░░░░ 57%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,169 | 14,078 | +91 | 14,174 | 14,425 | INCREASING (+32.45/hr) |
| Heap InUse | 181.5MB | 162.2MB | +19.3MB | 142.7MB | 181.5MB | INCREASING (+7.71MB/hr) |
| Heap Sys | 309.9MB | 312.9MB | -3.0MB | 315.6MB | 318.0MB | |
| Heap Objects | 1,269,074 | 1,131,239 | +137835 | 791,758 | 1,309,284 | |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.16MB |
| 3 | `compress/flate.NewWriter` | 2.53MB |
| 4 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.29MB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 160.0kB |
| 6 | `kafka-go/protocol.newPage` | 128.0kB |
| 7 | `compress/flate.(*compressor).initDeflate` | 72.0kB |
| 8 | `experiment/local.(*Client).EvaluateV2` | 44.75kB |
| 9 | `bufio.NewWriterSize` | 40.0kB |
| 10 | `reflect.unsafe_NewArray` | 27.62kB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `experiment/local.(*Client).EvaluateV2` | 440.54MB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 438.38MB |
| 3 | `compress/flate.NewWriter` | 274.64MB |
| 4 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 108.23MB |
| 5 | `experiment/local.topologicalSort` | 59.45MB |
| 6 | `io.ReadAll` | 47.94MB |
| 7 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 8 | `v3/newrelic.newAnalyticsEvents` | 23.48MB |
| 9 | `v3/newrelic.newLogEvents` | 18.77MB |
| 10 | `segmentio/kafka-go.makeLayout` | 16.48MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 8/10 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.16MB | 8/10 | `███░░░░░░░░░░░░ 25%` |
| 3 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.29MB | 8/10 | `░░░░░░░░░░░░░░░ 6%` |
| 4 | `compress/flate.NewWriter` | 1.63MB | 7/10 | `░░░░░░░░░░░░░░░ 4%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 260.0kB | 4/10 | `███████████████ 100%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 228.67kB | 5/10 | `███████████████ 100%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 120.0kB | 4/10 | `███████████████ 100%` |
| 8 | `kafka-go/protocol.newPage` | 112.0kB | 4/10 | `███████████████ 100%` |
| 9 | `compress/flate.(*compressor).initDeflate` | 81.6kB | 5/10 | `███████████████ 100%` |
| 10 | `v3/newrelic.newAnalyticsEvents` | 80.0kB | 2/10 | `███████████████ 100%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.(*Engine).Evaluate` | 340.95MB | 5/10 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 285.41MB | 6/10 | `████████████░░░ 83%` |
| 3 | `compress/flate.NewWriter` | 128.07MB | 8/10 | `█████░░░░░░░░░░ 37%` |
| 4 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 70.33MB | 6/10 | `███░░░░░░░░░░░░ 20%` |
| 5 | `experiment/local.topologicalSort` | 46.4MB | 5/10 | `██░░░░░░░░░░░░░ 13%` |
| 6 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 8/10 | `█░░░░░░░░░░░░░░ 10%` |
| 7 | `io.ReadAll` | 32.54MB | 5/10 | `█░░░░░░░░░░░░░░ 9%` |
| 8 | `v3/newrelic.newAnalyticsEvents` | 13.39MB | 6/10 | `░░░░░░░░░░░░░░░ 3%` |
| 9 | `segmentio/kafka-go.makeLayout` | 10.13MB | 4/10 | `░░░░░░░░░░░░░░░ 2%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.16MB | 5/10 | `░░░░░░░░░░░░░░░ 2%` |

## Alerts

No anomalies detected.
