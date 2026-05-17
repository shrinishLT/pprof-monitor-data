# Overview: stage
*Last updated: 2026-05-18 00:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T00:01 (108 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,067 | avg: 14,135 | max: 14,653 | trend: decreasing (-1.51/hr))
```
▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▂▅▃█▁▂▁▁▂▂▃▁▁▁▂▁▁▂▁▁▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 107.6MB | avg: 146.5MB | max: 213.6MB | trend: stable (+0.17MB/hr))
```
▄▄▁▄▁▁▅▅▁▁▆▅▇▃▃▅▂▂▅▆▁▃▅▅▂▄▂▂▂▁▄▁▂▄▂▁▄▄▄▅▅▃▂▂▄▃▃▁▂▁▄▅▄▅▄▅▅▄▆█▄▆▂▅▅▄▆▄▄▁▄▄▅▃▅▅▂▅▃▃▅▃▄▅▃▁▂▁▅▁▁▂▁▅▆▁
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,067 | 14,071 | -4 | 14,135 | 14,653 | decreasing (-1.51/hr) |
| Heap InUse | 107.6MB | 186.0MB | -78.4MB | 146.5MB | 213.6MB | stable (+0.17MB/hr) |
| Heap Sys | 1013.3MB | 1013.3MB | +0.0MB | 868.2MB | 1016.6MB | |
| Heap Objects | 340,272 | 1,363,418 | -1023146 | 810,937 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 1 | 14,067 | 107.6MB | 107.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.0MB |
| 6 | `reflect.unsafe_NewArray` | 2.51MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `compress/flate.NewWriter` | 1.76MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 84.8GB |
| 2 | `reflect.unsafe_NewArray` | 36.65GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 31.49GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 31.26GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 31.07GB |
| 6 | `internal/evaluation.mergeMetadata` | 30.15GB |
| 7 | `reflect.MakeSlice` | 20.39GB |
| 8 | `experiment/local.topologicalSort` | 15.49GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 15.39GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 13.61GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 106/108 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/108 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 11.13MB | 103/108 | `████░░░░░░░░░░░ 30%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 106/108 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.91MB | 98/108 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/108 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/108 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.25MB | 2/108 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `segmentio/kafka-go.makePartitions` | 3.06MB | 88/108 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `compress/flate.NewWriter` | 2.79MB | 90/108 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 40.96GB | 99/108 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 21.58GB | 84/108 | `███████░░░░░░░░ 52%` |
| 3 | `internal/evaluation.mergeMetadata` | 17.95GB | 95/108 | `██████░░░░░░░░░ 43%` |
| 4 | `reflect.unsafe_NewArray` | 17.7GB | 99/108 | `██████░░░░░░░░░ 43%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 17.59GB | 101/108 | `██████░░░░░░░░░ 42%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 17.53GB | 100/108 | `██████░░░░░░░░░ 42%` |
| 7 | `reflect.MakeSlice` | 10.06GB | 97/108 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 9.41GB | 84/108 | `███░░░░░░░░░░░░ 22%` |
| 9 | `experiment/local.topologicalSort` | 9.1GB | 96/108 | `███░░░░░░░░░░░░ 22%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 8.97GB | 97/108 | `███░░░░░░░░░░░░ 21%` |

## Alerts

No anomalies detected.
