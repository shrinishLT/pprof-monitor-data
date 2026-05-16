# Overview: stage
*Last updated: 2026-05-16 13:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T13:03 (38 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,653 | avg: 14,167 | max: 14,653 | trend: INCREASING (+6.84/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█
```

**Heap InUse** (current: 159.7MB | avg: 144.8MB | max: 201.6MB | trend: INCREASING (+1.22MB/hr))
```
▃▄▁▆▃▃▂▄▅▆▁▂▅▅▁▅▁▁▅▅▂▁▆▆█▄▄▆▃▃▆▆▁▄▅▆▂▅
```

## Current Status

Goroutines: `████████████████████ 100%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 15%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,653 | 14,312 | +341 | 14,167 | 14,653 | INCREASING (+6.84/hr) |
| Heap InUse | 159.7MB | 120.8MB | +38.9MB | 144.8MB | 201.6MB | INCREASING (+1.22MB/hr) |
| Heap Sys | 1011.5MB | 1011.6MB | -0.1MB | 601.8MB | 1016.6MB | |
| Heap Objects | 758,392 | 479,139 | +279253 | 809,555 | 1,341,103 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 28 | 14,165 | 145.6MB | 201.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `bytes.growSlice` | 3.52MB |
| 6 | `reflect.unsafe_NewArray` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `bufio.NewReaderSize` | 1.52MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 22.07GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 13.96GB |
| 3 | `reflect.unsafe_NewArray` | 9.65GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 9.41GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 9.29GB |
| 6 | `internal/evaluation.mergeMetadata` | 9.07GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 6.1GB |
| 8 | `reflect.MakeSlice` | 5.35GB |
| 9 | `experiment/local.topologicalSort` | 4.66GB |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 4.65GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 36/38 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/38 | `█████░░░░░░░░░░ 39%` |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.23MB | 36/38 | `███░░░░░░░░░░░░ 25%` |
| 4 | `runtime.mallocgc` | 9.07MB | 33/38 | `███░░░░░░░░░░░░ 24%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.68MB | 28/38 | `███░░░░░░░░░░░░ 23%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/38 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/38 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `reflect.unsafe_New` | 3.0MB | 1/38 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.7MB | 23/38 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `bytes.growSlice` | 2.6MB | 6/38 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 12.94GB | 14/38 | `███████████████ 100%` |
| 2 | `segmentio/kafka-go.makePartitions` | 9.6GB | 29/38 | `███████████░░░░ 74%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 5.67GB | 14/38 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 4.91GB | 25/38 | `█████░░░░░░░░░░ 37%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 4.23GB | 30/38 | `████░░░░░░░░░░░ 32%` |
| 6 | `reflect.unsafe_NewArray` | 4.19GB | 29/38 | `████░░░░░░░░░░░ 32%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 4.15GB | 31/38 | `████░░░░░░░░░░░ 32%` |
| 8 | `reflect.MakeSlice` | 2.52GB | 27/38 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `experiment/local.topologicalSort` | 2.42GB | 26/38 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 2.35GB | 27/38 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

No anomalies detected.
