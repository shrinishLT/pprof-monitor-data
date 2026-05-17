# Overview: stage
*Last updated: 2026-05-17 16:32 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T16:32 (93 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,064 | avg: 14,145 | max: 14,653 | trend: decreasing (-0.83/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁▂▁
```

**Heap InUse** (current: 174.3MB | avg: 147.9MB | max: 213.6MB | trend: stable (+0.49MB/hr))
```
▂▄▁▅▃▃▂▃▅▆▁▂▅▄▁▅▁▁▅▅▁▁▆▆▇▃▃▆▂▃▅▆▁▃▅▅▂▄▂▂▂▂▅▂▂▄▂▂▄▄▄▅▆▃▂▂▄▄▃▁▂▁▅▅▄▅▅▅▅▅▆█▄▆▂▅▅▄▆▅▄▁▄▄▅▃▅▅▂▆▃▃▅
```

## Current Status

Goroutines: `███████████████████░ 95%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 17%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,064 | 14,202 | -138 | 14,145 | 14,653 | decreasing (-0.83/hr) |
| Heap InUse | 174.3MB | 136.8MB | +37.5MB | 147.9MB | 213.6MB | stable (+0.49MB/hr) |
| Heap Sys | 1013.2MB | 1013.2MB | +0.0MB | 844.8MB | 1016.6MB | |
| Heap Objects | 1,231,736 | 732,883 | +498853 | 823,948 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 34 | 14,126 | 157.4MB | 213.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `reflect.mapassign_faststr0` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 71.48GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 31.26GB |
| 3 | `reflect.unsafe_NewArray` | 30.82GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 29.84GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 29.45GB |
| 6 | `internal/evaluation.mergeMetadata` | 28.65GB |
| 7 | `reflect.MakeSlice` | 17.18GB |
| 8 | `experiment/local.topologicalSort` | 14.69GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 14.53GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 13.61GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 91/93 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/93 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 10.96MB | 88/93 | `████░░░░░░░░░░░ 29%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 91/93 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.89MB | 83/93 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/93 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/93 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.25MB | 2/93 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.95MB | 74/93 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.76MB | 2/93 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 34.24GB | 84/93 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 19.47GB | 69/93 | `████████░░░░░░░ 56%` |
| 3 | `internal/evaluation.mergeMetadata` | 15.79GB | 80/93 | `██████░░░░░░░░░ 46%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 15.29GB | 86/93 | `██████░░░░░░░░░ 44%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 15.26GB | 85/93 | `██████░░░░░░░░░ 44%` |
| 6 | `reflect.unsafe_NewArray` | 14.8GB | 84/93 | `██████░░░░░░░░░ 43%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 8.49GB | 69/93 | `███░░░░░░░░░░░░ 24%` |
| 8 | `reflect.MakeSlice` | 8.44GB | 82/93 | `███░░░░░░░░░░░░ 24%` |
| 9 | `experiment/local.topologicalSort` | 7.99GB | 81/93 | `███░░░░░░░░░░░░ 23%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 7.86GB | 82/93 | `███░░░░░░░░░░░░ 22%` |

## Alerts

No anomalies detected.
