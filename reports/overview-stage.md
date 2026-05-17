# Overview: stage
*Last updated: 2026-05-17 23:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T23:01 (106 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,067 | avg: 14,136 | max: 14,653 | trend: decreasing (-1.45/hr))
```
▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 175.2MB | avg: 146.5MB | max: 213.6MB | trend: stable (+0.18MB/hr))
```
▁▂▅▄▁▅▁▁▅▅▁▁▆▆▇▃▃▆▂▃▅▆▁▃▅▅▂▄▂▂▂▂▅▂▂▄▂▂▄▄▄▅▆▃▂▂▄▄▃▁▂▁▅▅▄▅▅▅▅▅▆█▄▆▂▅▅▄▆▅▄▁▄▄▅▃▅▅▂▆▃▃▅▃▄▅▃▂▃▁▆▂▂▃▁▅
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 17%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,067 | 14,067 | +0 | 14,136 | 14,653 | decreasing (-1.45/hr) |
| Heap InUse | 175.2MB | 105.6MB | +69.6MB | 146.5MB | 213.6MB | stable (+0.18MB/hr) |
| Heap Sys | 1013.3MB | 1014.3MB | -1.0MB | 865.5MB | 1016.6MB | |
| Heap Objects | 1,226,628 | 237,808 | +988820 | 810,165 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 47 | 14,111 | 151.5MB | 213.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `reflect.unsafe_NewArray` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 83.03GB |
| 2 | `reflect.unsafe_NewArray` | 35.91GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 31.47GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 31.26GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 31.05GB |
| 6 | `internal/evaluation.mergeMetadata` | 30.13GB |
| 7 | `reflect.MakeSlice` | 19.96GB |
| 8 | `experiment/local.topologicalSort` | 15.48GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 15.37GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 13.61GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 104/106 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/106 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 11.11MB | 101/106 | `████░░░░░░░░░░░ 30%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 104/106 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.91MB | 96/106 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/106 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/106 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.25MB | 2/106 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `segmentio/kafka-go.makePartitions` | 3.05MB | 86/106 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `compress/flate.NewWriter` | 2.79MB | 88/106 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 40.07GB | 97/106 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 21.34GB | 82/106 | `███████░░░░░░░░ 53%` |
| 3 | `internal/evaluation.mergeMetadata` | 17.69GB | 93/106 | `██████░░░░░░░░░ 44%` |
| 4 | `reflect.unsafe_NewArray` | 17.31GB | 97/106 | `██████░░░░░░░░░ 43%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 17.31GB | 99/106 | `██████░░░░░░░░░ 43%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 17.25GB | 98/106 | `██████░░░░░░░░░ 43%` |
| 7 | `reflect.MakeSlice` | 9.84GB | 95/106 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 9.3GB | 82/106 | `███░░░░░░░░░░░░ 23%` |
| 9 | `experiment/local.topologicalSort` | 8.97GB | 94/106 | `███░░░░░░░░░░░░ 22%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 8.83GB | 95/106 | `███░░░░░░░░░░░░ 22%` |

## Alerts

No anomalies detected.
