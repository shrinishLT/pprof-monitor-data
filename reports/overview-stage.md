# Overview: stage
*Last updated: 2026-05-18 07:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T07:01 (122 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,095 | avg: 14,136 | max: 14,653 | trend: decreasing (-0.96/hr))
```
▁▁▁▁▁▂▁▁▂▅▃█▁▂▁▁▂▂▃▁▁▁▂▁▁▂▁▁▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▆▅▁
```

**Heap InUse** (current: 135.3MB | avg: 148.6MB | max: 277.6MB | trend: stable (+0.31MB/hr))
```
▂▄▁▁▃▄▁▂▃▃▁▃▁▁▁▁▃▁▁▃▁▁▂▃▃▃▄▂▁▁▃▂▂▁▁▁▃▃▂▃▃▃▃▃▄▅▃▄▁▃▃▃▄▃▂▁▂▂▃▂▃▃▁▄▂▂▃▂▃▃▂▁▁▁▃▁▁▂▁▃▄▁▂▄▂▁▂▃▄▁▄▃▂█▄▂
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 13%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,095 | 14,469 | -374 | 14,136 | 14,653 | decreasing (-0.96/hr) |
| Heap InUse | 135.3MB | 188.5MB | -53.2MB | 148.6MB | 277.6MB | stable (+0.31MB/hr) |
| Heap Sys | 1013.1MB | 1013.0MB | +0.1MB | 884.8MB | 1016.6MB | |
| Heap Objects | 679,153 | 944,678 | -265525 | 825,643 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 15 | 14,134 | 161.3MB | 277.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `reflect.unsafe_NewArray` | 2.5MB |
| 6 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `reflect.mapassign_faststr0` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 97.31GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 43.83GB |
| 3 | `reflect.unsafe_NewArray` | 42.15GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 38.6GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 38.11GB |
| 6 | `internal/evaluation.mergeMetadata` | 37.15GB |
| 7 | `reflect.MakeSlice` | 23.39GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.05GB |
| 9 | `experiment/local.topologicalSort` | 18.93GB |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 18.86GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 120/122 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/122 | `██████░░░░░░░░░ 42%` |
| 3 | `runtime.mallocgc` | 11.24MB | 117/122 | `████░░░░░░░░░░░ 30%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 120/122 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.92MB | 112/122 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 8.5MB | 2/122 | `███░░░░░░░░░░░░ 23%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/122 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `segmentio/kafka-go.makePartitions` | 3.06MB | 102/122 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `internal/evaluation.mergeMetadata` | 3.0MB | 3/122 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `compress/flate.NewWriter` | 2.82MB | 100/122 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 47.23GB | 113/122 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 23.27GB | 98/122 | `███████░░░░░░░░ 49%` |
| 3 | `reflect.unsafe_NewArray` | 20.41GB | 113/122 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 19.88GB | 109/122 | `██████░░░░░░░░░ 42%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 19.63GB | 115/122 | `██████░░░░░░░░░ 41%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 19.53GB | 114/122 | `██████░░░░░░░░░ 41%` |
| 7 | `reflect.MakeSlice` | 11.56GB | 111/122 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 10.14GB | 98/122 | `███░░░░░░░░░░░░ 21%` |
| 9 | `experiment/local.topologicalSort` | 10.09GB | 110/122 | `███░░░░░░░░░░░░ 21%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 9.96GB | 111/122 | `███░░░░░░░░░░░░ 21%` |

## Alerts

No anomalies detected.
