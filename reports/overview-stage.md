# Overview: stage
*Last updated: 2026-05-17 12:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T12:03 (84 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,064 | avg: 14,148 | max: 14,653 | trend: decreasing (-0.69/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁▂▁
```

**Heap InUse** (current: 153.0MB | avg: 147.3MB | max: 213.6MB | trend: INCREASING (+0.56MB/hr))
```
▂▄▁▅▃▃▂▃▅▆▁▂▅▄▁▅▁▁▅▅▁▁▆▆▇▃▃▆▂▃▅▆▁▃▅▅▂▄▂▂▂▂▅▂▂▄▂▂▄▄▄▅▆▃▂▂▄▄▃▁▂▁▅▅▄▅▅▅▅▅▆█▄▆▂▅▅▄▆▅▄▁▄▄
```

## Current Status

Goroutines: `███████████████████░ 95%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 15%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,064 | 14,163 | -99 | 14,148 | 14,653 | decreasing (-0.69/hr) |
| Heap InUse | 153.0MB | 149.6MB | +3.4MB | 147.3MB | 213.6MB | INCREASING (+0.56MB/hr) |
| Heap Sys | 1013.0MB | 1012.7MB | +0.3MB | 826.8MB | 1016.6MB | |
| Heap Objects | 953,238 | 665,368 | +287870 | 815,367 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 25 | 14,127 | 158.6MB | 213.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 6 | `reflect.unsafe_NewArray` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `compress/flate.NewWriter` | 1.76MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 63.38GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 28.43GB |
| 3 | `reflect.unsafe_NewArray` | 27.38GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 27.18GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 26.84GB |
| 6 | `internal/evaluation.mergeMetadata` | 26.15GB |
| 7 | `reflect.MakeSlice` | 15.23GB |
| 8 | `experiment/local.topologicalSort` | 13.41GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 13.27GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 12.37GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 82/84 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/84 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 10.83MB | 79/84 | `████░░░░░░░░░░░ 29%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 82/84 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.88MB | 74/84 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/84 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/84 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/84 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `segmentio/kafka-go.makePartitions` | 3.01MB | 66/84 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.76MB | 2/84 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 30.21GB | 75/84 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 17.87GB | 60/84 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.mergeMetadata` | 14.27GB | 71/84 | `███████░░░░░░░░ 47%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 13.69GB | 77/84 | `██████░░░░░░░░░ 45%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 13.68GB | 76/84 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 13.06GB | 75/84 | `██████░░░░░░░░░ 43%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 7.8GB | 60/84 | `███░░░░░░░░░░░░ 25%` |
| 8 | `reflect.MakeSlice` | 7.47GB | 73/84 | `███░░░░░░░░░░░░ 24%` |
| 9 | `experiment/local.topologicalSort` | 7.2GB | 72/84 | `███░░░░░░░░░░░░ 23%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 7.09GB | 73/84 | `███░░░░░░░░░░░░ 23%` |

## Alerts

No anomalies detected.
