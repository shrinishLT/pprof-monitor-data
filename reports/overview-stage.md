# Overview: stage
*Last updated: 2026-05-18 14:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T14:03 (136 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,074 | avg: 14,131 | max: 14,653 | trend: decreasing (-1.04/hr))
```
▁▁▂▂▄▁▁▁▂▁▁▃▁▂▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁█▄▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▆▆▁▁▁▁▁▁▁▁▁▁▁▃▁▂▁
```

**Heap InUse** (current: 190.8MB | avg: 148.6MB | max: 277.6MB | trend: stable (+0.24MB/hr))
```
▁▁▃▁▁▃▁▁▂▃▃▃▄▂▁▁▃▂▂▁▁▁▃▃▂▃▃▃▃▃▄▅▃▄▁▃▃▃▄▃▂▁▂▂▃▂▃▃▁▄▂▂▃▂▃▃▂▁▁▁▃▁▁▂▁▃▄▁▂▄▂▁▂▃▄▁▄▃▂█▄▂▂▁▁▄▂▁▁▂▃▃▄▁▃▄
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 18%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,074 | 14,176 | -102 | 14,131 | 14,653 | decreasing (-1.04/hr) |
| Heap InUse | 190.8MB | 157.5MB | +33.3MB | 148.6MB | 277.6MB | stable (+0.24MB/hr) |
| Heap Sys | 1013.3MB | 1013.1MB | +0.2MB | 898.0MB | 1016.6MB | |
| Heap Objects | 1,374,627 | 714,797 | +659830 | 824,655 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 29 | 14,113 | 155.4MB | 277.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `reflect.unsafe_NewArray` | 2.5MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 110.05GB |
| 2 | `reflect.unsafe_NewArray` | 47.57GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 45.02GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 41.38GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 40.84GB |
| 6 | `internal/evaluation.mergeMetadata` | 39.79GB |
| 7 | `reflect.MakeSlice` | 26.42GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 20.25GB |
| 9 | `experiment/local.topologicalSort` | 20.23GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 19.57GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 134/136 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/136 | `██████░░░░░░░░░ 42%` |
| 3 | `runtime.mallocgc` | 11.34MB | 131/136 | `████░░░░░░░░░░░ 30%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 134/136 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.93MB | 126/136 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 8.5MB | 2/136 | `███░░░░░░░░░░░░ 23%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/136 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `segmentio/kafka-go.makePartitions` | 3.12MB | 114/136 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `internal/evaluation.mergeMetadata` | 3.0MB | 3/136 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `compress/flate.NewWriter` | 2.84MB | 112/136 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 53.5GB | 127/136 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 25.86GB | 112/136 | `███████░░░░░░░░ 48%` |
| 3 | `reflect.unsafe_NewArray` | 23.12GB | 127/136 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 21.92GB | 123/136 | `██████░░░░░░░░░ 40%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 21.76GB | 129/136 | `██████░░░░░░░░░ 40%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 21.64GB | 128/136 | `██████░░░░░░░░░ 40%` |
| 7 | `reflect.MakeSlice` | 13.07GB | 125/136 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 11.26GB | 112/136 | `███░░░░░░░░░░░░ 21%` |
| 9 | `experiment/local.topologicalSort` | 11.12GB | 124/136 | `███░░░░░░░░░░░░ 20%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 11.0GB | 125/136 | `███░░░░░░░░░░░░ 20%` |

## Alerts

No anomalies detected.
