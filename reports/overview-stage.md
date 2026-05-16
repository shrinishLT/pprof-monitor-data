# Overview: stage
*Last updated: 2026-05-16 21:32 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T21:32 (55 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,070 | avg: 14,156 | max: 14,653 | trend: stable (+0.48/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁
```

**Heap InUse** (current: 117.3MB | avg: 142.5MB | max: 201.6MB | trend: stable (+0.18MB/hr))
```
▃▄▁▆▃▃▂▄▅▆▁▂▅▅▁▅▁▁▅▅▂▁▆▆█▄▄▆▃▃▆▆▁▄▅▆▂▅▂▂▃▂▅▂▂▅▂▂▄▅▅▅▆▄▂
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 11%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,070 | 14,145 | -75 | 14,156 | 14,653 | stable (+0.48/hr) |
| Heap InUse | 117.3MB | 142.9MB | -25.6MB | 142.5MB | 201.6MB | stable (+0.18MB/hr) |
| Heap Sys | 1012.2MB | 1012.5MB | -0.3MB | 728.7MB | 1016.6MB | |
| Heap Objects | 515,563 | 608,352 | -92789 | 765,654 | 1,341,103 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 45 | 14,152 | 142.5MB | 201.6MB |

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
| 9 | `reflect.unsafe_NewArray` | 2.01MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 37.4GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 17.98GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 17.7GB |
| 4 | `internal/evaluation.mergeMetadata` | 17.24GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 16.23GB |
| 6 | `reflect.unsafe_NewArray` | 16.12GB |
| 7 | `reflect.MakeSlice` | 8.95GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 8.83GB |
| 9 | `experiment/local.topologicalSort` | 8.82GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 7.09GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 53/55 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/55 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 10.1MB | 50/55 | `████░░░░░░░░░░░ 27%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.23MB | 53/55 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.8MB | 45/55 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/55 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/55 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/55 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.85MB | 40/55 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `compress/flate.NewWriter` | 2.69MB | 47/55 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 17.19GB | 46/55 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 14.57GB | 31/55 | `████████████░░░ 84%` |
| 3 | `internal/evaluation.mergeMetadata` | 8.57GB | 42/55 | `███████░░░░░░░░ 49%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 7.86GB | 47/55 | `██████░░░░░░░░░ 45%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 7.81GB | 48/55 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 7.47GB | 46/55 | `██████░░░░░░░░░ 43%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 6.37GB | 31/55 | `█████░░░░░░░░░░ 37%` |
| 8 | `reflect.MakeSlice` | 4.36GB | 44/55 | `███░░░░░░░░░░░░ 25%` |
| 9 | `experiment/local.topologicalSort` | 4.29GB | 43/55 | `███░░░░░░░░░░░░ 24%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 4.19GB | 44/55 | `███░░░░░░░░░░░░ 24%` |

## Alerts

No anomalies detected.
