# Overview: stage
*Last updated: 2026-05-18 01:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T01:01 (110 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,073 | avg: 14,134 | max: 14,653 | trend: decreasing (-1.56/hr))
```
▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▂▅▃█▁▂▁▁▂▂▃▁▁▁▂▁▁▂▁▁▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 186.8MB | avg: 146.9MB | max: 213.6MB | trend: stable (+0.21MB/hr))
```
▁▄▁▁▅▅▁▁▆▅▇▃▃▅▂▂▅▆▁▃▅▅▂▄▂▂▂▁▄▁▂▄▂▁▄▄▄▅▅▃▂▂▄▃▃▁▂▁▄▅▄▅▄▅▅▄▆█▄▆▂▅▅▄▆▄▄▁▄▄▅▃▅▅▂▅▃▃▅▃▄▅▃▁▂▁▅▁▁▂▁▅▆▁▄▆
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 18%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,073 | 14,067 | +6 | 14,134 | 14,653 | decreasing (-1.56/hr) |
| Heap InUse | 186.8MB | 152.6MB | +34.2MB | 146.9MB | 213.6MB | stable (+0.21MB/hr) |
| Heap Sys | 1013.3MB | 1013.3MB | +0.0MB | 870.8MB | 1016.6MB | |
| Heap Objects | 1,370,912 | 941,232 | +429680 | 817,212 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 3 | 14,069 | 149.0MB | 186.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 6 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `compress/flate.NewWriter` | 1.76MB |
| 10 | `kafka-go/protocol.newPage` | 1.6MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 86.61GB |
| 2 | `reflect.unsafe_NewArray` | 37.45GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 31.56GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 31.26GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 31.14GB |
| 6 | `internal/evaluation.mergeMetadata` | 30.21GB |
| 7 | `reflect.MakeSlice` | 20.8GB |
| 8 | `experiment/local.topologicalSort` | 15.52GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 15.42GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 13.61GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 108/110 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/110 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 11.15MB | 105/110 | `████░░░░░░░░░░░ 30%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 108/110 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.91MB | 100/110 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/110 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/110 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.25MB | 2/110 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `segmentio/kafka-go.makePartitions` | 3.06MB | 90/110 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `compress/flate.NewWriter` | 2.78MB | 92/110 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 41.86GB | 101/110 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 21.8GB | 86/110 | `███████░░░░░░░░ 52%` |
| 3 | `internal/evaluation.mergeMetadata` | 18.21GB | 97/110 | `██████░░░░░░░░░ 43%` |
| 4 | `reflect.unsafe_NewArray` | 18.08GB | 101/110 | `██████░░░░░░░░░ 43%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 17.86GB | 103/110 | `██████░░░░░░░░░ 42%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 17.79GB | 102/110 | `██████░░░░░░░░░ 42%` |
| 7 | `reflect.MakeSlice` | 10.27GB | 99/110 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 9.5GB | 86/110 | `███░░░░░░░░░░░░ 22%` |
| 9 | `experiment/local.topologicalSort` | 9.24GB | 98/110 | `███░░░░░░░░░░░░ 22%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 9.1GB | 99/110 | `███░░░░░░░░░░░░ 21%` |

## Alerts

No anomalies detected.
