# Overview: stage
*Last updated: 2026-05-17 04:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T04:02 (68 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,071 | avg: 14,151 | max: 14,653 | trend: stable (-0.50/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃▁▁▁▁▁▁▁▁▅▁▁
```

**Heap InUse** (current: 175.6MB | avg: 143.3MB | max: 201.6MB | trend: stable (+0.25MB/hr))
```
▃▄▁▆▃▃▂▄▅▆▁▂▅▅▁▅▁▁▅▅▂▁▆▆█▄▄▆▃▃▆▆▁▄▅▆▂▅▂▂▃▂▅▂▂▅▂▂▄▅▅▅▆▄▂▂▅▄▄▂▃▁▅▆▄▆▅▆
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 17%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,071 | 14,065 | +6 | 14,151 | 14,653 | stable (-0.50/hr) |
| Heap InUse | 175.6MB | 163.2MB | +12.4MB | 143.3MB | 201.6MB | stable (+0.25MB/hr) |
| Heap Sys | 1012.9MB | 1012.9MB | +0.0MB | 783.0MB | 1016.6MB | |
| Heap Objects | 1,221,634 | 1,070,262 | +151372 | 772,985 | 1,341,103 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 9 | 14,111 | 148.6MB | 175.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `segmentio/kafka-go.makeLayout` | 1.03MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 49.12GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 22.63GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 22.35GB |
| 4 | `internal/evaluation.mergeMetadata` | 21.76GB |
| 5 | `reflect.unsafe_NewArray` | 21.16GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 16.3GB |
| 7 | `reflect.MakeSlice` | 11.76GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 11.19GB |
| 9 | `experiment/local.topologicalSort` | 11.12GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 7.12GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 66/68 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/68 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 10.51MB | 63/68 | `████░░░░░░░░░░░ 28%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 66/68 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.84MB | 58/68 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/68 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/68 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/68 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.92MB | 52/68 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `compress/flate.NewWriter` | 2.67MB | 55/68 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 23.03GB | 59/68 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 15.07GB | 44/68 | `█████████░░░░░░ 65%` |
| 3 | `internal/evaluation.mergeMetadata` | 11.15GB | 55/68 | `███████░░░░░░░░ 48%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 10.5GB | 60/68 | `██████░░░░░░░░░ 45%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 10.47GB | 61/68 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 9.97GB | 59/68 | `██████░░░░░░░░░ 43%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 6.59GB | 44/68 | `████░░░░░░░░░░░ 28%` |
| 8 | `reflect.MakeSlice` | 5.75GB | 57/68 | `███░░░░░░░░░░░░ 24%` |
| 9 | `experiment/local.topologicalSort` | 5.61GB | 56/68 | `███░░░░░░░░░░░░ 24%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 5.52GB | 57/68 | `███░░░░░░░░░░░░ 23%` |

## Alerts

No anomalies detected.
