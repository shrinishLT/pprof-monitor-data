# Overview: stage
*Last updated: 2026-05-16 09:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T09:31 (31 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,076 | avg: 14,141 | max: 14,602 | trend: decreasing (-1.46/hr))
```
▁▁▁▁▁▅▅▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁█▃▁▁▁▁▁
```

**Heap InUse** (current: 178.0MB | avg: 143.5MB | max: 201.6MB | trend: INCREASING (+1.60MB/hr))
```
▃▄▁▆▃▃▂▄▅▆▁▂▅▅▁▅▁▁▅▅▂▁▆▆█▄▄▆▃▃▆
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 17%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,076 | 14,064 | +12 | 14,141 | 14,602 | decreasing (-1.46/hr) |
| Heap InUse | 178.0MB | 127.3MB | +50.7MB | 143.5MB | 201.6MB | INCREASING (+1.60MB/hr) |
| Heap Sys | 1013.7MB | 1013.7MB | +0.0MB | 509.0MB | 1016.6MB | |
| Heap Objects | 1,258,836 | 650,373 | +608463 | 813,553 | 1,341,103 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 21 | 14,126 | 143.8MB | 201.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `reflect.mapassign_faststr0` | 2.5MB |
| 6 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `compress/flate.NewWriter` | 1.76MB |
| 10 | `reflect.unsafe_NewArray` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 15.66GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 13.37GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 7.25GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 7.15GB |
| 5 | `internal/evaluation.mergeMetadata` | 6.99GB |
| 6 | `reflect.unsafe_NewArray` | 6.85GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 5.85GB |
| 8 | `reflect.MakeSlice` | 3.84GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 3.58GB |
| 10 | `experiment/local.topologicalSort` | 3.57GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 29/31 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/31 | `█████░░░░░░░░░░ 39%` |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.22MB | 29/31 | `███░░░░░░░░░░░░ 25%` |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.57MB | 21/31 | `███░░░░░░░░░░░░ 23%` |
| 5 | `runtime.mallocgc` | 8.25MB | 26/31 | `███░░░░░░░░░░░░ 22%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/31 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/31 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `segmentio/kafka-go.makePartitions` | 2.64MB | 18/31 | `█░░░░░░░░░░░░░░ 7%` |
| 9 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB | 20/31 | `█░░░░░░░░░░░░░░ 6%` |
| 10 | `compress/flate.NewWriter` | 2.49MB | 26/31 | `█░░░░░░░░░░░░░░ 6%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 12.34GB | 7/31 | `███████████████ 100%` |
| 2 | `segmentio/kafka-go.makePartitions` | 6.51GB | 22/31 | `███████░░░░░░░░ 52%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 5.41GB | 7/31 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 3.81GB | 18/31 | `████░░░░░░░░░░░ 30%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 3.1GB | 23/31 | `███░░░░░░░░░░░░ 25%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 3.01GB | 24/31 | `███░░░░░░░░░░░░ 24%` |
| 7 | `reflect.unsafe_NewArray` | 2.85GB | 22/31 | `███░░░░░░░░░░░░ 23%` |
| 8 | `experiment/local.topologicalSort` | 1.85GB | 19/31 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 1.79GB | 20/31 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `reflect.MakeSlice` | 1.75GB | 20/31 | `██░░░░░░░░░░░░░ 14%` |

## Alerts

No anomalies detected.
