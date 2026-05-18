# Overview: stage
*Last updated: 2026-05-18 10:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T10:31 (129 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,071 | avg: 14,132 | max: 14,653 | trend: decreasing (-1.12/hr))
```
▁▂▅▃█▁▂▁▁▂▂▃▁▁▁▂▁▁▂▁▁▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▆▅▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 125.2MB | avg: 147.9MB | max: 277.6MB | trend: stable (+0.21MB/hr))
```
▂▃▃▁▃▁▁▁▁▃▁▁▃▁▁▂▃▃▃▄▂▁▁▃▂▂▁▁▁▃▃▂▃▃▃▃▃▄▅▃▄▁▃▃▃▄▃▂▁▂▂▃▂▃▃▁▄▂▂▃▂▃▃▂▁▁▁▃▁▁▂▁▃▄▁▂▄▂▁▂▃▄▁▄▃▂█▄▂▂▁▁▄▂▁▁
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 12%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,071 | 14,071 | +0 | 14,132 | 14,653 | decreasing (-1.12/hr) |
| Heap InUse | 125.2MB | 112.0MB | +13.2MB | 147.9MB | 277.6MB | stable (+0.21MB/hr) |
| Heap Sys | 1013.1MB | 1013.1MB | +0.0MB | 891.8MB | 1016.6MB | |
| Heap Objects | 564,351 | 410,318 | +154033 | 819,248 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 22 | 14,114 | 153.4MB | 277.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.5MB |
| 6 | `compress/flate.NewWriter` | 3.53MB |
| 7 | `reflect.mapassign_faststr0` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 103.59GB |
| 2 | `reflect.unsafe_NewArray` | 44.77GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 43.83GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 38.85GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 38.36GB |
| 6 | `internal/evaluation.mergeMetadata` | 37.42GB |
| 7 | `reflect.MakeSlice` | 24.89GB |
| 8 | `experiment/local.topologicalSort` | 19.07GB |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 19.05GB |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 19.0GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 127/129 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/129 | `██████░░░░░░░░░ 42%` |
| 3 | `runtime.mallocgc` | 11.29MB | 124/129 | `████░░░░░░░░░░░ 30%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 127/129 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.92MB | 119/129 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 8.5MB | 2/129 | `███░░░░░░░░░░░░ 23%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/129 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `segmentio/kafka-go.makePartitions` | 3.1MB | 107/129 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `internal/evaluation.mergeMetadata` | 3.0MB | 3/129 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `compress/flate.NewWriter` | 2.82MB | 107/129 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 50.36GB | 120/129 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 24.64GB | 105/129 | `███████░░░░░░░░ 48%` |
| 3 | `reflect.unsafe_NewArray` | 21.77GB | 120/129 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 20.93GB | 116/129 | `██████░░░░░░░░░ 41%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 20.73GB | 122/129 | `██████░░░░░░░░░ 41%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 20.62GB | 121/129 | `██████░░░░░░░░░ 40%` |
| 7 | `reflect.MakeSlice` | 12.32GB | 118/129 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 10.73GB | 105/129 | `███░░░░░░░░░░░░ 21%` |
| 9 | `experiment/local.topologicalSort` | 10.62GB | 117/129 | `███░░░░░░░░░░░░ 21%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 10.5GB | 118/129 | `███░░░░░░░░░░░░ 20%` |

## Alerts

No anomalies detected.
