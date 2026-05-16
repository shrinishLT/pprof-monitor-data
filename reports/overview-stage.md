# Overview: stage
*Last updated: 2026-05-16 23:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T23:31 (59 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,098 | avg: 14,157 | max: 14,653 | trend: INCREASING (+0.58/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃▁▁
```

**Heap InUse** (current: 144.0MB | avg: 142.5MB | max: 201.6MB | trend: stable (+0.14MB/hr))
```
▃▄▁▆▃▃▂▄▅▆▁▂▅▅▁▅▁▁▅▅▂▁▆▆█▄▄▆▃▃▆▆▁▄▅▆▂▅▂▂▃▂▅▂▂▅▂▂▄▅▅▅▆▄▂▂▅▄▄
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 14%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,098 | 14,067 | +31 | 14,157 | 14,653 | INCREASING (+0.58/hr) |
| Heap InUse | 144.0MB | 145.9MB | -1.9MB | 142.5MB | 201.6MB | stable (+0.14MB/hr) |
| Heap Sys | 1012.9MB | 1012.8MB | +0.1MB | 747.9MB | 1016.6MB | |
| Heap Objects | 800,441 | 826,865 | -26424 | 763,130 | 1,341,103 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.0MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `reflect.unsafe_NewArray` | 2.51MB |
| 8 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 41.0GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 19.52GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 19.23GB |
| 4 | `internal/evaluation.mergeMetadata` | 18.78GB |
| 5 | `reflect.unsafe_NewArray` | 17.66GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 16.23GB |
| 7 | `reflect.MakeSlice` | 9.8GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 9.62GB |
| 9 | `experiment/local.topologicalSort` | 9.6GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 7.09GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 57/59 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/59 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 10.25MB | 54/59 | `████░░░░░░░░░░░ 27%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 57/59 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.82MB | 49/59 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/59 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/59 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/59 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.94MB | 43/59 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `compress/flate.NewWriter` | 2.67MB | 49/59 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 18.99GB | 50/59 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 14.76GB | 35/59 | `███████████░░░░ 77%` |
| 3 | `internal/evaluation.mergeMetadata` | 9.4GB | 46/59 | `███████░░░░░░░░ 49%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 8.71GB | 51/59 | `██████░░░░░░░░░ 45%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 8.67GB | 52/59 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 8.23GB | 50/59 | `██████░░░░░░░░░ 43%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 6.45GB | 35/59 | `█████░░░░░░░░░░ 33%` |
| 8 | `reflect.MakeSlice` | 4.78GB | 48/59 | `███░░░░░░░░░░░░ 25%` |
| 9 | `experiment/local.topologicalSort` | 4.72GB | 47/59 | `███░░░░░░░░░░░░ 24%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 4.62GB | 48/59 | `███░░░░░░░░░░░░ 24%` |

## Alerts

No anomalies detected.
