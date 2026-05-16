# Overview: stage
*Last updated: 2026-05-17 01:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T01:02 (62 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,073 | avg: 14,153 | max: 14,653 | trend: stable (-0.28/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃▁▁▁▁▁
```

**Heap InUse** (current: 107.8MB | avg: 141.1MB | max: 201.6MB | trend: stable (-0.14MB/hr))
```
▃▄▁▆▃▃▂▄▅▆▁▂▅▅▁▅▁▁▅▅▂▁▆▆█▄▄▆▃▃▆▆▁▄▅▆▂▅▂▂▃▂▅▂▂▅▂▂▄▅▅▅▆▄▂▂▅▄▄▂▃▁
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,073 | 14,075 | -2 | 14,153 | 14,653 | stable (-0.28/hr) |
| Heap InUse | 107.8MB | 125.0MB | -17.2MB | 141.1MB | 201.6MB | stable (-0.14MB/hr) |
| Heap Sys | 1014.0MB | 1012.9MB | +1.1MB | 760.7MB | 1016.6MB | |
| Heap Objects | 354,512 | 606,368 | -251856 | 747,387 | 1,341,103 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 3 | 14,070 | 113.9MB | 125.0MB |

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
| 1 | `segmentio/kafka-go.makePartitions` | 43.71GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 19.65GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 19.35GB |
| 4 | `internal/evaluation.mergeMetadata` | 18.89GB |
| 5 | `reflect.unsafe_NewArray` | 18.83GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 16.23GB |
| 7 | `reflect.MakeSlice` | 10.44GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 9.68GB |
| 9 | `experiment/local.topologicalSort` | 9.66GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 7.09GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 60/62 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/62 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 10.34MB | 57/62 | `████░░░░░░░░░░░ 28%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 60/62 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.83MB | 52/62 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/62 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/62 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/62 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.91MB | 46/62 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `compress/flate.NewWriter` | 2.67MB | 51/62 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 20.33GB | 53/62 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 14.87GB | 38/62 | `██████████░░░░░ 73%` |
| 3 | `internal/evaluation.mergeMetadata` | 9.98GB | 49/62 | `███████░░░░░░░░ 49%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 9.3GB | 54/62 | `██████░░░░░░░░░ 45%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 9.27GB | 55/62 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 8.81GB | 53/62 | `██████░░░░░░░░░ 43%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 6.5GB | 38/62 | `████░░░░░░░░░░░ 31%` |
| 8 | `reflect.MakeSlice` | 5.1GB | 51/62 | `███░░░░░░░░░░░░ 25%` |
| 9 | `experiment/local.topologicalSort` | 5.01GB | 50/62 | `███░░░░░░░░░░░░ 24%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 4.91GB | 51/62 | `███░░░░░░░░░░░░ 24%` |

## Alerts

No anomalies detected.
