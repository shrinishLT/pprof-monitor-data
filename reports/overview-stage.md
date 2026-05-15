# Overview: stage
*Last updated: 2026-05-16 00:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T00:31 (13 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,065 | avg: 14,148 | max: 14,425 | trend: decreasing (-3.81/hr))
```
▁▂▁▁▁█▇▄▁▃▁▁▁
```

**Heap InUse** (current: 161.9MB | avg: 138.7MB | max: 181.5MB | trend: INCREASING (+1.35MB/hr))
```
▃▅▁▇▄▄▃▄▆█▁▃▆
```

## Current Status

Goroutines: `███████████████████░ 97%`
Heap InUse: `██████████░░░░░░░░░░ 50%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,065 | 14,061 | +4 | 14,148 | 14,425 | decreasing (-3.81/hr) |
| Heap InUse | 161.9MB | 121.1MB | +40.8MB | 138.7MB | 181.5MB | INCREASING (+1.35MB/hr) |
| Heap Sys | 185.5MB | 185.4MB | +0.1MB | 282.8MB | 318.0MB | |
| Heap Objects | 1,143,482 | 680,000 | +463482 | 775,489 | 1,309,284 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 3 | 14,061 | 125.1MB | 161.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 4 | `runtime.mallocgc` | 7.51MB |
| 5 | `segmentio/kafka-go.makePartitions` | 2.51MB |
| 6 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `compress/flate.NewWriter` | 1.76MB |
| 10 | `reflect.unsafe_NewArray` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 938.72MB |
| 2 | `reflect.unsafe_NewArray` | 395.02MB |
| 3 | `reflect.MakeSlice` | 242.01MB |
| 4 | `segmentio/kafka-go.makeLayout` | 87.38MB |
| 5 | `v3/newrelic.newAnalyticsEvents` | 77.04MB |
| 6 | `internal/reflectlite.unsafe_New` | 42.5MB |
| 7 | `compress/flate.NewWriter` | 40.55MB |
| 8 | `io.ReadAll` | 37.5MB |
| 9 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 10 | `reflect.mapassign_faststr0` | 35.01MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 11/13 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.18MB | 11/13 | `███░░░░░░░░░░░░ 25%` |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB | 3/13 | `██░░░░░░░░░░░░░ 16%` |
| 4 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB | 2/13 | `█░░░░░░░░░░░░░░ 6%` |
| 5 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.29MB | 11/13 | `░░░░░░░░░░░░░░░ 6%` |
| 6 | `aws/endpoints.init` | 2.0MB | 2/13 | `░░░░░░░░░░░░░░░ 5%` |
| 7 | `runtime.mallocgc` | 1.89MB | 8/13 | `░░░░░░░░░░░░░░░ 5%` |
| 8 | `compress/flate.NewWriter` | 1.81MB | 10/13 | `░░░░░░░░░░░░░░░ 4%` |
| 9 | `segmentio/kafka-go.makePartitions` | 1.51MB | 3/13 | `░░░░░░░░░░░░░░░ 4%` |
| 10 | `reflect.unsafe_NewArray` | 646.55kB | 5/13 | `███████████████ 100%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 458.76MB | 4/13 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 340.95MB | 5/13 | `███████████░░░░ 74%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 285.41MB | 6/13 | `█████████░░░░░░ 62%` |
| 4 | `reflect.MakeSlice` | 235.51MB | 2/13 | `███████░░░░░░░░ 51%` |
| 5 | `reflect.unsafe_NewArray` | 193.99MB | 4/13 | `██████░░░░░░░░░ 42%` |
| 6 | `compress/flate.NewWriter` | 101.89MB | 11/13 | `███░░░░░░░░░░░░ 22%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 70.33MB | 6/13 | `██░░░░░░░░░░░░░ 15%` |
| 8 | `experiment/local.topologicalSort` | 46.4MB | 5/13 | `█░░░░░░░░░░░░░░ 10%` |
| 9 | `internal/reflectlite.unsafe_New` | 41.25MB | 2/13 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 11/13 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

No anomalies detected.
