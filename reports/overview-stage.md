# Overview: stage
*Last updated: 2026-05-17 05:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T05:02 (70 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,064 | avg: 14,148 | max: 14,653 | trend: decreasing (-0.84/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁
```

**Heap InUse** (current: 162.4MB | avg: 144.0MB | max: 201.6MB | trend: stable (+0.34MB/hr))
```
▃▄▁▆▃▃▂▄▅▆▁▂▅▅▁▅▁▁▅▅▂▁▆▆█▄▄▆▃▃▆▆▁▄▅▆▂▅▂▂▃▂▅▂▂▅▂▂▄▅▅▅▆▄▂▂▅▄▄▂▃▁▅▆▄▆▅▆▆▅
```

## Current Status

Goroutines: `███████████████████░ 95%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 15%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,064 | 14,076 | -12 | 14,148 | 14,653 | decreasing (-0.84/hr) |
| Heap InUse | 162.4MB | 171.6MB | -9.2MB | 144.0MB | 201.6MB | stable (+0.34MB/hr) |
| Heap Sys | 1012.9MB | 1012.9MB | +0.0MB | 789.6MB | 1016.6MB | |
| Heap Objects | 1,037,447 | 1,154,151 | -116704 | 782,209 | 1,341,103 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 11 | 14,103 | 151.9MB | 175.6MB |

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
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `reflect.unsafe_NewArray` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 50.84GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 23.04GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 22.76GB |
| 4 | `internal/evaluation.mergeMetadata` | 22.14GB |
| 5 | `reflect.unsafe_NewArray` | 21.93GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 16.3GB |
| 7 | `reflect.MakeSlice` | 12.19GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 11.4GB |
| 9 | `experiment/local.topologicalSort` | 11.32GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 7.12GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 68/70 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/70 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 10.56MB | 65/70 | `████░░░░░░░░░░░ 28%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 68/70 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.85MB | 60/70 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/70 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/70 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/70 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.89MB | 54/70 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `compress/flate.NewWriter` | 2.68MB | 57/70 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 23.93GB | 61/70 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 15.12GB | 46/70 | `█████████░░░░░░ 63%` |
| 3 | `internal/evaluation.mergeMetadata` | 11.54GB | 57/70 | `███████░░░░░░░░ 48%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 10.89GB | 62/70 | `██████░░░░░░░░░ 45%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 10.87GB | 63/70 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 10.35GB | 61/70 | `██████░░░░░░░░░ 43%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 6.61GB | 46/70 | `████░░░░░░░░░░░ 27%` |
| 8 | `reflect.MakeSlice` | 5.96GB | 59/70 | `███░░░░░░░░░░░░ 24%` |
| 9 | `experiment/local.topologicalSort` | 5.81GB | 58/70 | `███░░░░░░░░░░░░ 24%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 5.72GB | 59/70 | `███░░░░░░░░░░░░ 23%` |

## Alerts

No anomalies detected.
