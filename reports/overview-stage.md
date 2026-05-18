# Overview: stage
*Last updated: 2026-05-18 09:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T09:03 (126 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,074 | avg: 14,134 | max: 14,653 | trend: decreasing (-1.06/hr))
```
▁▂▁▁▂▅▃█▁▂▁▁▂▂▃▁▁▁▂▁▁▂▁▁▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▆▅▁▁▁▁▁
```

**Heap InUse** (current: 180.9MB | avg: 148.4MB | max: 277.6MB | trend: stable (+0.27MB/hr))
```
▃▄▁▂▃▃▁▃▁▁▁▁▃▁▁▃▁▁▂▃▃▃▄▂▁▁▃▂▂▁▁▁▃▃▂▃▃▃▃▃▄▅▃▄▁▃▃▃▄▃▂▁▂▂▃▂▃▃▁▄▂▂▃▂▃▃▂▁▁▁▃▁▁▂▁▃▄▁▂▄▂▁▂▃▄▁▄▃▂█▄▂▂▁▁▄
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 17%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,074 | 14,068 | +6 | 14,134 | 14,653 | decreasing (-1.06/hr) |
| Heap InUse | 180.9MB | 128.5MB | +52.4MB | 148.4MB | 277.6MB | stable (+0.27MB/hr) |
| Heap Sys | 1013.1MB | 1013.1MB | +0.0MB | 888.9MB | 1016.6MB | |
| Heap Objects | 1,236,341 | 618,468 | +617873 | 824,066 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 19 | 14,121 | 157.3MB | 277.6MB |

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
| 9 | `reflect.unsafe_NewArray` | 2.0MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 100.97GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 43.83GB |
| 3 | `reflect.unsafe_NewArray` | 43.68GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 38.74GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 38.26GB |
| 6 | `internal/evaluation.mergeMetadata` | 37.32GB |
| 7 | `reflect.MakeSlice` | 24.27GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.05GB |
| 9 | `experiment/local.topologicalSort` | 19.02GB |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 18.94GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 124/126 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/126 | `██████░░░░░░░░░ 42%` |
| 3 | `runtime.mallocgc` | 11.27MB | 121/126 | `████░░░░░░░░░░░ 30%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 124/126 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.92MB | 116/126 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 8.5MB | 2/126 | `███░░░░░░░░░░░░ 23%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/126 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `segmentio/kafka-go.makePartitions` | 3.06MB | 105/126 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `internal/evaluation.mergeMetadata` | 3.0MB | 3/126 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `compress/flate.NewWriter` | 2.83MB | 104/126 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 49.02GB | 117/126 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 24.07GB | 102/126 | `███████░░░░░░░░ 49%` |
| 3 | `reflect.unsafe_NewArray` | 21.19GB | 117/126 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 20.49GB | 113/126 | `██████░░░░░░░░░ 41%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 20.27GB | 119/126 | `██████░░░░░░░░░ 41%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 20.17GB | 118/126 | `██████░░░░░░░░░ 41%` |
| 7 | `reflect.MakeSlice` | 11.99GB | 115/126 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 10.49GB | 102/126 | `███░░░░░░░░░░░░ 21%` |
| 9 | `experiment/local.topologicalSort` | 10.4GB | 114/126 | `███░░░░░░░░░░░░ 21%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 10.27GB | 115/126 | `███░░░░░░░░░░░░ 20%` |

## Alerts

No anomalies detected.
