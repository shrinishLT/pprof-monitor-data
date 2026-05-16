# Overview: stage
*Last updated: 2026-05-16 18:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T18:03 (48 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,078 | avg: 14,160 | max: 14,653 | trend: INCREASING (+1.88/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁
```

**Heap InUse** (current: 109.9MB | avg: 140.8MB | max: 201.6MB | trend: stable (-0.19MB/hr))
```
▃▄▁▆▃▃▂▄▅▆▁▂▅▅▁▅▁▁▅▅▂▁▆▆█▄▄▆▃▃▆▆▁▄▅▆▂▅▂▂▃▂▅▂▂▅▂▂
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,078 | 14,076 | +2 | 14,160 | 14,653 | INCREASING (+1.88/hr) |
| Heap InUse | 109.9MB | 116.0MB | -6.1MB | 140.8MB | 201.6MB | stable (-0.19MB/hr) |
| Heap Sys | 1012.6MB | 1012.5MB | +0.1MB | 687.3MB | 1016.6MB | |
| Heap Objects | 386,671 | 478,699 | -92028 | 756,693 | 1,341,103 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 38 | 14,156 | 140.3MB | 201.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `reflect.mapassign_faststr0` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `segmentio/kafka-go.makePartitions` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 31.09GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 16.23GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 15.48GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 15.26GB |
| 5 | `internal/evaluation.mergeMetadata` | 14.85GB |
| 6 | `reflect.unsafe_NewArray` | 13.47GB |
| 7 | `experiment/local.topologicalSort` | 7.62GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 7.58GB |
| 9 | `reflect.MakeSlice` | 7.51GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 7.09GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 46/48 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/48 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 9.77MB | 43/48 | `████░░░░░░░░░░░ 26%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.23MB | 46/48 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.76MB | 38/48 | `███░░░░░░░░░░░░ 23%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/48 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/48 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/48 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `reflect.unsafe_New` | 3.0MB | 1/48 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `segmentio/kafka-go.makePartitions` | 2.88MB | 33/48 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 14.08GB | 24/48 | `███████████████ 100%` |
| 2 | `segmentio/kafka-go.makePartitions` | 14.05GB | 39/48 | `██████████████░ 99%` |
| 3 | `internal/evaluation.mergeMetadata` | 7.01GB | 35/48 | `███████░░░░░░░░ 49%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 6.3GB | 40/48 | `██████░░░░░░░░░ 44%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 6.24GB | 41/48 | `██████░░░░░░░░░ 44%` |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 6.16GB | 24/48 | `██████░░░░░░░░░ 43%` |
| 7 | `reflect.unsafe_NewArray` | 6.12GB | 39/48 | `██████░░░░░░░░░ 43%` |
| 8 | `reflect.MakeSlice` | 3.61GB | 37/48 | `███░░░░░░░░░░░░ 25%` |
| 9 | `experiment/local.topologicalSort` | 3.49GB | 36/48 | `███░░░░░░░░░░░░ 24%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 3.4GB | 37/48 | `███░░░░░░░░░░░░ 24%` |

## Alerts

No anomalies detected.
