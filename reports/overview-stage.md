# Overview: stage
*Last updated: 2026-05-17 10:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T10:03 (80 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,127 | avg: 14,151 | max: 14,653 | trend: stable (-0.34/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁
```

**Heap InUse** (current: 163.6MB | avg: 147.6MB | max: 213.6MB | trend: INCREASING (+0.70MB/hr))
```
▂▄▁▅▃▃▂▃▅▆▁▂▅▄▁▅▁▁▅▅▁▁▆▆▇▃▃▆▂▃▅▆▁▃▅▅▂▄▂▂▂▂▅▂▂▄▂▂▄▄▄▅▆▃▂▂▄▄▃▁▂▁▅▅▄▅▅▅▅▅▆█▄▆▂▅▅▄▆▅
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 16%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,127 | 14,075 | +52 | 14,151 | 14,653 | stable (-0.34/hr) |
| Heap InUse | 163.6MB | 192.0MB | -28.4MB | 147.6MB | 213.6MB | INCREASING (+0.70MB/hr) |
| Heap Sys | 1013.0MB | 1013.0MB | +0.0MB | 817.5MB | 1016.6MB | |
| Heap Objects | 1,069,013 | 1,405,098 | -336085 | 820,064 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 21 | 14,134 | 162.1MB | 213.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `reflect.unsafe_NewArray` | 3.01MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `reflect.mapassign_faststr0` | 2.0MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 59.91GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 28.27GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 26.98GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 26.65GB |
| 5 | `internal/evaluation.mergeMetadata` | 25.96GB |
| 6 | `reflect.unsafe_NewArray` | 25.85GB |
| 7 | `reflect.MakeSlice` | 14.38GB |
| 8 | `experiment/local.topologicalSort` | 13.31GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 13.18GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 12.3GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 78/80 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/80 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 10.77MB | 75/80 | `████░░░░░░░░░░░ 29%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 78/80 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.87MB | 70/80 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/80 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/80 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/80 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.97MB | 62/80 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.76MB | 2/80 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 28.42GB | 71/80 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 17.12GB | 56/80 | `█████████░░░░░░ 60%` |
| 3 | `internal/evaluation.mergeMetadata` | 13.56GB | 67/80 | `███████░░░░░░░░ 47%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 12.96GB | 73/80 | `██████░░░░░░░░░ 45%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 12.96GB | 72/80 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 12.29GB | 71/80 | `██████░░░░░░░░░ 43%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 7.47GB | 56/80 | `███░░░░░░░░░░░░ 26%` |
| 8 | `reflect.MakeSlice` | 7.04GB | 69/80 | `███░░░░░░░░░░░░ 24%` |
| 9 | `experiment/local.topologicalSort` | 6.84GB | 68/80 | `███░░░░░░░░░░░░ 24%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 6.74GB | 69/80 | `███░░░░░░░░░░░░ 23%` |

## Alerts

No anomalies detected.
