# Overview: stage
*Last updated: 2026-05-17 00:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T00:31 (61 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,075 | avg: 14,154 | max: 14,653 | trend: stable (-0.03/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃▁▁▁▁
```

**Heap InUse** (current: 125.0MB | avg: 141.6MB | max: 201.6MB | trend: stable (-0.03MB/hr))
```
▃▄▁▆▃▃▂▄▅▆▁▂▅▅▁▅▁▁▅▅▂▁▆▆█▄▄▆▃▃▆▆▁▄▅▆▂▅▂▂▃▂▅▂▂▅▂▂▄▅▅▅▆▄▂▂▅▄▄▂▃
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 12%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,075 | 14,062 | +13 | 14,154 | 14,653 | stable (-0.03/hr) |
| Heap InUse | 125.0MB | 108.8MB | +16.2MB | 141.6MB | 201.6MB | stable (-0.03MB/hr) |
| Heap Sys | 1012.9MB | 1012.9MB | +0.0MB | 756.6MB | 1016.6MB | |
| Heap Objects | 606,368 | 352,471 | +253897 | 753,828 | 1,341,103 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 2 | 14,068 | 116.9MB | 125.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 6 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `encoding/json.(*decodeState).literalStore` | 2.04MB |
| 9 | `reflect.unsafe_NewArray` | 2.0MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 42.75GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 19.59GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 19.29GB |
| 4 | `internal/evaluation.mergeMetadata` | 18.84GB |
| 5 | `reflect.unsafe_NewArray` | 18.41GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 16.23GB |
| 7 | `reflect.MakeSlice` | 10.23GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 9.65GB |
| 9 | `experiment/local.topologicalSort` | 9.63GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 7.09GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 59/61 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/61 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 10.31MB | 56/61 | `████░░░░░░░░░░░ 28%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 59/61 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.82MB | 51/61 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/61 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/61 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/61 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.92MB | 45/61 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `compress/flate.NewWriter` | 2.69MB | 50/61 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 19.89GB | 52/61 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 14.84GB | 37/61 | `███████████░░░░ 74%` |
| 3 | `internal/evaluation.mergeMetadata` | 9.8GB | 48/61 | `███████░░░░░░░░ 49%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 9.11GB | 53/61 | `██████░░░░░░░░░ 45%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 9.07GB | 54/61 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 8.62GB | 52/61 | `██████░░░░░░░░░ 43%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 6.49GB | 37/61 | `████░░░░░░░░░░░ 32%` |
| 8 | `reflect.MakeSlice` | 5.0GB | 50/61 | `███░░░░░░░░░░░░ 25%` |
| 9 | `experiment/local.topologicalSort` | 4.92GB | 49/61 | `███░░░░░░░░░░░░ 24%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 4.82GB | 50/61 | `███░░░░░░░░░░░░ 24%` |

## Alerts

No anomalies detected.
