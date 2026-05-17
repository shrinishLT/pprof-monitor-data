# Overview: stage
*Last updated: 2026-05-17 05:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T05:31 (71 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,067 | avg: 14,147 | max: 14,653 | trend: decreasing (-1.00/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁
```

**Heap InUse** (current: 183.6MB | avg: 144.5MB | max: 201.6MB | trend: stable (+0.42MB/hr))
```
▃▄▁▆▃▃▂▄▅▆▁▂▅▅▁▅▁▁▅▅▂▁▆▆█▄▄▆▃▃▆▆▁▄▅▆▂▅▂▂▃▂▅▂▂▅▂▂▄▅▅▅▆▄▂▂▅▄▄▂▃▁▅▆▄▆▅▆▆▅▆
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 18%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,067 | 14,064 | +3 | 14,147 | 14,653 | decreasing (-1.00/hr) |
| Heap InUse | 183.6MB | 162.4MB | +21.2MB | 144.5MB | 201.6MB | stable (+0.42MB/hr) |
| Heap Sys | 1012.9MB | 1012.9MB | +0.0MB | 792.7MB | 1016.6MB | |
| Heap Objects | 1,343,690 | 1,037,447 | +306243 | 790,117 | 1,343,690 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 12 | 14,100 | 154.6MB | 183.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `reflect.mapassign_faststr0` | 2.0MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 51.71GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 23.07GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 22.78GB |
| 4 | `reflect.unsafe_NewArray` | 22.31GB |
| 5 | `internal/evaluation.mergeMetadata` | 22.16GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 16.3GB |
| 7 | `reflect.MakeSlice` | 12.42GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 11.41GB |
| 9 | `experiment/local.topologicalSort` | 11.33GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 7.12GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 69/71 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/71 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 10.58MB | 66/71 | `████░░░░░░░░░░░ 28%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 69/71 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.85MB | 61/71 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/71 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/71 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/71 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.9MB | 55/71 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `compress/flate.NewWriter` | 2.68MB | 58/71 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 24.38GB | 62/71 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 15.15GB | 47/71 | `█████████░░░░░░ 62%` |
| 3 | `internal/evaluation.mergeMetadata` | 11.72GB | 58/71 | `███████░░░░░░░░ 48%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 11.08GB | 63/71 | `██████░░░░░░░░░ 45%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 11.06GB | 64/71 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 10.55GB | 62/71 | `██████░░░░░░░░░ 43%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 6.62GB | 47/71 | `████░░░░░░░░░░░ 27%` |
| 8 | `reflect.MakeSlice` | 6.07GB | 60/71 | `███░░░░░░░░░░░░ 24%` |
| 9 | `experiment/local.topologicalSort` | 5.9GB | 59/71 | `███░░░░░░░░░░░░ 24%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 5.81GB | 60/71 | `███░░░░░░░░░░░░ 23%` |

## Alerts

No anomalies detected.
