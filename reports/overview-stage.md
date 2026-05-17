# Overview: stage
*Last updated: 2026-05-17 08:32 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T08:32 (77 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,065 | avg: 14,153 | max: 14,653 | trend: stable (-0.00/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁
```

**Heap InUse** (current: 176.9MB | avg: 146.7MB | max: 213.6MB | trend: INCREASING (+0.64MB/hr))
```
▂▄▁▅▃▃▂▃▅▆▁▂▅▄▁▅▁▁▅▅▁▁▆▆▇▃▃▆▂▃▅▆▁▃▅▅▂▄▂▂▂▂▅▂▂▄▂▂▄▄▄▅▆▃▂▂▄▄▃▁▂▁▅▅▄▅▅▅▅▅▆█▄▆▂▅▅
```

## Current Status

Goroutines: `███████████████████░ 95%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 17%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,065 | 14,110 | -45 | 14,153 | 14,653 | stable (-0.00/hr) |
| Heap InUse | 176.9MB | 175.1MB | +1.8MB | 146.7MB | 213.6MB | INCREASING (+0.64MB/hr) |
| Heap Sys | 1013.0MB | 1013.0MB | +0.0MB | 809.9MB | 1016.6MB | |
| Heap Objects | 1,281,544 | 1,226,117 | +55427 | 806,740 | 1,343,690 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 18 | 14,142 | 160.5MB | 213.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 57.16GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 28.27GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 26.75GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 26.41GB |
| 5 | `internal/evaluation.mergeMetadata` | 25.73GB |
| 6 | `reflect.unsafe_NewArray` | 24.65GB |
| 7 | `reflect.MakeSlice` | 13.72GB |
| 8 | `experiment/local.topologicalSort` | 13.18GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 13.05GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 12.3GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 75/77 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/77 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 10.71MB | 72/77 | `████░░░░░░░░░░░ 29%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 75/77 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.87MB | 67/77 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/77 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/77 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/77 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.94MB | 60/77 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.76MB | 2/77 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 27.07GB | 68/77 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 16.49GB | 53/77 | `█████████░░░░░░ 60%` |
| 3 | `internal/evaluation.mergeMetadata` | 12.99GB | 64/77 | `███████░░░░░░░░ 47%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 12.36GB | 69/77 | `██████░░░░░░░░░ 45%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 12.36GB | 70/77 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 11.71GB | 68/77 | `██████░░░░░░░░░ 43%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 7.2GB | 53/77 | `███░░░░░░░░░░░░ 26%` |
| 8 | `reflect.MakeSlice` | 6.72GB | 66/77 | `███░░░░░░░░░░░░ 24%` |
| 9 | `experiment/local.topologicalSort` | 6.54GB | 65/77 | `███░░░░░░░░░░░░ 24%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 6.45GB | 66/77 | `███░░░░░░░░░░░░ 23%` |

## Alerts

No anomalies detected.
