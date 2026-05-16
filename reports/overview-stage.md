# Overview: stage
*Last updated: 2026-05-16 07:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T07:03 (27 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,067 | avg: 14,152 | max: 14,602 | trend: INCREASING (+3.02/hr))
```
▁▁▁▁▁▅▅▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁█▃▁
```

**Heap InUse** (current: 143.5MB | avg: 142.1MB | max: 201.6MB | trend: INCREASING (+1.71MB/hr))
```
▃▄▁▆▃▃▂▄▅▆▁▂▅▅▁▅▁▁▅▅▂▁▆▆█▄▄
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 14%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,067 | 14,262 | -195 | 14,152 | 14,602 | INCREASING (+3.02/hr) |
| Heap InUse | 143.5MB | 143.6MB | -0.1MB | 142.1MB | 201.6MB | INCREASING (+1.71MB/hr) |
| Heap Sys | 1013.6MB | 1013.4MB | +0.2MB | 434.2MB | 1016.6MB | |
| Heap Objects | 801,403 | 680,693 | +120710 | 793,436 | 1,341,103 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 17 | 14,138 | 141.7MB | 201.6MB |

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
| 9 | `segmentio/kafka-go.makePartitions` | 1.5MB |
| 10 | `reflect.mapassign_faststr0` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 13.37GB |
| 2 | `segmentio/kafka-go.makePartitions` | 11.29GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 7.01GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 6.92GB |
| 5 | `internal/evaluation.mergeMetadata` | 6.78GB |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 5.85GB |
| 7 | `reflect.unsafe_NewArray` | 4.94GB |
| 8 | `experiment/local.topologicalSort` | 3.46GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 3.44GB |
| 10 | `reflect.MakeSlice` | 2.77GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 25/27 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/27 | `█████░░░░░░░░░░ 39%` |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.22MB | 25/27 | `███░░░░░░░░░░░░ 25%` |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.47MB | 17/27 | `███░░░░░░░░░░░░ 23%` |
| 5 | `runtime.mallocgc` | 7.55MB | 22/27 | `███░░░░░░░░░░░░ 20%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/27 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/27 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `segmentio/kafka-go.makePartitions` | 2.67MB | 15/27 | `█░░░░░░░░░░░░░░ 7%` |
| 9 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB | 16/27 | `█░░░░░░░░░░░░░░ 6%` |
| 10 | `compress/flate.NewWriter` | 2.38MB | 22/27 | `░░░░░░░░░░░░░░░ 6%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 10.98GB | 3/27 | `███████████████ 100%` |
| 2 | `segmentio/kafka-go.makePartitions` | 4.86GB | 18/27 | `██████░░░░░░░░░ 44%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 4.81GB | 3/27 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 2.93GB | 14/27 | `████░░░░░░░░░░░ 26%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 2.27GB | 19/27 | `███░░░░░░░░░░░░ 20%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 2.18GB | 20/27 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `reflect.unsafe_NewArray` | 2.12GB | 18/27 | `██░░░░░░░░░░░░░ 19%` |
| 8 | `experiment/local.topologicalSort` | 1.41GB | 15/27 | `█░░░░░░░░░░░░░░ 12%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 1.35GB | 16/27 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `reflect.MakeSlice` | 1.34GB | 16/27 | `█░░░░░░░░░░░░░░ 12%` |

## Alerts

No anomalies detected.
