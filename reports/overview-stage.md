# Overview: stage
*Last updated: 2026-05-17 16:04 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T16:04 (92 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,202 | avg: 14,146 | max: 14,653 | trend: decreasing (-0.74/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁▂
```

**Heap InUse** (current: 136.8MB | avg: 147.6MB | max: 213.6MB | trend: stable (+0.47MB/hr))
```
▂▄▁▅▃▃▂▃▅▆▁▂▅▄▁▅▁▁▅▅▁▁▆▆▇▃▃▆▂▃▅▆▁▃▅▅▂▄▂▂▂▂▅▂▂▄▂▂▄▄▄▅▆▃▂▂▄▄▃▁▂▁▅▅▄▅▅▅▅▅▆█▄▆▂▅▅▄▆▅▄▁▄▄▅▃▅▅▂▆▃▃
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 13%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,202 | 14,067 | +135 | 14,146 | 14,653 | decreasing (-0.74/hr) |
| Heap InUse | 136.8MB | 138.0MB | -1.2MB | 147.6MB | 213.6MB | stable (+0.47MB/hr) |
| Heap Sys | 1013.2MB | 1013.2MB | +0.0MB | 843.0MB | 1016.6MB | |
| Heap Objects | 732,883 | 725,391 | +7492 | 819,515 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 33 | 14,127 | 156.9MB | 213.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `internal/evaluation.mergeMetadata` | 3.0MB |
| 6 | `reflect.mapassign_faststr0` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `experiment/local.(*Client).EvaluateV2` | 2.16MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 70.68GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 30.97GB |
| 3 | `reflect.unsafe_NewArray` | 30.45GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 29.74GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 29.37GB |
| 6 | `internal/evaluation.mergeMetadata` | 28.57GB |
| 7 | `reflect.MakeSlice` | 16.97GB |
| 8 | `experiment/local.topologicalSort` | 14.65GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 14.49GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 13.47GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 90/92 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/92 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 10.95MB | 87/92 | `████░░░░░░░░░░░ 29%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 90/92 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.89MB | 82/92 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/92 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/92 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.25MB | 2/92 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.95MB | 73/92 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.76MB | 2/92 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 33.8GB | 83/92 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 19.3GB | 68/92 | `████████░░░░░░░ 57%` |
| 3 | `internal/evaluation.mergeMetadata` | 15.63GB | 79/92 | `██████░░░░░░░░░ 46%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 15.12GB | 85/92 | `██████░░░░░░░░░ 44%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 15.09GB | 84/92 | `██████░░░░░░░░░ 44%` |
| 6 | `reflect.unsafe_NewArray` | 14.6GB | 83/92 | `██████░░░░░░░░░ 43%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 8.42GB | 68/92 | `███░░░░░░░░░░░░ 24%` |
| 8 | `reflect.MakeSlice` | 8.33GB | 81/92 | `███░░░░░░░░░░░░ 24%` |
| 9 | `experiment/local.topologicalSort` | 7.91GB | 80/92 | `███░░░░░░░░░░░░ 23%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 7.78GB | 81/92 | `███░░░░░░░░░░░░ 23%` |

## Alerts

No anomalies detected.
