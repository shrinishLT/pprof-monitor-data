# Overview: stage
*Last updated: 2026-05-17 18:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T18:31 (97 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,074 | avg: 14,142 | max: 14,653 | trend: decreasing (-1.08/hr))
```
▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁▂▁▁▁▁▁
```

**Heap InUse** (current: 132.6MB | avg: 148.0MB | max: 213.6MB | trend: stable (+0.45MB/hr))
```
▄▁▅▃▃▂▃▅▆▁▂▅▄▁▅▁▁▅▅▁▁▆▆▇▃▃▆▂▃▅▆▁▃▅▅▂▄▂▂▂▂▅▂▂▄▂▂▄▄▄▅▆▃▂▂▄▄▃▁▂▁▅▅▄▅▅▅▅▅▆█▄▆▂▅▅▄▆▅▄▁▄▄▅▃▅▅▂▆▃▃▅▃▄▅▃
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 13%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,074 | 14,083 | -9 | 14,142 | 14,653 | decreasing (-1.08/hr) |
| Heap InUse | 132.6MB | 178.4MB | -45.8MB | 148.0MB | 213.6MB | stable (+0.45MB/hr) |
| Heap Sys | 1013.2MB | 1013.2MB | +0.0MB | 851.8MB | 1016.6MB | |
| Heap Objects | 683,244 | 1,165,512 | -482268 | 826,257 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 38 | 14,120 | 156.7MB | 213.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `reflect.mapassign_faststr0` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 74.99GB |
| 2 | `reflect.unsafe_NewArray` | 32.34GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 31.26GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 30.17GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 29.76GB |
| 6 | `internal/evaluation.mergeMetadata` | 28.94GB |
| 7 | `reflect.MakeSlice` | 18.03GB |
| 8 | `experiment/local.topologicalSort` | 14.83GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 14.69GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 13.61GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 95/97 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/97 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 11.01MB | 92/97 | `████░░░░░░░░░░░ 30%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 95/97 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.9MB | 87/97 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/97 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/97 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.25MB | 2/97 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.97MB | 78/97 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.76MB | 2/97 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 36.04GB | 88/97 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 20.12GB | 73/97 | `████████░░░░░░░ 55%` |
| 3 | `internal/evaluation.mergeMetadata` | 16.41GB | 84/97 | `██████░░░░░░░░░ 45%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 15.94GB | 90/97 | `██████░░░░░░░░░ 44%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 15.91GB | 89/97 | `██████░░░░░░░░░ 44%` |
| 6 | `reflect.unsafe_NewArray` | 15.57GB | 88/97 | `██████░░░░░░░░░ 43%` |
| 7 | `reflect.MakeSlice` | 8.87GB | 86/97 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 8.77GB | 73/97 | `███░░░░░░░░░░░░ 24%` |
| 9 | `experiment/local.topologicalSort` | 8.31GB | 85/97 | `███░░░░░░░░░░░░ 23%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 8.18GB | 86/97 | `███░░░░░░░░░░░░ 22%` |

## Alerts

No anomalies detected.
