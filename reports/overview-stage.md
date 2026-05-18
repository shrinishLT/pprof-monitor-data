# Overview: stage
*Last updated: 2026-05-18 06:33 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T06:33 (121 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,469 | avg: 14,136 | max: 14,653 | trend: decreasing (-0.95/hr))
```
▃▁▁▁▁▁▂▁▁▂▅▃█▁▂▁▁▂▂▃▁▁▁▂▁▁▂▁▁▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▆▅
```

**Heap InUse** (current: 188.5MB | avg: 148.7MB | max: 277.6MB | trend: stable (+0.33MB/hr))
```
▂▂▄▁▁▃▄▁▂▃▃▁▃▁▁▁▁▃▁▁▃▁▁▂▃▃▃▄▂▁▁▃▂▂▁▁▁▃▃▂▃▃▃▃▃▄▅▃▄▁▃▃▃▄▃▂▁▂▂▃▂▃▃▁▄▂▂▃▂▃▃▂▁▁▁▃▁▁▂▁▃▄▁▂▄▂▁▂▃▄▁▄▃▂█▄
```

## Current Status

Goroutines: `███████████████████░ 98%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 18%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,469 | 14,507 | -38 | 14,136 | 14,653 | decreasing (-0.95/hr) |
| Heap InUse | 188.5MB | 277.6MB | -89.1MB | 148.7MB | 277.6MB | stable (+0.33MB/hr) |
| Heap Sys | 1013.0MB | 1012.8MB | +0.2MB | 883.8MB | 1016.6MB | |
| Heap Objects | 944,678 | 1,008,508 | -63830 | 826,853 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 14 | 14,137 | 163.1MB | 277.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `internal/evaluation.mergeMetadata` | 2.5MB |
| 6 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 2.0MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 96.55GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 43.75GB |
| 3 | `reflect.unsafe_NewArray` | 41.8GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 38.39GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 37.9GB |
| 6 | `internal/evaluation.mergeMetadata` | 36.94GB |
| 7 | `reflect.MakeSlice` | 23.2GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.02GB |
| 9 | `experiment/local.topologicalSort` | 18.83GB |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 18.76GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 119/121 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/121 | `██████░░░░░░░░░ 42%` |
| 3 | `runtime.mallocgc` | 11.24MB | 116/121 | `████░░░░░░░░░░░ 30%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 119/121 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.92MB | 111/121 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 8.5MB | 2/121 | `███░░░░░░░░░░░░ 23%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/121 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `segmentio/kafka-go.makePartitions` | 3.07MB | 101/121 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `internal/evaluation.mergeMetadata` | 3.0MB | 3/121 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `compress/flate.NewWriter` | 2.82MB | 100/121 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 46.78GB | 112/121 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 23.05GB | 97/121 | `███████░░░░░░░░ 49%` |
| 3 | `reflect.unsafe_NewArray` | 20.22GB | 112/121 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 19.72GB | 108/121 | `██████░░░░░░░░░ 42%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 19.46GB | 114/121 | `██████░░░░░░░░░ 41%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 19.37GB | 113/121 | `██████░░░░░░░░░ 41%` |
| 7 | `reflect.MakeSlice` | 11.45GB | 110/121 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 10.05GB | 97/121 | `███░░░░░░░░░░░░ 21%` |
| 9 | `experiment/local.topologicalSort` | 10.01GB | 109/121 | `███░░░░░░░░░░░░ 21%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 9.88GB | 110/121 | `███░░░░░░░░░░░░ 21%` |

## Alerts

No anomalies detected.
