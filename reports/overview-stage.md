# Overview: stage
*Last updated: 2026-05-16 04:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T04:31 (22 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,079 | avg: 14,138 | max: 14,425 | trend: decreasing (-4.10/hr))
```
▁▂▁▁▁█▇▄▁▃▁▁▁▁▁▁▆▁▄▁▁▁
```

**Heap InUse** (current: 106.8MB | avg: 135.6MB | max: 181.5MB | trend: decreasing (-0.91MB/hr))
```
▃▅▁▇▄▄▃▄▆█▁▃▆▆▁▆▁▂▇▆▂▂
```

## Current Status

Goroutines: `███████████████████░ 97%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 17%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,079 | 14,079 | +0 | 14,138 | 14,425 | decreasing (-4.10/hr) |
| Heap InUse | 106.8MB | 109.4MB | -2.6MB | 135.6MB | 181.5MB | decreasing (-0.91MB/hr) |
| Heap Sys | 604.8MB | 604.8MB | +0.0MB | 339.5MB | 608.5MB | |
| Heap Objects | 379,099 | 424,050 | -44951 | 748,483 | 1,309,284 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 12 | 14,108 | 129.7MB | 169.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 1.07MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 7.18GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 3.59GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 3.55GB |
| 4 | `internal/evaluation.mergeMetadata` | 3.52GB |
| 5 | `reflect.unsafe_NewArray` | 3.15GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 1.88GB |
| 7 | `experiment/local.topologicalSort` | 1.83GB |
| 8 | `reflect.MakeSlice` | 1.75GB |
| 9 | `segmentio/kafka-go.makeLayout` | 783.27MB |
| 10 | `internal/evaluation.(*Engine).evaluateFlag` | 686.54MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 20/22 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.21MB | 20/22 | `███░░░░░░░░░░░░ 25%` |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 8.25MB | 12/22 | `███░░░░░░░░░░░░ 22%` |
| 4 | `runtime.mallocgc` | 6.22MB | 17/22 | `██░░░░░░░░░░░░░ 16%` |
| 5 | `segmentio/kafka-go.makePartitions` | 3.0MB | 11/22 | `█░░░░░░░░░░░░░░ 8%` |
| 6 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB | 11/22 | `█░░░░░░░░░░░░░░ 6%` |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.3MB | 20/22 | `░░░░░░░░░░░░░░░ 6%` |
| 8 | `compress/flate.NewWriter` | 2.23MB | 18/22 | `░░░░░░░░░░░░░░░ 6%` |
| 9 | `aws/endpoints.init` | 2.0MB | 11/22 | `░░░░░░░░░░░░░░░ 5%` |
| 10 | `encoding/json.(*decodeState).objectInterface` | 2.0MB | 1/22 | `░░░░░░░░░░░░░░░ 5%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 3.03GB | 13/22 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 1.77GB | 9/22 | `████████░░░░░░░ 58%` |
| 3 | `reflect.unsafe_NewArray` | 1.32GB | 13/22 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 1.26GB | 14/22 | `██████░░░░░░░░░ 41%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 1.19GB | 15/22 | `█████░░░░░░░░░░ 39%` |
| 6 | `reflect.MakeSlice` | 897.91MB | 11/22 | `███████████████ 100%` |
| 7 | `experiment/local.topologicalSort` | 846.5MB | 10/22 | `███████████████ 100%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 805.43MB | 11/22 | `███████████████ 100%` |
| 9 | `internal/evaluation.(*Engine).evaluateFlag` | 600.44MB | 5/22 | `███████████████ 100%` |
| 10 | `segmentio/kafka-go.makeLayout` | 264.03MB | 16/22 | `███████████████ 100%` |

## Alerts

No anomalies detected.
