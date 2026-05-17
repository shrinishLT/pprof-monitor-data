# Overview: stage
*Last updated: 2026-05-17 19:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T19:02 (98 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,086 | avg: 14,142 | max: 14,653 | trend: decreasing (-1.12/hr))
```
▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁▂▁▁▁▁▁▁
```

**Heap InUse** (current: 113.9MB | avg: 147.7MB | max: 213.6MB | trend: stable (+0.39MB/hr))
```
▁▅▃▃▂▃▅▆▁▂▅▄▁▅▁▁▅▅▁▁▆▆▇▃▃▆▂▃▅▆▁▃▅▅▂▄▂▂▂▂▅▂▂▄▂▂▄▄▄▅▆▃▂▂▄▄▃▁▂▁▅▅▄▅▅▅▅▅▆█▄▆▂▅▅▄▆▅▄▁▄▄▅▃▅▅▂▆▃▃▅▃▄▅▃▂
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 11%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,086 | 14,074 | +12 | 14,142 | 14,653 | decreasing (-1.12/hr) |
| Heap InUse | 113.9MB | 132.6MB | -18.7MB | 147.7MB | 213.6MB | stable (+0.39MB/hr) |
| Heap Sys | 1013.2MB | 1013.2MB | +0.0MB | 853.4MB | 1016.6MB | |
| Heap Objects | 439,268 | 683,244 | -243976 | 822,308 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 39 | 14,119 | 155.6MB | 213.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.0MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 1.07MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 75.99GB |
| 2 | `reflect.unsafe_NewArray` | 32.77GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 31.26GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 30.22GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 29.81GB |
| 6 | `internal/evaluation.mergeMetadata` | 28.99GB |
| 7 | `reflect.MakeSlice` | 18.27GB |
| 8 | `experiment/local.topologicalSort` | 14.86GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 14.72GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 13.61GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 96/98 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/98 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 11.02MB | 93/98 | `████░░░░░░░░░░░ 30%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 96/98 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.9MB | 88/98 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/98 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/98 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.25MB | 2/98 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.98MB | 79/98 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.76MB | 2/98 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 36.49GB | 89/98 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 20.27GB | 74/98 | `████████░░░░░░░ 55%` |
| 3 | `internal/evaluation.mergeMetadata` | 16.56GB | 85/98 | `██████░░░░░░░░░ 45%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 16.1GB | 91/98 | `██████░░░░░░░░░ 44%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 16.06GB | 90/98 | `██████░░░░░░░░░ 44%` |
| 6 | `reflect.unsafe_NewArray` | 15.76GB | 89/98 | `██████░░░░░░░░░ 43%` |
| 7 | `reflect.MakeSlice` | 8.98GB | 87/98 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 8.84GB | 74/98 | `███░░░░░░░░░░░░ 24%` |
| 9 | `experiment/local.topologicalSort` | 8.38GB | 86/98 | `███░░░░░░░░░░░░ 22%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 8.25GB | 87/98 | `███░░░░░░░░░░░░ 22%` |

## Alerts

No anomalies detected.
