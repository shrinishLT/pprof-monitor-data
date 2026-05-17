# Overview: stage
*Last updated: 2026-05-17 08:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T08:01 (76 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,110 | avg: 14,155 | max: 14,653 | trend: stable (+0.18/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁
```

**Heap InUse** (current: 175.1MB | avg: 146.3MB | max: 213.6MB | trend: INCREASING (+0.60MB/hr))
```
▂▄▁▅▃▃▂▃▅▆▁▂▅▄▁▅▁▁▅▅▁▁▆▆▇▃▃▆▂▃▅▆▁▃▅▅▂▄▂▂▂▂▅▂▂▄▂▂▄▄▄▅▆▃▂▂▄▄▃▁▂▁▅▅▄▅▅▅▅▅▆█▄▆▂▅
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 17%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,110 | 14,083 | +27 | 14,155 | 14,653 | stable (+0.18/hr) |
| Heap InUse | 175.1MB | 124.4MB | +50.7MB | 146.3MB | 213.6MB | INCREASING (+0.60MB/hr) |
| Heap Sys | 1013.0MB | 1013.0MB | +0.0MB | 807.2MB | 1016.6MB | |
| Heap Objects | 1,226,117 | 532,210 | +693907 | 800,493 | 1,343,690 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 17 | 14,146 | 159.6MB | 213.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `reflect.unsafe_NewArray` | 3.51MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `compress/flate.NewWriter` | 1.76MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 56.21GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 28.27GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 26.72GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 26.38GB |
| 5 | `internal/evaluation.mergeMetadata` | 25.71GB |
| 6 | `reflect.unsafe_NewArray` | 24.26GB |
| 7 | `reflect.MakeSlice` | 13.5GB |
| 8 | `experiment/local.topologicalSort` | 13.16GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 13.04GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 12.3GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 74/76 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/76 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 10.69MB | 71/76 | `████░░░░░░░░░░░ 29%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 74/76 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.86MB | 66/76 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/76 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/76 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/76 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.93MB | 59/76 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.76MB | 2/76 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 26.62GB | 67/76 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 16.26GB | 52/76 | `█████████░░░░░░ 61%` |
| 3 | `internal/evaluation.mergeMetadata` | 12.78GB | 63/76 | `███████░░░░░░░░ 48%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 12.16GB | 68/76 | `██████░░░░░░░░░ 45%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 12.15GB | 69/76 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 11.51GB | 67/76 | `██████░░░░░░░░░ 43%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 7.1GB | 52/76 | `████░░░░░░░░░░░ 26%` |
| 8 | `reflect.MakeSlice` | 6.61GB | 65/76 | `███░░░░░░░░░░░░ 24%` |
| 9 | `experiment/local.topologicalSort` | 6.44GB | 64/76 | `███░░░░░░░░░░░░ 24%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 6.34GB | 65/76 | `███░░░░░░░░░░░░ 23%` |

## Alerts

No anomalies detected.
