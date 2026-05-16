# Overview: stage
*Last updated: 2026-05-17 01:32 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T01:31 (63 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,064 | avg: 14,151 | max: 14,653 | trend: decreasing (-0.53/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃▁▁▁▁▁▁
```

**Heap InUse** (current: 161.9MB | avg: 141.4MB | max: 201.6MB | trend: stable (-0.07MB/hr))
```
▃▄▁▆▃▃▂▄▅▆▁▂▅▅▁▅▁▁▅▅▂▁▆▆█▄▄▆▃▃▆▆▁▄▅▆▂▅▂▂▃▂▅▂▂▅▂▂▄▅▅▅▆▄▂▂▅▄▄▂▃▁▅
```

## Current Status

Goroutines: `███████████████████░ 95%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 15%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,064 | 14,073 | -9 | 14,151 | 14,653 | decreasing (-0.53/hr) |
| Heap InUse | 161.9MB | 107.8MB | +54.1MB | 141.4MB | 201.6MB | stable (-0.07MB/hr) |
| Heap Sys | 1012.9MB | 1014.0MB | -1.1MB | 764.8MB | 1016.6MB | |
| Heap Objects | 1,097,394 | 354,512 | +742882 | 752,943 | 1,341,103 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 4 | 14,068 | 125.9MB | 161.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.5MB |
| 6 | `reflect.unsafe_NewArray` | 3.03MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `kafka-go/protocol.newPage` | 1.6MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 44.54GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 19.67GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 19.37GB |
| 4 | `reflect.unsafe_NewArray` | 19.2GB |
| 5 | `internal/evaluation.mergeMetadata` | 18.9GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 16.23GB |
| 7 | `reflect.MakeSlice` | 10.65GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 9.69GB |
| 9 | `experiment/local.topologicalSort` | 9.67GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 7.09GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 61/63 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/63 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 10.38MB | 58/63 | `████░░░░░░░░░░░ 28%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 61/63 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.83MB | 53/63 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/63 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/63 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/63 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.95MB | 47/63 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `compress/flate.NewWriter` | 2.67MB | 51/63 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 20.78GB | 54/63 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 14.91GB | 39/63 | `██████████░░░░░ 71%` |
| 3 | `internal/evaluation.mergeMetadata` | 10.16GB | 50/63 | `███████░░░░░░░░ 48%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 9.48GB | 55/63 | `██████░░░░░░░░░ 45%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 9.45GB | 56/63 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 9.0GB | 54/63 | `██████░░░░░░░░░ 43%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 6.52GB | 39/63 | `████░░░░░░░░░░░ 31%` |
| 8 | `reflect.MakeSlice` | 5.21GB | 52/63 | `███░░░░░░░░░░░░ 25%` |
| 9 | `experiment/local.topologicalSort` | 5.1GB | 51/63 | `███░░░░░░░░░░░░ 24%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 5.0GB | 52/63 | `███░░░░░░░░░░░░ 24%` |

## Alerts

No anomalies detected.
