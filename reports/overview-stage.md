# Overview: stage
*Last updated: 2026-05-16 11:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T11:01 (34 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,067 | avg: 14,138 | max: 14,602 | trend: decreasing (-2.21/hr))
```
▁▁▁▁▁▅▅▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁█▃▁▁▁▁▁▂▁▁
```

**Heap InUse** (current: 142.7MB | avg: 143.6MB | max: 201.6MB | trend: INCREASING (+1.22MB/hr))
```
▃▄▁▆▃▃▂▄▅▆▁▂▅▅▁▅▁▁▅▅▂▁▆▆█▄▄▆▃▃▆▆▁▄
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 14%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,067 | 14,071 | -4 | 14,138 | 14,602 | decreasing (-2.21/hr) |
| Heap InUse | 142.7MB | 107.5MB | +35.2MB | 143.6MB | 201.6MB | INCREASING (+1.22MB/hr) |
| Heap Sys | 1013.8MB | 1013.8MB | +0.0MB | 553.5MB | 1016.6MB | |
| Heap Objects | 825,503 | 384,321 | +441182 | 814,967 | 1,341,103 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 24 | 14,123 | 143.9MB | 201.6MB |

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
| 10 | `reflect.unsafe_NewArray` | 1.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 18.35GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 13.38GB |
| 3 | `reflect.unsafe_NewArray` | 8.01GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 7.31GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 7.2GB |
| 6 | `internal/evaluation.mergeMetadata` | 7.04GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 5.86GB |
| 8 | `reflect.MakeSlice` | 4.47GB |
| 9 | `experiment/local.topologicalSort` | 3.6GB |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 3.6GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 32/34 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/34 | `█████░░░░░░░░░░ 39%` |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.22MB | 32/34 | `███░░░░░░░░░░░░ 25%` |
| 4 | `runtime.mallocgc` | 8.65MB | 29/34 | `███░░░░░░░░░░░░ 23%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.63MB | 24/34 | `███░░░░░░░░░░░░ 23%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/34 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/34 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `segmentio/kafka-go.makePartitions` | 2.67MB | 21/34 | `█░░░░░░░░░░░░░░ 7%` |
| 9 | `compress/flate.NewWriter` | 2.54MB | 29/34 | `█░░░░░░░░░░░░░░ 6%` |
| 10 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB | 23/34 | `█░░░░░░░░░░░░░░ 6%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 12.65GB | 10/34 | `███████████████ 100%` |
| 2 | `segmentio/kafka-go.makePartitions` | 7.83GB | 25/34 | `█████████░░░░░░ 61%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 5.54GB | 10/34 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 4.27GB | 21/34 | `█████░░░░░░░░░░ 33%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 3.58GB | 26/34 | `████░░░░░░░░░░░ 28%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 3.49GB | 27/34 | `████░░░░░░░░░░░ 27%` |
| 7 | `reflect.unsafe_NewArray` | 3.42GB | 25/34 | `████░░░░░░░░░░░ 27%` |
| 8 | `experiment/local.topologicalSort` | 2.09GB | 22/34 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `reflect.MakeSlice` | 2.08GB | 23/34 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 2.02GB | 23/34 | `██░░░░░░░░░░░░░ 15%` |

## Alerts

No anomalies detected.
