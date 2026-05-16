# Overview: stage
*Last updated: 2026-05-16 15:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T15:31 (43 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,192 | avg: 14,162 | max: 14,653 | trend: INCREASING (+3.53/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂
```

**Heap InUse** (current: 162.6MB | avg: 142.9MB | max: 201.6MB | trend: stable (+0.38MB/hr))
```
▃▄▁▆▃▃▂▄▅▆▁▂▅▅▁▅▁▁▅▅▂▁▆▆█▄▄▆▃▃▆▆▁▄▅▆▂▅▂▂▃▂▅
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 15%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,192 | 14,069 | +123 | 14,162 | 14,653 | INCREASING (+3.53/hr) |
| Heap InUse | 162.6MB | 111.3MB | +51.3MB | 142.9MB | 201.6MB | stable (+0.38MB/hr) |
| Heap Sys | 1012.1MB | 1012.1MB | +0.0MB | 649.5MB | 1016.6MB | |
| Heap Objects | 944,601 | 420,345 | +524256 | 783,302 | 1,341,103 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 33 | 14,158 | 142.9MB | 201.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `experiment/local.(*Client).EvaluateV2` | 4.26MB |
| 6 | `internal/evaluation.mergeMetadata` | 3.5MB |
| 7 | `internal/evaluation.(*Engine).Evaluate` | 3.22MB |
| 8 | `compress/flate.NewWriter` | 2.64MB |
| 9 | `bytes.growSlice` | 2.52MB |
| 10 | `segmentio/kafka-go.makePartitions` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 26.43GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 15.9GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 12.31GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 12.14GB |
| 5 | `internal/evaluation.mergeMetadata` | 11.91GB |
| 6 | `reflect.unsafe_NewArray` | 11.5GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 6.94GB |
| 8 | `reflect.MakeSlice` | 6.43GB |
| 9 | `experiment/local.topologicalSort` | 6.07GB |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 6.02GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 41/43 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/43 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 9.47MB | 38/43 | `███░░░░░░░░░░░░ 25%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.23MB | 41/43 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.73MB | 33/43 | `███░░░░░░░░░░░░ 23%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/43 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/43 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/43 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `reflect.unsafe_New` | 3.0MB | 1/43 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `segmentio/kafka-go.makePartitions` | 2.81MB | 28/43 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 13.54GB | 19/43 | `███████████████ 100%` |
| 2 | `segmentio/kafka-go.makePartitions` | 11.82GB | 34/43 | `█████████████░░ 87%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 5.92GB | 19/43 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 5.88GB | 30/43 | `██████░░░░░░░░░ 43%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 5.19GB | 35/43 | `█████░░░░░░░░░░ 38%` |
| 6 | `reflect.unsafe_NewArray` | 5.16GB | 34/43 | `█████░░░░░░░░░░ 38%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 5.12GB | 36/43 | `█████░░░░░░░░░░ 37%` |
| 8 | `reflect.MakeSlice` | 3.06GB | 32/43 | `███░░░░░░░░░░░░ 22%` |
| 9 | `experiment/local.topologicalSort` | 2.92GB | 31/43 | `███░░░░░░░░░░░░ 21%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 2.84GB | 32/43 | `███░░░░░░░░░░░░ 20%` |

## Alerts

No anomalies detected.
