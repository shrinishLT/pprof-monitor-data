# Overview: stage
*Last updated: 2026-05-18 02:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T02:03 (112 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,069 | avg: 14,133 | max: 14,653 | trend: decreasing (-1.60/hr))
```
▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▂▅▃█▁▂▁▁▂▂▃▁▁▁▂▁▁▂▁▁▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 126.5MB | avg: 146.7MB | max: 213.6MB | trend: stable (+0.18MB/hr))
```
▁▁▅▅▁▁▆▅▇▃▃▅▂▂▅▆▁▃▄▅▂▄▁▂▂▁▄▁▂▄▁▁▄▄▄▅▅▃▁▂▄▃▃▁▂▁▄▅▄▅▄▅▅▄▆█▄▆▂▅▅▄▆▄▄▁▃▄▅▃▅▄▁▅▃▃▅▃▄▅▂▁▂▁▅▁▁▂▁▅▆▁▄▆▄▂
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 12%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,069 | 14,067 | +2 | 14,133 | 14,653 | decreasing (-1.60/hr) |
| Heap InUse | 126.5MB | 150.8MB | -24.3MB | 146.7MB | 213.6MB | stable (+0.18MB/hr) |
| Heap Sys | 1013.3MB | 1013.3MB | +0.0MB | 873.4MB | 1016.6MB | |
| Heap Objects | 596,544 | 941,742 | -345198 | 816,353 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 5 | 14,069 | 144.9MB | 186.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `reflect.unsafe_NewArray` | 3.0MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 88.41GB |
| 2 | `reflect.unsafe_NewArray` | 38.25GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 31.62GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 31.26GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 31.18GB |
| 6 | `internal/evaluation.mergeMetadata` | 30.26GB |
| 7 | `reflect.MakeSlice` | 21.25GB |
| 8 | `experiment/local.topologicalSort` | 15.54GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 15.44GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 13.61GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 110/112 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/112 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 11.17MB | 107/112 | `████░░░░░░░░░░░ 30%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 110/112 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.91MB | 102/112 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/112 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/112 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.25MB | 2/112 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `segmentio/kafka-go.makePartitions` | 3.05MB | 92/112 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `compress/flate.NewWriter` | 2.78MB | 93/112 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 42.75GB | 103/112 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 22.02GB | 88/112 | `███████░░░░░░░░ 51%` |
| 3 | `reflect.unsafe_NewArray` | 18.47GB | 103/112 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 18.45GB | 99/112 | `██████░░░░░░░░░ 43%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 18.12GB | 105/112 | `██████░░░░░░░░░ 42%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 18.05GB | 104/112 | `██████░░░░░░░░░ 42%` |
| 7 | `reflect.MakeSlice` | 10.49GB | 101/112 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 9.6GB | 88/112 | `███░░░░░░░░░░░░ 22%` |
| 9 | `experiment/local.topologicalSort` | 9.36GB | 100/112 | `███░░░░░░░░░░░░ 21%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 9.22GB | 101/112 | `███░░░░░░░░░░░░ 21%` |

## Alerts

No anomalies detected.
