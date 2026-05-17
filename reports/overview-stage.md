# Overview: stage
*Last updated: 2026-05-17 20:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T20:31 (101 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,075 | avg: 14,140 | max: 14,653 | trend: decreasing (-1.25/hr))
```
▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁▂▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 179.3MB | avg: 147.4MB | max: 213.6MB | trend: stable (+0.33MB/hr))
```
▃▂▃▅▆▁▂▅▄▁▅▁▁▅▅▁▁▆▆▇▃▃▆▂▃▅▆▁▃▅▅▂▄▂▂▂▂▅▂▂▄▂▂▄▄▄▅▆▃▂▂▄▄▃▁▂▁▅▅▄▅▅▅▅▅▆█▄▆▂▅▅▄▆▅▄▁▄▄▅▃▅▅▂▆▃▃▅▃▄▅▃▂▃▁▆
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 17%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,075 | 14,079 | -4 | 14,140 | 14,653 | decreasing (-1.25/hr) |
| Heap InUse | 179.3MB | 108.3MB | +71.0MB | 147.4MB | 213.6MB | stable (+0.33MB/hr) |
| Heap Sys | 1013.3MB | 1013.3MB | +0.0MB | 858.2MB | 1016.6MB | |
| Heap Objects | 1,276,022 | 352,102 | +923920 | 820,804 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 42 | 14,116 | 154.4MB | 213.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.51MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `reflect.mapassign_faststr0` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 78.62GB |
| 2 | `reflect.unsafe_NewArray` | 33.92GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 31.26GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 30.77GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 30.36GB |
| 6 | `internal/evaluation.mergeMetadata` | 29.5GB |
| 7 | `reflect.MakeSlice` | 18.91GB |
| 8 | `experiment/local.topologicalSort` | 15.14GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 15.0GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 13.61GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 99/101 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/101 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 11.06MB | 96/101 | `████░░░░░░░░░░░ 30%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 99/101 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.9MB | 91/101 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/101 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/101 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.25MB | 2/101 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `segmentio/kafka-go.makePartitions` | 3.01MB | 81/101 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.76MB | 2/101 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 37.83GB | 92/101 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 20.7GB | 77/101 | `████████░░░░░░░ 54%` |
| 3 | `internal/evaluation.mergeMetadata` | 16.99GB | 88/101 | `██████░░░░░░░░░ 44%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 16.56GB | 94/101 | `██████░░░░░░░░░ 43%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 16.52GB | 93/101 | `██████░░░░░░░░░ 43%` |
| 6 | `reflect.unsafe_NewArray` | 16.34GB | 92/101 | `██████░░░░░░░░░ 43%` |
| 7 | `reflect.MakeSlice` | 9.3GB | 90/101 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 9.02GB | 77/101 | `███░░░░░░░░░░░░ 23%` |
| 9 | `experiment/local.topologicalSort` | 8.61GB | 89/101 | `███░░░░░░░░░░░░ 22%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 8.47GB | 90/101 | `███░░░░░░░░░░░░ 22%` |

## Alerts

No anomalies detected.
