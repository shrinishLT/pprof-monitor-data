# Overview: stage
*Last updated: 2026-05-17 09:32 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T09:32 (79 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,075 | avg: 14,151 | max: 14,653 | trend: stable (-0.31/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁
```

**Heap InUse** (current: 192.0MB | avg: 147.4MB | max: 213.6MB | trend: INCREASING (+0.70MB/hr))
```
▂▄▁▅▃▃▂▃▅▆▁▂▅▄▁▅▁▁▅▅▁▁▆▆▇▃▃▆▂▃▅▆▁▃▅▅▂▄▂▂▂▂▅▂▂▄▂▂▄▄▄▅▆▃▂▂▄▄▃▁▂▁▅▅▄▅▅▅▅▅▆█▄▆▂▅▅▄▆
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 18%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,075 | 14,067 | +8 | 14,151 | 14,653 | stable (-0.31/hr) |
| Heap InUse | 192.0MB | 157.8MB | +34.2MB | 147.4MB | 213.6MB | INCREASING (+0.70MB/hr) |
| Heap Sys | 1013.0MB | 1013.0MB | +0.0MB | 815.0MB | 1016.6MB | |
| Heap Objects | 1,405,098 | 1,011,985 | +393113 | 816,913 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 20 | 14,135 | 162.0MB | 213.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 5.29MB |
| 6 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `segmentio/kafka-go.makePartitions` | 1.5MB |
| 10 | `reflect.mapassign_faststr0` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 59.0GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 28.27GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 26.95GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 26.62GB |
| 5 | `internal/evaluation.mergeMetadata` | 25.92GB |
| 6 | `reflect.unsafe_NewArray` | 25.46GB |
| 7 | `reflect.MakeSlice` | 14.16GB |
| 8 | `experiment/local.topologicalSort` | 13.29GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 13.17GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 12.3GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 77/79 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/79 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 10.75MB | 74/79 | `████░░░░░░░░░░░ 29%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 77/79 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.87MB | 69/79 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/79 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/79 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/79 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.97MB | 62/79 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.76MB | 2/79 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 27.97GB | 70/79 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 16.92GB | 55/79 | `█████████░░░░░░ 60%` |
| 3 | `internal/evaluation.mergeMetadata` | 13.38GB | 66/79 | `███████░░░░░░░░ 47%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 12.77GB | 72/79 | `██████░░░░░░░░░ 45%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 12.77GB | 71/79 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 12.09GB | 70/79 | `██████░░░░░░░░░ 43%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 7.39GB | 55/79 | `███░░░░░░░░░░░░ 26%` |
| 8 | `reflect.MakeSlice` | 6.93GB | 68/79 | `███░░░░░░░░░░░░ 24%` |
| 9 | `experiment/local.topologicalSort` | 6.75GB | 67/79 | `███░░░░░░░░░░░░ 24%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 6.64GB | 68/79 | `███░░░░░░░░░░░░ 23%` |

## Alerts

No anomalies detected.
