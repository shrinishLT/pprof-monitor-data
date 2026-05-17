# Overview: stage
*Last updated: 2026-05-17 22:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T22:31 (105 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,067 | avg: 14,137 | max: 14,653 | trend: decreasing (-1.42/hr))
```
▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 105.6MB | avg: 146.2MB | max: 213.6MB | trend: stable (+0.15MB/hr))
```
▆▁▂▅▄▁▅▁▁▅▅▁▁▆▆▇▃▃▆▂▃▅▆▁▃▅▅▂▄▂▂▂▂▅▂▂▄▂▂▄▄▄▅▆▃▂▂▄▄▃▁▂▁▅▅▄▅▅▅▅▅▆█▄▆▂▅▅▄▆▅▄▁▄▄▅▃▅▅▂▆▃▃▅▃▄▅▃▂▃▁▆▂▂▃▁
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,067 | 14,064 | +3 | 14,137 | 14,653 | decreasing (-1.42/hr) |
| Heap InUse | 105.6MB | 131.4MB | -25.8MB | 146.2MB | 213.6MB | stable (+0.15MB/hr) |
| Heap Sys | 1014.3MB | 1013.0MB | +1.3MB | 864.1MB | 1016.6MB | |
| Heap Objects | 237,808 | 700,605 | -462797 | 806,198 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 46 | 14,112 | 150.9MB | 213.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.51MB |
| 6 | `compress/flate.NewWriter` | 4.41MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 1.61MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 82.14GB |
| 2 | `reflect.unsafe_NewArray` | 35.53GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 31.47GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 31.26GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 31.05GB |
| 6 | `internal/evaluation.mergeMetadata` | 30.13GB |
| 7 | `reflect.MakeSlice` | 19.74GB |
| 8 | `experiment/local.topologicalSort` | 15.48GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 15.37GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 13.61GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 103/105 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/105 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 11.1MB | 100/105 | `████░░░░░░░░░░░ 30%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 103/105 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.91MB | 95/105 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/105 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/105 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.25MB | 2/105 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `segmentio/kafka-go.makePartitions` | 3.07MB | 85/105 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `compress/flate.NewWriter` | 2.78MB | 87/105 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 39.62GB | 96/105 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 21.22GB | 81/105 | `████████░░░░░░░ 53%` |
| 3 | `internal/evaluation.mergeMetadata` | 17.56GB | 92/105 | `██████░░░░░░░░░ 44%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 17.16GB | 98/105 | `██████░░░░░░░░░ 43%` |
| 5 | `reflect.unsafe_NewArray` | 17.12GB | 96/105 | `██████░░░░░░░░░ 43%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 17.11GB | 97/105 | `██████░░░░░░░░░ 43%` |
| 7 | `reflect.MakeSlice` | 9.73GB | 94/105 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 9.25GB | 81/105 | `███░░░░░░░░░░░░ 23%` |
| 9 | `experiment/local.topologicalSort` | 8.9GB | 93/105 | `███░░░░░░░░░░░░ 22%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 8.76GB | 94/105 | `███░░░░░░░░░░░░ 22%` |

## Alerts

No anomalies detected.
