# Overview: stage
*Last updated: 2026-05-18 11:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T11:31 (131 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,070 | avg: 14,131 | max: 14,653 | trend: decreasing (-1.16/hr))
```
▅▃█▁▂▁▁▂▂▃▁▁▁▂▁▁▂▁▁▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▆▅▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 170.7MB | avg: 148.0MB | max: 277.6MB | trend: stable (+0.20MB/hr))
```
▃▁▃▁▁▁▁▃▁▁▃▁▁▂▃▃▃▄▂▁▁▃▂▂▁▁▁▃▃▂▃▃▃▃▃▄▅▃▄▁▃▃▃▄▃▂▁▂▂▃▂▃▃▁▄▂▂▃▂▃▃▂▁▁▁▃▁▁▂▁▃▄▁▂▄▂▁▂▃▄▁▄▃▂█▄▂▂▁▁▄▂▁▁▂▃
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 16%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,070 | 14,065 | +5 | 14,131 | 14,653 | decreasing (-1.16/hr) |
| Heap InUse | 170.7MB | 137.1MB | +33.6MB | 148.0MB | 277.6MB | stable (+0.20MB/hr) |
| Heap Sys | 1013.1MB | 1013.1MB | +0.0MB | 893.6MB | 1016.6MB | |
| Heap Objects | 1,145,216 | 758,507 | +386709 | 821,272 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 24 | 14,110 | 153.4MB | 277.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 6.01MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `reflect.mapassign_faststr0` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 105.42GB |
| 2 | `reflect.unsafe_NewArray` | 45.54GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 43.83GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 38.9GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 38.41GB |
| 6 | `internal/evaluation.mergeMetadata` | 37.47GB |
| 7 | `reflect.MakeSlice` | 25.34GB |
| 8 | `experiment/local.topologicalSort` | 19.09GB |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 19.05GB |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 19.02GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 129/131 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/131 | `██████░░░░░░░░░ 42%` |
| 3 | `runtime.mallocgc` | 11.31MB | 126/131 | `████░░░░░░░░░░░ 30%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 129/131 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.93MB | 121/131 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 8.5MB | 2/131 | `███░░░░░░░░░░░░ 23%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/131 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `segmentio/kafka-go.makePartitions` | 3.11MB | 109/131 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `internal/evaluation.mergeMetadata` | 3.0MB | 3/131 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `compress/flate.NewWriter` | 2.83MB | 109/131 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 51.26GB | 122/131 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 25.0GB | 107/131 | `███████░░░░░░░░ 48%` |
| 3 | `reflect.unsafe_NewArray` | 22.15GB | 122/131 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 21.21GB | 118/131 | `██████░░░░░░░░░ 41%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 21.02GB | 124/131 | `██████░░░░░░░░░ 41%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 20.91GB | 123/131 | `██████░░░░░░░░░ 40%` |
| 7 | `reflect.MakeSlice` | 12.53GB | 120/131 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 10.89GB | 107/131 | `███░░░░░░░░░░░░ 21%` |
| 9 | `experiment/local.topologicalSort` | 10.77GB | 119/131 | `███░░░░░░░░░░░░ 21%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 10.64GB | 120/131 | `███░░░░░░░░░░░░ 20%` |

## Alerts

No anomalies detected.
