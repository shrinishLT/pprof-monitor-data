# Overview: stage
*Last updated: 2026-05-17 04:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T04:31 (69 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,076 | avg: 14,150 | max: 14,653 | trend: decreasing (-0.66/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁
```

**Heap InUse** (current: 171.6MB | avg: 143.7MB | max: 201.6MB | trend: stable (+0.31MB/hr))
```
▃▄▁▆▃▃▂▄▅▆▁▂▅▅▁▅▁▁▅▅▂▁▆▆█▄▄▆▃▃▆▆▁▄▅▆▂▅▂▂▃▂▅▂▂▅▂▂▄▅▅▅▆▄▂▂▅▄▄▂▃▁▅▆▄▆▅▆▆
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 16%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,076 | 14,071 | +5 | 14,150 | 14,653 | decreasing (-0.66/hr) |
| Heap InUse | 171.6MB | 175.6MB | -4.0MB | 143.7MB | 201.6MB | stable (+0.31MB/hr) |
| Heap Sys | 1012.9MB | 1012.9MB | +0.0MB | 786.3MB | 1016.6MB | |
| Heap Objects | 1,154,151 | 1,221,634 | -67483 | 778,510 | 1,341,103 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 10 | 14,107 | 150.9MB | 175.6MB |

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
| 9 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 10 | `reflect.mapassign_faststr0` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 49.96GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 23.04GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 22.76GB |
| 4 | `internal/evaluation.mergeMetadata` | 22.14GB |
| 5 | `reflect.unsafe_NewArray` | 21.51GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 16.3GB |
| 7 | `reflect.MakeSlice` | 11.97GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 11.4GB |
| 9 | `experiment/local.topologicalSort` | 11.32GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 7.12GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 67/69 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/69 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 10.54MB | 64/69 | `████░░░░░░░░░░░ 28%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 67/69 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.85MB | 59/69 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/69 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/69 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/69 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.9MB | 53/69 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `compress/flate.NewWriter` | 2.67MB | 56/69 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 23.48GB | 60/69 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 15.09GB | 45/69 | `█████████░░░░░░ 64%` |
| 3 | `internal/evaluation.mergeMetadata` | 11.35GB | 56/69 | `███████░░░░░░░░ 48%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 10.7GB | 61/69 | `██████░░░░░░░░░ 45%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 10.68GB | 62/69 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 10.16GB | 60/69 | `██████░░░░░░░░░ 43%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 6.6GB | 45/69 | `████░░░░░░░░░░░ 28%` |
| 8 | `reflect.MakeSlice` | 5.85GB | 58/69 | `███░░░░░░░░░░░░ 24%` |
| 9 | `experiment/local.topologicalSort` | 5.71GB | 57/69 | `███░░░░░░░░░░░░ 24%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 5.62GB | 58/69 | `███░░░░░░░░░░░░ 23%` |

## Alerts

No anomalies detected.
