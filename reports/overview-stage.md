# Overview: stage
*Last updated: 2026-05-18 13:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T13:03 (134 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,070 | avg: 14,131 | max: 14,653 | trend: decreasing (-1.07/hr))
```
▁▂▁▁▂▂▄▁▁▁▂▁▁▃▁▂▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁█▄▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▆▆▁▁▁▁▁▁▁▁▁▁▁▃▁
```

**Heap InUse** (current: 114.8MB | avg: 148.3MB | max: 277.6MB | trend: stable (+0.21MB/hr))
```
▁▁▁▁▃▁▁▃▁▁▂▃▃▃▄▂▁▁▃▂▂▁▁▁▃▃▂▃▃▃▃▃▄▅▃▄▁▃▃▃▄▃▂▁▂▂▃▂▃▃▁▄▂▂▃▂▃▃▂▁▁▁▃▁▁▂▁▃▄▁▂▄▂▁▂▃▄▁▄▃▂█▄▂▂▁▁▄▂▁▁▂▃▃▄▁
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 11%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,070 | 14,269 | -199 | 14,131 | 14,653 | decreasing (-1.07/hr) |
| Heap InUse | 114.8MB | 192.6MB | -77.8MB | 148.3MB | 277.6MB | stable (+0.21MB/hr) |
| Heap Sys | 1013.2MB | 1012.7MB | +0.5MB | 896.3MB | 1016.6MB | |
| Heap Objects | 446,824 | 898,789 | -451965 | 821,371 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 27 | 14,113 | 154.0MB | 277.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 6 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.mapassign_faststr0` | 2.0MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `reflect.unsafe_NewArray` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 108.21GB |
| 2 | `reflect.unsafe_NewArray` | 46.77GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 44.41GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 40.01GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 39.52GB |
| 6 | `internal/evaluation.mergeMetadata` | 38.52GB |
| 7 | `reflect.MakeSlice` | 25.99GB |
| 8 | `experiment/local.topologicalSort` | 19.59GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 19.56GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 19.31GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 132/134 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/134 | `██████░░░░░░░░░ 42%` |
| 3 | `runtime.mallocgc` | 11.32MB | 129/134 | `████░░░░░░░░░░░ 30%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 132/134 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.93MB | 124/134 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 8.5MB | 2/134 | `███░░░░░░░░░░░░ 23%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/134 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `segmentio/kafka-go.makePartitions` | 3.14MB | 112/134 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `internal/evaluation.mergeMetadata` | 3.0MB | 3/134 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `compress/flate.NewWriter` | 2.84MB | 110/134 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 52.6GB | 125/134 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 25.51GB | 110/134 | `███████░░░░░░░░ 48%` |
| 3 | `reflect.unsafe_NewArray` | 22.73GB | 125/134 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 21.63GB | 121/134 | `██████░░░░░░░░░ 41%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 21.46GB | 127/134 | `██████░░░░░░░░░ 40%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 21.34GB | 126/134 | `██████░░░░░░░░░ 40%` |
| 7 | `reflect.MakeSlice` | 12.85GB | 123/134 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 11.11GB | 110/134 | `███░░░░░░░░░░░░ 21%` |
| 9 | `experiment/local.topologicalSort` | 10.98GB | 122/134 | `███░░░░░░░░░░░░ 20%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 10.85GB | 123/134 | `███░░░░░░░░░░░░ 20%` |

## Alerts

No anomalies detected.
