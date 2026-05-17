# Overview: stage
*Last updated: 2026-05-17 19:32 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T19:31 (99 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,073 | avg: 14,141 | max: 14,653 | trend: decreasing (-1.17/hr))
```
▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁▂▁▁▁▁▁▁▁
```

**Heap InUse** (current: 129.9MB | avg: 147.5MB | max: 213.6MB | trend: stable (+0.36MB/hr))
```
▅▃▃▂▃▅▆▁▂▅▄▁▅▁▁▅▅▁▁▆▆▇▃▃▆▂▃▅▆▁▃▅▅▂▄▂▂▂▂▅▂▂▄▂▂▄▄▄▅▆▃▂▂▄▄▃▁▂▁▅▅▄▅▅▅▅▅▆█▄▆▂▅▅▄▆▅▄▁▄▄▅▃▅▅▂▆▃▃▅▃▄▅▃▂▃
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 12%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,073 | 14,086 | -13 | 14,141 | 14,653 | decreasing (-1.17/hr) |
| Heap InUse | 129.9MB | 113.9MB | +16.0MB | 147.5MB | 213.6MB | stable (+0.36MB/hr) |
| Heap Sys | 1013.2MB | 1013.2MB | +0.0MB | 855.0MB | 1016.6MB | |
| Heap Objects | 686,917 | 439,268 | +247649 | 820,940 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 40 | 14,118 | 155.0MB | 213.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `reflect.unsafe_NewArray` | 2.0MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 76.83GB |
| 2 | `reflect.unsafe_NewArray` | 33.14GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 31.26GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 30.44GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 30.05GB |
| 6 | `internal/evaluation.mergeMetadata` | 29.19GB |
| 7 | `reflect.MakeSlice` | 18.47GB |
| 8 | `experiment/local.topologicalSort` | 14.98GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 14.84GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 13.61GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 97/99 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/99 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 11.04MB | 94/99 | `████░░░░░░░░░░░ 30%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 97/99 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.9MB | 89/99 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/99 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/99 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.25MB | 2/99 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.99MB | 80/99 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.76MB | 2/99 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 36.93GB | 90/99 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 20.42GB | 75/99 | `████████░░░░░░░ 55%` |
| 3 | `internal/evaluation.mergeMetadata` | 16.7GB | 86/99 | `██████░░░░░░░░░ 45%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 16.25GB | 92/99 | `██████░░░░░░░░░ 44%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 16.21GB | 91/99 | `██████░░░░░░░░░ 43%` |
| 6 | `reflect.unsafe_NewArray` | 15.96GB | 90/99 | `██████░░░░░░░░░ 43%` |
| 7 | `reflect.MakeSlice` | 9.09GB | 88/99 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 8.9GB | 75/99 | `███░░░░░░░░░░░░ 24%` |
| 9 | `experiment/local.topologicalSort` | 8.46GB | 87/99 | `███░░░░░░░░░░░░ 22%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 8.33GB | 88/99 | `███░░░░░░░░░░░░ 22%` |

## Alerts

No anomalies detected.
