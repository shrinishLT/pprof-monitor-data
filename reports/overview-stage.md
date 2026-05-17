# Overview: stage
*Last updated: 2026-05-18 05:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T05:01 (118 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,071 | avg: 14,130 | max: 14,653 | trend: decreasing (-1.60/hr))
```
▁▁▇▃▁▁▁▁▁▂▁▁▂▅▃█▁▂▁▁▂▂▃▁▁▁▂▁▁▂▁▁▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁
```

**Heap InUse** (current: 178.4MB | avg: 147.4MB | max: 213.6MB | trend: stable (+0.22MB/hr))
```
▆▅▇▃▃▅▂▂▅▆▁▃▄▅▁▄▁▂▂▁▄▁▂▄▁▁▄▄▄▄▅▃▁▁▄▃▃▁▂▁▄▅▄▅▄▅▅▄▆█▄▆▂▅▅▄▆▄▃▁▃▄▅▃▄▄▁▅▃▃▅▃▄▅▂▁▂▁▅▁▁▂▁▅▆▁▄▆▃▂▂▅▅▁▆▅
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 17%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,071 | 14,065 | +6 | 14,130 | 14,653 | decreasing (-1.60/hr) |
| Heap InUse | 178.4MB | 183.5MB | -5.1MB | 147.4MB | 213.6MB | stable (+0.22MB/hr) |
| Heap Sys | 1012.8MB | 1012.8MB | +0.0MB | 880.5MB | 1016.6MB | |
| Heap Objects | 1,225,819 | 1,334,866 | -109047 | 825,055 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 11 | 14,078 | 152.8MB | 186.8MB |

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
| 10 | `reflect.unsafe_NewArray` | 1.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 93.76GB |
| 2 | `reflect.unsafe_NewArray` | 40.55GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 34.93GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 34.38GB |
| 5 | `internal/evaluation.mergeMetadata` | 33.45GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 31.26GB |
| 7 | `reflect.MakeSlice` | 22.53GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 17.19GB |
| 9 | `experiment/local.topologicalSort` | 17.1GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 13.61GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 116/118 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/118 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 11.21MB | 113/118 | `████░░░░░░░░░░░ 30%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 116/118 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.92MB | 108/118 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/118 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/118 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.25MB | 2/118 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `segmentio/kafka-go.makePartitions` | 3.07MB | 98/118 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `compress/flate.NewWriter` | 2.82MB | 99/118 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 45.44GB | 109/118 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 22.61GB | 94/118 | `███████░░░░░░░░ 49%` |
| 3 | `reflect.unsafe_NewArray` | 19.63GB | 109/118 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 19.28GB | 105/118 | `██████░░░░░░░░░ 42%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 19.0GB | 111/118 | `██████░░░░░░░░░ 41%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 18.92GB | 110/118 | `██████░░░░░░░░░ 41%` |
| 7 | `reflect.MakeSlice` | 11.13GB | 107/118 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 9.85GB | 94/118 | `███░░░░░░░░░░░░ 21%` |
| 9 | `experiment/local.topologicalSort` | 9.79GB | 106/118 | `███░░░░░░░░░░░░ 21%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 9.66GB | 107/118 | `███░░░░░░░░░░░░ 21%` |

## Alerts

No anomalies detected.
