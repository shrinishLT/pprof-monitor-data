# Overview: stage
*Last updated: 2026-05-16 14:32 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T14:32 (41 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,120 | avg: 14,164 | max: 14,653 | trend: INCREASING (+4.52/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁
```

**Heap InUse** (current: 125.0MB | avg: 143.2MB | max: 201.6MB | trend: INCREASING (+0.51MB/hr))
```
▃▄▁▆▃▃▂▄▅▆▁▂▅▅▁▅▁▁▅▅▂▁▆▆█▄▄▆▃▃▆▆▁▄▅▆▂▅▂▂▃
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 12%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,120 | 14,165 | -45 | 14,164 | 14,653 | INCREASING (+4.52/hr) |
| Heap InUse | 125.0MB | 122.7MB | +2.3MB | 143.2MB | 201.6MB | INCREASING (+0.51MB/hr) |
| Heap Sys | 1012.1MB | 1012.1MB | +0.0MB | 631.8MB | 1016.6MB | |
| Heap Objects | 538,798 | 480,061 | +58737 | 788,220 | 1,341,103 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 31 | 14,160 | 143.3MB | 201.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `bufio.NewWriterSize` | 1.02MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 24.74GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 15.23GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 11.17GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 10.99GB |
| 5 | `internal/evaluation.mergeMetadata` | 10.79GB |
| 6 | `reflect.unsafe_NewArray` | 10.76GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 6.64GB |
| 8 | `reflect.MakeSlice` | 6.02GB |
| 9 | `experiment/local.topologicalSort` | 5.51GB |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 5.48GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 39/41 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/41 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 9.32MB | 36/41 | `███░░░░░░░░░░░░ 25%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.23MB | 39/41 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.71MB | 31/41 | `███░░░░░░░░░░░░ 23%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/41 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/41 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `reflect.unsafe_New` | 3.0MB | 1/41 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.79MB | 26/41 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `compress/flate.NewWriter` | 2.63MB | 34/41 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 13.27GB | 17/41 | `███████████████ 100%` |
| 2 | `segmentio/kafka-go.makePartitions` | 10.94GB | 32/41 | `████████████░░░ 82%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 5.81GB | 17/41 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 5.47GB | 28/41 | `██████░░░░░░░░░ 41%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 4.78GB | 33/41 | `█████░░░░░░░░░░ 36%` |
| 6 | `reflect.unsafe_NewArray` | 4.77GB | 32/41 | `█████░░░░░░░░░░ 35%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 4.71GB | 34/41 | `█████░░░░░░░░░░ 35%` |
| 8 | `reflect.MakeSlice` | 2.84GB | 30/41 | `███░░░░░░░░░░░░ 21%` |
| 9 | `experiment/local.topologicalSort` | 2.71GB | 29/41 | `███░░░░░░░░░░░░ 20%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 2.63GB | 30/41 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

No anomalies detected.
