# Overview: stage
*Last updated: 2026-05-16 05:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T05:01 (23 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,065 | avg: 14,135 | max: 14,425 | trend: decreasing (-5.17/hr))
```
▁▂▁▁▁█▇▄▁▃▁▁▁▁▁▁▆▁▄▁▁▁▁
```

**Heap InUse** (current: 183.6MB | avg: 137.7MB | max: 183.6MB | trend: stable (+0.25MB/hr))
```
▃▅▁▇▄▄▃▄▆▇▁▃▆▅▁▆▁▂▆▆▂▂█
```

## Current Status

Goroutines: `███████████████████░ 97%`
Heap InUse: `██████░░░░░░░░░░░░░░ 30%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,065 | 14,079 | -14 | 14,135 | 14,425 | decreasing (-5.17/hr) |
| Heap InUse | 183.6MB | 106.8MB | +76.8MB | 137.7MB | 183.6MB | stable (+0.25MB/hr) |
| Heap Sys | 605.0MB | 604.8MB | +0.2MB | 351.1MB | 608.5MB | |
| Heap Objects | 1,341,103 | 379,099 | +962004 | 774,250 | 1,341,103 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 13 | 14,104 | 133.8MB | 183.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `reflect.unsafe_NewArray` | 2.0MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 7.96GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 3.59GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 3.55GB |
| 4 | `internal/evaluation.mergeMetadata` | 3.52GB |
| 5 | `reflect.unsafe_NewArray` | 3.48GB |
| 6 | `reflect.MakeSlice` | 1.94GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 1.88GB |
| 8 | `experiment/local.topologicalSort` | 1.83GB |
| 9 | `segmentio/kafka-go.makeLayout` | 876.87MB |
| 10 | `internal/evaluation.(*Engine).evaluateFlag` | 686.54MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 21/23 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.21MB | 21/23 | `███░░░░░░░░░░░░ 25%` |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 8.31MB | 13/23 | `███░░░░░░░░░░░░ 22%` |
| 4 | `runtime.mallocgc` | 6.54MB | 18/23 | `██░░░░░░░░░░░░░ 17%` |
| 5 | `segmentio/kafka-go.makePartitions` | 2.96MB | 12/23 | `█░░░░░░░░░░░░░░ 8%` |
| 6 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB | 12/23 | `█░░░░░░░░░░░░░░ 6%` |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.3MB | 21/23 | `░░░░░░░░░░░░░░░ 6%` |
| 8 | `compress/flate.NewWriter` | 2.3MB | 19/23 | `░░░░░░░░░░░░░░░ 6%` |
| 9 | `aws/endpoints.init` | 2.0MB | 12/23 | `░░░░░░░░░░░░░░░ 5%` |
| 10 | `encoding/json.(*decodeState).objectInterface` | 2.0MB | 1/23 | `░░░░░░░░░░░░░░░ 5%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 3.39GB | 14/23 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 1.94GB | 10/23 | `████████░░░░░░░ 57%` |
| 3 | `reflect.unsafe_NewArray` | 1.47GB | 14/23 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 1.41GB | 15/23 | `██████░░░░░░░░░ 41%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 1.34GB | 16/23 | `█████░░░░░░░░░░ 39%` |
| 6 | `reflect.MakeSlice` | 988.63MB | 12/23 | `███████████████ 100%` |
| 7 | `experiment/local.topologicalSort` | 939.9MB | 11/23 | `███████████████ 100%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 898.74MB | 12/23 | `███████████████ 100%` |
| 9 | `internal/evaluation.(*Engine).evaluateFlag` | 614.79MB | 6/23 | `███████████████ 100%` |
| 10 | `segmentio/kafka-go.makeLayout` | 300.08MB | 17/23 | `███████████████ 100%` |

## Alerts

No anomalies detected.
