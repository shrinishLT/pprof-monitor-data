# Overview: stage
*Last updated: 2026-05-17 21:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T21:03 (102 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,064 | avg: 14,139 | max: 14,653 | trend: decreasing (-1.30/hr))
```
▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 110.0MB | avg: 147.1MB | max: 213.6MB | trend: stable (+0.28MB/hr))
```
▂▃▅▆▁▂▅▄▁▅▁▁▅▅▁▁▆▆▇▃▃▆▂▃▅▆▁▃▅▅▂▄▂▂▂▂▅▂▂▄▂▂▄▄▄▅▆▃▂▂▄▄▃▁▂▁▅▅▄▅▅▅▅▅▆█▄▆▂▅▅▄▆▅▄▁▄▄▅▃▅▅▂▆▃▃▅▃▄▅▃▂▃▁▆▂
```

## Current Status

Goroutines: `███████████████████░ 95%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,064 | 14,075 | -11 | 14,139 | 14,653 | decreasing (-1.30/hr) |
| Heap InUse | 110.0MB | 179.3MB | -69.3MB | 147.1MB | 213.6MB | stable (+0.28MB/hr) |
| Heap Sys | 1013.3MB | 1013.3MB | +0.0MB | 859.7MB | 1016.6MB | |
| Heap Objects | 397,499 | 1,276,022 | -878523 | 816,654 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 43 | 14,115 | 153.4MB | 213.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 5.5MB |
| 6 | `compress/flate.NewWriter` | 3.53MB |
| 7 | `reflect.unsafe_NewArray` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `reflect.mapassign_faststr0` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 79.53GB |
| 2 | `reflect.unsafe_NewArray` | 34.33GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 31.26GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 30.77GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 30.36GB |
| 6 | `internal/evaluation.mergeMetadata` | 29.5GB |
| 7 | `reflect.MakeSlice` | 19.13GB |
| 8 | `experiment/local.topologicalSort` | 15.14GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 15.01GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 13.61GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 100/102 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/102 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 11.07MB | 97/102 | `████░░░░░░░░░░░ 30%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 100/102 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.9MB | 92/102 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/102 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/102 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.25MB | 2/102 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `segmentio/kafka-go.makePartitions` | 3.04MB | 82/102 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.76MB | 2/102 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 38.28GB | 93/102 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 20.83GB | 78/102 | `████████░░░░░░░ 54%` |
| 3 | `internal/evaluation.mergeMetadata` | 17.13GB | 89/102 | `██████░░░░░░░░░ 44%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 16.71GB | 95/102 | `██████░░░░░░░░░ 43%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 16.66GB | 94/102 | `██████░░░░░░░░░ 43%` |
| 6 | `reflect.unsafe_NewArray` | 16.54GB | 93/102 | `██████░░░░░░░░░ 43%` |
| 7 | `reflect.MakeSlice` | 9.41GB | 91/102 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 9.08GB | 78/102 | `███░░░░░░░░░░░░ 23%` |
| 9 | `experiment/local.topologicalSort` | 8.68GB | 90/102 | `███░░░░░░░░░░░░ 22%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 8.55GB | 91/102 | `███░░░░░░░░░░░░ 22%` |

## Alerts

No anomalies detected.
