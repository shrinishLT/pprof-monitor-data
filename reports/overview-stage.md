# Overview: stage
*Last updated: 2026-05-18 08:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T08:02 (124 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,066 | avg: 14,135 | max: 14,653 | trend: decreasing (-1.01/hr))
```
▁▁▁▂▁▁▂▅▃█▁▂▁▁▂▂▃▁▁▁▂▁▁▂▁▁▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▆▅▁▁▁
```

**Heap InUse** (current: 109.0MB | avg: 148.3MB | max: 277.6MB | trend: stable (+0.27MB/hr))
```
▁▁▃▄▁▂▃▃▁▃▁▁▁▁▃▁▁▃▁▁▂▃▃▃▄▂▁▁▃▂▂▁▁▁▃▃▂▃▃▃▃▃▄▅▃▄▁▃▃▃▄▃▂▁▂▂▃▂▃▃▁▄▂▂▃▂▃▃▂▁▁▁▃▁▁▂▁▃▄▁▂▄▂▁▂▃▄▁▄▃▂█▄▂▂▁
```

## Current Status

Goroutines: `███████████████████░ 95%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,066 | 14,076 | -10 | 14,135 | 14,653 | decreasing (-1.01/hr) |
| Heap InUse | 109.0MB | 150.3MB | -41.3MB | 148.3MB | 277.6MB | stable (+0.27MB/hr) |
| Heap Sys | 1013.1MB | 1013.1MB | +0.0MB | 886.9MB | 1016.6MB | |
| Heap Objects | 356,649 | 892,417 | -535768 | 822,399 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 17 | 14,126 | 157.6MB | 277.6MB |

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
| 10 | `reflect.unsafe_NewArray` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 99.16GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 43.83GB |
| 3 | `reflect.unsafe_NewArray` | 42.91GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 38.68GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 38.2GB |
| 6 | `internal/evaluation.mergeMetadata` | 37.25GB |
| 7 | `reflect.MakeSlice` | 23.83GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.05GB |
| 9 | `experiment/local.topologicalSort` | 18.99GB |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 18.91GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 122/124 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/124 | `██████░░░░░░░░░ 42%` |
| 3 | `runtime.mallocgc` | 11.26MB | 119/124 | `████░░░░░░░░░░░ 30%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 122/124 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.92MB | 114/124 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 8.5MB | 2/124 | `███░░░░░░░░░░░░ 23%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/124 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `segmentio/kafka-go.makePartitions` | 3.07MB | 103/124 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `internal/evaluation.mergeMetadata` | 3.0MB | 3/124 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `compress/flate.NewWriter` | 2.83MB | 102/124 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 48.12GB | 115/124 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 23.68GB | 100/124 | `███████░░░░░░░░ 49%` |
| 3 | `reflect.unsafe_NewArray` | 20.8GB | 115/124 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 20.19GB | 111/124 | `██████░░░░░░░░░ 41%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 19.95GB | 117/124 | `██████░░░░░░░░░ 41%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 19.85GB | 116/124 | `██████░░░░░░░░░ 41%` |
| 7 | `reflect.MakeSlice` | 11.78GB | 113/124 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 10.32GB | 100/124 | `███░░░░░░░░░░░░ 21%` |
| 9 | `experiment/local.topologicalSort` | 10.25GB | 112/124 | `███░░░░░░░░░░░░ 21%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 10.12GB | 113/124 | `███░░░░░░░░░░░░ 21%` |

## Alerts

No anomalies detected.
