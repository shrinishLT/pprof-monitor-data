# Overview: stage
*Last updated: 2026-05-18 14:33 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T14:33 (137 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,140 | avg: 14,131 | max: 14,653 | trend: decreasing (-1.01/hr))
```
▁▂▂▄▁▁▁▂▁▁▃▁▂▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁█▄▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▆▆▁▁▁▁▁▁▁▁▁▁▁▃▁▂▁▂
```

**Heap InUse** (current: 138.5MB | avg: 148.6MB | max: 277.6MB | trend: stable (+0.22MB/hr))
```
▁▃▁▁▃▁▁▂▃▃▃▄▂▁▁▃▂▂▁▁▁▃▃▂▃▃▃▃▃▄▅▃▄▁▃▃▃▄▃▂▁▂▂▃▂▃▃▁▄▂▂▃▂▃▃▂▁▁▁▃▁▁▂▁▃▄▁▂▄▂▁▂▃▄▁▄▃▂█▄▂▂▁▁▄▂▁▁▂▃▃▄▁▃▄▂
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 13%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,140 | 14,074 | +66 | 14,131 | 14,653 | decreasing (-1.01/hr) |
| Heap InUse | 138.5MB | 190.8MB | -52.3MB | 148.6MB | 277.6MB | stable (+0.22MB/hr) |
| Heap Sys | 1013.4MB | 1013.3MB | +0.1MB | 898.9MB | 1016.6MB | |
| Heap Objects | 605,948 | 1,374,627 | -768679 | 823,059 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 30 | 14,114 | 154.8MB | 277.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 6 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `compress/flate.NewWriter` | 1.76MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 1.6MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 110.95GB |
| 2 | `reflect.unsafe_NewArray` | 47.98GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 45.02GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 41.94GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 41.38GB |
| 6 | `internal/evaluation.mergeMetadata` | 40.3GB |
| 7 | `reflect.MakeSlice` | 26.61GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 20.54GB |
| 9 | `experiment/local.topologicalSort` | 20.5GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 19.57GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 135/137 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/137 | `██████░░░░░░░░░ 42%` |
| 3 | `runtime.mallocgc` | 11.34MB | 132/137 | `████░░░░░░░░░░░ 30%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 135/137 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.93MB | 127/137 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 8.5MB | 2/137 | `███░░░░░░░░░░░░ 23%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/137 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `segmentio/kafka-go.makePartitions` | 3.12MB | 115/137 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `internal/evaluation.mergeMetadata` | 3.0MB | 3/137 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `compress/flate.NewWriter` | 2.84MB | 113/137 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 53.95GB | 128/137 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 26.03GB | 113/137 | `███████░░░░░░░░ 48%` |
| 3 | `reflect.unsafe_NewArray` | 23.32GB | 128/137 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 22.07GB | 124/137 | `██████░░░░░░░░░ 40%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 21.91GB | 130/137 | `██████░░░░░░░░░ 40%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 21.79GB | 129/137 | `██████░░░░░░░░░ 40%` |
| 7 | `reflect.MakeSlice` | 13.18GB | 126/137 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 11.34GB | 113/137 | `███░░░░░░░░░░░░ 21%` |
| 9 | `experiment/local.topologicalSort` | 11.2GB | 125/137 | `███░░░░░░░░░░░░ 20%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 11.07GB | 126/137 | `███░░░░░░░░░░░░ 20%` |

## Alerts

No anomalies detected.
