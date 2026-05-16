# Overview: stage
*Last updated: 2026-05-16 06:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T06:02 (25 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,602 | avg: 14,151 | max: 14,602 | trend: INCREASING (+3.42/hr))
```
▁▁▁▁▁▅▅▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁█
```

**Heap InUse** (current: 201.6MB | avg: 142.0MB | max: 201.6MB | trend: INCREASING (+2.09MB/hr))
```
▃▄▁▆▃▃▂▄▅▆▁▂▅▅▁▅▁▁▅▅▂▁▆▆█
```

## Current Status

Goroutines: `████████████████████ 100%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 19%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,602 | 14,065 | +537 | 14,151 | 14,602 | INCREASING (+3.42/hr) |
| Heap InUse | 201.6MB | 180.3MB | +21.3MB | 142.0MB | 201.6MB | INCREASING (+2.09MB/hr) |
| Heap Sys | 1016.6MB | 604.9MB | +411.7MB | 387.9MB | 1016.6MB | |
| Heap Objects | 838,813 | 1,294,129 | -455316 | 797,627 | 1,341,103 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 15 | 14,135 | 141.4MB | 201.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB |
| 3 | `runtime.mallocgc` | 12.1MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 6 | `database/sql.convertAssignRows` | 7.0MB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB |
| 8 | `bytes.growSlice` | 4.02MB |
| 9 | `bufio.NewWriterSize` | 2.51MB |
| 10 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 9.62GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 6.19GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 4.56GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 4.49GB |
| 5 | `internal/evaluation.mergeMetadata` | 4.42GB |
| 6 | `reflect.unsafe_NewArray` | 4.21GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 2.74GB |
| 8 | `reflect.MakeSlice` | 2.35GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 2.32GB |
| 10 | `experiment/local.topologicalSort` | 2.28GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 23/25 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/25 | `█████░░░░░░░░░░ 39%` |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.21MB | 23/25 | `███░░░░░░░░░░░░ 25%` |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.4MB | 15/25 | `███░░░░░░░░░░░░ 22%` |
| 5 | `runtime.mallocgc` | 7.1MB | 20/25 | `██░░░░░░░░░░░░░ 19%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/25 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/25 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `segmentio/kafka-go.makePartitions` | 2.81MB | 13/25 | `█░░░░░░░░░░░░░░ 7%` |
| 9 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB | 14/25 | `█░░░░░░░░░░░░░░ 6%` |
| 10 | `compress/flate.NewWriter` | 2.31MB | 20/25 | `░░░░░░░░░░░░░░░ 6%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 6.19GB | 1/25 | `███████████████ 100%` |
| 2 | `segmentio/kafka-go.makePartitions` | 4.11GB | 16/25 | `█████████░░░░░░ 66%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 2.74GB | 1/25 | `██████░░░░░░░░░ 44%` |
| 4 | `internal/evaluation.mergeMetadata` | 2.28GB | 12/25 | `█████░░░░░░░░░░ 36%` |
| 5 | `reflect.unsafe_NewArray` | 1.79GB | 16/25 | `████░░░░░░░░░░░ 28%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 1.72GB | 17/25 | `████░░░░░░░░░░░ 27%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 1.65GB | 18/25 | `███░░░░░░░░░░░░ 26%` |
| 8 | `reflect.MakeSlice` | 1.15GB | 14/25 | `██░░░░░░░░░░░░░ 18%` |
| 9 | `experiment/local.topologicalSort` | 1.09GB | 13/25 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 1.05GB | 14/25 | `██░░░░░░░░░░░░░ 16%` |

## Alerts

No anomalies detected.
