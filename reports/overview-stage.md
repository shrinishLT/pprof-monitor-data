# Overview: stage
*Last updated: 2026-05-18 04:32 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T04:32 (117 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,065 | avg: 14,131 | max: 14,653 | trend: decreasing (-1.58/hr))
```
▁▁▁▇▃▁▁▁▁▁▂▁▁▂▅▃█▁▂▁▁▂▂▃▁▁▁▂▁▁▂▁▁▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁
```

**Heap InUse** (current: 183.5MB | avg: 147.1MB | max: 213.6MB | trend: stable (+0.20MB/hr))
```
▁▆▅▇▃▃▅▂▂▅▆▁▃▄▅▁▄▁▂▂▁▄▁▂▄▁▁▄▄▄▄▅▃▁▁▄▃▃▁▂▁▄▅▄▅▄▅▅▄▆█▄▆▂▅▅▄▆▄▃▁▃▄▅▃▄▄▁▅▃▃▅▃▄▅▂▁▂▁▅▁▁▂▁▅▆▁▄▆▃▂▂▅▅▁▆
```

## Current Status

Goroutines: `███████████████████░ 95%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 18%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,065 | 14,163 | -98 | 14,131 | 14,653 | decreasing (-1.58/hr) |
| Heap InUse | 183.5MB | 112.0MB | +71.5MB | 147.1MB | 213.6MB | stable (+0.20MB/hr) |
| Heap Sys | 1012.8MB | 1013.8MB | -1.0MB | 879.3MB | 1016.6MB | |
| Heap Objects | 1,334,866 | 339,035 | +995831 | 821,629 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 10 | 14,079 | 150.2MB | 186.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 5.01MB |
| 6 | `compress/flate.NewWriter` | 3.53MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `reflect.mapassign_faststr0` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 92.89GB |
| 2 | `reflect.unsafe_NewArray` | 40.18GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 34.89GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 34.34GB |
| 5 | `internal/evaluation.mergeMetadata` | 33.41GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 31.26GB |
| 7 | `reflect.MakeSlice` | 22.34GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 17.17GB |
| 9 | `experiment/local.topologicalSort` | 17.08GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 13.61GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 115/117 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/117 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 11.21MB | 112/117 | `████░░░░░░░░░░░ 30%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 115/117 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.92MB | 107/117 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/117 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/117 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.25MB | 2/117 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `segmentio/kafka-go.makePartitions` | 3.07MB | 97/117 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `compress/flate.NewWriter` | 2.81MB | 98/117 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 44.99GB | 108/117 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 22.52GB | 93/117 | `███████░░░░░░░░ 50%` |
| 3 | `reflect.unsafe_NewArray` | 19.44GB | 108/117 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 19.15GB | 104/117 | `██████░░░░░░░░░ 42%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 18.86GB | 110/117 | `██████░░░░░░░░░ 41%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 18.78GB | 109/117 | `██████░░░░░░░░░ 41%` |
| 7 | `reflect.MakeSlice` | 11.02GB | 106/117 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 9.81GB | 93/117 | `███░░░░░░░░░░░░ 21%` |
| 9 | `experiment/local.topologicalSort` | 9.72GB | 105/117 | `███░░░░░░░░░░░░ 21%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 9.59GB | 106/117 | `███░░░░░░░░░░░░ 21%` |

## Alerts

No anomalies detected.
