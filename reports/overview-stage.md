# Overview: stage
*Last updated: 2026-05-17 07:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T07:02 (74 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,185 | avg: 14,156 | max: 14,653 | trend: stable (+0.46/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂
```

**Heap InUse** (current: 185.7MB | avg: 146.2MB | max: 213.6MB | trend: INCREASING (+0.63MB/hr))
```
▂▄▁▅▃▃▂▃▅▆▁▂▅▄▁▅▁▁▅▅▁▁▆▆▇▃▃▆▂▃▅▆▁▃▅▅▂▄▂▂▂▂▅▂▂▄▂▂▄▄▄▅▆▃▂▂▄▄▃▁▂▁▅▅▄▅▅▅▅▅▆█▄▆
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 18%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,185 | 14,300 | -115 | 14,156 | 14,653 | stable (+0.46/hr) |
| Heap InUse | 185.7MB | 159.3MB | +26.4MB | 146.2MB | 213.6MB | INCREASING (+0.63MB/hr) |
| Heap Sys | 1013.0MB | 1012.9MB | +0.1MB | 801.6MB | 1016.6MB | |
| Heap Objects | 1,293,781 | 684,090 | +609691 | 798,367 | 1,343,690 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 15 | 14,153 | 160.9MB | 213.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `reflect.unsafe_NewArray` | 3.0MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 54.47GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 28.27GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 26.6GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 26.25GB |
| 5 | `internal/evaluation.mergeMetadata` | 25.59GB |
| 6 | `reflect.unsafe_NewArray` | 23.5GB |
| 7 | `experiment/local.topologicalSort` | 13.09GB |
| 8 | `reflect.MakeSlice` | 13.06GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 12.98GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 12.3GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 72/74 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/74 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 10.65MB | 69/74 | `████░░░░░░░░░░░ 29%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 72/74 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.86MB | 64/74 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/74 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/74 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/74 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.89MB | 57/74 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.76MB | 2/74 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 25.72GB | 65/74 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 15.78GB | 50/74 | `█████████░░░░░░ 61%` |
| 3 | `internal/evaluation.mergeMetadata` | 12.36GB | 61/74 | `███████░░░░░░░░ 48%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 11.73GB | 66/74 | `██████░░░░░░░░░ 45%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 11.72GB | 67/74 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 11.13GB | 65/74 | `██████░░░░░░░░░ 43%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 6.89GB | 50/74 | `████░░░░░░░░░░░ 26%` |
| 8 | `reflect.MakeSlice` | 6.39GB | 63/74 | `███░░░░░░░░░░░░ 24%` |
| 9 | `experiment/local.topologicalSort` | 6.22GB | 62/74 | `███░░░░░░░░░░░░ 24%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 6.13GB | 63/74 | `███░░░░░░░░░░░░ 23%` |

## Alerts

No anomalies detected.
