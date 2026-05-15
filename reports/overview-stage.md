# Overview: stage
*Last updated: 2026-05-15 23:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-15T23:03 (9 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,078 | avg: 14,174 | max: 14,425 | trend: INCREASING (+45.43/hr))
```
▁▂▁▁▁█▇▄▁
```

**Heap InUse** (current: 162.2MB | avg: 138.4MB | max: 177.0MB | trend: INCREASING (+4.14MB/hr))
```
▃▅▁█▄▄▃▄▆
```

## Current Status

Goroutines: `███████████████████░ 97%`
Heap InUse: `██████████░░░░░░░░░░ 51%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,078 | 14,250 | -172 | 14,174 | 14,425 | INCREASING (+45.43/hr) |
| Heap InUse | 162.2MB | 141.4MB | +20.8MB | 138.4MB | 177.0MB | INCREASING (+4.14MB/hr) |
| Heap Sys | 312.9MB | 312.3MB | +0.6MB | 316.2MB | 318.0MB | |
| Heap Objects | 1,131,239 | 762,611 | +368628 | 738,723 | 1,309,284 | |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.16MB |
| 3 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.29MB |
| 4 | `compress/flate.NewWriter` | 1.9MB |
| 5 | `compress/flate.(*compressor).initDeflate` | 64.0kB |
| 6 | `reflect.unsafe_NewArray` | 58.52kB |
| 7 | `bufio.NewWriterSize` | 32.0kB |
| 8 | `runtime.mallocgc` | 17.38kB |
| 9 | `encoding/json.typeFields` | 5.45kB |
| 10 | `http2/hpack.init` | 5.25kB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.(*Engine).Evaluate` | 375.94MB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 373.99MB |
| 3 | `compress/flate.NewWriter` | 228.45MB |
| 4 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 92.63MB |
| 5 | `experiment/local.topologicalSort` | 51.04MB |
| 6 | `io.ReadAll` | 39.76MB |
| 7 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 8 | `v3/newrelic.newAnalyticsEvents` | 19.39MB |
| 9 | `v3/newrelic.newLogEvents` | 15.19MB |
| 10 | `segmentio/kafka-go.makeLayout` | 13.72MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 7/9 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.16MB | 7/9 | `███░░░░░░░░░░░░ 25%` |
| 3 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.29MB | 7/9 | `░░░░░░░░░░░░░░░ 6%` |
| 4 | `compress/flate.NewWriter` | 1.48MB | 6/9 | `░░░░░░░░░░░░░░░ 4%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 293.33kB | 3/9 | `███████████████ 100%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 274.65kB | 4/9 | `███████████████ 100%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 120.0kB | 4/9 | `███████████████ 100%` |
| 8 | `kafka-go/protocol.newPage` | 106.67kB | 3/9 | `███████████████ 100%` |
| 9 | `compress/flate.(*compressor).initDeflate` | 84.0kB | 4/9 | `███████████████ 100%` |
| 10 | `v3/newrelic.newAnalyticsEvents` | 80.0kB | 2/9 | `███████████████ 100%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.(*Engine).Evaluate` | 316.6MB | 4/9 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 254.39MB | 5/9 | `████████████░░░ 80%` |
| 3 | `compress/flate.NewWriter` | 107.13MB | 7/9 | `█████░░░░░░░░░░ 33%` |
| 4 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 62.75MB | 5/9 | `██░░░░░░░░░░░░░ 19%` |
| 5 | `experiment/local.topologicalSort` | 43.14MB | 4/9 | `██░░░░░░░░░░░░░ 13%` |
| 6 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 7/9 | `█░░░░░░░░░░░░░░ 11%` |
| 7 | `io.ReadAll` | 28.7MB | 4/9 | `█░░░░░░░░░░░░░░ 9%` |
| 8 | `v3/newrelic.newAnalyticsEvents` | 11.37MB | 5/9 | `░░░░░░░░░░░░░░░ 3%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.16MB | 5/9 | `░░░░░░░░░░░░░░░ 2%` |
| 10 | `segmentio/kafka-go.makeLayout` | 8.01MB | 3/9 | `░░░░░░░░░░░░░░░ 2%` |

## Alerts

No anomalies detected.
