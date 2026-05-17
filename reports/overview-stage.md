# Overview: stage
*Last updated: 2026-05-17 12:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T12:31 (85 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,114 | avg: 14,148 | max: 14,653 | trend: decreasing (-0.72/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁▂▁▁
```

**Heap InUse** (current: 171.8MB | avg: 147.6MB | max: 213.6MB | trend: INCREASING (+0.58MB/hr))
```
▂▄▁▅▃▃▂▃▅▆▁▂▅▄▁▅▁▁▅▅▁▁▆▆▇▃▃▆▂▃▅▆▁▃▅▅▂▄▂▂▂▂▅▂▂▄▂▂▄▄▄▅▆▃▂▂▄▄▃▁▂▁▅▅▄▅▅▅▅▅▆█▄▆▂▅▅▄▆▅▄▁▄▄▅
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 16%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,114 | 14,064 | +50 | 14,148 | 14,653 | decreasing (-0.72/hr) |
| Heap InUse | 171.8MB | 153.0MB | +18.8MB | 147.6MB | 213.6MB | INCREASING (+0.58MB/hr) |
| Heap Sys | 1013.1MB | 1013.0MB | +0.1MB | 829.0MB | 1016.6MB | |
| Heap Objects | 1,078,097 | 953,238 | +124859 | 818,458 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 26 | 14,127 | 159.1MB | 213.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 6 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `reflect.unsafe_NewArray` | 2.0MB |
| 10 | `reflect.mapassign_faststr0` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 64.23GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 29.03GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 27.8GB |
| 4 | `reflect.unsafe_NewArray` | 27.76GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 27.46GB |
| 6 | `internal/evaluation.mergeMetadata` | 26.73GB |
| 7 | `reflect.MakeSlice` | 15.45GB |
| 8 | `experiment/local.topologicalSort` | 13.72GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 13.57GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 12.63GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 83/85 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/85 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 10.85MB | 80/85 | `████░░░░░░░░░░░ 29%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 83/85 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.88MB | 75/85 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/85 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/85 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/85 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `segmentio/kafka-go.makePartitions` | 3.02MB | 67/85 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.76MB | 2/85 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 30.66GB | 76/85 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 18.05GB | 61/85 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.mergeMetadata` | 14.44GB | 72/85 | `███████░░░░░░░░ 47%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 13.87GB | 78/85 | `██████░░░░░░░░░ 45%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 13.86GB | 77/85 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 13.25GB | 76/85 | `██████░░░░░░░░░ 43%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 7.88GB | 61/85 | `███░░░░░░░░░░░░ 25%` |
| 8 | `reflect.MakeSlice` | 7.58GB | 74/85 | `███░░░░░░░░░░░░ 24%` |
| 9 | `experiment/local.topologicalSort` | 7.29GB | 73/85 | `███░░░░░░░░░░░░ 23%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 7.18GB | 74/85 | `███░░░░░░░░░░░░ 23%` |

## Alerts

No anomalies detected.
