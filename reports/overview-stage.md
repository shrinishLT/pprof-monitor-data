# Overview: stage
*Last updated: 2026-05-16 12:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T12:31 (37 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,312 | avg: 14,154 | max: 14,602 | trend: INCREASING (+3.03/hr))
```
▁▁▁▁▁▅▅▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁█▃▁▁▁▁▁▂▁▁▃▆▄
```

**Heap InUse** (current: 120.8MB | avg: 144.4MB | max: 201.6MB | trend: INCREASING (+1.18MB/hr))
```
▃▄▁▆▃▃▂▄▅▆▁▂▅▅▁▅▁▁▅▅▂▁▆▆█▄▄▆▃▃▆▆▁▄▅▆▂
```

## Current Status

Goroutines: `███████████████████░ 98%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 11%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,312 | 14,457 | -145 | 14,154 | 14,602 | INCREASING (+3.03/hr) |
| Heap InUse | 120.8MB | 176.8MB | -56.0MB | 144.4MB | 201.6MB | INCREASING (+1.18MB/hr) |
| Heap Sys | 1011.6MB | 1011.6MB | +0.0MB | 590.7MB | 1016.6MB | |
| Heap Objects | 479,139 | 824,648 | -345509 | 810,938 | 1,341,103 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 27 | 14,147 | 145.1MB | 201.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 6 | `reflect.unsafe_New` | 3.0MB |
| 7 | `bufio.NewReaderSize` | 2.52MB |
| 8 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `reflect.unsafe_NewArray` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 21.13GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 13.96GB |
| 3 | `reflect.unsafe_NewArray` | 9.22GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 8.99GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 8.83GB |
| 6 | `internal/evaluation.mergeMetadata` | 8.66GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 6.1GB |
| 8 | `reflect.MakeSlice` | 5.13GB |
| 9 | `experiment/local.topologicalSort` | 4.44GB |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 4.42GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 35/37 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/37 | `█████░░░░░░░░░░ 39%` |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.23MB | 35/37 | `███░░░░░░░░░░░░ 25%` |
| 4 | `runtime.mallocgc` | 8.97MB | 32/37 | `███░░░░░░░░░░░░ 24%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.67MB | 27/37 | `███░░░░░░░░░░░░ 23%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/37 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/37 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `reflect.unsafe_New` | 3.0MB | 1/37 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.7MB | 23/37 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `compress/flate.NewWriter` | 2.54MB | 31/37 | `█░░░░░░░░░░░░░░ 6%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 12.87GB | 13/37 | `███████████████ 100%` |
| 2 | `segmentio/kafka-go.makePartitions` | 9.16GB | 28/37 | `██████████░░░░░ 71%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 5.63GB | 13/37 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 4.74GB | 24/37 | `█████░░░░░░░░░░ 36%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 4.05GB | 29/37 | `████░░░░░░░░░░░ 31%` |
| 6 | `reflect.unsafe_NewArray` | 4.0GB | 28/37 | `████░░░░░░░░░░░ 31%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 3.97GB | 30/37 | `████░░░░░░░░░░░ 30%` |
| 8 | `reflect.MakeSlice` | 2.41GB | 26/37 | `██░░░░░░░░░░░░░ 18%` |
| 9 | `experiment/local.topologicalSort` | 2.33GB | 25/37 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 2.26GB | 26/37 | `██░░░░░░░░░░░░░ 17%` |

## Alerts

No anomalies detected.
