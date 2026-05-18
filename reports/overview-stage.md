# Overview: stage
*Last updated: 2026-05-18 13:33 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T13:33 (135 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,176 | avg: 14,132 | max: 14,653 | trend: decreasing (-1.02/hr))
```
▂▁▁▂▂▄▁▁▁▂▁▁▃▁▂▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁█▄▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▆▆▁▁▁▁▁▁▁▁▁▁▁▃▁▂
```

**Heap InUse** (current: 157.5MB | avg: 148.3MB | max: 277.6MB | trend: stable (+0.21MB/hr))
```
▁▁▁▃▁▁▃▁▁▂▃▃▃▄▂▁▁▃▂▂▁▁▁▃▃▂▃▃▃▃▃▄▅▃▄▁▃▃▃▄▃▂▁▂▂▃▂▃▃▁▄▂▂▃▂▃▃▂▁▁▁▃▁▁▂▁▃▄▁▂▄▂▁▂▃▄▁▄▃▂█▄▂▂▁▁▄▂▁▁▂▃▃▄▁▃
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 15%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,176 | 14,070 | +106 | 14,132 | 14,653 | decreasing (-1.02/hr) |
| Heap InUse | 157.5MB | 114.8MB | +42.7MB | 148.3MB | 277.6MB | stable (+0.21MB/hr) |
| Heap Sys | 1013.1MB | 1013.2MB | -0.1MB | 897.2MB | 1016.6MB | |
| Heap Objects | 714,797 | 446,824 | +267973 | 820,581 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 28 | 14,115 | 154.1MB | 277.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.unsafe_NewArray` | 2.01MB |
| 9 | `bytes.growSlice` | 2.01MB |
| 10 | `segmentio/kafka-go.makePartitions` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 109.14GB |
| 2 | `reflect.unsafe_NewArray` | 47.18GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 44.41GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 40.73GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 40.21GB |
| 6 | `internal/evaluation.mergeMetadata` | 39.18GB |
| 7 | `reflect.MakeSlice` | 26.2GB |
| 8 | `experiment/local.topologicalSort` | 19.92GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 19.91GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 19.31GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 133/135 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/135 | `██████░░░░░░░░░ 42%` |
| 3 | `runtime.mallocgc` | 11.33MB | 130/135 | `████░░░░░░░░░░░ 30%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 133/135 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.93MB | 125/135 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 8.5MB | 2/135 | `███░░░░░░░░░░░░ 23%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/135 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `segmentio/kafka-go.makePartitions` | 3.13MB | 113/135 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `internal/evaluation.mergeMetadata` | 3.0MB | 3/135 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `compress/flate.NewWriter` | 2.84MB | 111/135 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 53.05GB | 126/135 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 25.68GB | 111/135 | `███████░░░░░░░░ 48%` |
| 3 | `reflect.unsafe_NewArray` | 22.93GB | 126/135 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 21.77GB | 122/135 | `██████░░░░░░░░░ 41%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 21.61GB | 128/135 | `██████░░░░░░░░░ 40%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 21.48GB | 127/135 | `██████░░░░░░░░░ 40%` |
| 7 | `reflect.MakeSlice` | 12.96GB | 124/135 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 11.19GB | 111/135 | `███░░░░░░░░░░░░ 21%` |
| 9 | `experiment/local.topologicalSort` | 11.05GB | 123/135 | `███░░░░░░░░░░░░ 20%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 10.92GB | 124/135 | `███░░░░░░░░░░░░ 20%` |

## Alerts

No anomalies detected.
