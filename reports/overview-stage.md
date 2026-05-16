# Overview: stage
*Last updated: 2026-05-17 00:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T00:03 (60 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,062 | avg: 14,155 | max: 14,653 | trend: stable (+0.24/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃▁▁▁
```

**Heap InUse** (current: 108.8MB | avg: 141.9MB | max: 201.6MB | trend: stable (+0.02MB/hr))
```
▃▄▁▆▃▃▂▄▅▆▁▂▅▅▁▅▁▁▅▅▂▁▆▆█▄▄▆▃▃▆▆▁▄▅▆▂▅▂▂▃▂▅▂▂▅▂▂▄▅▅▅▆▄▂▂▅▄▄▂
```

## Current Status

Goroutines: `███████████████████░ 95%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,062 | 14,098 | -36 | 14,155 | 14,653 | stable (+0.24/hr) |
| Heap InUse | 108.8MB | 144.0MB | -35.2MB | 141.9MB | 201.6MB | stable (+0.02MB/hr) |
| Heap Sys | 1012.9MB | 1012.9MB | +0.0MB | 752.3MB | 1016.6MB | |
| Heap Objects | 352,471 | 800,441 | -447970 | 756,286 | 1,341,103 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 1 | 14,062 | 108.8MB | 108.8MB |

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
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `reflect.unsafe_NewArray` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 41.96GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 19.53GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 19.24GB |
| 4 | `internal/evaluation.mergeMetadata` | 18.8GB |
| 5 | `reflect.unsafe_NewArray` | 18.05GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 16.23GB |
| 7 | `reflect.MakeSlice` | 10.04GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 9.63GB |
| 9 | `experiment/local.topologicalSort` | 9.6GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 7.09GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 58/60 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/60 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 10.28MB | 55/60 | `████░░░░░░░░░░░ 28%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 58/60 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.82MB | 50/60 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/60 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/60 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/60 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.92MB | 44/60 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `compress/flate.NewWriter` | 2.69MB | 50/60 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 19.44GB | 51/60 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 14.8GB | 36/60 | `███████████░░░░ 76%` |
| 3 | `internal/evaluation.mergeMetadata` | 9.6GB | 47/60 | `███████░░░░░░░░ 49%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 8.91GB | 52/60 | `██████░░░░░░░░░ 45%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 8.87GB | 53/60 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 8.43GB | 51/60 | `██████░░░░░░░░░ 43%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 6.47GB | 36/60 | `████░░░░░░░░░░░ 33%` |
| 8 | `reflect.MakeSlice` | 4.89GB | 49/60 | `███░░░░░░░░░░░░ 25%` |
| 9 | `experiment/local.topologicalSort` | 4.82GB | 48/60 | `███░░░░░░░░░░░░ 24%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 4.72GB | 49/60 | `███░░░░░░░░░░░░ 24%` |

## Alerts

No anomalies detected.
