# Overview: stage
*Last updated: 2026-05-17 02:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T02:03 (64 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,066 | avg: 14,150 | max: 14,653 | trend: decreasing (-0.75/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃▁▁▁▁▁▁▁
```

**Heap InUse** (current: 172.1MB | avg: 141.9MB | max: 201.6MB | trend: stable (+0.02MB/hr))
```
▃▄▁▆▃▃▂▄▅▆▁▂▅▅▁▅▁▁▅▅▂▁▆▆█▄▄▆▃▃▆▆▁▄▅▆▂▅▂▂▃▂▅▂▂▅▂▂▄▅▅▅▆▄▂▂▅▄▄▂▃▁▅▆
```

## Current Status

Goroutines: `███████████████████░ 95%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 16%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,066 | 14,064 | +2 | 14,150 | 14,653 | decreasing (-0.75/hr) |
| Heap InUse | 172.1MB | 161.9MB | +10.2MB | 141.9MB | 201.6MB | stable (+0.02MB/hr) |
| Heap Sys | 1012.9MB | 1012.9MB | +0.0MB | 768.6MB | 1016.6MB | |
| Heap Objects | 1,200,936 | 1,097,394 | +103542 | 759,943 | 1,341,103 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 5 | 14,068 | 135.1MB | 172.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 6 | `reflect.mapassign_faststr0` | 3.0MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `compress/flate.NewWriter` | 1.76MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 45.52GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 19.72GB |
| 3 | `reflect.unsafe_NewArray` | 19.62GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 19.42GB |
| 5 | `internal/evaluation.mergeMetadata` | 18.95GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 16.3GB |
| 7 | `reflect.MakeSlice` | 10.88GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 9.72GB |
| 9 | `experiment/local.topologicalSort` | 9.69GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 7.12GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 62/64 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/64 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 10.4MB | 59/64 | `████░░░░░░░░░░░ 28%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 62/64 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.83MB | 54/64 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/64 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/64 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/64 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.95MB | 48/64 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `compress/flate.NewWriter` | 2.65MB | 52/64 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 21.23GB | 55/64 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 14.94GB | 40/64 | `██████████░░░░░ 70%` |
| 3 | `internal/evaluation.mergeMetadata` | 10.33GB | 51/64 | `███████░░░░░░░░ 48%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 9.66GB | 56/64 | `██████░░░░░░░░░ 45%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 9.63GB | 57/64 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 9.2GB | 55/64 | `██████░░░░░░░░░ 43%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 6.53GB | 40/64 | `████░░░░░░░░░░░ 30%` |
| 8 | `reflect.MakeSlice` | 5.32GB | 53/64 | `███░░░░░░░░░░░░ 25%` |
| 9 | `experiment/local.topologicalSort` | 5.19GB | 52/64 | `███░░░░░░░░░░░░ 24%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 5.09GB | 53/64 | `███░░░░░░░░░░░░ 23%` |

## Alerts

No anomalies detected.
