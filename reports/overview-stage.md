# Overview: stage
*Last updated: 2026-05-16 21:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T21:03 (54 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,145 | avg: 14,157 | max: 14,653 | trend: INCREASING (+0.87/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂
```

**Heap InUse** (current: 142.9MB | avg: 143.0MB | max: 201.6MB | trend: stable (+0.30MB/hr))
```
▃▄▁▆▃▃▂▄▅▆▁▂▅▅▁▅▁▁▅▅▂▁▆▆█▄▄▆▃▃▆▆▁▄▅▆▂▅▂▂▃▂▅▂▂▅▂▂▄▅▅▅▆▄
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 14%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,145 | 14,070 | +75 | 14,157 | 14,653 | INCREASING (+0.87/hr) |
| Heap InUse | 142.9MB | 180.5MB | -37.6MB | 143.0MB | 201.6MB | stable (+0.30MB/hr) |
| Heap Sys | 1012.5MB | 1012.6MB | -0.1MB | 723.4MB | 1016.6MB | |
| Heap Objects | 608,352 | 1,279,638 | -671286 | 770,286 | 1,341,103 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 44 | 14,154 | 143.1MB | 201.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `reflect.unsafe_NewArray` | 1.53MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 36.51GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 17.34GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 17.07GB |
| 4 | `internal/evaluation.mergeMetadata` | 16.61GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 16.23GB |
| 6 | `reflect.unsafe_NewArray` | 15.75GB |
| 7 | `reflect.MakeSlice` | 8.75GB |
| 8 | `experiment/local.topologicalSort` | 8.52GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 8.5GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 7.09GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 52/54 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/54 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 10.06MB | 49/54 | `████░░░░░░░░░░░ 27%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.23MB | 52/54 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.8MB | 44/54 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/54 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/54 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/54 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.84MB | 39/54 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `compress/flate.NewWriter` | 2.69MB | 46/54 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 16.74GB | 45/54 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 14.51GB | 30/54 | `█████████████░░ 86%` |
| 3 | `internal/evaluation.mergeMetadata` | 8.35GB | 41/54 | `███████░░░░░░░░ 49%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 7.65GB | 46/54 | `██████░░░░░░░░░ 45%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 7.6GB | 47/54 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 7.27GB | 45/54 | `██████░░░░░░░░░ 43%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 6.34GB | 30/54 | `█████░░░░░░░░░░ 37%` |
| 8 | `reflect.MakeSlice` | 4.25GB | 43/54 | `███░░░░░░░░░░░░ 25%` |
| 9 | `experiment/local.topologicalSort` | 4.18GB | 42/54 | `███░░░░░░░░░░░░ 24%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 4.08GB | 43/54 | `███░░░░░░░░░░░░ 24%` |

## Alerts

No anomalies detected.
