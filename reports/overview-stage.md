# Overview: stage
*Last updated: 2026-05-18 11:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T11:02 (130 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,065 | avg: 14,132 | max: 14,653 | trend: decreasing (-1.14/hr))
```
▂▅▃█▁▂▁▁▂▂▃▁▁▁▂▁▁▂▁▁▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▆▅▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 137.1MB | avg: 147.9MB | max: 277.6MB | trend: stable (+0.19MB/hr))
```
▃▃▁▃▁▁▁▁▃▁▁▃▁▁▂▃▃▃▄▂▁▁▃▂▂▁▁▁▃▃▂▃▃▃▃▃▄▅▃▄▁▃▃▃▄▃▂▁▂▂▃▂▃▃▁▄▂▂▃▂▃▃▂▁▁▁▃▁▁▂▁▃▄▁▂▄▂▁▂▃▄▁▄▃▂█▄▂▂▁▁▄▂▁▁▂
```

## Current Status

Goroutines: `███████████████████░ 95%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 13%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,065 | 14,071 | -6 | 14,132 | 14,653 | decreasing (-1.14/hr) |
| Heap InUse | 137.1MB | 125.2MB | +11.9MB | 147.9MB | 277.6MB | stable (+0.19MB/hr) |
| Heap Sys | 1013.1MB | 1013.1MB | +0.0MB | 892.7MB | 1016.6MB | |
| Heap Objects | 758,507 | 564,351 | +194156 | 818,780 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 23 | 14,112 | 152.6MB | 277.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.01MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 1.6MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 104.54GB |
| 2 | `reflect.unsafe_NewArray` | 45.16GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 43.83GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 38.86GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 38.38GB |
| 6 | `internal/evaluation.mergeMetadata` | 37.44GB |
| 7 | `reflect.MakeSlice` | 25.11GB |
| 8 | `experiment/local.topologicalSort` | 19.08GB |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 19.05GB |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 19.0GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 128/130 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/130 | `██████░░░░░░░░░ 42%` |
| 3 | `runtime.mallocgc` | 11.3MB | 125/130 | `████░░░░░░░░░░░ 30%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 128/130 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.93MB | 120/130 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 8.5MB | 2/130 | `███░░░░░░░░░░░░ 23%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/130 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `segmentio/kafka-go.makePartitions` | 3.09MB | 108/130 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `internal/evaluation.mergeMetadata` | 3.0MB | 3/130 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `compress/flate.NewWriter` | 2.84MB | 108/130 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 50.81GB | 121/130 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 24.82GB | 106/130 | `███████░░░░░░░░ 48%` |
| 3 | `reflect.unsafe_NewArray` | 21.96GB | 121/130 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 21.07GB | 117/130 | `██████░░░░░░░░░ 41%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 20.87GB | 123/130 | `██████░░░░░░░░░ 41%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 20.76GB | 122/130 | `██████░░░░░░░░░ 40%` |
| 7 | `reflect.MakeSlice` | 12.42GB | 119/130 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 10.81GB | 106/130 | `███░░░░░░░░░░░░ 21%` |
| 9 | `experiment/local.topologicalSort` | 10.7GB | 118/130 | `███░░░░░░░░░░░░ 21%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 10.57GB | 119/130 | `███░░░░░░░░░░░░ 20%` |

## Alerts

No anomalies detected.
