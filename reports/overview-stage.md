# Overview: stage
*Last updated: 2026-05-17 22:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T22:01 (104 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,064 | avg: 14,138 | max: 14,653 | trend: decreasing (-1.38/hr))
```
▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 131.4MB | avg: 146.6MB | max: 213.6MB | trend: stable (+0.20MB/hr))
```
▅▆▁▂▅▄▁▅▁▁▅▅▁▁▆▆▇▃▃▆▂▃▅▆▁▃▅▅▂▄▂▂▂▂▅▂▂▄▂▂▄▄▄▅▆▃▂▂▄▄▃▁▂▁▅▅▄▅▅▅▅▅▆█▄▆▂▅▅▄▆▅▄▁▄▄▅▃▅▅▂▆▃▃▅▃▄▅▃▂▃▁▆▂▂▃
```

## Current Status

Goroutines: `███████████████████░ 95%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 12%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,064 | 14,073 | -9 | 14,138 | 14,653 | decreasing (-1.38/hr) |
| Heap InUse | 131.4MB | 110.8MB | +20.6MB | 146.6MB | 213.6MB | stable (+0.20MB/hr) |
| Heap Sys | 1013.0MB | 1012.3MB | +0.7MB | 862.6MB | 1016.6MB | |
| Heap Objects | 700,605 | 413,699 | +286906 | 811,664 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 45 | 14,113 | 152.0MB | 213.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 5.01MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 81.22GB |
| 2 | `reflect.unsafe_NewArray` | 35.07GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 31.45GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 31.26GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 31.03GB |
| 6 | `internal/evaluation.mergeMetadata` | 30.11GB |
| 7 | `reflect.MakeSlice` | 19.53GB |
| 8 | `experiment/local.topologicalSort` | 15.47GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 15.36GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 13.61GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 102/104 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/104 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 11.09MB | 99/104 | `████░░░░░░░░░░░ 30%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 102/104 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.9MB | 94/104 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/104 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/104 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.25MB | 2/104 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `segmentio/kafka-go.makePartitions` | 3.05MB | 84/104 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `compress/flate.NewWriter` | 2.76MB | 86/104 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 39.17GB | 95/104 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 21.1GB | 80/104 | `████████░░░░░░░ 53%` |
| 3 | `internal/evaluation.mergeMetadata` | 17.42GB | 91/104 | `██████░░░░░░░░░ 44%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 17.01GB | 97/104 | `██████░░░░░░░░░ 43%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 16.96GB | 96/104 | `██████░░░░░░░░░ 43%` |
| 6 | `reflect.unsafe_NewArray` | 16.92GB | 95/104 | `██████░░░░░░░░░ 43%` |
| 7 | `reflect.MakeSlice` | 9.63GB | 93/104 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 9.2GB | 80/104 | `███░░░░░░░░░░░░ 23%` |
| 9 | `experiment/local.topologicalSort` | 8.83GB | 92/104 | `███░░░░░░░░░░░░ 22%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 8.69GB | 93/104 | `███░░░░░░░░░░░░ 22%` |

## Alerts

No anomalies detected.
