# Overview: stage
*Last updated: 2026-05-18 16:33 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T16:33 (141 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,406 | avg: 14,135 | max: 14,653 | trend: decreasing (-0.59/hr))
```
▁▁▁▂▁▁▃▁▂▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁█▄▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▆▆▁▁▁▁▁▁▁▁▁▁▁▃▁▂▁▂▄▂▂▅
```

**Heap InUse** (current: 159.7MB | avg: 149.1MB | max: 277.6MB | trend: stable (+0.25MB/hr))
```
▃▁▁▂▃▃▃▄▂▁▁▃▂▂▁▁▁▃▃▂▃▃▃▃▃▄▅▃▄▁▃▃▃▄▃▂▁▂▂▃▂▃▃▁▄▂▂▃▂▃▃▂▁▁▁▃▁▁▂▁▃▄▁▂▄▂▁▂▃▄▁▄▃▂█▄▂▂▁▁▄▂▁▁▂▃▃▄▁▃▄▂▁▄▄▃
```

## Current Status

Goroutines: `███████████████████░ 98%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 15%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,406 | 14,216 | +190 | 14,135 | 14,653 | decreasing (-0.59/hr) |
| Heap InUse | 159.7MB | 193.6MB | -33.9MB | 149.1MB | 277.6MB | stable (+0.25MB/hr) |
| Heap Sys | 1012.6MB | 1012.8MB | -0.2MB | 902.1MB | 1016.6MB | |
| Heap Objects | 683,702 | 1,010,506 | -326804 | 821,962 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 34 | 14,133 | 156.2MB | 277.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `reflect.mapassign_faststr0` | 3.5MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `bytes.growSlice` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 114.58GB |
| 2 | `reflect.unsafe_NewArray` | 49.58GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 46.39GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 45.17GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 44.66GB |
| 6 | `internal/evaluation.mergeMetadata` | 43.51GB |
| 7 | `reflect.MakeSlice` | 27.5GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 22.2GB |
| 9 | `experiment/local.topologicalSort` | 22.16GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.18GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 139/141 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/141 | `██████░░░░░░░░░ 42%` |
| 3 | `runtime.mallocgc` | 11.36MB | 136/141 | `████░░░░░░░░░░░ 31%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 139/141 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.93MB | 131/141 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 8.5MB | 2/141 | `███░░░░░░░░░░░░ 23%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/141 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `segmentio/kafka-go.makePartitions` | 3.12MB | 119/141 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `internal/evaluation.mergeMetadata` | 3.0MB | 3/141 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `compress/flate.NewWriter` | 2.83MB | 115/141 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 55.74GB | 132/141 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 26.7GB | 117/141 | `███████░░░░░░░░ 47%` |
| 3 | `reflect.unsafe_NewArray` | 24.09GB | 132/141 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 22.69GB | 128/141 | `██████░░░░░░░░░ 40%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 22.56GB | 134/141 | `██████░░░░░░░░░ 40%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 22.43GB | 133/141 | `██████░░░░░░░░░ 40%` |
| 7 | `reflect.MakeSlice` | 13.61GB | 130/141 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 11.63GB | 117/141 | `███░░░░░░░░░░░░ 20%` |
| 9 | `experiment/local.topologicalSort` | 11.52GB | 129/141 | `███░░░░░░░░░░░░ 20%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 11.39GB | 130/141 | `███░░░░░░░░░░░░ 20%` |

## Alerts

No anomalies detected.
