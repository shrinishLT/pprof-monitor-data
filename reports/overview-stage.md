# Overview: stage
*Last updated: 2026-05-16 08:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T08:01 (29 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,066 | avg: 14,146 | max: 14,602 | trend: stable (+0.39/hr))
```
▁▁▁▁▁▅▅▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁█▃▁▁▁
```

**Heap InUse** (current: 125.7MB | avg: 142.8MB | max: 201.6MB | trend: INCREASING (+1.65MB/hr))
```
▃▄▁▆▃▃▂▄▅▆▁▂▅▅▁▅▁▁▅▅▂▁▆▆█▄▄▆▃
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 12%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,066 | 14,084 | -18 | 14,146 | 14,602 | stable (+0.39/hr) |
| Heap InUse | 125.7MB | 180.8MB | -55.1MB | 142.8MB | 201.6MB | INCREASING (+1.65MB/hr) |
| Heap Sys | 1013.7MB | 1013.6MB | +0.1MB | 474.2MB | 1016.6MB | |
| Heap Objects | 661,233 | 1,226,909 | -565676 | 803,825 | 1,341,103 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 19 | 14,132 | 142.9MB | 201.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 1.6MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 13.37GB |
| 2 | `segmentio/kafka-go.makePartitions` | 13.06GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 7.13GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 7.04GB |
| 5 | `internal/evaluation.mergeMetadata` | 6.89GB |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 5.85GB |
| 7 | `reflect.unsafe_NewArray` | 5.72GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 3.52GB |
| 9 | `experiment/local.topologicalSort` | 3.51GB |
| 10 | `reflect.MakeSlice` | 3.19GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 27/29 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/29 | `█████░░░░░░░░░░ 39%` |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.22MB | 27/29 | `███░░░░░░░░░░░░ 25%` |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.53MB | 19/29 | `███░░░░░░░░░░░░ 23%` |
| 5 | `runtime.mallocgc` | 7.93MB | 24/29 | `███░░░░░░░░░░░░ 21%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/29 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/29 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `segmentio/kafka-go.makePartitions` | 2.68MB | 17/29 | `█░░░░░░░░░░░░░░ 7%` |
| 9 | `compress/flate.NewWriter` | 2.52MB | 24/29 | `█░░░░░░░░░░░░░░ 6%` |
| 10 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB | 18/29 | `█░░░░░░░░░░░░░░ 6%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 11.93GB | 5/29 | `███████████████ 100%` |
| 2 | `segmentio/kafka-go.makePartitions` | 5.64GB | 20/29 | `███████░░░░░░░░ 47%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 5.23GB | 5/29 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 3.42GB | 16/29 | `████░░░░░░░░░░░ 28%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 2.72GB | 21/29 | `███░░░░░░░░░░░░ 22%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 2.63GB | 22/29 | `███░░░░░░░░░░░░ 22%` |
| 7 | `reflect.unsafe_NewArray` | 2.46GB | 20/29 | `███░░░░░░░░░░░░ 20%` |
| 8 | `experiment/local.topologicalSort` | 1.65GB | 17/29 | `██░░░░░░░░░░░░░ 13%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 1.59GB | 18/29 | `█░░░░░░░░░░░░░░ 13%` |
| 10 | `reflect.MakeSlice` | 1.53GB | 18/29 | `█░░░░░░░░░░░░░░ 12%` |

## Alerts

No anomalies detected.
