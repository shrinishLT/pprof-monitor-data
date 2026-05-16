# Overview: stage
*Last updated: 2026-05-16 20:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T20:03 (52 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,225 | avg: 14,159 | max: 14,653 | trend: INCREASING (+1.43/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂
```

**Heap InUse** (current: 166.8MB | avg: 142.3MB | max: 201.6MB | trend: stable (+0.16MB/hr))
```
▃▄▁▆▃▃▂▄▅▆▁▂▅▅▁▅▁▁▅▅▂▁▆▆█▄▄▆▃▃▆▆▁▄▅▆▂▅▂▂▃▂▅▂▂▅▂▂▄▅▅▅
```

## Current Status

Goroutines: `███████████████████░ 97%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 16%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,225 | 14,107 | +118 | 14,159 | 14,653 | INCREASING (+1.43/hr) |
| Heap InUse | 166.8MB | 157.2MB | +9.6MB | 142.3MB | 201.6MB | stable (+0.16MB/hr) |
| Heap Sys | 1012.4MB | 1012.6MB | -0.2MB | 712.3MB | 1016.6MB | |
| Heap Objects | 755,748 | 956,624 | -200876 | 763,604 | 1,341,103 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 42 | 14,156 | 142.2MB | 201.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `reflect.unsafe_New` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 34.7GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 17.22GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 16.96GB |
| 4 | `internal/evaluation.mergeMetadata` | 16.51GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 16.23GB |
| 6 | `reflect.unsafe_NewArray` | 14.95GB |
| 7 | `experiment/local.topologicalSort` | 8.47GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 8.44GB |
| 9 | `reflect.MakeSlice` | 8.35GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 7.09GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 50/52 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/52 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 9.97MB | 47/52 | `████░░░░░░░░░░░ 27%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.23MB | 50/52 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.79MB | 42/52 | `███░░░░░░░░░░░░ 23%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/52 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/52 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/52 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.85MB | 37/52 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `compress/flate.NewWriter` | 2.65MB | 44/52 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 15.84GB | 43/52 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 14.39GB | 28/52 | `█████████████░░ 90%` |
| 3 | `internal/evaluation.mergeMetadata` | 7.93GB | 39/52 | `███████░░░░░░░░ 50%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 7.22GB | 44/52 | `██████░░░░░░░░░ 45%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 7.16GB | 45/52 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 6.89GB | 43/52 | `██████░░░░░░░░░ 43%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 6.29GB | 28/52 | `█████░░░░░░░░░░ 39%` |
| 8 | `reflect.MakeSlice` | 4.04GB | 41/52 | `███░░░░░░░░░░░░ 25%` |
| 9 | `experiment/local.topologicalSort` | 3.96GB | 40/52 | `███░░░░░░░░░░░░ 25%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 3.86GB | 41/52 | `███░░░░░░░░░░░░ 24%` |

## Alerts

No anomalies detected.
