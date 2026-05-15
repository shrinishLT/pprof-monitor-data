# Overview: stage
*Last updated: 2026-05-16 03:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T03:02 (19 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,266 | avg: 14,148 | max: 14,425 | trend: INCREASING (+0.93/hr))
```
▁▂▁▁▁█▇▄▁▃▁▁▁▁▁▁▆▁▄
```

**Heap InUse** (current: 169.5MB | avg: 136.8MB | max: 181.5MB | trend: stable (-0.34MB/hr))
```
▃▅▁▇▄▄▃▄▆█▁▃▆▆▁▆▁▂▇
```

## Current Status

Goroutines: `███████████████████░ 98%`
Heap InUse: `█████░░░░░░░░░░░░░░░ 27%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,266 | 14,067 | +199 | 14,148 | 14,425 | INCREASING (+0.93/hr) |
| Heap InUse | 169.5MB | 106.6MB | +62.9MB | 136.8MB | 181.5MB | stable (-0.34MB/hr) |
| Heap Sys | 608.5MB | 608.0MB | +0.5MB | 297.5MB | 608.5MB | |
| Heap Objects | 989,532 | 393,321 | +596211 | 761,615 | 1,309,284 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 9 | 14,119 | 130.2MB | 169.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.01MB |
| 6 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `reflect.mapassign_faststr0` | 1.5MB |
| 10 | `bytes.growSlice` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 4.9GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 2.87GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 2.83GB |
| 4 | `internal/evaluation.mergeMetadata` | 2.81GB |
| 5 | `reflect.unsafe_NewArray` | 2.15GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 1.5GB |
| 7 | `experiment/local.topologicalSort` | 1.47GB |
| 8 | `reflect.MakeSlice` | 1.19GB |
| 9 | `internal/evaluation.(*Engine).evaluateFlag` | 545.03MB |
| 10 | `segmentio/kafka-go.makeLayout` | 529.58MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 17/19 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.2MB | 17/19 | `███░░░░░░░░░░░░ 25%` |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB | 9/19 | `███░░░░░░░░░░░░ 21%` |
| 4 | `runtime.mallocgc` | 4.95MB | 14/19 | `██░░░░░░░░░░░░░ 13%` |
| 5 | `segmentio/kafka-go.makePartitions` | 3.0MB | 8/19 | `█░░░░░░░░░░░░░░ 8%` |
| 6 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB | 8/19 | `█░░░░░░░░░░░░░░ 6%` |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.3MB | 17/19 | `░░░░░░░░░░░░░░░ 6%` |
| 8 | `compress/flate.NewWriter` | 2.15MB | 15/19 | `░░░░░░░░░░░░░░░ 5%` |
| 9 | `aws/endpoints.init` | 2.0MB | 8/19 | `░░░░░░░░░░░░░░░ 5%` |
| 10 | `bytes.growSlice` | 1.25MB | 2/19 | `░░░░░░░░░░░░░░░ 3%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 1.96GB | 10/19 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 1000.09MB | 6/19 | `███████████████ 100%` |
| 3 | `reflect.unsafe_NewArray` | 866.16MB | 10/19 | `███████████████ 100%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 699.61MB | 11/19 | `███████████████ 100%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 651.21MB | 12/19 | `███████████████ 100%` |
| 6 | `reflect.MakeSlice` | 613.83MB | 8/19 | `███████████████ 100%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 524.78MB | 2/19 | `███████████████ 100%` |
| 8 | `experiment/local.topologicalSort` | 442.75MB | 7/19 | `███████████████ 100%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 420.11MB | 8/19 | `███████████████ 100%` |
| 10 | `segmentio/kafka-go.makeLayout` | 159.26MB | 13/19 | `███████████████ 100%` |

## Alerts

No anomalies detected.
