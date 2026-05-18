# Overview: stage
*Last updated: 2026-05-18 15:33 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T15:33 (139 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,147 | avg: 14,133 | max: 14,653 | trend: decreasing (-0.84/hr))
```
▂▄▁▁▁▂▁▁▃▁▂▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁█▄▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▆▆▁▁▁▁▁▁▁▁▁▁▁▃▁▂▁▂▄▂
```

**Heap InUse** (current: 184.6MB | avg: 148.7MB | max: 277.6MB | trend: stable (+0.22MB/hr))
```
▁▁▃▁▁▂▃▃▃▄▂▁▁▃▂▂▁▁▁▃▃▂▃▃▃▃▃▄▅▃▄▁▃▃▃▄▃▂▁▂▂▃▂▃▃▁▄▂▂▃▂▃▃▂▁▁▁▃▁▁▂▁▃▄▁▂▄▂▁▂▃▄▁▄▃▂█▄▂▂▁▁▄▂▁▁▂▃▃▄▁▃▄▂▁▄
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 18%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,147 | 14,316 | -169 | 14,133 | 14,653 | decreasing (-0.84/hr) |
| Heap InUse | 184.6MB | 129.1MB | +55.5MB | 148.7MB | 277.6MB | stable (+0.22MB/hr) |
| Heap Sys | 1012.5MB | 1013.1MB | -0.6MB | 900.5MB | 1016.6MB | |
| Heap Objects | 981,831 | 461,518 | +520313 | 821,600 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 32 | 14,122 | 154.9MB | 277.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.01MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `reflect.mapassign_faststr0` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 112.76GB |
| 2 | `reflect.unsafe_NewArray` | 48.77GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 45.69GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 43.43GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 42.9GB |
| 6 | `internal/evaluation.mergeMetadata` | 41.83GB |
| 7 | `reflect.MakeSlice` | 27.07GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 21.36GB |
| 9 | `experiment/local.topologicalSort` | 21.3GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 19.87GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 137/139 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/139 | `██████░░░░░░░░░ 42%` |
| 3 | `runtime.mallocgc` | 11.35MB | 134/139 | `████░░░░░░░░░░░ 30%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 137/139 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.93MB | 129/139 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 8.5MB | 2/139 | `███░░░░░░░░░░░░ 23%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/139 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `segmentio/kafka-go.makePartitions` | 3.12MB | 117/139 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `internal/evaluation.mergeMetadata` | 3.0MB | 3/139 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `compress/flate.NewWriter` | 2.83MB | 114/139 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 54.85GB | 130/139 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 26.37GB | 115/139 | `███████░░░░░░░░ 48%` |
| 3 | `reflect.unsafe_NewArray` | 23.7GB | 130/139 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 22.37GB | 126/139 | `██████░░░░░░░░░ 40%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 22.23GB | 132/139 | `██████░░░░░░░░░ 40%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 22.1GB | 131/139 | `██████░░░░░░░░░ 40%` |
| 7 | `reflect.MakeSlice` | 13.39GB | 128/139 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 11.48GB | 115/139 | `███░░░░░░░░░░░░ 20%` |
| 9 | `experiment/local.topologicalSort` | 11.35GB | 127/139 | `███░░░░░░░░░░░░ 20%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 11.23GB | 128/139 | `███░░░░░░░░░░░░ 20%` |

## Alerts

No anomalies detected.
