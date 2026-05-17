# Overview: stage
*Last updated: 2026-05-18 02:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T02:31 (113 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,066 | avg: 14,132 | max: 14,653 | trend: decreasing (-1.62/hr))
```
▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▂▅▃█▁▂▁▁▂▂▃▁▁▁▂▁▁▂▁▁▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 131.6MB | avg: 146.6MB | max: 213.6MB | trend: stable (+0.16MB/hr))
```
▁▅▅▁▁▆▅▇▃▃▅▂▂▅▆▁▃▄▅▁▄▁▂▂▁▄▁▂▄▁▁▄▄▄▄▅▃▁▁▄▃▃▁▂▁▄▅▄▅▄▅▅▄▆█▄▆▂▅▅▄▆▄▃▁▃▄▅▃▄▄▁▅▃▃▅▃▄▅▂▁▂▁▅▁▁▂▁▅▆▁▄▆▃▂▂
```

## Current Status

Goroutines: `███████████████████░ 95%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 12%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,066 | 14,069 | -3 | 14,132 | 14,653 | decreasing (-1.62/hr) |
| Heap InUse | 131.6MB | 126.5MB | +5.1MB | 146.6MB | 213.6MB | stable (+0.16MB/hr) |
| Heap Sys | 1011.1MB | 1013.3MB | -2.2MB | 874.6MB | 1016.6MB | |
| Heap Objects | 657,392 | 596,544 | +60848 | 814,947 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 6 | 14,068 | 142.7MB | 186.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 1.6MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 89.24GB |
| 2 | `reflect.unsafe_NewArray` | 38.62GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 33.91GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 33.43GB |
| 5 | `internal/evaluation.mergeMetadata` | 32.5GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 31.26GB |
| 7 | `reflect.MakeSlice` | 21.47GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.68GB |
| 9 | `experiment/local.topologicalSort` | 16.61GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 13.61GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 111/113 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/113 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 11.17MB | 108/113 | `████░░░░░░░░░░░ 30%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 111/113 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.91MB | 103/113 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/113 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/113 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.25MB | 2/113 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `segmentio/kafka-go.makePartitions` | 3.04MB | 93/113 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `compress/flate.NewWriter` | 2.79MB | 94/113 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 43.2GB | 104/113 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 22.12GB | 89/113 | `███████░░░░░░░░ 51%` |
| 3 | `reflect.unsafe_NewArray` | 18.66GB | 104/113 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 18.59GB | 100/113 | `██████░░░░░░░░░ 43%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 18.27GB | 106/113 | `██████░░░░░░░░░ 42%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 18.2GB | 105/113 | `██████░░░░░░░░░ 42%` |
| 7 | `reflect.MakeSlice` | 10.59GB | 102/113 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 9.64GB | 89/113 | `███░░░░░░░░░░░░ 22%` |
| 9 | `experiment/local.topologicalSort` | 9.43GB | 101/113 | `███░░░░░░░░░░░░ 21%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 9.3GB | 102/113 | `███░░░░░░░░░░░░ 21%` |

## Alerts

No anomalies detected.
