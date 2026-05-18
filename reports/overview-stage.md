# Overview: stage
*Last updated: 2026-05-18 12:33 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T12:33 (133 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,269 | avg: 14,132 | max: 14,653 | trend: decreasing (-1.06/hr))
```
█▁▂▁▁▂▂▃▁▁▁▂▁▁▂▁▁▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▆▅▁▁▁▁▁▁▁▁▁▁▁▃
```

**Heap InUse** (current: 192.6MB | avg: 148.5MB | max: 277.6MB | trend: stable (+0.24MB/hr))
```
▃▁▁▁▁▃▁▁▃▁▁▂▃▃▃▄▂▁▁▃▂▂▁▁▁▃▃▂▃▃▃▃▃▄▅▃▄▁▃▃▃▄▃▂▁▂▂▃▂▃▃▁▄▂▂▃▂▃▃▂▁▁▁▃▁▁▂▁▃▄▁▂▄▂▁▂▃▄▁▄▃▂█▄▂▂▁▁▄▂▁▁▂▃▃▄
```

## Current Status

Goroutines: `███████████████████░ 97%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 18%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,269 | 14,064 | +205 | 14,132 | 14,653 | decreasing (-1.06/hr) |
| Heap InUse | 192.6MB | 168.2MB | +24.4MB | 148.5MB | 277.6MB | stable (+0.24MB/hr) |
| Heap Sys | 1012.7MB | 1013.1MB | -0.4MB | 895.4MB | 1016.6MB | |
| Heap Objects | 898,789 | 1,131,404 | -232615 | 824,187 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 26 | 14,114 | 155.5MB | 277.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.51MB |
| 6 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `bytes.growSlice` | 1.51MB |
| 10 | `reflect.mapassign_faststr0` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 107.33GB |
| 2 | `reflect.unsafe_NewArray` | 46.37GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 43.83GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 39.53GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 39.01GB |
| 6 | `internal/evaluation.mergeMetadata` | 38.05GB |
| 7 | `reflect.MakeSlice` | 25.78GB |
| 8 | `experiment/local.topologicalSort` | 19.36GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 19.33GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 19.05GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 131/133 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/133 | `██████░░░░░░░░░ 42%` |
| 3 | `runtime.mallocgc` | 11.32MB | 128/133 | `████░░░░░░░░░░░ 30%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 131/133 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.93MB | 123/133 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 8.5MB | 2/133 | `███░░░░░░░░░░░░ 23%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/133 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `segmentio/kafka-go.makePartitions` | 3.14MB | 111/133 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `internal/evaluation.mergeMetadata` | 3.0MB | 3/133 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `compress/flate.NewWriter` | 2.84MB | 110/133 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 52.15GB | 124/133 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 25.34GB | 109/133 | `███████░░░░░░░░ 48%` |
| 3 | `reflect.unsafe_NewArray` | 22.54GB | 124/133 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 21.49GB | 120/133 | `██████░░░░░░░░░ 41%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 21.31GB | 126/133 | `██████░░░░░░░░░ 40%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 21.19GB | 125/133 | `██████░░░░░░░░░ 40%` |
| 7 | `reflect.MakeSlice` | 12.75GB | 122/133 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 11.04GB | 109/133 | `███░░░░░░░░░░░░ 21%` |
| 9 | `experiment/local.topologicalSort` | 10.91GB | 121/133 | `███░░░░░░░░░░░░ 20%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 10.78GB | 122/133 | `███░░░░░░░░░░░░ 20%` |

## Alerts

No anomalies detected.
