# Overview: stage
*Last updated: 2026-05-16 15:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T15:02 (42 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,069 | avg: 14,161 | max: 14,653 | trend: INCREASING (+3.57/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁
```

**Heap InUse** (current: 111.3MB | avg: 142.4MB | max: 201.6MB | trend: stable (+0.27MB/hr))
```
▃▄▁▆▃▃▂▄▅▆▁▂▅▅▁▅▁▁▅▅▂▁▆▆█▄▄▆▃▃▆▆▁▄▅▆▂▅▂▂▃▂
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,069 | 14,120 | -51 | 14,161 | 14,653 | INCREASING (+3.57/hr) |
| Heap InUse | 111.3MB | 125.0MB | -13.7MB | 142.4MB | 201.6MB | stable (+0.27MB/hr) |
| Heap Sys | 1012.1MB | 1012.1MB | +0.0MB | 640.8MB | 1016.6MB | |
| Heap Objects | 420,345 | 538,798 | -118453 | 779,461 | 1,341,103 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 32 | 14,157 | 142.3MB | 201.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `reflect.mapassign_faststr0` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 25.61GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 15.75GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 11.69GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 11.5GB |
| 5 | `internal/evaluation.mergeMetadata` | 11.3GB |
| 6 | `reflect.unsafe_NewArray` | 11.14GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 6.88GB |
| 8 | `reflect.MakeSlice` | 6.25GB |
| 9 | `experiment/local.topologicalSort` | 5.77GB |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 5.7GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 40/42 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/42 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 9.4MB | 37/42 | `███░░░░░░░░░░░░ 25%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.23MB | 40/42 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.72MB | 32/42 | `███░░░░░░░░░░░░ 23%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/42 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/42 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `reflect.unsafe_New` | 3.0MB | 1/42 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.82MB | 27/42 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `compress/flate.NewWriter` | 2.63MB | 35/42 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 13.41GB | 18/42 | `███████████████ 100%` |
| 2 | `segmentio/kafka-go.makePartitions` | 11.38GB | 33/42 | `████████████░░░ 84%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 5.86GB | 18/42 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 5.67GB | 29/42 | `██████░░░░░░░░░ 42%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 4.98GB | 34/42 | `█████░░░░░░░░░░ 37%` |
| 6 | `reflect.unsafe_NewArray` | 4.97GB | 33/42 | `█████░░░░░░░░░░ 37%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 4.91GB | 35/42 | `█████░░░░░░░░░░ 36%` |
| 8 | `reflect.MakeSlice` | 2.95GB | 31/42 | `███░░░░░░░░░░░░ 21%` |
| 9 | `experiment/local.topologicalSort` | 2.81GB | 30/42 | `███░░░░░░░░░░░░ 20%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 2.73GB | 31/42 | `███░░░░░░░░░░░░ 20%` |

## Alerts

No anomalies detected.
