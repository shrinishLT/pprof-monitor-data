# Overview: stage
*Last updated: 2026-05-16 03:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T03:31 (20 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,065 | avg: 14,144 | max: 14,425 | trend: decreasing (-1.57/hr))
```
▁▂▁▁▁█▇▄▁▃▁▁▁▁▁▁▆▁▄▁
```

**Heap InUse** (current: 168.4MB | avg: 138.4MB | max: 181.5MB | trend: INCREASING (+0.61MB/hr))
```
▃▅▁▇▄▄▃▄▆█▁▃▆▆▁▆▁▂▇▆
```

## Current Status

Goroutines: `███████████████████░ 97%`
Heap InUse: `█████░░░░░░░░░░░░░░░ 27%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,065 | 14,266 | -201 | 14,144 | 14,425 | decreasing (-1.57/hr) |
| Heap InUse | 168.4MB | 169.5MB | -1.1MB | 138.4MB | 181.5MB | INCREASING (+0.61MB/hr) |
| Heap Sys | 607.6MB | 608.5MB | -0.9MB | 313.0MB | 608.5MB | |
| Heap Objects | 1,192,810 | 989,532 | +203278 | 783,174 | 1,309,284 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 10 | 14,114 | 134.0MB | 169.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.51MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `reflect.mapassign_faststr0` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 5.61GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 3.09GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 3.05GB |
| 4 | `internal/evaluation.mergeMetadata` | 3.03GB |
| 5 | `reflect.unsafe_NewArray` | 2.45GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 1.61GB |
| 7 | `experiment/local.topologicalSort` | 1.58GB |
| 8 | `reflect.MakeSlice` | 1.37GB |
| 9 | `segmentio/kafka-go.makeLayout` | 599.83MB |
| 10 | `internal/evaluation.(*Engine).evaluateFlag` | 579.54MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 18/20 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.21MB | 18/20 | `███░░░░░░░░░░░░ 25%` |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 8.1MB | 10/20 | `███░░░░░░░░░░░░ 22%` |
| 4 | `runtime.mallocgc` | 5.43MB | 15/20 | `██░░░░░░░░░░░░░ 14%` |
| 5 | `segmentio/kafka-go.makePartitions` | 3.06MB | 9/20 | `█░░░░░░░░░░░░░░ 8%` |
| 6 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB | 9/20 | `█░░░░░░░░░░░░░░ 6%` |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.3MB | 18/20 | `░░░░░░░░░░░░░░░ 6%` |
| 8 | `compress/flate.NewWriter` | 2.18MB | 16/20 | `░░░░░░░░░░░░░░░ 5%` |
| 9 | `aws/endpoints.init` | 2.0MB | 9/20 | `░░░░░░░░░░░░░░░ 5%` |
| 10 | `bytes.growSlice` | 1.25MB | 2/20 | `░░░░░░░░░░░░░░░ 3%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 2.29GB | 11/20 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 1.27GB | 7/20 | `████████░░░░░░░ 55%` |
| 3 | `reflect.unsafe_NewArray` | 1015.49MB | 11/20 | `███████████████ 100%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 901.58MB | 12/20 | `███████████████ 100%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 844.52MB | 13/20 | `███████████████ 100%` |
| 6 | `reflect.MakeSlice` | 701.5MB | 9/20 | `███████████████ 100%` |
| 7 | `experiment/local.topologicalSort` | 589.64MB | 8/20 | `███████████████ 100%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 556.61MB | 9/20 | `███████████████ 100%` |
| 9 | `internal/evaluation.(*Engine).evaluateFlag` | 543.03MB | 3/20 | `███████████████ 100%` |
| 10 | `segmentio/kafka-go.makeLayout` | 190.73MB | 14/20 | `███████████████ 100%` |

## Alerts

No anomalies detected.
