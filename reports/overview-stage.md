# Overview: stage
*Last updated: 2026-05-16 16:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T16:02 (44 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,151 | avg: 14,162 | max: 14,653 | trend: INCREASING (+3.22/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂
```

**Heap InUse** (current: 111.4MB | avg: 142.2MB | max: 201.6MB | trend: stable (+0.16MB/hr))
```
▃▄▁▆▃▃▂▄▅▆▁▂▅▅▁▅▁▁▅▅▂▁▆▆█▄▄▆▃▃▆▆▁▄▅▆▂▅▂▂▃▂▅▂
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,151 | 14,192 | -41 | 14,162 | 14,653 | INCREASING (+3.22/hr) |
| Heap InUse | 111.4MB | 162.6MB | -51.2MB | 142.2MB | 201.6MB | stable (+0.16MB/hr) |
| Heap Sys | 1012.2MB | 1012.1MB | +0.1MB | 657.7MB | 1016.6MB | |
| Heap Objects | 366,703 | 944,601 | -577898 | 773,833 | 1,341,103 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 34 | 14,158 | 142.0MB | 201.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 6 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `compress/flate.NewWriter` | 1.76MB |
| 10 | `kafka-go/protocol.newPage` | 1.06MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 27.42GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 15.91GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 12.47GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 12.3GB |
| 5 | `internal/evaluation.mergeMetadata` | 12.05GB |
| 6 | `reflect.unsafe_NewArray` | 11.91GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 6.95GB |
| 8 | `reflect.MakeSlice` | 6.67GB |
| 9 | `experiment/local.topologicalSort` | 6.15GB |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 6.11GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 42/44 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/44 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 9.53MB | 39/44 | `███░░░░░░░░░░░░ 26%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.23MB | 42/44 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.74MB | 34/44 | `███░░░░░░░░░░░░ 23%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/44 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/44 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/44 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `reflect.unsafe_New` | 3.0MB | 1/44 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `segmentio/kafka-go.makePartitions` | 2.83MB | 29/44 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 13.66GB | 20/44 | `███████████████ 100%` |
| 2 | `segmentio/kafka-go.makePartitions` | 12.27GB | 35/44 | `█████████████░░ 89%` |
| 3 | `internal/evaluation.mergeMetadata` | 6.08GB | 31/44 | `██████░░░░░░░░░ 44%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 5.97GB | 20/44 | `██████░░░░░░░░░ 43%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 5.38GB | 36/44 | `█████░░░░░░░░░░ 39%` |
| 6 | `reflect.unsafe_NewArray` | 5.35GB | 35/44 | `█████░░░░░░░░░░ 39%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 5.31GB | 37/44 | `█████░░░░░░░░░░ 38%` |
| 8 | `reflect.MakeSlice` | 3.17GB | 33/44 | `███░░░░░░░░░░░░ 23%` |
| 9 | `experiment/local.topologicalSort` | 3.02GB | 32/44 | `███░░░░░░░░░░░░ 22%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 2.93GB | 33/44 | `███░░░░░░░░░░░░ 21%` |

## Alerts

No anomalies detected.
