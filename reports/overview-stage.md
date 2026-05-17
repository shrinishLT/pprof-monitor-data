# Overview: stage
*Last updated: 2026-05-17 11:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T11:01 (82 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,068 | avg: 14,149 | max: 14,653 | trend: decreasing (-0.61/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 107.5MB | avg: 147.2MB | max: 213.6MB | trend: INCREASING (+0.59MB/hr))
```
▂▄▁▅▃▃▂▃▅▆▁▂▅▄▁▅▁▁▅▅▁▁▆▆▇▃▃▆▂▃▅▆▁▃▅▅▂▄▂▂▂▂▅▂▂▄▂▂▄▄▄▅▆▃▂▂▄▄▃▁▂▁▅▅▄▅▅▅▅▅▆█▄▆▂▅▅▄▆▅▄▁
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,068 | 14,067 | +1 | 14,149 | 14,653 | decreasing (-0.61/hr) |
| Heap InUse | 107.5MB | 151.3MB | -43.8MB | 147.2MB | 213.6MB | INCREASING (+0.59MB/hr) |
| Heap Sys | 1013.0MB | 1013.0MB | +0.0MB | 822.2MB | 1016.6MB | |
| Heap Objects | 346,564 | 920,541 | -573977 | 815,515 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 23 | 14,129 | 159.2MB | 213.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.5MB |
| 6 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `reflect.mapassign_faststr0` | 1.5MB |
| 10 | `v3/newrelic.newAnalyticsEvents` | 1.06MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 61.59GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 28.27GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 27.02GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 26.69GB |
| 5 | `reflect.unsafe_NewArray` | 26.62GB |
| 6 | `internal/evaluation.mergeMetadata` | 25.99GB |
| 7 | `reflect.MakeSlice` | 14.8GB |
| 8 | `experiment/local.topologicalSort` | 13.32GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 13.2GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 12.3GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 80/82 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/82 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 10.8MB | 77/82 | `████░░░░░░░░░░░ 29%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 80/82 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.88MB | 72/82 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/82 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/82 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/82 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `segmentio/kafka-go.makePartitions` | 3.01MB | 64/82 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.76MB | 2/82 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 29.31GB | 73/82 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 17.5GB | 58/82 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.mergeMetadata` | 13.92GB | 69/82 | `███████░░░░░░░░ 47%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 13.34GB | 75/82 | `██████░░░░░░░░░ 45%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 13.33GB | 74/82 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 12.67GB | 73/82 | `██████░░░░░░░░░ 43%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 7.64GB | 58/82 | `███░░░░░░░░░░░░ 26%` |
| 8 | `reflect.MakeSlice` | 7.25GB | 71/82 | `███░░░░░░░░░░░░ 24%` |
| 9 | `experiment/local.topologicalSort` | 7.03GB | 70/82 | `███░░░░░░░░░░░░ 23%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 6.92GB | 71/82 | `███░░░░░░░░░░░░ 23%` |

## Alerts

No anomalies detected.
