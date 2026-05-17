# Overview: stage
*Last updated: 2026-05-18 03:32 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T03:31 (115 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,064 | avg: 14,131 | max: 14,653 | trend: decreasing (-1.64/hr))
```
▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▂▅▃█▁▂▁▁▂▂▃▁▁▁▂▁▁▂▁▁▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 181.6MB | avg: 147.1MB | max: 213.6MB | trend: stable (+0.20MB/hr))
```
▅▁▁▆▅▇▃▃▅▂▂▅▆▁▃▄▅▁▄▁▂▂▁▄▁▂▄▁▁▄▄▄▄▅▃▁▁▄▃▃▁▂▁▄▅▄▅▄▅▅▄▆█▄▆▂▅▅▄▆▄▃▁▃▄▅▃▄▄▁▅▃▃▅▃▄▅▂▁▂▁▅▁▁▂▁▅▆▁▄▆▃▂▂▅▅
```

## Current Status

Goroutines: `███████████████████░ 95%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 17%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,064 | 14,087 | -23 | 14,131 | 14,653 | decreasing (-1.64/hr) |
| Heap InUse | 181.6MB | 169.5MB | +12.1MB | 147.1MB | 213.6MB | stable (+0.20MB/hr) |
| Heap Sys | 1012.8MB | 1012.6MB | +0.2MB | 877.0MB | 1016.6MB | |
| Heap Objects | 1,290,015 | 1,077,758 | +212257 | 821,363 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 8 | 14,070 | 150.9MB | 186.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.0MB |
| 6 | `reflect.unsafe_NewArray` | 2.51MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `compress/flate.NewWriter` | 1.76MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 91.08GB |
| 2 | `reflect.unsafe_NewArray` | 39.38GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 34.34GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 33.85GB |
| 5 | `internal/evaluation.mergeMetadata` | 32.91GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 31.26GB |
| 7 | `reflect.MakeSlice` | 21.9GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.91GB |
| 9 | `experiment/local.topologicalSort` | 16.82GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 13.61GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 113/115 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/115 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 11.19MB | 110/115 | `████░░░░░░░░░░░ 30%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 113/115 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.91MB | 105/115 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/115 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/115 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.25MB | 2/115 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `segmentio/kafka-go.makePartitions` | 3.05MB | 95/115 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `compress/flate.NewWriter` | 2.79MB | 96/115 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 44.09GB | 106/115 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 22.32GB | 91/115 | `███████░░░░░░░░ 50%` |
| 3 | `reflect.unsafe_NewArray` | 19.05GB | 106/115 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 18.87GB | 102/115 | `██████░░░░░░░░░ 42%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 18.57GB | 108/115 | `██████░░░░░░░░░ 42%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 18.49GB | 107/115 | `██████░░░░░░░░░ 41%` |
| 7 | `reflect.MakeSlice` | 10.81GB | 104/115 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 9.73GB | 91/115 | `███░░░░░░░░░░░░ 22%` |
| 9 | `experiment/local.topologicalSort` | 9.58GB | 103/115 | `███░░░░░░░░░░░░ 21%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 9.44GB | 104/115 | `███░░░░░░░░░░░░ 21%` |

## Alerts

No anomalies detected.
