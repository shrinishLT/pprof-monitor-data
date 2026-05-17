# Overview: stage
*Last updated: 2026-05-17 14:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T14:31 (89 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,067 | avg: 14,147 | max: 14,653 | trend: decreasing (-0.70/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁
```

**Heap InUse** (current: 115.6MB | avg: 147.5MB | max: 213.6MB | trend: stable (+0.50MB/hr))
```
▂▄▁▅▃▃▂▃▅▆▁▂▅▄▁▅▁▁▅▅▁▁▆▆▇▃▃▆▂▃▅▆▁▃▅▅▂▄▂▂▂▂▅▂▂▄▂▂▄▄▄▅▆▃▂▂▄▄▃▁▂▁▅▅▄▅▅▅▅▅▆█▄▆▂▅▅▄▆▅▄▁▄▄▅▃▅▅▂
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 11%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,067 | 14,190 | -123 | 14,147 | 14,653 | decreasing (-0.70/hr) |
| Heap InUse | 115.6MB | 165.8MB | -50.2MB | 147.5MB | 213.6MB | stable (+0.50MB/hr) |
| Heap Sys | 1013.2MB | 1013.2MB | +0.0MB | 837.3MB | 1016.6MB | |
| Heap Objects | 467,793 | 1,066,296 | -598503 | 816,869 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 30 | 14,128 | 157.4MB | 213.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `segmentio/kafka-go.makePartitions` | 1.5MB |
| 10 | `reflect.mapassign_faststr0` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 67.82GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 30.31GB |
| 3 | `reflect.unsafe_NewArray` | 29.25GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 29.02GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 28.68GB |
| 6 | `internal/evaluation.mergeMetadata` | 27.91GB |
| 7 | `reflect.MakeSlice` | 16.28GB |
| 8 | `experiment/local.topologicalSort` | 14.31GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 14.14GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 13.2GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 87/89 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/89 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 10.91MB | 84/89 | `████░░░░░░░░░░░ 29%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 87/89 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.89MB | 79/89 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/89 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/89 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/89 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.97MB | 71/89 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.76MB | 2/89 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 32.45GB | 80/89 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 18.77GB | 65/89 | `████████░░░░░░░ 57%` |
| 3 | `internal/evaluation.mergeMetadata` | 15.12GB | 76/89 | `██████░░░░░░░░░ 46%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 14.59GB | 82/89 | `██████░░░░░░░░░ 44%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 14.57GB | 81/89 | `██████░░░░░░░░░ 44%` |
| 6 | `reflect.unsafe_NewArray` | 14.03GB | 80/89 | `██████░░░░░░░░░ 43%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 8.19GB | 65/89 | `███░░░░░░░░░░░░ 25%` |
| 8 | `reflect.MakeSlice` | 8.01GB | 78/89 | `███░░░░░░░░░░░░ 24%` |
| 9 | `experiment/local.topologicalSort` | 7.64GB | 77/89 | `███░░░░░░░░░░░░ 23%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 7.53GB | 78/89 | `███░░░░░░░░░░░░ 23%` |

## Alerts

No anomalies detected.
