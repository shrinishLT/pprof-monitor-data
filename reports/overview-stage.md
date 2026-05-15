# Overview: stage
*Last updated: 2026-05-16 00:40 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T00:40 (14 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,074 | avg: 14,143 | max: 14,425 | trend: decreasing (-7.27/hr))
```
▁▂▁▁▁█▇▄▁▃▁▁▁▁
```

**Heap InUse** (current: 156.8MB | avg: 140.0MB | max: 181.5MB | trend: INCREASING (+2.12MB/hr))
```
▃▅▁▇▄▄▃▄▆█▁▃▆▆
```

## Current Status

Goroutines: `███████████████████░ 97%`
Heap InUse: `█████████░░░░░░░░░░░ 49%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,074 | 14,065 | +9 | 14,143 | 14,425 | decreasing (-7.27/hr) |
| Heap InUse | 156.8MB | 161.9MB | -5.1MB | 140.0MB | 181.5MB | INCREASING (+2.12MB/hr) |
| Heap Sys | 189.1MB | 185.5MB | +3.6MB | 276.1MB | 318.0MB | |
| Heap Objects | 1,125,781 | 1,143,482 | -17701 | 800,510 | 1,309,284 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 4 | 14,064 | 133.0MB | 161.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 4 | `runtime.mallocgc` | 7.51MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `bufio.NewReaderSize` | 1.02MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 1.14GB |
| 2 | `reflect.unsafe_NewArray` | 499.43MB |
| 3 | `reflect.MakeSlice` | 294.01MB |
| 4 | `segmentio/kafka-go.makeLayout` | 115.85MB |
| 5 | `v3/newrelic.newAnalyticsEvents` | 89.65MB |
| 6 | `internal/evaluation.mergeMetadata` | 64.52MB |
| 7 | `experiment/local.(*Client).EvaluateV2` | 64.1MB |
| 8 | `internal/evaluation.(*Engine).Evaluate` | 63.58MB |
| 9 | `internal/reflectlite.unsafe_New` | 55.51MB |
| 10 | `compress/flate.NewWriter` | 53.77MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 12/14 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.18MB | 12/14 | `███░░░░░░░░░░░░ 25%` |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 6.75MB | 4/14 | `██░░░░░░░░░░░░░ 18%` |
| 4 | `runtime.mallocgc` | 2.51MB | 9/14 | `█░░░░░░░░░░░░░░ 6%` |
| 5 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB | 3/14 | `█░░░░░░░░░░░░░░ 6%` |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.29MB | 12/14 | `░░░░░░░░░░░░░░░ 6%` |
| 7 | `segmentio/kafka-go.makePartitions` | 2.0MB | 4/14 | `░░░░░░░░░░░░░░░ 5%` |
| 8 | `aws/endpoints.init` | 2.0MB | 3/14 | `░░░░░░░░░░░░░░░ 5%` |
| 9 | `compress/flate.NewWriter` | 1.88MB | 11/14 | `░░░░░░░░░░░░░░░ 5%` |
| 10 | `reflect.unsafe_NewArray` | 646.55kB | 5/14 | `███████████████ 100%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 600.48MB | 5/14 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 294.72MB | 6/14 | `███████░░░░░░░░ 49%` |
| 3 | `reflect.unsafe_NewArray` | 255.08MB | 5/14 | `██████░░░░░░░░░ 42%` |
| 4 | `reflect.MakeSlice` | 255.01MB | 3/14 | `██████░░░░░░░░░ 42%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 253.8MB | 7/14 | `██████░░░░░░░░░ 42%` |
| 6 | `compress/flate.NewWriter` | 97.88MB | 12/14 | `██░░░░░░░░░░░░░ 16%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 70.33MB | 6/14 | `█░░░░░░░░░░░░░░ 11%` |
| 8 | `internal/evaluation.mergeMetadata` | 64.52MB | 1/14 | `█░░░░░░░░░░░░░░ 10%` |
| 9 | `experiment/local.topologicalSort` | 46.4MB | 5/14 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `internal/reflectlite.unsafe_New` | 46.0MB | 3/14 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

No anomalies detected.
