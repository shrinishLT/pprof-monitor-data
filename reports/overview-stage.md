# Overview: stage
*Last updated: 2026-05-18 17:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T17:02 (142 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,253 | avg: 14,136 | max: 14,653 | trend: decreasing (-0.51/hr))
```
▁▁▂▁▁▃▁▂▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁█▄▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▆▆▁▁▁▁▁▁▁▁▁▁▁▃▁▂▁▂▄▂▂▅▃
```

**Heap InUse** (current: 194.2MB | avg: 149.4MB | max: 277.6MB | trend: stable (+0.27MB/hr))
```
▁▁▂▃▃▃▄▂▁▁▃▂▂▁▁▁▃▃▂▃▃▃▃▃▄▅▃▄▁▃▃▃▄▃▂▁▂▂▃▂▃▃▁▄▂▂▃▂▃▃▂▁▁▁▃▁▁▂▁▃▄▁▂▄▂▁▂▃▄▁▄▃▂█▄▂▂▁▁▄▂▁▁▂▃▃▄▁▃▄▂▁▄▄▃▄
```

## Current Status

Goroutines: `███████████████████░ 97%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 19%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,253 | 14,406 | -153 | 14,136 | 14,653 | decreasing (-0.51/hr) |
| Heap InUse | 194.2MB | 159.7MB | +34.5MB | 149.4MB | 277.6MB | stable (+0.27MB/hr) |
| Heap Sys | 1012.9MB | 1012.6MB | +0.3MB | 902.9MB | 1016.6MB | |
| Heap Objects | 1,160,702 | 683,702 | +477000 | 824,347 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 35 | 14,136 | 157.3MB | 277.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `bytes.growSlice` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 115.4GB |
| 2 | `reflect.unsafe_NewArray` | 49.93GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 46.98GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 45.51GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 44.97GB |
| 6 | `internal/evaluation.mergeMetadata` | 43.84GB |
| 7 | `reflect.MakeSlice` | 27.69GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 22.38GB |
| 9 | `experiment/local.topologicalSort` | 22.33GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.43GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 140/142 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/142 | `██████░░░░░░░░░ 42%` |
| 3 | `runtime.mallocgc` | 11.37MB | 137/142 | `████░░░░░░░░░░░ 31%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 140/142 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.93MB | 132/142 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 8.5MB | 2/142 | `███░░░░░░░░░░░░ 23%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/142 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `segmentio/kafka-go.makePartitions` | 3.12MB | 120/142 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `internal/evaluation.mergeMetadata` | 3.0MB | 3/142 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `compress/flate.NewWriter` | 2.83MB | 116/142 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 56.19GB | 133/142 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 26.88GB | 118/142 | `███████░░░░░░░░ 47%` |
| 3 | `reflect.unsafe_NewArray` | 24.29GB | 133/142 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 22.85GB | 129/142 | `██████░░░░░░░░░ 40%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 22.73GB | 135/142 | `██████░░░░░░░░░ 40%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 22.6GB | 134/142 | `██████░░░░░░░░░ 40%` |
| 7 | `reflect.MakeSlice` | 13.71GB | 131/142 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 11.7GB | 118/142 | `███░░░░░░░░░░░░ 20%` |
| 9 | `experiment/local.topologicalSort` | 11.6GB | 130/142 | `███░░░░░░░░░░░░ 20%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 11.47GB | 131/142 | `███░░░░░░░░░░░░ 20%` |

## Alerts

No anomalies detected.
