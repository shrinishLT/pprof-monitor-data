# Overview: stage
*Last updated: 2026-05-17 03:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T03:01 (66 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,439 | avg: 14,153 | max: 14,653 | trend: stable (-0.08/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃▁▁▁▁▁▁▁▁▅
```

**Heap InUse** (current: 170.8MB | avg: 142.5MB | max: 201.6MB | trend: stable (+0.13MB/hr))
```
▃▄▁▆▃▃▂▄▅▆▁▂▅▅▁▅▁▁▅▅▂▁▆▆█▄▄▆▃▃▆▆▁▄▅▆▂▅▂▂▃▂▅▂▂▅▂▂▄▅▅▅▆▄▂▂▅▄▄▂▃▁▅▆▄▆
```

## Current Status

Goroutines: `███████████████████░ 98%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 16%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,439 | 14,082 | +357 | 14,153 | 14,653 | stable (-0.08/hr) |
| Heap InUse | 170.8MB | 152.0MB | +18.8MB | 142.5MB | 201.6MB | stable (+0.13MB/hr) |
| Heap Sys | 1012.5MB | 1012.3MB | +0.2MB | 776.0MB | 1016.6MB | |
| Heap Objects | 749,984 | 884,784 | -134800 | 761,683 | 1,341,103 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 7 | 14,123 | 142.6MB | 172.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `reflect.mapassign_faststr0` | 3.0MB |
| 6 | `bufio.NewReaderSize` | 2.51MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `bytes.growSlice` | 2.01MB |
| 10 | `segmentio/kafka-go.makePartitions` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 47.32GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 22.58GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 22.3GB |
| 4 | `internal/evaluation.mergeMetadata` | 21.71GB |
| 5 | `reflect.unsafe_NewArray` | 20.36GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 16.3GB |
| 7 | `reflect.MakeSlice` | 11.31GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 11.16GB |
| 9 | `experiment/local.topologicalSort` | 11.1GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 7.12GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 64/66 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/66 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 10.46MB | 61/66 | `████░░░░░░░░░░░ 28%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 64/66 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.84MB | 56/66 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/66 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/66 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/66 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.91MB | 50/66 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `compress/flate.NewWriter` | 2.65MB | 53/66 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 22.13GB | 57/66 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 15.01GB | 42/66 | `██████████░░░░░ 67%` |
| 3 | `internal/evaluation.mergeMetadata` | 10.75GB | 53/66 | `███████░░░░░░░░ 48%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 10.09GB | 58/66 | `██████░░░░░░░░░ 45%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 10.06GB | 59/66 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 9.58GB | 57/66 | `██████░░░░░░░░░ 43%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 6.56GB | 42/66 | `████░░░░░░░░░░░ 29%` |
| 8 | `reflect.MakeSlice` | 5.53GB | 55/66 | `███░░░░░░░░░░░░ 24%` |
| 9 | `experiment/local.topologicalSort` | 5.4GB | 54/66 | `███░░░░░░░░░░░░ 24%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 5.31GB | 55/66 | `███░░░░░░░░░░░░ 23%` |

## Alerts

No anomalies detected.
