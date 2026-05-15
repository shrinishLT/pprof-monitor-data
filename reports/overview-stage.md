# Overview: stage
*Last updated: 2026-05-16 01:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T01:31 (16 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,065 | avg: 14,133 | max: 14,425 | trend: decreasing (-11.02/hr))
```
▁▂▁▁▁█▇▄▁▃▁▁▁▁▁▁
```

**Heap InUse** (current: 162.0MB | avg: 138.8MB | max: 181.5MB | trend: INCREASING (+0.83MB/hr))
```
▃▅▁▇▄▄▃▄▆█▁▃▆▆▁▆
```

## Current Status

Goroutines: `███████████████████░ 97%`
Heap InUse: `██████████░░░░░░░░░░ 50%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,065 | 14,071 | -6 | 14,133 | 14,425 | decreasing (-11.02/hr) |
| Heap InUse | 162.0MB | 99.1MB | +62.9MB | 138.8MB | 181.5MB | INCREASING (+0.83MB/hr) |
| Heap Sys | 188.8MB | 188.9MB | -0.1MB | 265.2MB | 318.0MB | |
| Heap Objects | 1,189,012 | 391,212 | +797800 | 799,210 | 1,309,284 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 6 | 14,066 | 132.2MB | 162.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 4 | `runtime.mallocgc` | 7.51MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 2.48GB |
| 2 | `reflect.unsafe_NewArray` | 1.07GB |
| 3 | `reflect.MakeSlice` | 620.51MB |
| 4 | `segmentio/kafka-go.makeLayout` | 250.73MB |
| 5 | `v3/newrelic.newAnalyticsEvents` | 163.34MB |
| 6 | `internal/reflectlite.unsafe_New` | 127.51MB |
| 7 | `experiment/local.(*Client).EvaluateV2` | 118.05MB |
| 8 | `internal/evaluation.mergeMetadata` | 118.03MB |
| 9 | `compress/flate.NewWriter` | 108.42MB |
| 10 | `internal/evaluation.(*Engine).Evaluate` | 106.16MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 14/16 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.19MB | 14/16 | `███░░░░░░░░░░░░ 25%` |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 7.5MB | 6/16 | `███░░░░░░░░░░░░ 20%` |
| 4 | `runtime.mallocgc` | 3.42MB | 11/16 | `█░░░░░░░░░░░░░░ 9%` |
| 5 | `segmentio/kafka-go.makePartitions` | 2.75MB | 6/16 | `█░░░░░░░░░░░░░░ 7%` |
| 6 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB | 5/16 | `█░░░░░░░░░░░░░░ 6%` |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.3MB | 14/16 | `░░░░░░░░░░░░░░░ 6%` |
| 8 | `compress/flate.NewWriter` | 2.14MB | 13/16 | `░░░░░░░░░░░░░░░ 5%` |
| 9 | `aws/endpoints.init` | 2.0MB | 5/16 | `░░░░░░░░░░░░░░░ 5%` |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 1.0MB | 1/16 | `░░░░░░░░░░░░░░░ 2%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 1.03GB | 7/16 | `███████████████ 100%` |
| 2 | `reflect.unsafe_NewArray` | 450.35MB | 7/16 | `███████████████ 100%` |
| 3 | `reflect.MakeSlice` | 365.91MB | 5/16 | `███████████████ 100%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 244.85MB | 8/16 | `███████████████ 100%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 220.91MB | 9/16 | `███████████████ 100%` |
| 6 | `compress/flate.NewWriter` | 97.75MB | 14/16 | `███████████████ 100%` |
| 7 | `internal/evaluation.mergeMetadata` | 92.36MB | 3/16 | `███████████████ 100%` |
| 8 | `segmentio/kafka-go.makeLayout` | 75.18MB | 10/16 | `███████████████ 100%` |
| 9 | `internal/reflectlite.unsafe_New` | 70.81MB | 5/16 | `███████████████ 100%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 70.33MB | 6/16 | `███████████████ 100%` |

## Alerts

No anomalies detected.
