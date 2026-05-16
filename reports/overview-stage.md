# Overview: stage
*Last updated: 2026-05-16 22:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T22:01 (56 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,255 | avg: 14,157 | max: 14,653 | trend: INCREASING (+0.83/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃
```

**Heap InUse** (current: 120.9MB | avg: 142.1MB | max: 201.6MB | trend: stable (+0.09MB/hr))
```
▃▄▁▆▃▃▂▄▅▆▁▂▅▅▁▅▁▁▅▅▂▁▆▆█▄▄▆▃▃▆▆▁▄▅▆▂▅▂▂▃▂▅▂▂▅▂▂▄▅▅▅▆▄▂▂
```

## Current Status

Goroutines: `███████████████████░ 97%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 11%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,255 | 14,070 | +185 | 14,157 | 14,653 | INCREASING (+0.83/hr) |
| Heap InUse | 120.9MB | 117.3MB | +3.6MB | 142.1MB | 201.6MB | stable (+0.09MB/hr) |
| Heap Sys | 1012.5MB | 1012.2MB | +0.3MB | 733.7MB | 1016.6MB | |
| Heap Objects | 436,468 | 515,563 | -79095 | 759,776 | 1,341,103 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 46 | 14,154 | 142.0MB | 201.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 6 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `reflect.unsafe_NewArray` | 1.5MB |
| 10 | `bufio.NewWriterSize` | 1.02MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 38.3GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 18.27GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 17.98GB |
| 4 | `internal/evaluation.mergeMetadata` | 17.53GB |
| 5 | `reflect.unsafe_NewArray` | 16.5GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 16.23GB |
| 7 | `reflect.MakeSlice` | 9.17GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 8.98GB |
| 9 | `experiment/local.topologicalSort` | 8.98GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 7.09GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 54/56 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/56 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 10.14MB | 51/56 | `████░░░░░░░░░░░ 27%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.23MB | 54/56 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.8MB | 46/56 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/56 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/56 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/56 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.87MB | 41/56 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `compress/flate.NewWriter` | 2.69MB | 47/56 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 17.64GB | 47/56 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 14.62GB | 32/56 | `████████████░░░ 82%` |
| 3 | `internal/evaluation.mergeMetadata` | 8.77GB | 43/56 | `███████░░░░░░░░ 49%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 8.08GB | 48/56 | `██████░░░░░░░░░ 45%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 8.03GB | 49/56 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 7.66GB | 47/56 | `██████░░░░░░░░░ 43%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 6.39GB | 32/56 | `█████░░░░░░░░░░ 36%` |
| 8 | `reflect.MakeSlice` | 4.46GB | 45/56 | `███░░░░░░░░░░░░ 25%` |
| 9 | `experiment/local.topologicalSort` | 4.39GB | 44/56 | `███░░░░░░░░░░░░ 24%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 4.29GB | 45/56 | `███░░░░░░░░░░░░ 24%` |

## Alerts

No anomalies detected.
