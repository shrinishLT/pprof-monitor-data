# Overview: stage
*Last updated: 2026-05-17 23:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T23:31 (107 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,071 | avg: 14,136 | max: 14,653 | trend: decreasing (-1.48/hr))
```
▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▂▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▁▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 186.0MB | avg: 146.8MB | max: 213.6MB | trend: stable (+0.22MB/hr))
```
▂▄▄▁▄▁▁▅▅▁▁▆▅▇▃▃▅▂▂▅▆▁▃▅▅▂▄▂▂▂▁▄▁▂▄▂▁▄▄▄▅▅▃▂▂▄▃▃▁▂▁▄▅▄▅▄▅▅▄▆█▄▆▂▅▅▄▆▄▄▁▄▄▅▃▅▅▂▅▃▃▅▃▄▅▃▁▂▁▅▁▁▂▁▅▆
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 18%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,071 | 14,067 | +4 | 14,136 | 14,653 | decreasing (-1.48/hr) |
| Heap InUse | 186.0MB | 175.2MB | +10.8MB | 146.8MB | 213.6MB | stable (+0.22MB/hr) |
| Heap Sys | 1013.3MB | 1013.3MB | +0.0MB | 866.9MB | 1016.6MB | |
| Heap Objects | 1,363,418 | 1,226,628 | +136790 | 815,335 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `reflect.mapassign_faststr0` | 3.5MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.51MB |
| 8 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 83.93GB |
| 2 | `reflect.unsafe_NewArray` | 36.27GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 31.49GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 31.26GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 31.07GB |
| 6 | `internal/evaluation.mergeMetadata` | 30.15GB |
| 7 | `reflect.MakeSlice` | 20.17GB |
| 8 | `experiment/local.topologicalSort` | 15.49GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 15.39GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 13.61GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 105/107 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/107 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 11.12MB | 102/107 | `████░░░░░░░░░░░ 30%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 105/107 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.91MB | 97/107 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/107 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/107 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.25MB | 2/107 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `segmentio/kafka-go.makePartitions` | 3.05MB | 87/107 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `compress/flate.NewWriter` | 2.8MB | 89/107 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 40.52GB | 98/107 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 21.46GB | 83/107 | `███████░░░░░░░░ 52%` |
| 3 | `internal/evaluation.mergeMetadata` | 17.82GB | 94/107 | `██████░░░░░░░░░ 43%` |
| 4 | `reflect.unsafe_NewArray` | 17.5GB | 98/107 | `██████░░░░░░░░░ 43%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 17.45GB | 100/107 | `██████░░░░░░░░░ 43%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 17.39GB | 99/107 | `██████░░░░░░░░░ 42%` |
| 7 | `reflect.MakeSlice` | 9.95GB | 96/107 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 9.36GB | 83/107 | `███░░░░░░░░░░░░ 23%` |
| 9 | `experiment/local.topologicalSort` | 9.04GB | 95/107 | `███░░░░░░░░░░░░ 22%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 8.9GB | 96/107 | `███░░░░░░░░░░░░ 21%` |

## Alerts

No anomalies detected.
