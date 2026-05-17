# Overview: stage
*Last updated: 2026-05-18 01:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T01:31 (111 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,067 | avg: 14,133 | max: 14,653 | trend: decreasing (-1.58/hr))
```
▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▂▅▃█▁▂▁▁▂▂▃▁▁▁▂▁▁▂▁▁▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 150.8MB | avg: 146.9MB | max: 213.6MB | trend: stable (+0.20MB/hr))
```
▄▁▁▅▅▁▁▆▅▇▃▃▅▂▂▅▆▁▃▄▅▂▄▁▂▂▁▄▁▂▄▁▁▄▄▄▅▅▃▁▂▄▃▃▁▂▁▄▅▄▅▄▅▅▄▆█▄▆▂▅▅▄▆▄▄▁▃▄▅▃▅▄▁▅▃▃▅▃▄▅▂▁▂▁▅▁▁▂▁▅▆▁▄▆▄
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 14%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,067 | 14,073 | -6 | 14,133 | 14,653 | decreasing (-1.58/hr) |
| Heap InUse | 150.8MB | 186.8MB | -36.0MB | 146.9MB | 213.6MB | stable (+0.20MB/hr) |
| Heap Sys | 1013.3MB | 1013.3MB | +0.0MB | 872.1MB | 1016.6MB | |
| Heap Objects | 941,742 | 1,370,912 | -429170 | 818,334 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 4 | 14,068 | 149.4MB | 186.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 6 | `reflect.unsafe_NewArray` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `reflect.mapassign_faststr0` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 87.46GB |
| 2 | `reflect.unsafe_NewArray` | 37.85GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 31.59GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 31.26GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 31.15GB |
| 6 | `internal/evaluation.mergeMetadata` | 30.23GB |
| 7 | `reflect.MakeSlice` | 21.02GB |
| 8 | `experiment/local.topologicalSort` | 15.53GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 15.43GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 13.61GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 109/111 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/111 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 11.16MB | 106/111 | `████░░░░░░░░░░░ 30%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 109/111 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.91MB | 101/111 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/111 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/111 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.25MB | 2/111 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `segmentio/kafka-go.makePartitions` | 3.06MB | 91/111 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `compress/flate.NewWriter` | 2.78MB | 92/111 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 42.31GB | 102/111 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 21.91GB | 87/111 | `███████░░░░░░░░ 51%` |
| 3 | `internal/evaluation.mergeMetadata` | 18.33GB | 98/111 | `██████░░░░░░░░░ 43%` |
| 4 | `reflect.unsafe_NewArray` | 18.28GB | 102/111 | `██████░░░░░░░░░ 43%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 17.99GB | 104/111 | `██████░░░░░░░░░ 42%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 17.92GB | 103/111 | `██████░░░░░░░░░ 42%` |
| 7 | `reflect.MakeSlice` | 10.38GB | 100/111 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 9.55GB | 87/111 | `███░░░░░░░░░░░░ 22%` |
| 9 | `experiment/local.topologicalSort` | 9.3GB | 99/111 | `███░░░░░░░░░░░░ 21%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 9.16GB | 100/111 | `███░░░░░░░░░░░░ 21%` |

## Alerts

No anomalies detected.
