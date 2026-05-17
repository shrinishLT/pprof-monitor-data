# Overview: stage
*Last updated: 2026-05-17 17:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T17:02 (94 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,064 | avg: 14,145 | max: 14,653 | trend: decreasing (-0.91/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁▂▁▁
```

**Heap InUse** (current: 136.5MB | avg: 147.8MB | max: 213.6MB | trend: stable (+0.46MB/hr))
```
▂▄▁▅▃▃▂▃▅▆▁▂▅▄▁▅▁▁▅▅▁▁▆▆▇▃▃▆▂▃▅▆▁▃▅▅▂▄▂▂▂▂▅▂▂▄▂▂▄▄▄▅▆▃▂▂▄▄▃▁▂▁▅▅▄▅▅▅▅▅▆█▄▆▂▅▅▄▆▅▄▁▄▄▅▃▅▅▂▆▃▃▅▃
```

## Current Status

Goroutines: `███████████████████░ 95%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 13%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,064 | 14,064 | +0 | 14,145 | 14,653 | decreasing (-0.91/hr) |
| Heap InUse | 136.5MB | 174.3MB | -37.8MB | 147.8MB | 213.6MB | stable (+0.46MB/hr) |
| Heap Sys | 1013.2MB | 1013.2MB | +0.0MB | 846.6MB | 1016.6MB | |
| Heap Objects | 710,617 | 1,231,736 | -521119 | 822,742 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 35 | 14,124 | 156.8MB | 213.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `reflect.unsafe_NewArray` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 72.34GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 31.26GB |
| 3 | `reflect.unsafe_NewArray` | 31.18GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 29.84GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 29.45GB |
| 6 | `internal/evaluation.mergeMetadata` | 28.65GB |
| 7 | `reflect.MakeSlice` | 17.4GB |
| 8 | `experiment/local.topologicalSort` | 14.69GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 14.53GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 13.61GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 92/94 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/94 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 10.98MB | 89/94 | `████░░░░░░░░░░░ 29%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 92/94 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.89MB | 84/94 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/94 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/94 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.25MB | 2/94 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.95MB | 75/94 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.76MB | 2/94 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 34.69GB | 85/94 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 19.64GB | 70/94 | `████████░░░░░░░ 56%` |
| 3 | `internal/evaluation.mergeMetadata` | 15.95GB | 81/94 | `██████░░░░░░░░░ 45%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 15.46GB | 87/94 | `██████░░░░░░░░░ 44%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 15.43GB | 86/94 | `██████░░░░░░░░░ 44%` |
| 6 | `reflect.unsafe_NewArray` | 14.99GB | 85/94 | `██████░░░░░░░░░ 43%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 8.57GB | 70/94 | `███░░░░░░░░░░░░ 24%` |
| 8 | `reflect.MakeSlice` | 8.55GB | 83/94 | `███░░░░░░░░░░░░ 24%` |
| 9 | `experiment/local.topologicalSort` | 8.07GB | 82/94 | `███░░░░░░░░░░░░ 23%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 7.94GB | 83/94 | `███░░░░░░░░░░░░ 22%` |

## Alerts

No anomalies detected.
