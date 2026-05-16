# Overview: stage
*Last updated: 2026-05-16 07:32 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T07:32 (28 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,084 | avg: 14,149 | max: 14,602 | trend: INCREASING (+1.71/hr))
```
▁▁▁▁▁▅▅▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁█▃▁▁
```

**Heap InUse** (current: 180.8MB | avg: 143.5MB | max: 201.6MB | trend: INCREASING (+2.11MB/hr))
```
▃▄▁▆▃▃▂▄▅▆▁▂▅▅▁▅▁▁▅▅▂▁▆▆█▄▄▆
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 17%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,084 | 14,067 | +17 | 14,149 | 14,602 | INCREASING (+1.71/hr) |
| Heap InUse | 180.8MB | 143.5MB | +37.3MB | 143.5MB | 201.6MB | INCREASING (+2.11MB/hr) |
| Heap Sys | 1013.6MB | 1013.6MB | +0.0MB | 454.9MB | 1016.6MB | |
| Heap Objects | 1,226,909 | 801,403 | +425506 | 808,917 | 1,341,103 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 18 | 14,135 | 143.9MB | 201.6MB |

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
| 10 | `reflect.unsafe_NewArray` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 13.37GB |
| 2 | `segmentio/kafka-go.makePartitions` | 12.21GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 7.1GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 7.01GB |
| 5 | `internal/evaluation.mergeMetadata` | 6.85GB |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 5.85GB |
| 7 | `reflect.unsafe_NewArray` | 5.34GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 3.5GB |
| 9 | `experiment/local.topologicalSort` | 3.49GB |
| 10 | `reflect.MakeSlice` | 2.99GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 26/28 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/28 | `█████░░░░░░░░░░ 39%` |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.22MB | 26/28 | `███░░░░░░░░░░░░ 25%` |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB | 18/28 | `███░░░░░░░░░░░░ 23%` |
| 5 | `runtime.mallocgc` | 7.75MB | 23/28 | `███░░░░░░░░░░░░ 21%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/28 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/28 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `segmentio/kafka-go.makePartitions` | 2.72MB | 16/28 | `█░░░░░░░░░░░░░░ 7%` |
| 9 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB | 17/28 | `█░░░░░░░░░░░░░░ 6%` |
| 10 | `compress/flate.NewWriter` | 2.43MB | 23/28 | `░░░░░░░░░░░░░░░ 6%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 11.57GB | 4/28 | `███████████████ 100%` |
| 2 | `segmentio/kafka-go.makePartitions` | 5.25GB | 19/28 | `██████░░░░░░░░░ 45%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 5.07GB | 4/28 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 3.19GB | 15/28 | `████░░░░░░░░░░░ 27%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 2.51GB | 20/28 | `███░░░░░░░░░░░░ 21%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 2.42GB | 21/28 | `███░░░░░░░░░░░░ 20%` |
| 7 | `reflect.unsafe_NewArray` | 2.29GB | 19/28 | `██░░░░░░░░░░░░░ 19%` |
| 8 | `experiment/local.topologicalSort` | 1.54GB | 16/28 | `█░░░░░░░░░░░░░░ 13%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 1.48GB | 17/28 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `reflect.MakeSlice` | 1.44GB | 17/28 | `█░░░░░░░░░░░░░░ 12%` |

## Alerts

No anomalies detected.
