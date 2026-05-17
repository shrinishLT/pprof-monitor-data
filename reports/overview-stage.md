# Overview: stage
*Last updated: 2026-05-17 11:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T11:31 (83 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,163 | avg: 14,149 | max: 14,653 | trend: decreasing (-0.56/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁▂
```

**Heap InUse** (current: 149.6MB | avg: 147.2MB | max: 213.6MB | trend: INCREASING (+0.57MB/hr))
```
▂▄▁▅▃▃▂▃▅▆▁▂▅▄▁▅▁▁▅▅▁▁▆▆▇▃▃▆▂▃▅▆▁▃▅▅▂▄▂▂▂▂▅▂▂▄▂▂▄▄▄▅▆▃▂▂▄▄▃▁▂▁▅▅▄▅▅▅▅▅▆█▄▆▂▅▅▄▆▅▄▁▄
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 14%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,163 | 14,068 | +95 | 14,149 | 14,653 | decreasing (-0.56/hr) |
| Heap InUse | 149.6MB | 107.5MB | +42.1MB | 147.2MB | 213.6MB | INCREASING (+0.57MB/hr) |
| Heap Sys | 1012.7MB | 1013.0MB | -0.3MB | 824.5MB | 1016.6MB | |
| Heap Objects | 665,368 | 346,564 | +318804 | 813,706 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 24 | 14,130 | 158.8MB | 213.6MB |

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
| 8 | `reflect.mapassign_faststr0` | 2.0MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `bufio.NewWriterSize` | 1.53MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 62.48GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 28.42GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 27.07GB |
| 4 | `reflect.unsafe_NewArray` | 26.97GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 26.74GB |
| 6 | `internal/evaluation.mergeMetadata` | 26.04GB |
| 7 | `reflect.MakeSlice` | 15.0GB |
| 8 | `experiment/local.topologicalSort` | 13.34GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 13.22GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 12.37GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 81/83 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/83 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 10.82MB | 78/83 | `████░░░░░░░░░░░ 29%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 81/83 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.88MB | 73/83 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/83 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/83 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/83 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `segmentio/kafka-go.makePartitions` | 3.02MB | 65/83 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.76MB | 2/83 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 29.76GB | 74/83 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 17.69GB | 59/83 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.mergeMetadata` | 14.1GB | 70/83 | `███████░░░░░░░░ 47%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 13.52GB | 76/83 | `██████░░░░░░░░░ 45%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 13.51GB | 75/83 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 12.87GB | 74/83 | `██████░░░░░░░░░ 43%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 7.72GB | 59/83 | `███░░░░░░░░░░░░ 25%` |
| 8 | `reflect.MakeSlice` | 7.36GB | 72/83 | `███░░░░░░░░░░░░ 24%` |
| 9 | `experiment/local.topologicalSort` | 7.12GB | 71/83 | `███░░░░░░░░░░░░ 23%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 7.01GB | 72/83 | `███░░░░░░░░░░░░ 23%` |

## Alerts

No anomalies detected.
