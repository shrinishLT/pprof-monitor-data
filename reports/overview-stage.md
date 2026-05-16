# Overview: stage
*Last updated: 2026-05-16 22:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T22:31 (57 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,273 | avg: 14,160 | max: 14,653 | trend: INCREASING (+1.21/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃
```

**Heap InUse** (current: 155.8MB | avg: 142.4MB | max: 201.6MB | trend: stable (+0.13MB/hr))
```
▃▄▁▆▃▃▂▄▅▆▁▂▅▅▁▅▁▁▅▅▂▁▆▆█▄▄▆▃▃▆▆▁▄▅▆▂▅▂▂▃▂▅▂▂▅▂▂▄▅▅▅▆▄▂▂▅
```

## Current Status

Goroutines: `███████████████████░ 97%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 15%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,273 | 14,255 | +18 | 14,160 | 14,653 | INCREASING (+1.21/hr) |
| Heap InUse | 155.8MB | 120.9MB | +34.9MB | 142.4MB | 201.6MB | stable (+0.13MB/hr) |
| Heap Sys | 1012.5MB | 1012.5MB | +0.0MB | 738.6MB | 1016.6MB | |
| Heap Objects | 849,901 | 436,468 | +413433 | 761,357 | 1,341,103 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 47 | 14,156 | 142.3MB | 201.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `reflect.mapassign_faststr0` | 2.5MB |
| 6 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `bytes.growSlice` | 2.01MB |
| 9 | `reflect.unsafe_NewArray` | 2.0MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 39.18GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 18.98GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 18.69GB |
| 4 | `internal/evaluation.mergeMetadata` | 18.25GB |
| 5 | `reflect.unsafe_NewArray` | 16.86GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 16.23GB |
| 7 | `reflect.MakeSlice` | 9.38GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 9.34GB |
| 9 | `experiment/local.topologicalSort` | 9.34GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 7.09GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 55/57 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/57 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 10.18MB | 52/57 | `████░░░░░░░░░░░ 27%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 55/57 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.81MB | 47/57 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/57 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/57 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/57 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.87MB | 41/57 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `compress/flate.NewWriter` | 2.69MB | 47/57 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 18.09GB | 48/57 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 14.67GB | 33/57 | `████████████░░░ 81%` |
| 3 | `internal/evaluation.mergeMetadata` | 8.99GB | 44/57 | `███████░░░░░░░░ 49%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 8.29GB | 49/57 | `██████░░░░░░░░░ 45%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 8.25GB | 50/57 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 7.85GB | 48/57 | `██████░░░░░░░░░ 43%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 6.41GB | 33/57 | `█████░░░░░░░░░░ 35%` |
| 8 | `reflect.MakeSlice` | 4.57GB | 46/57 | `███░░░░░░░░░░░░ 25%` |
| 9 | `experiment/local.topologicalSort` | 4.5GB | 45/57 | `███░░░░░░░░░░░░ 24%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 4.4GB | 46/57 | `███░░░░░░░░░░░░ 24%` |

## Alerts

No anomalies detected.
