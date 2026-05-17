# Overview: stage
*Last updated: 2026-05-17 13:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T13:01 (86 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,210 | avg: 14,148 | max: 14,653 | trend: decreasing (-0.60/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁▂▁▁▂
```

**Heap InUse** (current: 137.1MB | avg: 147.4MB | max: 213.6MB | trend: INCREASING (+0.54MB/hr))
```
▂▄▁▅▃▃▂▃▅▆▁▂▅▄▁▅▁▁▅▅▁▁▆▆▇▃▃▆▂▃▅▆▁▃▅▅▂▄▂▂▂▂▅▂▂▄▂▂▄▄▄▅▆▃▂▂▄▄▃▁▂▁▅▅▄▅▅▅▅▅▆█▄▆▂▅▅▄▆▅▄▁▄▄▅▃
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 13%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,210 | 14,114 | +96 | 14,148 | 14,653 | decreasing (-0.60/hr) |
| Heap InUse | 137.1MB | 171.8MB | -34.7MB | 147.4MB | 213.6MB | INCREASING (+0.54MB/hr) |
| Heap Sys | 1012.9MB | 1013.1MB | -0.2MB | 831.1MB | 1016.6MB | |
| Heap Objects | 528,228 | 1,078,097 | -549869 | 815,083 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 27 | 14,130 | 158.3MB | 213.6MB |

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
| 9 | `segmentio/kafka-go.makePartitions` | 1.5MB |
| 10 | `encoding/json.(*decodeState).objectInterface` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 65.13GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 29.03GB |
| 3 | `reflect.unsafe_NewArray` | 28.15GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 27.85GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 27.52GB |
| 6 | `internal/evaluation.mergeMetadata` | 26.79GB |
| 7 | `reflect.MakeSlice` | 15.67GB |
| 8 | `experiment/local.topologicalSort` | 13.74GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 13.59GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 12.63GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 84/86 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/86 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 10.86MB | 81/86 | `████░░░░░░░░░░░ 29%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 84/86 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.88MB | 76/86 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/86 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/86 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/86 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.99MB | 68/86 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.76MB | 2/86 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 31.11GB | 77/86 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 18.23GB | 62/86 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.mergeMetadata` | 14.61GB | 73/86 | `███████░░░░░░░░ 46%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 14.05GB | 79/86 | `██████░░░░░░░░░ 45%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 14.04GB | 78/86 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 13.45GB | 77/86 | `██████░░░░░░░░░ 43%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 7.95GB | 62/86 | `███░░░░░░░░░░░░ 25%` |
| 8 | `reflect.MakeSlice` | 7.69GB | 75/86 | `███░░░░░░░░░░░░ 24%` |
| 9 | `experiment/local.topologicalSort` | 7.38GB | 74/86 | `███░░░░░░░░░░░░ 23%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 7.27GB | 75/86 | `███░░░░░░░░░░░░ 23%` |

## Alerts

No anomalies detected.
