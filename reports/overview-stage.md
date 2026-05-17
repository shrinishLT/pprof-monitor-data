# Overview: stage
*Last updated: 2026-05-17 17:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T17:31 (95 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,071 | avg: 14,144 | max: 14,653 | trend: decreasing (-0.98/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁▂▁▁▁
```

**Heap InUse** (current: 155.1MB | avg: 147.9MB | max: 213.6MB | trend: stable (+0.45MB/hr))
```
▂▄▁▅▃▃▂▃▅▆▁▂▅▄▁▅▁▁▅▅▁▁▆▆▇▃▃▆▂▃▅▆▁▃▅▅▂▄▂▂▂▂▅▂▂▄▂▂▄▄▄▅▆▃▂▂▄▄▃▁▂▁▅▅▄▅▅▅▅▅▆█▄▆▂▅▅▄▆▅▄▁▄▄▅▃▅▅▂▆▃▃▅▃▄
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 15%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,071 | 14,064 | +7 | 14,144 | 14,653 | decreasing (-0.98/hr) |
| Heap InUse | 155.1MB | 136.5MB | +18.6MB | 147.9MB | 213.6MB | stable (+0.45MB/hr) |
| Heap Sys | 1013.2MB | 1013.2MB | +0.0MB | 848.4MB | 1016.6MB | |
| Heap Objects | 960,378 | 710,617 | +249761 | 824,191 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 36 | 14,122 | 156.8MB | 213.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.0MB |
| 6 | `reflect.unsafe_NewArray` | 3.0MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `compress/flate.NewWriter` | 1.76MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 73.2GB |
| 2 | `reflect.unsafe_NewArray` | 31.57GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 31.26GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 29.87GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 29.49GB |
| 6 | `internal/evaluation.mergeMetadata` | 28.68GB |
| 7 | `reflect.MakeSlice` | 17.6GB |
| 8 | `experiment/local.topologicalSort` | 14.7GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 14.54GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 13.61GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 93/95 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/95 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 10.99MB | 90/95 | `████░░░░░░░░░░░ 30%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 93/95 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.89MB | 85/95 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/95 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/95 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.25MB | 2/95 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.96MB | 76/95 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.76MB | 2/95 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 35.14GB | 86/95 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 19.81GB | 71/95 | `████████░░░░░░░ 56%` |
| 3 | `internal/evaluation.mergeMetadata` | 16.11GB | 82/95 | `██████░░░░░░░░░ 45%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 15.62GB | 88/95 | `██████░░░░░░░░░ 44%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 15.59GB | 87/95 | `██████░░░░░░░░░ 44%` |
| 6 | `reflect.unsafe_NewArray` | 15.18GB | 86/95 | `██████░░░░░░░░░ 43%` |
| 7 | `reflect.MakeSlice` | 8.65GB | 84/95 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 8.64GB | 71/95 | `███░░░░░░░░░░░░ 24%` |
| 9 | `experiment/local.topologicalSort` | 8.15GB | 83/95 | `███░░░░░░░░░░░░ 23%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 8.02GB | 84/95 | `███░░░░░░░░░░░░ 22%` |

## Alerts

No anomalies detected.
