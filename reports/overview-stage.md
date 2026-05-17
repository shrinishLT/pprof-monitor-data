# Overview: stage
*Last updated: 2026-05-18 00:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T00:31 (109 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,067 | avg: 14,135 | max: 14,653 | trend: decreasing (-1.54/hr))
```
▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▂▅▃█▁▂▁▁▂▂▃▁▁▁▂▁▁▂▁▁▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 152.6MB | avg: 146.5MB | max: 213.6MB | trend: stable (+0.17MB/hr))
```
▄▁▄▁▁▅▅▁▁▆▅▇▃▃▅▂▂▅▆▁▃▅▅▂▄▂▂▂▁▄▁▂▄▂▁▄▄▄▅▅▃▂▂▄▃▃▁▂▁▄▅▄▅▄▅▅▄▆█▄▆▂▅▅▄▆▄▄▁▄▄▅▃▅▅▂▅▃▃▅▃▄▅▃▁▂▁▅▁▁▂▁▅▆▁▄
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 15%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,067 | 14,067 | +0 | 14,135 | 14,653 | decreasing (-1.54/hr) |
| Heap InUse | 152.6MB | 107.6MB | +45.0MB | 146.5MB | 213.6MB | stable (+0.17MB/hr) |
| Heap Sys | 1013.3MB | 1013.3MB | +0.0MB | 869.5MB | 1016.6MB | |
| Heap Objects | 941,232 | 340,272 | +600960 | 812,132 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 2 | 14,067 | 130.1MB | 152.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.0MB |
| 6 | `compress/flate.NewWriter` | 3.53MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `reflect.mapassign_faststr0` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 85.67GB |
| 2 | `reflect.unsafe_NewArray` | 37.05GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 31.52GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 31.26GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 31.09GB |
| 6 | `internal/evaluation.mergeMetadata` | 30.18GB |
| 7 | `reflect.MakeSlice` | 20.58GB |
| 8 | `experiment/local.topologicalSort` | 15.5GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 15.4GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 13.61GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 107/109 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/109 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 11.14MB | 104/109 | `████░░░░░░░░░░░ 30%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 107/109 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.91MB | 99/109 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/109 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/109 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.25MB | 2/109 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `segmentio/kafka-go.makePartitions` | 3.07MB | 89/109 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `compress/flate.NewWriter` | 2.79MB | 91/109 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 41.41GB | 100/109 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 21.69GB | 85/109 | `███████░░░░░░░░ 52%` |
| 3 | `internal/evaluation.mergeMetadata` | 18.08GB | 96/109 | `██████░░░░░░░░░ 43%` |
| 4 | `reflect.unsafe_NewArray` | 17.89GB | 100/109 | `██████░░░░░░░░░ 43%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 17.72GB | 102/109 | `██████░░░░░░░░░ 42%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 17.66GB | 101/109 | `██████░░░░░░░░░ 42%` |
| 7 | `reflect.MakeSlice` | 10.16GB | 98/109 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 9.46GB | 85/109 | `███░░░░░░░░░░░░ 22%` |
| 9 | `experiment/local.topologicalSort` | 9.17GB | 97/109 | `███░░░░░░░░░░░░ 22%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 9.03GB | 98/109 | `███░░░░░░░░░░░░ 21%` |

## Alerts

No anomalies detected.
