# Overview: stage
*Last updated: 2026-05-18 04:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T04:02 (116 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,163 | avg: 14,132 | max: 14,653 | trend: decreasing (-1.57/hr))
```
▁▁▁▁▇▃▁▁▁▁▁▂▁▁▂▅▃█▁▂▁▁▂▂▃▁▁▁▂▁▁▂▁▁▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂
```

**Heap InUse** (current: 112.0MB | avg: 146.8MB | max: 213.6MB | trend: stable (+0.17MB/hr))
```
▁▁▆▅▇▃▃▅▂▂▅▆▁▃▄▅▁▄▁▂▂▁▄▁▂▄▁▁▄▄▄▄▅▃▁▁▄▃▃▁▂▁▄▅▄▅▄▅▅▄▆█▄▆▂▅▅▄▆▄▃▁▃▄▅▃▄▄▁▅▃▃▅▃▄▅▂▁▂▁▅▁▁▂▁▅▆▁▄▆▃▂▂▅▅▁
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 11%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,163 | 14,064 | +99 | 14,132 | 14,653 | decreasing (-1.57/hr) |
| Heap InUse | 112.0MB | 181.6MB | -69.6MB | 146.8MB | 213.6MB | stable (+0.17MB/hr) |
| Heap Sys | 1013.8MB | 1012.8MB | +1.0MB | 878.2MB | 1016.6MB | |
| Heap Objects | 339,035 | 1,290,015 | -950980 | 817,205 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 9 | 14,080 | 146.6MB | 186.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `reflect.mapassign_faststr0` | 3.0MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 91.99GB |
| 2 | `reflect.unsafe_NewArray` | 39.79GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 34.39GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 33.89GB |
| 5 | `internal/evaluation.mergeMetadata` | 32.94GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 31.26GB |
| 7 | `reflect.MakeSlice` | 22.12GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.94GB |
| 9 | `experiment/local.topologicalSort` | 16.84GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 13.61GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 114/116 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/116 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 11.2MB | 111/116 | `████░░░░░░░░░░░ 30%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 114/116 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.92MB | 106/116 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/116 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/116 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.25MB | 2/116 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `segmentio/kafka-go.makePartitions` | 3.05MB | 96/116 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `compress/flate.NewWriter` | 2.8MB | 97/116 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 44.54GB | 107/116 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 22.42GB | 92/116 | `███████░░░░░░░░ 50%` |
| 3 | `reflect.unsafe_NewArray` | 19.25GB | 107/116 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 19.01GB | 103/116 | `██████░░░░░░░░░ 42%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 18.71GB | 109/116 | `██████░░░░░░░░░ 42%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 18.63GB | 108/116 | `██████░░░░░░░░░ 41%` |
| 7 | `reflect.MakeSlice` | 10.92GB | 105/116 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 9.77GB | 92/116 | `███░░░░░░░░░░░░ 21%` |
| 9 | `experiment/local.topologicalSort` | 9.65GB | 104/116 | `███░░░░░░░░░░░░ 21%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 9.51GB | 105/116 | `███░░░░░░░░░░░░ 21%` |

## Alerts

No anomalies detected.
