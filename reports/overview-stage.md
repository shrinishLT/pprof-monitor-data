# Overview: stage
*Last updated: 2026-05-17 21:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T21:31 (103 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,073 | avg: 14,139 | max: 14,653 | trend: decreasing (-1.34/hr))
```
▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 110.8MB | avg: 146.7MB | max: 213.6MB | trend: stable (+0.23MB/hr))
```
▃▅▆▁▂▅▄▁▅▁▁▅▅▁▁▆▆▇▃▃▆▂▃▅▆▁▃▅▅▂▄▂▂▂▂▅▂▂▄▂▂▄▄▄▅▆▃▂▂▄▄▃▁▂▁▅▅▄▅▅▅▅▅▆█▄▆▂▅▅▄▆▅▄▁▄▄▅▃▅▅▂▆▃▃▅▃▄▅▃▂▃▁▆▂▂
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,073 | 14,064 | +9 | 14,139 | 14,653 | decreasing (-1.34/hr) |
| Heap InUse | 110.8MB | 110.0MB | +0.8MB | 146.7MB | 213.6MB | stable (+0.23MB/hr) |
| Heap Sys | 1012.3MB | 1013.3MB | -1.0MB | 861.2MB | 1016.6MB | |
| Heap Objects | 413,699 | 397,499 | +16200 | 812,742 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 44 | 14,114 | 152.4MB | 213.6MB |

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
| 9 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 10 | `reflect.unsafe_NewArray` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 80.32GB |
| 2 | `reflect.unsafe_NewArray` | 34.68GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 31.42GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 31.26GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 31.0GB |
| 6 | `internal/evaluation.mergeMetadata` | 30.08GB |
| 7 | `reflect.MakeSlice` | 19.33GB |
| 8 | `experiment/local.topologicalSort` | 15.46GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 15.34GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 13.61GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 101/103 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/103 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 11.08MB | 98/103 | `████░░░░░░░░░░░ 30%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 101/103 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.9MB | 93/103 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/103 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/103 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.25MB | 2/103 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `segmentio/kafka-go.makePartitions` | 3.03MB | 83/103 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `compress/flate.NewWriter` | 2.76MB | 85/103 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 38.73GB | 94/103 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 20.97GB | 79/103 | `████████░░░░░░░ 54%` |
| 3 | `internal/evaluation.mergeMetadata` | 17.28GB | 90/103 | `██████░░░░░░░░░ 44%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 16.86GB | 96/103 | `██████░░░░░░░░░ 43%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 16.81GB | 95/103 | `██████░░░░░░░░░ 43%` |
| 6 | `reflect.unsafe_NewArray` | 16.73GB | 94/103 | `██████░░░░░░░░░ 43%` |
| 7 | `reflect.MakeSlice` | 9.52GB | 92/103 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 9.14GB | 79/103 | `███░░░░░░░░░░░░ 23%` |
| 9 | `experiment/local.topologicalSort` | 8.75GB | 91/103 | `███░░░░░░░░░░░░ 22%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 8.62GB | 92/103 | `███░░░░░░░░░░░░ 22%` |

## Alerts

No anomalies detected.
