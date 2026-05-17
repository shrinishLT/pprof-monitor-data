# Overview: stage
*Last updated: 2026-05-17 15:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T15:03 (90 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,096 | avg: 14,147 | max: 14,653 | trend: decreasing (-0.75/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁
```

**Heap InUse** (current: 180.5MB | avg: 147.9MB | max: 213.6MB | trend: INCREASING (+0.53MB/hr))
```
▂▄▁▅▃▃▂▃▅▆▁▂▅▄▁▅▁▁▅▅▁▁▆▆▇▃▃▆▂▃▅▆▁▃▅▅▂▄▂▂▂▂▅▂▂▄▂▂▄▄▄▅▆▃▂▂▄▄▃▁▂▁▅▅▄▅▅▅▅▅▆█▄▆▂▅▅▄▆▅▄▁▄▄▅▃▅▅▂▆
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 17%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,096 | 14,067 | +29 | 14,147 | 14,653 | decreasing (-0.75/hr) |
| Heap InUse | 180.5MB | 115.6MB | +64.9MB | 147.9MB | 213.6MB | INCREASING (+0.53MB/hr) |
| Heap Sys | 1013.1MB | 1013.2MB | -0.1MB | 839.2MB | 1016.6MB | |
| Heap Objects | 1,235,793 | 467,793 | +768000 | 821,524 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 31 | 14,127 | 158.2MB | 213.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `aws/endpoints.init` | 2.0MB |
| 8 | `compress/flate.NewWriter` | 1.76MB |
| 9 | `segmentio/kafka-go.makePartitions` | 1.5MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 1.07MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 68.78GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 30.82GB |
| 3 | `reflect.unsafe_NewArray` | 29.64GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 29.46GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 29.09GB |
| 6 | `internal/evaluation.mergeMetadata` | 28.32GB |
| 7 | `reflect.MakeSlice` | 16.5GB |
| 8 | `experiment/local.topologicalSort` | 14.52GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 14.35GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 13.4GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 88/90 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/90 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 10.92MB | 85/90 | `████░░░░░░░░░░░ 29%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 88/90 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.89MB | 80/90 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/90 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/90 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/90 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.95MB | 72/90 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.76MB | 2/90 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 32.9GB | 81/90 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 18.95GB | 66/90 | `████████░░░░░░░ 57%` |
| 3 | `internal/evaluation.mergeMetadata` | 15.3GB | 77/90 | `██████░░░░░░░░░ 46%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 14.77GB | 83/90 | `██████░░░░░░░░░ 44%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 14.75GB | 82/90 | `██████░░░░░░░░░ 44%` |
| 6 | `reflect.unsafe_NewArray` | 14.22GB | 81/90 | `██████░░░░░░░░░ 43%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 8.27GB | 66/90 | `███░░░░░░░░░░░░ 25%` |
| 8 | `reflect.MakeSlice` | 8.12GB | 79/90 | `███░░░░░░░░░░░░ 24%` |
| 9 | `experiment/local.topologicalSort` | 7.73GB | 78/90 | `███░░░░░░░░░░░░ 23%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 7.61GB | 79/90 | `███░░░░░░░░░░░░ 23%` |

## Alerts

No anomalies detected.
