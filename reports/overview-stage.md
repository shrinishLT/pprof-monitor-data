# Overview: stage
*Last updated: 2026-05-17 02:33 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T02:33 (65 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,082 | avg: 14,149 | max: 14,653 | trend: decreasing (-0.90/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 152.0MB | avg: 142.1MB | max: 201.6MB | trend: stable (+0.05MB/hr))
```
▃▄▁▆▃▃▂▄▅▆▁▂▅▅▁▅▁▁▅▅▂▁▆▆█▄▄▆▃▃▆▆▁▄▅▆▂▅▂▂▃▂▅▂▂▅▂▂▄▅▅▅▆▄▂▂▅▄▄▂▃▁▅▆▄
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 14%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,082 | 14,066 | +16 | 14,149 | 14,653 | decreasing (-0.90/hr) |
| Heap InUse | 152.0MB | 172.1MB | -20.1MB | 142.1MB | 201.6MB | stable (+0.05MB/hr) |
| Heap Sys | 1012.3MB | 1012.9MB | -0.6MB | 772.4MB | 1016.6MB | |
| Heap Objects | 884,784 | 1,200,936 | -316152 | 761,863 | 1,341,103 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 6 | 14,070 | 137.9MB | 172.1MB |

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
| 8 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `net/http.init.func16` | 1.03MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 46.44GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 22.14GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 21.84GB |
| 4 | `internal/evaluation.mergeMetadata` | 21.28GB |
| 5 | `reflect.unsafe_NewArray` | 20.0GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 16.3GB |
| 7 | `reflect.MakeSlice` | 11.09GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 10.93GB |
| 9 | `experiment/local.topologicalSort` | 10.87GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 7.12GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 63/65 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/65 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 10.43MB | 60/65 | `████░░░░░░░░░░░ 28%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 63/65 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.84MB | 55/65 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/65 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/65 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/65 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.93MB | 49/65 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `compress/flate.NewWriter` | 2.65MB | 53/65 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 21.68GB | 56/65 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 14.98GB | 41/65 | `██████████░░░░░ 69%` |
| 3 | `internal/evaluation.mergeMetadata` | 10.54GB | 52/65 | `███████░░░░░░░░ 48%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 9.87GB | 57/65 | `██████░░░░░░░░░ 45%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 9.85GB | 58/65 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 9.39GB | 56/65 | `██████░░░░░░░░░ 43%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 6.55GB | 41/65 | `████░░░░░░░░░░░ 30%` |
| 8 | `reflect.MakeSlice` | 5.43GB | 54/65 | `███░░░░░░░░░░░░ 25%` |
| 9 | `experiment/local.topologicalSort` | 5.3GB | 53/65 | `███░░░░░░░░░░░░ 24%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 5.2GB | 54/65 | `███░░░░░░░░░░░░ 23%` |

## Alerts

No anomalies detected.
