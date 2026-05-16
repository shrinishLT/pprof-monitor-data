# Overview: stage
*Last updated: 2026-05-16 19:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T19:01 (50 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,131 | avg: 14,159 | max: 14,653 | trend: INCREASING (+1.53/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁
```

**Heap InUse** (current: 161.1MB | avg: 141.5MB | max: 201.6MB | trend: stable (-0.01MB/hr))
```
▃▄▁▆▃▃▂▄▅▆▁▂▅▅▁▅▁▁▅▅▂▁▆▆█▄▄▆▃▃▆▆▁▄▅▆▂▅▂▂▃▂▅▂▂▅▂▂▄▅
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 15%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,131 | 14,159 | -28 | 14,159 | 14,653 | INCREASING (+1.53/hr) |
| Heap InUse | 161.1MB | 152.8MB | +8.3MB | 141.5MB | 201.6MB | stable (-0.01MB/hr) |
| Heap Sys | 1012.5MB | 1012.5MB | +0.0MB | 700.3MB | 1016.6MB | |
| Heap Objects | 806,714 | 867,089 | -60375 | 759,901 | 1,341,103 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 40 | 14,155 | 141.2MB | 201.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `reflect.unsafe_NewArray` | 2.52MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `segmentio/kafka-go.makePartitions` | 2.01MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 32.83GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 16.27GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.23GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 16.06GB |
| 5 | `internal/evaluation.mergeMetadata` | 15.66GB |
| 6 | `reflect.unsafe_NewArray` | 14.19GB |
| 7 | `experiment/local.topologicalSort` | 8.02GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 7.97GB |
| 9 | `reflect.MakeSlice` | 7.9GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 7.09GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 48/50 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/50 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 9.88MB | 45/50 | `████░░░░░░░░░░░ 26%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.23MB | 48/50 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.78MB | 40/50 | `███░░░░░░░░░░░░ 23%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/50 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/50 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/50 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `reflect.unsafe_New` | 3.0MB | 1/50 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `segmentio/kafka-go.makePartitions` | 2.86MB | 35/50 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 14.95GB | 41/50 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 14.25GB | 26/50 | `██████████████░ 95%` |
| 3 | `internal/evaluation.mergeMetadata` | 7.47GB | 37/50 | `███████░░░░░░░░ 49%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 6.76GB | 42/50 | `██████░░░░░░░░░ 45%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 6.7GB | 43/50 | `██████░░░░░░░░░ 44%` |
| 6 | `reflect.unsafe_NewArray` | 6.51GB | 41/50 | `██████░░░░░░░░░ 43%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 6.23GB | 26/50 | `██████░░░░░░░░░ 41%` |
| 8 | `reflect.MakeSlice` | 3.82GB | 39/50 | `███░░░░░░░░░░░░ 25%` |
| 9 | `experiment/local.topologicalSort` | 3.73GB | 38/50 | `███░░░░░░░░░░░░ 24%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 3.63GB | 39/50 | `███░░░░░░░░░░░░ 24%` |

## Alerts

No anomalies detected.
