# Overview: stage
*Last updated: 2026-05-16 19:32 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T19:32 (51 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,107 | avg: 14,158 | max: 14,653 | trend: INCREASING (+1.20/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁
```

**Heap InUse** (current: 157.2MB | avg: 141.8MB | max: 201.6MB | trend: stable (+0.06MB/hr))
```
▃▄▁▆▃▃▂▄▅▆▁▂▅▅▁▅▁▁▅▅▂▁▆▆█▄▄▆▃▃▆▆▁▄▅▆▂▅▂▂▃▂▅▂▂▅▂▂▄▅▅
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 15%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,107 | 14,131 | -24 | 14,158 | 14,653 | INCREASING (+1.20/hr) |
| Heap InUse | 157.2MB | 161.1MB | -3.9MB | 141.8MB | 201.6MB | stable (+0.06MB/hr) |
| Heap Sys | 1012.6MB | 1012.5MB | +0.1MB | 706.4MB | 1016.6MB | |
| Heap Objects | 956,624 | 806,714 | +149910 | 763,759 | 1,341,103 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 41 | 14,154 | 141.6MB | 201.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 6 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.mapassign_faststr0` | 2.0MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `compress/flate.NewWriter` | 1.76MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 33.76GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 17.08GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 16.83GB |
| 4 | `internal/evaluation.mergeMetadata` | 16.38GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 16.23GB |
| 6 | `reflect.unsafe_NewArray` | 14.56GB |
| 7 | `experiment/local.topologicalSort` | 8.4GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 8.37GB |
| 9 | `reflect.MakeSlice` | 8.13GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 7.09GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 49/51 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/51 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 9.93MB | 46/51 | `████░░░░░░░░░░░ 27%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.23MB | 49/51 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.78MB | 41/51 | `███░░░░░░░░░░░░ 23%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/51 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/51 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/51 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `reflect.unsafe_New` | 3.0MB | 1/51 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `segmentio/kafka-go.makePartitions` | 2.88MB | 36/51 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 15.4GB | 42/51 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 14.32GB | 27/51 | `█████████████░░ 92%` |
| 3 | `internal/evaluation.mergeMetadata` | 7.71GB | 38/51 | `███████░░░░░░░░ 50%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 7.0GB | 43/51 | `██████░░░░░░░░░ 45%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 6.94GB | 44/51 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 6.7GB | 42/51 | `██████░░░░░░░░░ 43%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 6.26GB | 27/51 | `██████░░░░░░░░░ 40%` |
| 8 | `reflect.MakeSlice` | 3.93GB | 40/51 | `███░░░░░░░░░░░░ 25%` |
| 9 | `experiment/local.topologicalSort` | 3.85GB | 39/51 | `███░░░░░░░░░░░░ 25%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 3.75GB | 40/51 | `███░░░░░░░░░░░░ 24%` |

## Alerts

No anomalies detected.
