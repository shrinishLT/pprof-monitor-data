# Overview: stage
*Last updated: 2026-05-16 02:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T02:03 (17 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,344 | avg: 14,146 | max: 14,425 | trend: decreasing (-0.92/hr))
```
▁▂▁▁▁█▇▄▁▃▁▁▁▁▁▁▆
```

**Heap InUse** (current: 102.2MB | avg: 136.6MB | max: 181.5MB | trend: decreasing (-0.74MB/hr))
```
▃▅▁▇▄▄▃▄▆█▁▃▆▆▁▆▁
```

## Current Status

Goroutines: `███████████████████░ 99%`
Heap InUse: `██████░░░░░░░░░░░░░░ 32%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,344 | 14,065 | +279 | 14,146 | 14,425 | decreasing (-0.92/hr) |
| Heap InUse | 102.2MB | 162.0MB | -59.8MB | 136.6MB | 181.5MB | decreasing (-0.74MB/hr) |
| Heap Sys | 192.9MB | 188.8MB | +4.1MB | 261.0MB | 318.0MB | |
| Heap Objects | 300,456 | 1,189,012 | -888556 | 769,872 | 1,309,284 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 7 | 14,105 | 127.9MB | 162.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 4 | `runtime.mallocgc` | 7.51MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `bytes.growSlice` | 1.51MB |
| 10 | `reflect.unsafe_NewArray` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 3.41GB |
| 2 | `reflect.unsafe_NewArray` | 1.47GB |
| 3 | `reflect.MakeSlice` | 847.02MB |
| 4 | `segmentio/kafka-go.makeLayout` | 359.65MB |
| 5 | `internal/evaluation.mergeMetadata` | 245.06MB |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 238.06MB |
| 7 | `experiment/local.(*Client).EvaluateV2` | 235.34MB |
| 8 | `v3/newrelic.newAnalyticsEvents` | 221.13MB |
| 9 | `internal/reflectlite.unsafe_New` | 170.52MB |
| 10 | `compress/flate.NewWriter` | 138.38MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 15/17 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.2MB | 15/17 | `███░░░░░░░░░░░░ 25%` |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 7.71MB | 7/17 | `███░░░░░░░░░░░░ 21%` |
| 4 | `runtime.mallocgc` | 3.76MB | 12/17 | `█░░░░░░░░░░░░░░ 10%` |
| 5 | `segmentio/kafka-go.makePartitions` | 2.75MB | 6/17 | `█░░░░░░░░░░░░░░ 7%` |
| 6 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB | 6/17 | `█░░░░░░░░░░░░░░ 6%` |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.3MB | 15/17 | `░░░░░░░░░░░░░░░ 6%` |
| 8 | `compress/flate.NewWriter` | 2.17MB | 14/17 | `░░░░░░░░░░░░░░░ 5%` |
| 9 | `aws/endpoints.init` | 2.0MB | 6/17 | `░░░░░░░░░░░░░░░ 5%` |
| 10 | `bytes.growSlice` | 1.51MB | 1/17 | `░░░░░░░░░░░░░░░ 4%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 1.32GB | 8/17 | `███████████████ 100%` |
| 2 | `reflect.unsafe_NewArray` | 582.22MB | 8/17 | `███████████████ 100%` |
| 3 | `reflect.MakeSlice` | 446.09MB | 6/17 | `███████████████ 100%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 244.1MB | 9/17 | `███████████████ 100%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 222.35MB | 10/17 | `███████████████ 100%` |
| 6 | `internal/evaluation.mergeMetadata` | 130.53MB | 4/17 | `███████████████ 100%` |
| 7 | `segmentio/kafka-go.makeLayout` | 101.05MB | 11/17 | `███████████████ 100%` |
| 8 | `compress/flate.NewWriter` | 100.46MB | 15/17 | `███████████████ 100%` |
| 9 | `internal/reflectlite.unsafe_New` | 87.42MB | 6/17 | `███████████████ 100%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 70.33MB | 6/17 | `███████████████ 100%` |

## Alerts

No anomalies detected.
