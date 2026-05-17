# Overview: stage
*Last updated: 2026-05-17 20:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T20:03 (100 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,079 | avg: 14,141 | max: 14,653 | trend: decreasing (-1.21/hr))
```
▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁▂▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 108.3MB | avg: 147.1MB | max: 213.6MB | trend: stable (+0.30MB/hr))
```
▃▃▂▃▅▆▁▂▅▄▁▅▁▁▅▅▁▁▆▆▇▃▃▆▂▃▅▆▁▃▅▅▂▄▂▂▂▂▅▂▂▄▂▂▄▄▄▅▆▃▂▂▄▄▃▁▂▁▅▅▄▅▅▅▅▅▆█▄▆▂▅▅▄▆▅▄▁▄▄▅▃▅▅▂▆▃▃▅▃▄▅▃▂▃▁
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,079 | 14,073 | +6 | 14,141 | 14,653 | decreasing (-1.21/hr) |
| Heap InUse | 108.3MB | 129.9MB | -21.6MB | 147.1MB | 213.6MB | stable (+0.30MB/hr) |
| Heap Sys | 1013.3MB | 1013.2MB | +0.1MB | 856.6MB | 1016.6MB | |
| Heap Objects | 352,102 | 686,917 | -334815 | 816,252 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 41 | 14,117 | 153.8MB | 213.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `reflect.mapassign_faststr0` | 1.5MB |
| 10 | `encoding/json.(*decodeState).literalStore` | 1.04MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 77.77GB |
| 2 | `reflect.unsafe_NewArray` | 33.56GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 31.26GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 30.59GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 30.17GB |
| 6 | `internal/evaluation.mergeMetadata` | 29.32GB |
| 7 | `reflect.MakeSlice` | 18.71GB |
| 8 | `experiment/local.topologicalSort` | 15.05GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 14.91GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 13.61GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 98/100 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/100 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 11.05MB | 95/100 | `████░░░░░░░░░░░ 30%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 98/100 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.9MB | 90/100 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/100 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/100 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.25MB | 2/100 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.99MB | 80/100 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.76MB | 2/100 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 37.38GB | 91/100 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 20.56GB | 76/100 | `████████░░░░░░░ 55%` |
| 3 | `internal/evaluation.mergeMetadata` | 16.85GB | 87/100 | `██████░░░░░░░░░ 45%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 16.41GB | 93/100 | `██████░░░░░░░░░ 43%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 16.37GB | 92/100 | `██████░░░░░░░░░ 43%` |
| 6 | `reflect.unsafe_NewArray` | 16.15GB | 91/100 | `██████░░░░░░░░░ 43%` |
| 7 | `reflect.MakeSlice` | 9.19GB | 89/100 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 8.96GB | 76/100 | `███░░░░░░░░░░░░ 23%` |
| 9 | `experiment/local.topologicalSort` | 8.53GB | 88/100 | `███░░░░░░░░░░░░ 22%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 8.4GB | 89/100 | `███░░░░░░░░░░░░ 22%` |

## Alerts

No anomalies detected.
