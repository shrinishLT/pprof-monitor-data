# Overview: stage
*Last updated: 2026-05-16 00:29 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T00:29 (12 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,061 | avg: 14,155 | max: 14,425 | trend: INCREASING (+2.68/hr))
```
▁▂▁▁▁█▇▄▁▃▁▁
```

**Heap InUse** (current: 121.1MB | avg: 136.7MB | max: 181.5MB | trend: stable (-0.39MB/hr))
```
▃▅▁▇▄▄▃▄▆█▁▃
```

## Current Status

Goroutines: `███████████████████░ 97%`
Heap InUse: `███████░░░░░░░░░░░░░ 38%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,061 | 14,057 | +4 | 14,155 | 14,425 | INCREASING (+2.68/hr) |
| Heap InUse | 121.1MB | 92.3MB | +28.8MB | 136.7MB | 181.5MB | stable (-0.39MB/hr) |
| Heap Sys | 185.4MB | 149.9MB | +35.5MB | 290.9MB | 318.0MB | |
| Heap Objects | 680,000 | 340,299 | +339701 | 744,823 | 1,309,284 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 2 | 14,059 | 106.7MB | 121.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 4 | `runtime.mallocgc` | 7.51MB |
| 5 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `compress/flate.NewWriter` | 1.76MB |
| 10 | `reflect.unsafe_NewArray` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 895.66MB |
| 2 | `reflect.unsafe_NewArray` | 379.97MB |
| 3 | `reflect.MakeSlice` | 229.01MB |
| 4 | `segmentio/kafka-go.makeLayout` | 83.8MB |
| 5 | `v3/newrelic.newAnalyticsEvents` | 76.01MB |
| 6 | `compress/flate.NewWriter` | 40.55MB |
| 7 | `internal/reflectlite.unsafe_New` | 40.0MB |
| 8 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 9 | `io.ReadAll` | 36.14MB |
| 10 | `reflect.mapassign_faststr0` | 34.51MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 10/12 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.17MB | 10/12 | `███░░░░░░░░░░░░ 25%` |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 4.5MB | 2/12 | `█░░░░░░░░░░░░░░ 12%` |
| 4 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB | 1/12 | `█░░░░░░░░░░░░░░ 6%` |
| 5 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.29MB | 10/12 | `░░░░░░░░░░░░░░░ 6%` |
| 6 | `aws/endpoints.init` | 2.0MB | 1/12 | `░░░░░░░░░░░░░░░ 5%` |
| 7 | `compress/flate.NewWriter` | 1.81MB | 9/12 | `░░░░░░░░░░░░░░░ 4%` |
| 8 | `runtime.mallocgc` | 1.09MB | 7/12 | `░░░░░░░░░░░░░░░ 2%` |
| 9 | `segmentio/kafka-go.makePartitions` | 1.0MB | 2/12 | `░░░░░░░░░░░░░░░ 2%` |
| 10 | `reflect.unsafe_NewArray` | 421.62kB | 4/12 | `███████████████ 100%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.(*Engine).Evaluate` | 340.95MB | 5/12 | `███████████████ 100%` |
| 2 | `segmentio/kafka-go.makePartitions` | 298.77MB | 3/12 | `█████████████░░ 87%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 285.41MB | 6/12 | `████████████░░░ 83%` |
| 4 | `reflect.MakeSlice` | 229.01MB | 1/12 | `██████████░░░░░ 67%` |
| 5 | `reflect.unsafe_NewArray` | 126.98MB | 3/12 | `█████░░░░░░░░░░ 37%` |
| 6 | `compress/flate.NewWriter` | 108.03MB | 10/12 | `████░░░░░░░░░░░ 31%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 70.33MB | 6/12 | `███░░░░░░░░░░░░ 20%` |
| 8 | `experiment/local.topologicalSort` | 46.4MB | 5/12 | `██░░░░░░░░░░░░░ 13%` |
| 9 | `internal/reflectlite.unsafe_New` | 40.0MB | 1/12 | `█░░░░░░░░░░░░░░ 11%` |
| 10 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 10/12 | `█░░░░░░░░░░░░░░ 10%` |

## Alerts

No anomalies detected.
