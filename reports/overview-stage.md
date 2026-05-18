# Overview: stage
*Last updated: 2026-05-18 09:33 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T09:33 (127 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,070 | avg: 14,133 | max: 14,653 | trend: decreasing (-1.08/hr))
```
▂▁▁▂▅▃█▁▂▁▁▂▂▃▁▁▁▂▁▁▂▁▁▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▆▅▁▁▁▁▁▁
```

**Heap InUse** (current: 148.7MB | avg: 148.4MB | max: 277.6MB | trend: stable (+0.26MB/hr))
```
▄▁▂▃▃▁▃▁▁▁▁▃▁▁▃▁▁▂▃▃▃▄▂▁▁▃▂▂▁▁▁▃▃▂▃▃▃▃▃▄▅▃▄▁▃▃▃▄▃▂▁▂▂▃▂▃▃▁▄▂▂▃▂▃▃▂▁▁▁▃▁▁▂▁▃▄▁▂▄▂▁▂▃▄▁▄▃▂█▄▂▂▁▁▄▂
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 14%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,070 | 14,074 | -4 | 14,133 | 14,653 | decreasing (-1.08/hr) |
| Heap InUse | 148.7MB | 180.9MB | -32.2MB | 148.4MB | 277.6MB | stable (+0.26MB/hr) |
| Heap Sys | 1013.1MB | 1013.1MB | +0.0MB | 889.9MB | 1016.6MB | |
| Heap Objects | 876,005 | 1,236,341 | -360336 | 824,475 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 20 | 14,118 | 156.8MB | 277.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `aws/endpoints.init` | 2.0MB |
| 8 | `compress/flate.NewWriter` | 1.76MB |
| 9 | `compress/flate.(*compressor).initDeflate` | 1.6MB |
| 10 | `reflect.unsafe_NewArray` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 101.81GB |
| 2 | `reflect.unsafe_NewArray` | 44.04GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 43.83GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 38.82GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 38.32GB |
| 6 | `internal/evaluation.mergeMetadata` | 37.39GB |
| 7 | `reflect.MakeSlice` | 24.48GB |
| 8 | `experiment/local.topologicalSort` | 19.05GB |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 19.05GB |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 18.98GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 125/127 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/127 | `██████░░░░░░░░░ 42%` |
| 3 | `runtime.mallocgc` | 11.28MB | 122/127 | `████░░░░░░░░░░░ 30%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 125/127 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.92MB | 117/127 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 8.5MB | 2/127 | `███░░░░░░░░░░░░ 23%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/127 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `segmentio/kafka-go.makePartitions` | 3.06MB | 105/127 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `internal/evaluation.mergeMetadata` | 3.0MB | 3/127 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `compress/flate.NewWriter` | 2.82MB | 105/127 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 49.47GB | 118/127 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 24.26GB | 103/127 | `███████░░░░░░░░ 49%` |
| 3 | `reflect.unsafe_NewArray` | 21.38GB | 118/127 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 20.64GB | 114/127 | `██████░░░░░░░░░ 41%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 20.42GB | 120/127 | `██████░░░░░░░░░ 41%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 20.32GB | 119/127 | `██████░░░░░░░░░ 41%` |
| 7 | `reflect.MakeSlice` | 12.1GB | 116/127 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 10.57GB | 103/127 | `███░░░░░░░░░░░░ 21%` |
| 9 | `experiment/local.topologicalSort` | 10.48GB | 115/127 | `███░░░░░░░░░░░░ 21%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 10.35GB | 116/127 | `███░░░░░░░░░░░░ 20%` |

## Alerts

No anomalies detected.
