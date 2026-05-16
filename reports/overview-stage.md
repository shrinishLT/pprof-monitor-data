# Overview: stage
*Last updated: 2026-05-16 17:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T17:01 (46 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,068 | avg: 14,163 | max: 14,653 | trend: INCREASING (+3.11/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁
```

**Heap InUse** (current: 157.3MB | avg: 142.1MB | max: 201.6MB | trend: stable (+0.12MB/hr))
```
▃▄▁▆▃▃▂▄▅▆▁▂▅▅▁▅▁▁▅▅▂▁▆▆█▄▄▆▃▃▆▆▁▄▅▆▂▅▂▂▃▂▅▂▂▅
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 15%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,068 | 14,315 | -247 | 14,163 | 14,653 | INCREASING (+3.11/hr) |
| Heap InUse | 157.3MB | 122.5MB | +34.8MB | 142.1MB | 201.6MB | stable (+0.12MB/hr) |
| Heap Sys | 1012.3MB | 1012.1MB | +0.2MB | 673.1MB | 1016.6MB | |
| Heap Objects | 1,009,989 | 397,231 | +612758 | 770,780 | 1,341,103 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 36 | 14,160 | 141.9MB | 201.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.5MB |
| 6 | `compress/flate.NewWriter` | 3.53MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `reflect.unsafe_NewArray` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 29.16GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 16.22GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 14.79GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 14.55GB |
| 5 | `internal/evaluation.mergeMetadata` | 14.21GB |
| 6 | `reflect.unsafe_NewArray` | 12.67GB |
| 7 | `experiment/local.topologicalSort` | 7.28GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 7.23GB |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 7.08GB |
| 10 | `reflect.MakeSlice` | 7.08GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 44/46 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/46 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 9.66MB | 41/46 | `███░░░░░░░░░░░░ 26%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.23MB | 44/46 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.75MB | 36/46 | `███░░░░░░░░░░░░ 23%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/46 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/46 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/46 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `reflect.unsafe_New` | 3.0MB | 1/46 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `segmentio/kafka-go.makePartitions` | 2.95MB | 31/46 | `█░░░░░░░░░░░░░░ 8%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 13.89GB | 22/46 | `███████████████ 100%` |
| 2 | `segmentio/kafka-go.makePartitions` | 13.16GB | 37/46 | `██████████████░ 94%` |
| 3 | `internal/evaluation.mergeMetadata` | 6.54GB | 33/46 | `███████░░░░░░░░ 47%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 6.07GB | 22/46 | `██████░░░░░░░░░ 43%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 5.83GB | 38/46 | `██████░░░░░░░░░ 41%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 5.77GB | 39/46 | `██████░░░░░░░░░ 41%` |
| 7 | `reflect.unsafe_NewArray` | 5.74GB | 37/46 | `██████░░░░░░░░░ 41%` |
| 8 | `reflect.MakeSlice` | 3.39GB | 35/46 | `███░░░░░░░░░░░░ 24%` |
| 9 | `experiment/local.topologicalSort` | 3.25GB | 34/46 | `███░░░░░░░░░░░░ 23%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 3.16GB | 35/46 | `███░░░░░░░░░░░░ 22%` |

## Alerts

No anomalies detected.
