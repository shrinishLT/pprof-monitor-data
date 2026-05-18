# Overview: stage
*Last updated: 2026-05-18 07:33 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T07:33 (123 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,076 | avg: 14,135 | max: 14,653 | trend: decreasing (-0.98/hr))
```
▁▁▁▁▂▁▁▂▅▃█▁▂▁▁▂▂▃▁▁▁▂▁▁▂▁▁▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▆▅▁▁
```

**Heap InUse** (current: 150.3MB | avg: 148.6MB | max: 277.6MB | trend: stable (+0.31MB/hr))
```
▄▁▁▃▄▁▂▃▃▁▃▁▁▁▁▃▁▁▃▁▁▂▃▃▃▄▂▁▁▃▂▂▁▁▁▃▃▂▃▃▃▃▃▄▅▃▄▁▃▃▃▄▃▂▁▂▂▃▂▃▃▁▄▂▂▃▂▃▃▂▁▁▁▃▁▁▂▁▃▄▁▂▄▂▁▂▃▄▁▄▃▂█▄▂▂
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 14%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,076 | 14,095 | -19 | 14,135 | 14,653 | decreasing (-0.98/hr) |
| Heap InUse | 150.3MB | 135.3MB | +15.0MB | 148.6MB | 277.6MB | stable (+0.31MB/hr) |
| Heap Sys | 1013.1MB | 1013.1MB | +0.0MB | 885.9MB | 1016.6MB | |
| Heap Objects | 892,417 | 679,153 | +213264 | 826,186 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 16 | 14,130 | 160.6MB | 277.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.51MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `reflect.unsafe_NewArray` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 98.25GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 43.83GB |
| 3 | `reflect.unsafe_NewArray` | 42.55GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 38.66GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 38.18GB |
| 6 | `internal/evaluation.mergeMetadata` | 37.22GB |
| 7 | `reflect.MakeSlice` | 23.62GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.05GB |
| 9 | `experiment/local.topologicalSort` | 18.97GB |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 18.9GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 121/123 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/123 | `██████░░░░░░░░░ 42%` |
| 3 | `runtime.mallocgc` | 11.25MB | 118/123 | `████░░░░░░░░░░░ 30%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 121/123 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.92MB | 113/123 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 8.5MB | 2/123 | `███░░░░░░░░░░░░ 23%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/123 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `segmentio/kafka-go.makePartitions` | 3.07MB | 103/123 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `internal/evaluation.mergeMetadata` | 3.0MB | 3/123 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `compress/flate.NewWriter` | 2.82MB | 101/123 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 47.68GB | 114/123 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 23.47GB | 99/123 | `███████░░░░░░░░ 49%` |
| 3 | `reflect.unsafe_NewArray` | 20.6GB | 114/123 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 20.04GB | 110/123 | `██████░░░░░░░░░ 42%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 19.79GB | 116/123 | `██████░░░░░░░░░ 41%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 19.69GB | 115/123 | `██████░░░░░░░░░ 41%` |
| 7 | `reflect.MakeSlice` | 11.67GB | 112/123 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 10.23GB | 99/123 | `███░░░░░░░░░░░░ 21%` |
| 9 | `experiment/local.topologicalSort` | 10.17GB | 111/123 | `███░░░░░░░░░░░░ 21%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 10.04GB | 112/123 | `███░░░░░░░░░░░░ 21%` |

## Alerts

No anomalies detected.
