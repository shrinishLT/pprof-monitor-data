# Overview: stage
*Last updated: 2026-05-18 08:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T08:31 (125 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,068 | avg: 14,134 | max: 14,653 | trend: decreasing (-1.04/hr))
```
▁▁▂▁▁▂▅▃█▁▂▁▁▂▂▃▁▁▁▂▁▁▂▁▁▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▆▅▁▁▁▁
```

**Heap InUse** (current: 128.5MB | avg: 148.1MB | max: 277.6MB | trend: stable (+0.25MB/hr))
```
▁▃▄▁▂▃▃▁▃▁▁▁▁▃▁▁▃▁▁▂▃▃▃▄▂▁▁▃▂▂▁▁▁▃▃▂▃▃▃▃▃▄▅▃▄▁▃▃▃▄▃▂▁▂▂▃▂▃▃▁▄▂▂▃▂▃▃▂▁▁▁▃▁▁▂▁▃▄▁▂▄▂▁▂▃▄▁▄▃▂█▄▂▂▁▁
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 12%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,068 | 14,066 | +2 | 14,134 | 14,653 | decreasing (-1.04/hr) |
| Heap InUse | 128.5MB | 109.0MB | +19.5MB | 148.1MB | 277.6MB | stable (+0.25MB/hr) |
| Heap Sys | 1013.1MB | 1013.1MB | +0.0MB | 887.9MB | 1016.6MB | |
| Heap Objects | 618,468 | 356,649 | +261819 | 820,767 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 18 | 14,123 | 155.9MB | 277.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `aws/endpoints.init` | 2.0MB |
| 8 | `compress/flate.NewWriter` | 1.76MB |
| 9 | `segmentio/kafka-go.makePartitions` | 1.5MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 99.97GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 43.83GB |
| 3 | `reflect.unsafe_NewArray` | 43.27GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 38.73GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 38.25GB |
| 6 | `internal/evaluation.mergeMetadata` | 37.31GB |
| 7 | `reflect.MakeSlice` | 24.03GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.05GB |
| 9 | `experiment/local.topologicalSort` | 19.01GB |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 18.93GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 123/125 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/125 | `██████░░░░░░░░░ 42%` |
| 3 | `runtime.mallocgc` | 11.27MB | 120/125 | `████░░░░░░░░░░░ 30%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 123/125 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.92MB | 115/125 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 8.5MB | 2/125 | `███░░░░░░░░░░░░ 23%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/125 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `segmentio/kafka-go.makePartitions` | 3.06MB | 104/125 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `internal/evaluation.mergeMetadata` | 3.0MB | 3/125 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `compress/flate.NewWriter` | 2.82MB | 103/125 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 48.57GB | 116/125 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 23.88GB | 101/125 | `███████░░░░░░░░ 49%` |
| 3 | `reflect.unsafe_NewArray` | 20.99GB | 116/125 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 20.34GB | 112/125 | `██████░░░░░░░░░ 41%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 20.11GB | 118/125 | `██████░░░░░░░░░ 41%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 20.01GB | 117/125 | `██████░░░░░░░░░ 41%` |
| 7 | `reflect.MakeSlice` | 11.89GB | 114/125 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 10.4GB | 101/125 | `███░░░░░░░░░░░░ 21%` |
| 9 | `experiment/local.topologicalSort` | 10.33GB | 113/125 | `███░░░░░░░░░░░░ 21%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 10.2GB | 114/125 | `███░░░░░░░░░░░░ 21%` |

## Alerts

No anomalies detected.
