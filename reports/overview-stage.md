# Overview: stage
*Last updated: 2026-05-16 11:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T11:31 (35 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,229 | avg: 14,141 | max: 14,602 | trend: decreasing (-1.16/hr))
```
▁▁▁▁▁▅▅▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁█▃▁▁▁▁▁▂▁▁▃
```

**Heap InUse** (current: 165.1MB | avg: 144.2MB | max: 201.6MB | trend: INCREASING (+1.32MB/hr))
```
▃▄▁▆▃▃▂▄▅▆▁▂▅▅▁▅▁▁▅▅▂▁▆▆█▄▄▆▃▃▆▆▁▄▅
```

## Current Status

Goroutines: `███████████████████░ 97%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 16%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,229 | 14,067 | +162 | 14,141 | 14,602 | decreasing (-1.16/hr) |
| Heap InUse | 165.1MB | 142.7MB | +22.4MB | 144.2MB | 201.6MB | INCREASING (+1.32MB/hr) |
| Heap Sys | 1012.3MB | 1013.8MB | -1.5MB | 566.6MB | 1016.6MB | |
| Heap Objects | 992,047 | 825,503 | +166544 | 820,026 | 1,341,103 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 25 | 14,128 | 144.8MB | 201.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `bytes.growSlice` | 3.52MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `compress/flate.NewWriter` | 1.76MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 19.29GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 13.38GB |
| 3 | `reflect.unsafe_NewArray` | 8.42GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 7.86GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 7.74GB |
| 6 | `internal/evaluation.mergeMetadata` | 7.54GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 5.86GB |
| 8 | `reflect.MakeSlice` | 4.68GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 3.87GB |
| 10 | `experiment/local.topologicalSort` | 3.86GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 33/35 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/35 | `█████░░░░░░░░░░ 39%` |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.23MB | 33/35 | `███░░░░░░░░░░░░ 25%` |
| 4 | `runtime.mallocgc` | 8.77MB | 30/35 | `███░░░░░░░░░░░░ 23%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.64MB | 25/35 | `███░░░░░░░░░░░░ 23%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/35 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/35 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `segmentio/kafka-go.makePartitions` | 2.66MB | 22/35 | `█░░░░░░░░░░░░░░ 7%` |
| 9 | `compress/flate.NewWriter` | 2.51MB | 30/35 | `█░░░░░░░░░░░░░░ 6%` |
| 10 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB | 24/35 | `█░░░░░░░░░░░░░░ 6%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 12.72GB | 11/35 | `███████████████ 100%` |
| 2 | `segmentio/kafka-go.makePartitions` | 8.27GB | 26/35 | `█████████░░░░░░ 65%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 5.57GB | 11/35 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 4.42GB | 22/35 | `█████░░░░░░░░░░ 34%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 3.73GB | 27/35 | `████░░░░░░░░░░░ 29%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 3.65GB | 28/35 | `████░░░░░░░░░░░ 28%` |
| 7 | `reflect.unsafe_NewArray` | 3.61GB | 26/35 | `████░░░░░░░░░░░ 28%` |
| 8 | `reflect.MakeSlice` | 2.19GB | 24/35 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `experiment/local.topologicalSort` | 2.17GB | 23/35 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 2.1GB | 24/35 | `██░░░░░░░░░░░░░ 16%` |

## Alerts

No anomalies detected.
