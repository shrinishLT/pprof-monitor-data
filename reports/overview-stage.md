# Overview: stage
*Last updated: 2026-05-16 17:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T17:31 (47 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,076 | avg: 14,161 | max: 14,653 | trend: INCREASING (+2.45/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁
```

**Heap InUse** (current: 116.0MB | avg: 141.5MB | max: 201.6MB | trend: stable (-0.03MB/hr))
```
▃▄▁▆▃▃▂▄▅▆▁▂▅▅▁▅▁▁▅▅▂▁▆▆█▄▄▆▃▃▆▆▁▄▅▆▂▅▂▂▃▂▅▂▂▅▂
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 11%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,076 | 14,068 | +8 | 14,161 | 14,653 | INCREASING (+2.45/hr) |
| Heap InUse | 116.0MB | 157.3MB | -41.3MB | 141.5MB | 201.6MB | stable (-0.03MB/hr) |
| Heap Sys | 1012.5MB | 1012.3MB | +0.2MB | 680.3MB | 1016.6MB | |
| Heap Objects | 478,699 | 1,009,989 | -531290 | 764,566 | 1,341,103 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 37 | 14,158 | 141.2MB | 201.6MB |

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
| 8 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 9 | `reflect.mapassign_faststr0` | 2.0MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 30.09GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 16.22GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 15.35GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 15.14GB |
| 5 | `internal/evaluation.mergeMetadata` | 14.74GB |
| 6 | `reflect.unsafe_NewArray` | 13.04GB |
| 7 | `experiment/local.topologicalSort` | 7.56GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 7.52GB |
| 9 | `reflect.MakeSlice` | 7.27GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 7.08GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 45/47 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/47 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 9.72MB | 42/47 | `███░░░░░░░░░░░░ 26%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.23MB | 45/47 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.76MB | 37/47 | `███░░░░░░░░░░░░ 23%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/47 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/47 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/47 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `reflect.unsafe_New` | 3.0MB | 1/47 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `segmentio/kafka-go.makePartitions` | 2.92MB | 32/47 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 13.99GB | 23/47 | `███████████████ 100%` |
| 2 | `segmentio/kafka-go.makePartitions` | 13.61GB | 38/47 | `██████████████░ 97%` |
| 3 | `internal/evaluation.mergeMetadata` | 6.78GB | 34/47 | `███████░░░░░░░░ 48%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 6.12GB | 23/47 | `██████░░░░░░░░░ 43%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 6.07GB | 39/47 | `██████░░░░░░░░░ 43%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 6.01GB | 40/47 | `██████░░░░░░░░░ 42%` |
| 7 | `reflect.unsafe_NewArray` | 5.93GB | 38/47 | `██████░░░░░░░░░ 42%` |
| 8 | `reflect.MakeSlice` | 3.5GB | 36/47 | `███░░░░░░░░░░░░ 25%` |
| 9 | `experiment/local.topologicalSort` | 3.37GB | 35/47 | `███░░░░░░░░░░░░ 24%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 3.28GB | 36/47 | `███░░░░░░░░░░░░ 23%` |

## Alerts

No anomalies detected.
