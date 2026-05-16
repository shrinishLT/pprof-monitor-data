# Overview: stage
*Last updated: 2026-05-16 18:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T18:31 (49 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,159 | avg: 14,160 | max: 14,653 | trend: INCREASING (+1.76/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂
```

**Heap InUse** (current: 152.8MB | avg: 141.1MB | max: 201.6MB | trend: stable (-0.12MB/hr))
```
▃▄▁▆▃▃▂▄▅▆▁▂▅▅▁▅▁▁▅▅▂▁▆▆█▄▄▆▃▃▆▆▁▄▅▆▂▅▂▂▃▂▅▂▂▅▂▂▄
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 15%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,159 | 14,078 | +81 | 14,160 | 14,653 | INCREASING (+1.76/hr) |
| Heap InUse | 152.8MB | 109.9MB | +42.9MB | 141.1MB | 201.6MB | stable (-0.12MB/hr) |
| Heap Sys | 1012.5MB | 1012.6MB | -0.1MB | 693.9MB | 1016.6MB | |
| Heap Objects | 867,089 | 386,671 | +480418 | 758,946 | 1,341,103 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 39 | 14,156 | 140.7MB | 201.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.51MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `bufio.NewWriterSize` | 2.02MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 31.89GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 16.23GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 16.09GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 15.89GB |
| 5 | `internal/evaluation.mergeMetadata` | 15.49GB |
| 6 | `reflect.unsafe_NewArray` | 13.8GB |
| 7 | `experiment/local.topologicalSort` | 7.93GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 7.88GB |
| 9 | `reflect.MakeSlice` | 7.7GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 7.09GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 47/49 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/49 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 9.83MB | 44/49 | `████░░░░░░░░░░░ 26%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.23MB | 47/49 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.77MB | 39/49 | `███░░░░░░░░░░░░ 23%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/49 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/49 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/49 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `reflect.unsafe_New` | 3.0MB | 1/49 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `segmentio/kafka-go.makePartitions` | 2.88MB | 34/49 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 14.5GB | 40/49 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 14.17GB | 25/49 | `██████████████░ 97%` |
| 3 | `internal/evaluation.mergeMetadata` | 7.24GB | 36/49 | `███████░░░░░░░░ 49%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 6.54GB | 41/49 | `██████░░░░░░░░░ 45%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 6.47GB | 42/49 | `██████░░░░░░░░░ 44%` |
| 6 | `reflect.unsafe_NewArray` | 6.31GB | 40/49 | `██████░░░░░░░░░ 43%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 6.2GB | 25/49 | `██████░░░░░░░░░ 42%` |
| 8 | `reflect.MakeSlice` | 3.71GB | 38/49 | `███░░░░░░░░░░░░ 25%` |
| 9 | `experiment/local.topologicalSort` | 3.61GB | 37/49 | `███░░░░░░░░░░░░ 24%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 3.52GB | 38/49 | `███░░░░░░░░░░░░ 24%` |

## Alerts

No anomalies detected.
