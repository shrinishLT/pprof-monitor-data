# Overview: stage
*Last updated: 2026-05-16 00:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T00:01 (11 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,057 | avg: 14,163 | max: 14,425 | trend: INCREASING (+13.71/hr))
```
▁▂▁▁▁█▇▄▁▃▁
```

**Heap InUse** (current: 92.3MB | avg: 138.1MB | max: 181.5MB | trend: INCREASING (+1.20MB/hr))
```
▃▅▁▇▄▄▃▄▆█▁
```

## Current Status

Goroutines: `███████████████████░ 97%`
Heap InUse: `█████░░░░░░░░░░░░░░░ 29%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,057 | 14,169 | -112 | 14,163 | 14,425 | INCREASING (+13.71/hr) |
| Heap InUse | 92.3MB | 181.5MB | -89.2MB | 138.1MB | 181.5MB | INCREASING (+1.20MB/hr) |
| Heap Sys | 149.9MB | 309.9MB | -160.0MB | 300.5MB | 318.0MB | |
| Heap Objects | 340,299 | 1,269,074 | -928775 | 750,716 | 1,309,284 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 1 | 14,057 | 92.3MB | 92.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.16MB |
| 3 | `compress/flate.NewWriter` | 3.16MB |
| 4 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.29MB |
| 5 | `compress/flate.(*compressor).initDeflate` | 128.0kB |
| 6 | `bufio.NewReaderSize` | 32.0kB |
| 7 | `runtime.mallocgc` | 13.16kB |
| 8 | `http2/hpack.init` | 5.25kB |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 3.39kB |
| 10 | `reflect.mapassign_faststr0` | 912B |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `compress/flate.NewWriter` | 15.19MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.16MB |
| 4 | `io.ReadAll` | 6.8MB |
| 5 | `v3/newrelic.newAnalyticsEvents` | 2.32MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.29MB |
| 7 | `v3/newrelic.newLogEvents` | 1.9MB |
| 8 | `reflect.unsafe_NewArray` | 927.05kB |
| 9 | `segmentio/kafka-go.makeLayout` | 740.12kB |
| 10 | `segmentio/kafka-go.makePartitions` | 648.55kB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 9/11 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.16MB | 9/11 | `███░░░░░░░░░░░░ 25%` |
| 3 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.29MB | 9/11 | `░░░░░░░░░░░░░░░ 6%` |
| 4 | `compress/flate.NewWriter` | 1.82MB | 8/11 | `░░░░░░░░░░░░░░░ 4%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 260.0kB | 4/11 | `███████████████ 100%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 228.67kB | 5/11 | `███████████████ 100%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 120.0kB | 4/11 | `███████████████ 100%` |
| 8 | `kafka-go/protocol.newPage` | 112.0kB | 4/11 | `███████████████ 100%` |
| 9 | `compress/flate.(*compressor).initDeflate` | 89.33kB | 6/11 | `███████████████ 100%` |
| 10 | `v3/newrelic.newAnalyticsEvents` | 80.0kB | 2/11 | `███████████████ 100%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.(*Engine).Evaluate` | 340.95MB | 5/11 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 285.41MB | 6/11 | `████████████░░░ 83%` |
| 3 | `compress/flate.NewWriter` | 115.52MB | 9/11 | `█████░░░░░░░░░░ 33%` |
| 4 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 70.33MB | 6/11 | `███░░░░░░░░░░░░ 20%` |
| 5 | `experiment/local.topologicalSort` | 46.4MB | 5/11 | `██░░░░░░░░░░░░░ 13%` |
| 6 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 9/11 | `█░░░░░░░░░░░░░░ 10%` |
| 7 | `io.ReadAll` | 28.25MB | 6/11 | `█░░░░░░░░░░░░░░ 8%` |
| 8 | `v3/newrelic.newAnalyticsEvents` | 11.81MB | 7/11 | `░░░░░░░░░░░░░░░ 3%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.16MB | 6/11 | `░░░░░░░░░░░░░░░ 2%` |
| 10 | `segmentio/kafka-go.makeLayout` | 8.25MB | 5/11 | `░░░░░░░░░░░░░░░ 2%` |

## Alerts

No anomalies detected.
