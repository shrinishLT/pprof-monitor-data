# Overview: stage
*Last updated: 2026-05-16 10:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T10:31 (33 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,071 | avg: 14,140 | max: 14,602 | trend: decreasing (-1.60/hr))
```
▁▁▁▁▁▅▅▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁█▃▁▁▁▁▁▂▁
```

**Heap InUse** (current: 107.5MB | avg: 143.6MB | max: 201.6MB | trend: INCREASING (+1.34MB/hr))
```
▃▄▁▆▃▃▂▄▅▆▁▂▅▅▁▅▁▁▅▅▂▁▆▆█▄▄▆▃▃▆▆▁
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,071 | 14,177 | -106 | 14,140 | 14,602 | decreasing (-1.60/hr) |
| Heap InUse | 107.5MB | 183.5MB | -76.0MB | 143.6MB | 201.6MB | INCREASING (+1.34MB/hr) |
| Heap Sys | 1013.8MB | 1013.8MB | +0.0MB | 539.6MB | 1016.6MB | |
| Heap Objects | 384,321 | 1,278,923 | -894602 | 814,648 | 1,341,103 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 23 | 14,126 | 144.0MB | 201.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 5.01MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 1.06MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 17.48GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 13.38GB |
| 3 | `reflect.unsafe_NewArray` | 7.62GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 7.3GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 7.2GB |
| 6 | `internal/evaluation.mergeMetadata` | 7.03GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 5.86GB |
| 8 | `reflect.MakeSlice` | 4.26GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 3.6GB |
| 10 | `experiment/local.topologicalSort` | 3.6GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 31/33 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/33 | `█████░░░░░░░░░░ 39%` |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.22MB | 31/33 | `███░░░░░░░░░░░░ 25%` |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.61MB | 23/33 | `███░░░░░░░░░░░░ 23%` |
| 5 | `runtime.mallocgc` | 8.53MB | 28/33 | `███░░░░░░░░░░░░ 23%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/33 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/33 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `segmentio/kafka-go.makePartitions` | 2.73MB | 20/33 | `█░░░░░░░░░░░░░░ 7%` |
| 9 | `compress/flate.NewWriter` | 2.53MB | 28/33 | `█░░░░░░░░░░░░░░ 6%` |
| 10 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB | 22/33 | `█░░░░░░░░░░░░░░ 6%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 12.57GB | 9/33 | `███████████████ 100%` |
| 2 | `segmentio/kafka-go.makePartitions` | 7.39GB | 24/33 | `████████░░░░░░░ 58%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 5.51GB | 9/33 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 4.13GB | 20/33 | `████░░░░░░░░░░░ 32%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 3.43GB | 25/33 | `████░░░░░░░░░░░ 27%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 3.34GB | 26/33 | `███░░░░░░░░░░░░ 26%` |
| 7 | `reflect.unsafe_NewArray` | 3.23GB | 24/33 | `███░░░░░░░░░░░░ 25%` |
| 8 | `experiment/local.topologicalSort` | 2.02GB | 21/33 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `reflect.MakeSlice` | 1.97GB | 22/33 | `██░░░░░░░░░░░░░ 15%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 1.95GB | 22/33 | `██░░░░░░░░░░░░░ 15%` |

## Alerts

No anomalies detected.
