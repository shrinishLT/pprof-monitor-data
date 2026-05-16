# Overview: stage
*Last updated: 2026-05-16 10:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T10:01 (32 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,177 | avg: 14,142 | max: 14,602 | trend: decreasing (-0.92/hr))
```
▁▁▁▁▁▅▅▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁█▃▁▁▁▁▁▂
```

**Heap InUse** (current: 183.5MB | avg: 144.7MB | max: 201.6MB | trend: INCREASING (+1.91MB/hr))
```
▃▄▁▆▃▃▂▄▅▆▁▂▅▅▁▅▁▁▅▅▂▁▆▆█▄▄▆▃▃▆▆
```

## Current Status

Goroutines: `███████████████████░ 97%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 18%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,177 | 14,076 | +101 | 14,142 | 14,602 | decreasing (-0.92/hr) |
| Heap InUse | 183.5MB | 178.0MB | +5.5MB | 144.7MB | 201.6MB | INCREASING (+1.91MB/hr) |
| Heap Sys | 1013.8MB | 1013.7MB | +0.1MB | 524.7MB | 1016.6MB | |
| Heap Objects | 1,278,923 | 1,258,836 | +20087 | 828,095 | 1,341,103 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 22 | 14,128 | 145.6MB | 201.6MB |

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
| 8 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 9 | `reflect.unsafe_NewArray` | 2.0MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 16.57GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 13.37GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 7.28GB |
| 4 | `reflect.unsafe_NewArray` | 7.25GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 7.18GB |
| 6 | `internal/evaluation.mergeMetadata` | 7.0GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 5.85GB |
| 8 | `reflect.MakeSlice` | 4.04GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 3.59GB |
| 10 | `experiment/local.topologicalSort` | 3.58GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 30/32 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/32 | `█████░░░░░░░░░░ 39%` |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.22MB | 30/32 | `███░░░░░░░░░░░░ 25%` |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.59MB | 22/32 | `███░░░░░░░░░░░░ 23%` |
| 5 | `runtime.mallocgc` | 8.39MB | 27/32 | `███░░░░░░░░░░░░ 22%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/32 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/32 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `segmentio/kafka-go.makePartitions` | 2.61MB | 19/32 | `█░░░░░░░░░░░░░░ 7%` |
| 9 | `compress/flate.NewWriter` | 2.53MB | 27/32 | `█░░░░░░░░░░░░░░ 6%` |
| 10 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB | 21/32 | `█░░░░░░░░░░░░░░ 6%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 12.47GB | 8/32 | `███████████████ 100%` |
| 2 | `segmentio/kafka-go.makePartitions` | 6.95GB | 23/32 | `████████░░░░░░░ 55%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 5.46GB | 8/32 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 3.98GB | 19/32 | `████░░░░░░░░░░░ 31%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 3.27GB | 24/32 | `███░░░░░░░░░░░░ 26%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 3.18GB | 25/32 | `███░░░░░░░░░░░░ 25%` |
| 7 | `reflect.unsafe_NewArray` | 3.04GB | 23/32 | `███░░░░░░░░░░░░ 24%` |
| 8 | `experiment/local.topologicalSort` | 1.94GB | 20/32 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 1.87GB | 21/32 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `reflect.MakeSlice` | 1.86GB | 21/32 | `██░░░░░░░░░░░░░ 14%` |

## Alerts

No anomalies detected.
