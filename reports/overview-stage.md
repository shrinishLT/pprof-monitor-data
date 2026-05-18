# Overview: stage
*Last updated: 2026-05-18 16:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T16:02 (140 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,216 | avg: 14,133 | max: 14,653 | trend: decreasing (-0.77/hr))
```
▄▁▁▁▂▁▁▃▁▂▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁█▄▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▆▆▁▁▁▁▁▁▁▁▁▁▁▃▁▂▁▂▄▂▂
```

**Heap InUse** (current: 193.6MB | avg: 149.0MB | max: 277.6MB | trend: stable (+0.25MB/hr))
```
▁▃▁▁▂▃▃▃▄▂▁▁▃▂▂▁▁▁▃▃▂▃▃▃▃▃▄▅▃▄▁▃▃▃▄▃▂▁▂▂▃▂▃▃▁▄▂▂▃▂▃▃▂▁▁▁▃▁▁▂▁▃▄▁▂▄▂▁▂▃▄▁▄▃▂█▄▂▂▁▁▄▂▁▁▂▃▃▄▁▃▄▂▁▄▄
```

## Current Status

Goroutines: `███████████████████░ 97%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 19%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,216 | 14,147 | +69 | 14,133 | 14,653 | decreasing (-0.77/hr) |
| Heap InUse | 193.6MB | 184.6MB | +9.0MB | 149.0MB | 277.6MB | stable (+0.25MB/hr) |
| Heap Sys | 1012.8MB | 1012.5MB | +0.3MB | 901.3MB | 1016.6MB | |
| Heap Objects | 1,010,506 | 981,831 | +28675 | 822,949 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 33 | 14,125 | 156.1MB | 277.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `bufio.NewWriterSize` | 1.52MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 113.66GB |
| 2 | `reflect.unsafe_NewArray` | 49.16GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 45.71GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 43.73GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 43.2GB |
| 6 | `internal/evaluation.mergeMetadata` | 42.1GB |
| 7 | `reflect.MakeSlice` | 27.28GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 21.47GB |
| 9 | `experiment/local.topologicalSort` | 21.45GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 19.9GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 138/140 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/140 | `██████░░░░░░░░░ 42%` |
| 3 | `runtime.mallocgc` | 11.36MB | 135/140 | `████░░░░░░░░░░░ 31%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 138/140 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.93MB | 130/140 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 8.5MB | 2/140 | `███░░░░░░░░░░░░ 23%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/140 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `segmentio/kafka-go.makePartitions` | 3.12MB | 118/140 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `internal/evaluation.mergeMetadata` | 3.0MB | 3/140 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `compress/flate.NewWriter` | 2.83MB | 115/140 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 55.3GB | 131/140 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 26.54GB | 116/140 | `███████░░░░░░░░ 47%` |
| 3 | `reflect.unsafe_NewArray` | 23.9GB | 131/140 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 22.53GB | 127/140 | `██████░░░░░░░░░ 40%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 22.39GB | 133/140 | `██████░░░░░░░░░ 40%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 22.26GB | 132/140 | `██████░░░░░░░░░ 40%` |
| 7 | `reflect.MakeSlice` | 13.5GB | 129/140 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 11.56GB | 116/140 | `███░░░░░░░░░░░░ 20%` |
| 9 | `experiment/local.topologicalSort` | 11.43GB | 128/140 | `███░░░░░░░░░░░░ 20%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 11.31GB | 129/140 | `███░░░░░░░░░░░░ 20%` |

## Alerts

No anomalies detected.
