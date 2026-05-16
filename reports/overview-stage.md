# Overview: stage
*Last updated: 2026-05-16 05:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T05:31 (24 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,065 | avg: 14,132 | max: 14,425 | trend: decreasing (-5.94/hr))
```
▁▂▁▁▁█▇▄▁▃▁▁▁▁▁▁▆▁▄▁▁▁▁▁
```

**Heap InUse** (current: 180.3MB | avg: 139.5MB | max: 183.6MB | trend: INCREASING (+1.07MB/hr))
```
▃▅▁▇▄▄▃▄▆▇▁▃▆▅▁▆▁▂▆▆▂▂█▇
```

## Current Status

Goroutines: `███████████████████░ 97%`
Heap InUse: `█████░░░░░░░░░░░░░░░ 29%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,065 | 14,065 | +0 | 14,132 | 14,425 | decreasing (-5.94/hr) |
| Heap InUse | 180.3MB | 183.6MB | -3.3MB | 139.5MB | 183.6MB | INCREASING (+1.07MB/hr) |
| Heap Sys | 604.9MB | 605.0MB | -0.1MB | 361.7MB | 608.5MB | |
| Heap Objects | 1,294,129 | 1,341,103 | -46974 | 795,911 | 1,341,103 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 14 | 14,102 | 137.1MB | 183.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `net/http.init.func16` | 1.03MB |
| 10 | `segmentio/kafka-go.makePartitions` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 8.76GB |
| 2 | `reflect.unsafe_NewArray` | 3.82GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 3.61GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 3.58GB |
| 5 | `internal/evaluation.mergeMetadata` | 3.54GB |
| 6 | `reflect.MakeSlice` | 2.13GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 1.89GB |
| 8 | `experiment/local.topologicalSort` | 1.84GB |
| 9 | `segmentio/kafka-go.makeLayout` | 953.66MB |
| 10 | `internal/evaluation.(*Engine).evaluateFlag` | 692.04MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 22/24 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.21MB | 22/24 | `███░░░░░░░░░░░░ 25%` |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 8.36MB | 14/24 | `███░░░░░░░░░░░░ 22%` |
| 4 | `runtime.mallocgc` | 6.83MB | 19/24 | `██░░░░░░░░░░░░░ 18%` |
| 5 | `segmentio/kafka-go.makePartitions` | 2.81MB | 13/24 | `█░░░░░░░░░░░░░░ 7%` |
| 6 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB | 13/24 | `█░░░░░░░░░░░░░░ 6%` |
| 7 | `compress/flate.NewWriter` | 2.31MB | 20/24 | `░░░░░░░░░░░░░░░ 6%` |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.3MB | 22/24 | `░░░░░░░░░░░░░░░ 6%` |
| 9 | `aws/endpoints.init` | 2.0MB | 13/24 | `░░░░░░░░░░░░░░░ 5%` |
| 10 | `encoding/json.(*decodeState).objectInterface` | 2.0MB | 1/24 | `░░░░░░░░░░░░░░░ 5%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 3.74GB | 15/24 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 2.09GB | 11/24 | `████████░░░░░░░ 55%` |
| 3 | `reflect.unsafe_NewArray` | 1.63GB | 15/24 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 1.55GB | 16/24 | `██████░░░░░░░░░ 41%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 1.48GB | 17/24 | `█████░░░░░░░░░░ 39%` |
| 6 | `reflect.MakeSlice` | 1.06GB | 13/24 | `████░░░░░░░░░░░ 28%` |
| 7 | `experiment/local.topologicalSort` | 1018.59MB | 12/24 | `███████████████ 100%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 978.48MB | 13/24 | `███████████████ 100%` |
| 9 | `internal/evaluation.(*Engine).evaluateFlag` | 625.82MB | 7/24 | `███████████████ 100%` |
| 10 | `segmentio/kafka-go.makeLayout` | 336.39MB | 18/24 | `███████████████ 100%` |

## Alerts

No anomalies detected.
