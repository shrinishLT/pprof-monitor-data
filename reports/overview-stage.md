# Overview: stage
*Last updated: 2026-05-17 09:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T09:01 (78 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,067 | avg: 14,152 | max: 14,653 | trend: stable (-0.17/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁
```

**Heap InUse** (current: 157.8MB | avg: 146.8MB | max: 213.6MB | trend: INCREASING (+0.64MB/hr))
```
▂▄▁▅▃▃▂▃▅▆▁▂▅▄▁▅▁▁▅▅▁▁▆▆▇▃▃▆▂▃▅▆▁▃▅▅▂▄▂▂▂▂▅▂▂▄▂▂▄▄▄▅▆▃▂▂▄▄▃▁▂▁▅▅▄▅▅▅▅▅▆█▄▆▂▅▅▄
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 15%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,067 | 14,065 | +2 | 14,152 | 14,653 | stable (-0.17/hr) |
| Heap InUse | 157.8MB | 176.9MB | -19.1MB | 146.8MB | 213.6MB | INCREASING (+0.64MB/hr) |
| Heap Sys | 1013.0MB | 1013.0MB | +0.0MB | 812.5MB | 1016.6MB | |
| Heap Objects | 1,011,985 | 1,281,544 | -269559 | 809,372 | 1,343,690 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 19 | 14,138 | 160.4MB | 213.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 6.01MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `reflect.unsafe_NewArray` | 2.0MB |
| 10 | `reflect.mapassign_faststr0` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 57.99GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 28.27GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 26.88GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 26.55GB |
| 5 | `internal/evaluation.mergeMetadata` | 25.86GB |
| 6 | `reflect.unsafe_NewArray` | 25.02GB |
| 7 | `reflect.MakeSlice` | 13.93GB |
| 8 | `experiment/local.topologicalSort` | 13.25GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 13.13GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 12.3GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 76/78 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/78 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 10.73MB | 73/78 | `████░░░░░░░░░░░ 29%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 76/78 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.87MB | 68/78 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/78 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/78 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/78 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.99MB | 61/78 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.76MB | 2/78 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 27.52GB | 69/78 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 16.71GB | 54/78 | `█████████░░░░░░ 60%` |
| 3 | `internal/evaluation.mergeMetadata` | 13.18GB | 65/78 | `███████░░░░░░░░ 47%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 12.57GB | 70/78 | `██████░░░░░░░░░ 45%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 12.57GB | 71/78 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 11.9GB | 69/78 | `██████░░░░░░░░░ 43%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 7.29GB | 54/78 | `███░░░░░░░░░░░░ 26%` |
| 8 | `reflect.MakeSlice` | 6.82GB | 67/78 | `███░░░░░░░░░░░░ 24%` |
| 9 | `experiment/local.topologicalSort` | 6.65GB | 66/78 | `███░░░░░░░░░░░░ 24%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 6.55GB | 67/78 | `███░░░░░░░░░░░░ 23%` |

## Alerts

No anomalies detected.
