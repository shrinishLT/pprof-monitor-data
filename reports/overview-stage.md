# Overview: stage
*Last updated: 2026-05-17 13:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T13:31 (87 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,076 | avg: 14,148 | max: 14,653 | trend: decreasing (-0.69/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁▂▁▁▂▁
```

**Heap InUse** (current: 167.3MB | avg: 147.7MB | max: 213.6MB | trend: INCREASING (+0.56MB/hr))
```
▂▄▁▅▃▃▂▃▅▆▁▂▅▄▁▅▁▁▅▅▁▁▆▆▇▃▃▆▂▃▅▆▁▃▅▅▂▄▂▂▂▂▅▂▂▄▂▂▄▄▄▅▆▃▂▂▄▄▃▁▂▁▅▅▄▅▅▅▅▅▆█▄▆▂▅▅▄▆▅▄▁▄▄▅▃▅
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 16%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,076 | 14,210 | -134 | 14,148 | 14,653 | decreasing (-0.69/hr) |
| Heap InUse | 167.3MB | 137.1MB | +30.2MB | 147.7MB | 213.6MB | INCREASING (+0.56MB/hr) |
| Heap Sys | 1013.2MB | 1012.9MB | +0.3MB | 833.2MB | 1016.6MB | |
| Heap Objects | 1,070,126 | 528,228 | +541898 | 818,015 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 28 | 14,128 | 158.6MB | 213.6MB |

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
| 8 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 9 | `reflect.mapassign_faststr0` | 2.0MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 65.99GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 29.64GB |
| 3 | `reflect.unsafe_NewArray` | 28.5GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 28.48GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 28.13GB |
| 6 | `internal/evaluation.mergeMetadata` | 27.36GB |
| 7 | `reflect.MakeSlice` | 15.86GB |
| 8 | `experiment/local.topologicalSort` | 14.04GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 13.89GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 12.89GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 85/87 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/87 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 10.88MB | 82/87 | `████░░░░░░░░░░░ 29%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 85/87 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.88MB | 77/87 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/87 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/87 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/87 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.98MB | 69/87 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.76MB | 2/87 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 31.55GB | 78/87 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 18.41GB | 63/87 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.mergeMetadata` | 14.78GB | 74/87 | `███████░░░░░░░░ 46%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 14.23GB | 80/87 | `██████░░░░░░░░░ 45%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 14.22GB | 79/87 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 13.64GB | 78/87 | `██████░░░░░░░░░ 43%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 8.03GB | 63/87 | `███░░░░░░░░░░░░ 25%` |
| 8 | `reflect.MakeSlice` | 7.79GB | 76/87 | `███░░░░░░░░░░░░ 24%` |
| 9 | `experiment/local.topologicalSort` | 7.47GB | 75/87 | `███░░░░░░░░░░░░ 23%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 7.35GB | 76/87 | `███░░░░░░░░░░░░ 23%` |

## Alerts

No anomalies detected.
