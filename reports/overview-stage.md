# Overview: stage
*Last updated: 2026-05-16 12:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T12:03 (36 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,457 | avg: 14,150 | max: 14,602 | trend: INCREASING (+1.79/hr))
```
▁▁▁▁▁▅▅▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁█▃▁▁▁▁▁▂▁▁▃▆
```

**Heap InUse** (current: 176.8MB | avg: 145.1MB | max: 201.6MB | trend: INCREASING (+1.51MB/hr))
```
▃▄▁▆▃▃▂▄▅▆▁▂▅▅▁▅▁▁▅▅▂▁▆▆█▄▄▆▃▃▆▆▁▄▅▆
```

## Current Status

Goroutines: `███████████████████░ 99%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 17%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,457 | 14,229 | +228 | 14,150 | 14,602 | INCREASING (+1.79/hr) |
| Heap InUse | 176.8MB | 165.1MB | +11.7MB | 145.1MB | 201.6MB | INCREASING (+1.51MB/hr) |
| Heap Sys | 1011.6MB | 1012.3MB | -0.7MB | 579.0MB | 1016.6MB | |
| Heap Objects | 824,648 | 992,047 | -167399 | 820,155 | 1,341,103 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 26 | 14,140 | 146.0MB | 201.6MB |

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
| 8 | `reflect.unsafe_NewArray` | 2.01MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `reflect.mapassign_faststr0` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 20.3GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 13.38GB |
| 3 | `reflect.unsafe_NewArray` | 8.84GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 8.19GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 8.03GB |
| 6 | `internal/evaluation.mergeMetadata` | 7.85GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 5.86GB |
| 8 | `reflect.MakeSlice` | 4.92GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 4.02GB |
| 10 | `experiment/local.topologicalSort` | 4.02GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 34/36 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/36 | `█████░░░░░░░░░░ 39%` |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.23MB | 34/36 | `███░░░░░░░░░░░░ 25%` |
| 4 | `runtime.mallocgc` | 8.87MB | 31/36 | `███░░░░░░░░░░░░ 24%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.65MB | 26/36 | `███░░░░░░░░░░░░ 23%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/36 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/36 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `segmentio/kafka-go.makePartitions` | 2.66MB | 22/36 | `█░░░░░░░░░░░░░░ 7%` |
| 9 | `compress/flate.NewWriter` | 2.54MB | 31/36 | `█░░░░░░░░░░░░░░ 6%` |
| 10 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB | 25/36 | `█░░░░░░░░░░░░░░ 6%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 12.77GB | 12/36 | `███████████████ 100%` |
| 2 | `segmentio/kafka-go.makePartitions` | 8.72GB | 27/36 | `██████████░░░░░ 68%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 5.59GB | 12/36 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 4.57GB | 23/36 | `█████░░░░░░░░░░ 35%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 3.88GB | 28/36 | `████░░░░░░░░░░░ 30%` |
| 6 | `reflect.unsafe_NewArray` | 3.81GB | 27/36 | `████░░░░░░░░░░░ 29%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 3.8GB | 29/36 | `████░░░░░░░░░░░ 29%` |
| 8 | `reflect.MakeSlice` | 2.3GB | 25/36 | `██░░░░░░░░░░░░░ 18%` |
| 9 | `experiment/local.topologicalSort` | 2.25GB | 24/36 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 2.18GB | 25/36 | `██░░░░░░░░░░░░░ 17%` |

## Alerts

No anomalies detected.
