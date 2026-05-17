# Overview: stage
*Last updated: 2026-05-17 15:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T15:31 (91 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,067 | avg: 14,146 | max: 14,653 | trend: decreasing (-0.84/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁
```

**Heap InUse** (current: 138.0MB | avg: 147.8MB | max: 213.6MB | trend: stable (+0.50MB/hr))
```
▂▄▁▅▃▃▂▃▅▆▁▂▅▄▁▅▁▁▅▅▁▁▆▆▇▃▃▆▂▃▅▆▁▃▅▅▂▄▂▂▂▂▅▂▂▄▂▂▄▄▄▅▆▃▂▂▄▄▃▁▂▁▅▅▄▅▅▅▅▅▆█▄▆▂▅▅▄▆▅▄▁▄▄▅▃▅▅▂▆▃
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 13%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,067 | 14,096 | -29 | 14,146 | 14,653 | decreasing (-0.84/hr) |
| Heap InUse | 138.0MB | 180.5MB | -42.5MB | 147.8MB | 213.6MB | stable (+0.50MB/hr) |
| Heap Sys | 1013.2MB | 1013.1MB | +0.1MB | 841.1MB | 1016.6MB | |
| Heap Objects | 725,391 | 1,235,793 | -510402 | 820,467 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 32 | 14,125 | 157.5MB | 213.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.01MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `reflect.unsafe_NewArray` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 69.61GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 30.97GB |
| 3 | `reflect.unsafe_NewArray` | 30.01GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 29.61GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 29.25GB |
| 6 | `internal/evaluation.mergeMetadata` | 28.45GB |
| 7 | `reflect.MakeSlice` | 16.71GB |
| 8 | `experiment/local.topologicalSort` | 14.58GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 14.42GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 13.47GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 89/91 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/91 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 10.94MB | 86/91 | `████░░░░░░░░░░░ 29%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 89/91 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.89MB | 81/91 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/91 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/91 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/91 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.95MB | 73/91 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.76MB | 2/91 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 33.35GB | 82/91 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 19.13GB | 67/91 | `████████░░░░░░░ 57%` |
| 3 | `internal/evaluation.mergeMetadata` | 15.46GB | 78/91 | `██████░░░░░░░░░ 46%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 14.95GB | 84/91 | `██████░░░░░░░░░ 44%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 14.92GB | 83/91 | `██████░░░░░░░░░ 44%` |
| 6 | `reflect.unsafe_NewArray` | 14.41GB | 82/91 | `██████░░░░░░░░░ 43%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 8.34GB | 67/91 | `███░░░░░░░░░░░░ 25%` |
| 8 | `reflect.MakeSlice` | 8.22GB | 80/91 | `███░░░░░░░░░░░░ 24%` |
| 9 | `experiment/local.topologicalSort` | 7.82GB | 79/91 | `███░░░░░░░░░░░░ 23%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 7.7GB | 80/91 | `███░░░░░░░░░░░░ 23%` |

## Alerts

No anomalies detected.
