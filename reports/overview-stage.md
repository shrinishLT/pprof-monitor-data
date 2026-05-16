# Overview: stage
*Last updated: 2026-05-16 09:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T09:02 (30 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,064 | avg: 14,144 | max: 14,602 | trend: decreasing (-0.71/hr))
```
▁▁▁▁▁▅▅▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁█▃▁▁▁▁
```

**Heap InUse** (current: 127.3MB | avg: 142.3MB | max: 201.6MB | trend: INCREASING (+1.29MB/hr))
```
▃▄▁▆▃▃▂▄▅▆▁▂▅▅▁▅▁▁▅▅▂▁▆▆█▄▄▆▃▃
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 12%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,064 | 14,066 | -2 | 14,144 | 14,602 | decreasing (-0.71/hr) |
| Heap InUse | 127.3MB | 125.7MB | +1.6MB | 142.3MB | 201.6MB | INCREASING (+1.29MB/hr) |
| Heap Sys | 1013.7MB | 1013.7MB | +0.0MB | 492.1MB | 1016.6MB | |
| Heap Objects | 650,373 | 661,233 | -10860 | 798,710 | 1,341,103 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 20 | 14,128 | 142.1MB | 201.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 9 | `reflect.mapassign_faststr0` | 2.0MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 14.84GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 13.37GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 7.16GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 7.08GB |
| 5 | `internal/evaluation.mergeMetadata` | 6.92GB |
| 6 | `reflect.unsafe_NewArray` | 6.48GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 5.85GB |
| 8 | `reflect.MakeSlice` | 3.63GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 3.53GB |
| 10 | `experiment/local.topologicalSort` | 3.53GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 28/30 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/30 | `█████░░░░░░░░░░ 39%` |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.22MB | 28/30 | `███░░░░░░░░░░░░ 25%` |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.55MB | 20/30 | `███░░░░░░░░░░░░ 23%` |
| 5 | `runtime.mallocgc` | 8.1MB | 25/30 | `███░░░░░░░░░░░░ 22%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/30 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/30 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `segmentio/kafka-go.makePartitions` | 2.64MB | 18/30 | `█░░░░░░░░░░░░░░ 7%` |
| 9 | `compress/flate.NewWriter` | 2.52MB | 25/30 | `█░░░░░░░░░░░░░░ 6%` |
| 10 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB | 19/30 | `█░░░░░░░░░░░░░░ 6%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 12.17GB | 6/30 | `███████████████ 100%` |
| 2 | `segmentio/kafka-go.makePartitions` | 6.08GB | 21/30 | `███████░░░░░░░░ 49%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 5.33GB | 6/30 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 3.62GB | 17/30 | `████░░░░░░░░░░░ 29%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 2.92GB | 22/30 | `███░░░░░░░░░░░░ 23%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 2.83GB | 23/30 | `███░░░░░░░░░░░░ 23%` |
| 7 | `reflect.unsafe_NewArray` | 2.65GB | 21/30 | `███░░░░░░░░░░░░ 21%` |
| 8 | `experiment/local.topologicalSort` | 1.76GB | 18/30 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 1.69GB | 19/30 | `██░░░░░░░░░░░░░ 13%` |
| 10 | `reflect.MakeSlice` | 1.64GB | 19/30 | `██░░░░░░░░░░░░░ 13%` |

## Alerts

No anomalies detected.
