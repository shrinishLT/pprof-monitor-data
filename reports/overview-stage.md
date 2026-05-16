# Overview: stage
*Last updated: 2026-05-16 16:32 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T16:32 (45 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,315 | avg: 14,165 | max: 14,653 | trend: INCREASING (+3.90/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄
```

**Heap InUse** (current: 122.5MB | avg: 141.7MB | max: 201.6MB | trend: stable (+0.04MB/hr))
```
▃▄▁▆▃▃▂▄▅▆▁▂▅▅▁▅▁▁▅▅▂▁▆▆█▄▄▆▃▃▆▆▁▄▅▆▂▅▂▂▃▂▅▂▂
```

## Current Status

Goroutines: `███████████████████░ 97%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 12%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,315 | 14,151 | +164 | 14,165 | 14,653 | INCREASING (+3.90/hr) |
| Heap InUse | 122.5MB | 111.4MB | +11.1MB | 141.7MB | 201.6MB | stable (+0.04MB/hr) |
| Heap Sys | 1012.1MB | 1012.2MB | -0.1MB | 665.6MB | 1016.6MB | |
| Heap Objects | 397,231 | 366,703 | +30528 | 765,464 | 1,341,103 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 35 | 14,163 | 141.4MB | 201.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 5.01MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `reflect.unsafe_NewArray` | 2.0MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 28.34GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 16.22GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 13.51GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 13.3GB |
| 5 | `internal/evaluation.mergeMetadata` | 13.05GB |
| 6 | `reflect.unsafe_NewArray` | 12.31GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 7.08GB |
| 8 | `reflect.MakeSlice` | 6.89GB |
| 9 | `experiment/local.topologicalSort` | 6.66GB |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 6.62GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 43/45 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/45 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 9.6MB | 40/45 | `███░░░░░░░░░░░░ 26%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.23MB | 43/45 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.74MB | 35/45 | `███░░░░░░░░░░░░ 23%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/45 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/45 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/45 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `reflect.unsafe_New` | 3.0MB | 1/45 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `segmentio/kafka-go.makePartitions` | 2.9MB | 30/45 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 13.78GB | 21/45 | `███████████████ 100%` |
| 2 | `segmentio/kafka-go.makePartitions` | 12.72GB | 36/45 | `█████████████░░ 92%` |
| 3 | `internal/evaluation.mergeMetadata` | 6.3GB | 32/45 | `██████░░░░░░░░░ 45%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 6.03GB | 21/45 | `██████░░░░░░░░░ 43%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 5.6GB | 37/45 | `██████░░░░░░░░░ 40%` |
| 6 | `reflect.unsafe_NewArray` | 5.54GB | 36/45 | `██████░░░░░░░░░ 40%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 5.53GB | 38/45 | `██████░░░░░░░░░ 40%` |
| 8 | `reflect.MakeSlice` | 3.28GB | 34/45 | `███░░░░░░░░░░░░ 23%` |
| 9 | `experiment/local.topologicalSort` | 3.13GB | 33/45 | `███░░░░░░░░░░░░ 22%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 3.04GB | 34/45 | `███░░░░░░░░░░░░ 22%` |

## Alerts

No anomalies detected.
