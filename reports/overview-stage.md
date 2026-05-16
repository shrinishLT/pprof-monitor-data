# Overview: stage
*Last updated: 2026-05-17 03:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T03:31 (67 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,065 | avg: 14,152 | max: 14,653 | trend: stable (-0.31/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃▁▁▁▁▁▁▁▁▅▁
```

**Heap InUse** (current: 163.2MB | avg: 142.8MB | max: 201.6MB | trend: stable (+0.18MB/hr))
```
▃▄▁▆▃▃▂▄▅▆▁▂▅▅▁▅▁▁▅▅▂▁▆▆█▄▄▆▃▃▆▆▁▄▅▆▂▅▂▂▃▂▅▂▂▅▂▂▄▅▅▅▆▄▂▂▅▄▄▂▃▁▅▆▄▆▅
```

## Current Status

Goroutines: `███████████████████░ 95%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 16%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,065 | 14,439 | -374 | 14,152 | 14,653 | stable (-0.31/hr) |
| Heap InUse | 163.2MB | 170.8MB | -7.6MB | 142.8MB | 201.6MB | stable (+0.18MB/hr) |
| Heap Sys | 1012.9MB | 1012.5MB | +0.4MB | 779.6MB | 1016.6MB | |
| Heap Objects | 1,070,262 | 749,984 | +320278 | 766,289 | 1,341,103 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 8 | 14,116 | 145.2MB | 172.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `reflect.unsafe_NewArray` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 48.13GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 22.63GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 22.34GB |
| 4 | `internal/evaluation.mergeMetadata` | 21.75GB |
| 5 | `reflect.unsafe_NewArray` | 20.74GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 16.3GB |
| 7 | `reflect.MakeSlice` | 11.52GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 11.18GB |
| 9 | `experiment/local.topologicalSort` | 11.12GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 7.12GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 65/67 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/67 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 10.49MB | 62/67 | `████░░░░░░░░░░░ 28%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 65/67 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.84MB | 57/67 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/67 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/67 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/67 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.9MB | 51/67 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `compress/flate.NewWriter` | 2.65MB | 54/67 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 22.58GB | 58/67 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 15.04GB | 43/67 | `█████████░░░░░░ 66%` |
| 3 | `internal/evaluation.mergeMetadata` | 10.96GB | 54/67 | `███████░░░░░░░░ 48%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 10.29GB | 59/67 | `██████░░░░░░░░░ 45%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 10.27GB | 60/67 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 9.78GB | 58/67 | `██████░░░░░░░░░ 43%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 6.57GB | 43/67 | `████░░░░░░░░░░░ 29%` |
| 8 | `reflect.MakeSlice` | 5.64GB | 56/67 | `███░░░░░░░░░░░░ 24%` |
| 9 | `experiment/local.topologicalSort` | 5.51GB | 55/67 | `███░░░░░░░░░░░░ 24%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 5.41GB | 56/67 | `███░░░░░░░░░░░░ 23%` |

## Alerts

No anomalies detected.
