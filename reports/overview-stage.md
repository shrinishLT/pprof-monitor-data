# Overview: stage
*Last updated: 2026-05-16 06:35 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T06:35 (26 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,262 | avg: 14,155 | max: 14,602 | trend: INCREASING (+4.95/hr))
```
▁▁▁▁▁▅▅▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁█▃
```

**Heap InUse** (current: 143.6MB | avg: 142.0MB | max: 201.6MB | trend: INCREASING (+1.89MB/hr))
```
▃▄▁▆▃▃▂▄▅▆▁▂▅▅▁▅▁▁▅▅▂▁▆▆█▄
```

## Current Status

Goroutines: `███████████████████░ 97%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 14%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,262 | 14,602 | -340 | 14,155 | 14,602 | INCREASING (+4.95/hr) |
| Heap InUse | 143.6MB | 201.6MB | -58.0MB | 142.0MB | 201.6MB | INCREASING (+1.89MB/hr) |
| Heap Sys | 1013.4MB | 1016.6MB | -3.2MB | 411.9MB | 1016.6MB | |
| Heap Objects | 680,693 | 838,813 | -158120 | 793,130 | 1,341,103 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 16 | 14,143 | 141.6MB | 201.6MB |

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
| 8 | `bytes.growSlice` | 2.01MB |
| 9 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 10 | `reflect.mapassign_faststr0` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 13.37GB |
| 2 | `segmentio/kafka-go.makePartitions` | 10.49GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 7.0GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 6.91GB |
| 5 | `internal/evaluation.mergeMetadata` | 6.77GB |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 5.85GB |
| 7 | `reflect.unsafe_NewArray` | 4.59GB |
| 8 | `experiment/local.topologicalSort` | 3.45GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 3.44GB |
| 10 | `reflect.MakeSlice` | 2.58GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 24/26 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/26 | `█████░░░░░░░░░░ 39%` |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.22MB | 24/26 | `███░░░░░░░░░░░░ 25%` |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.44MB | 16/26 | `███░░░░░░░░░░░░ 23%` |
| 5 | `runtime.mallocgc` | 7.34MB | 21/26 | `███░░░░░░░░░░░░ 20%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/26 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/26 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `segmentio/kafka-go.makePartitions` | 2.75MB | 14/26 | `█░░░░░░░░░░░░░░ 7%` |
| 9 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB | 15/26 | `█░░░░░░░░░░░░░░ 6%` |
| 10 | `compress/flate.NewWriter` | 2.37MB | 21/26 | `░░░░░░░░░░░░░░░ 6%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 9.78GB | 2/26 | `███████████████ 100%` |
| 2 | `segmentio/kafka-go.makePartitions` | 4.49GB | 17/26 | `██████░░░░░░░░░ 45%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 4.29GB | 2/26 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 2.63GB | 13/26 | `████░░░░░░░░░░░ 26%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 2.01GB | 18/26 | `███░░░░░░░░░░░░ 20%` |
| 6 | `reflect.unsafe_NewArray` | 1.96GB | 17/26 | `███░░░░░░░░░░░░ 20%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 1.93GB | 19/26 | `██░░░░░░░░░░░░░ 19%` |
| 8 | `experiment/local.topologicalSort` | 1.26GB | 14/26 | `█░░░░░░░░░░░░░░ 12%` |
| 9 | `reflect.MakeSlice` | 1.24GB | 15/26 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 1.21GB | 15/26 | `█░░░░░░░░░░░░░░ 12%` |

## Alerts

No anomalies detected.
