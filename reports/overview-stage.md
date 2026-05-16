# Overview: stage
*Last updated: 2026-05-16 14:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T14:03 (40 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,165 | avg: 14,165 | max: 14,653 | trend: INCREASING (+5.20/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂
```

**Heap InUse** (current: 122.7MB | avg: 143.6MB | max: 201.6MB | trend: INCREASING (+0.69MB/hr))
```
▃▄▁▆▃▃▂▄▅▆▁▂▅▅▁▅▁▁▅▅▂▁▆▆█▄▄▆▃▃▆▆▁▄▅▆▂▅▂▂
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 12%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,165 | 14,074 | +91 | 14,165 | 14,653 | INCREASING (+5.20/hr) |
| Heap InUse | 122.7MB | 117.9MB | +4.8MB | 143.6MB | 201.6MB | INCREASING (+0.69MB/hr) |
| Heap Sys | 1012.1MB | 1012.0MB | +0.1MB | 622.3MB | 1016.6MB | |
| Heap Objects | 480,061 | 535,059 | -54998 | 794,456 | 1,341,103 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 30 | 14,162 | 143.9MB | 201.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `reflect.mapassign_faststr0` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 23.88GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 14.56GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 10.7GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 10.51GB |
| 5 | `reflect.unsafe_NewArray` | 10.4GB |
| 6 | `internal/evaluation.mergeMetadata` | 10.31GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 6.36GB |
| 8 | `reflect.MakeSlice` | 5.8GB |
| 9 | `experiment/local.topologicalSort` | 5.29GB |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 5.26GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 38/40 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/40 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 9.24MB | 35/40 | `███░░░░░░░░░░░░ 25%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.23MB | 38/40 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.7MB | 30/40 | `███░░░░░░░░░░░░ 23%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/40 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/40 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `reflect.unsafe_New` | 3.0MB | 1/40 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.76MB | 25/40 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `compress/flate.NewWriter` | 2.6MB | 33/40 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 13.15GB | 16/40 | `███████████████ 100%` |
| 2 | `segmentio/kafka-go.makePartitions` | 10.49GB | 31/40 | `███████████░░░░ 79%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 5.75GB | 16/40 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 5.27GB | 27/40 | `██████░░░░░░░░░ 40%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 4.59GB | 32/40 | `█████░░░░░░░░░░ 34%` |
| 6 | `reflect.unsafe_NewArray` | 4.58GB | 31/40 | `█████░░░░░░░░░░ 34%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 4.51GB | 33/40 | `█████░░░░░░░░░░ 34%` |
| 8 | `reflect.MakeSlice` | 2.73GB | 29/40 | `███░░░░░░░░░░░░ 20%` |
| 9 | `experiment/local.topologicalSort` | 2.61GB | 28/40 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 2.54GB | 29/40 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

No anomalies detected.
