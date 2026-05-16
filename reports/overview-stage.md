# Overview: stage
*Last updated: 2026-05-16 23:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T23:01 (58 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,067 | avg: 14,158 | max: 14,653 | trend: INCREASING (+0.82/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃▁
```

**Heap InUse** (current: 145.9MB | avg: 142.4MB | max: 201.6MB | trend: stable (+0.14MB/hr))
```
▃▄▁▆▃▃▂▄▅▆▁▂▅▅▁▅▁▁▅▅▂▁▆▆█▄▄▆▃▃▆▆▁▄▅▆▂▅▂▂▃▂▅▂▂▅▂▂▄▅▅▅▆▄▂▂▅▄
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 14%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,067 | 14,273 | -206 | 14,158 | 14,653 | INCREASING (+0.82/hr) |
| Heap InUse | 145.9MB | 155.8MB | -9.9MB | 142.4MB | 201.6MB | stable (+0.14MB/hr) |
| Heap Sys | 1012.8MB | 1012.5MB | +0.3MB | 743.3MB | 1016.6MB | |
| Heap Objects | 826,865 | 849,901 | -23036 | 762,487 | 1,341,103 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 48 | 14,155 | 142.4MB | 201.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 5.01MB |
| 6 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.unsafe_NewArray` | 2.01MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `compress/flate.NewWriter` | 1.76MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 40.06GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 18.99GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 18.7GB |
| 4 | `internal/evaluation.mergeMetadata` | 18.26GB |
| 5 | `reflect.unsafe_NewArray` | 17.26GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 16.23GB |
| 7 | `reflect.MakeSlice` | 9.58GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 9.35GB |
| 9 | `experiment/local.topologicalSort` | 9.34GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 7.09GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 56/58 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/58 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 10.21MB | 53/58 | `████░░░░░░░░░░░ 27%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 56/58 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.81MB | 48/58 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/58 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/58 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/58 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.92MB | 42/58 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `compress/flate.NewWriter` | 2.67MB | 48/58 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 18.54GB | 49/58 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 14.72GB | 34/58 | `███████████░░░░ 79%` |
| 3 | `internal/evaluation.mergeMetadata` | 9.2GB | 45/58 | `███████░░░░░░░░ 49%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 8.5GB | 50/58 | `██████░░░░░░░░░ 45%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 8.46GB | 51/58 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 8.04GB | 49/58 | `██████░░░░░░░░░ 43%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 6.43GB | 34/58 | `█████░░░░░░░░░░ 34%` |
| 8 | `reflect.MakeSlice` | 4.68GB | 47/58 | `███░░░░░░░░░░░░ 25%` |
| 9 | `experiment/local.topologicalSort` | 4.61GB | 46/58 | `███░░░░░░░░░░░░ 24%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 4.51GB | 47/58 | `███░░░░░░░░░░░░ 24%` |

## Alerts

No anomalies detected.
