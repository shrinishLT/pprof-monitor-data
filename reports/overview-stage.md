# Overview: stage
*Last updated: 2026-05-16 20:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T20:31 (53 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,070 | avg: 14,158 | max: 14,653 | trend: INCREASING (+0.97/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁
```

**Heap InUse** (current: 180.5MB | avg: 143.0MB | max: 201.6MB | trend: stable (+0.31MB/hr))
```
▃▄▁▆▃▃▂▄▅▆▁▂▅▅▁▅▁▁▅▅▂▁▆▆█▄▄▆▃▃▆▆▁▄▅▆▂▅▂▂▃▂▅▂▂▅▂▂▄▅▅▅▆
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 17%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,070 | 14,225 | -155 | 14,158 | 14,653 | INCREASING (+0.97/hr) |
| Heap InUse | 180.5MB | 166.8MB | +13.7MB | 143.0MB | 201.6MB | stable (+0.31MB/hr) |
| Heap Sys | 1012.6MB | 1012.4MB | +0.2MB | 717.9MB | 1016.6MB | |
| Heap Objects | 1,279,638 | 755,748 | +523890 | 773,341 | 1,341,103 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 43 | 14,154 | 143.1MB | 201.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `reflect.unsafe_NewArray` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 35.55GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 17.33GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 17.06GB |
| 4 | `internal/evaluation.mergeMetadata` | 16.6GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 16.23GB |
| 6 | `reflect.unsafe_NewArray` | 15.32GB |
| 7 | `reflect.MakeSlice` | 8.53GB |
| 8 | `experiment/local.topologicalSort` | 8.51GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 8.5GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 7.09GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 51/53 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/53 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 10.02MB | 48/53 | `████░░░░░░░░░░░ 27%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.23MB | 51/53 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.79MB | 43/53 | `███░░░░░░░░░░░░ 23%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/53 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/53 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/53 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.83MB | 38/53 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `compress/flate.NewWriter` | 2.69MB | 45/53 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 16.29GB | 44/53 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 14.45GB | 29/53 | `█████████████░░ 88%` |
| 3 | `internal/evaluation.mergeMetadata` | 8.15GB | 40/53 | `███████░░░░░░░░ 50%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 7.44GB | 45/53 | `██████░░░░░░░░░ 45%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 7.39GB | 46/53 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 7.08GB | 44/53 | `██████░░░░░░░░░ 43%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 6.32GB | 29/53 | `█████░░░░░░░░░░ 38%` |
| 8 | `reflect.MakeSlice` | 4.14GB | 42/53 | `███░░░░░░░░░░░░ 25%` |
| 9 | `experiment/local.topologicalSort` | 4.07GB | 41/53 | `███░░░░░░░░░░░░ 24%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 3.97GB | 42/53 | `███░░░░░░░░░░░░ 24%` |

## Alerts

No anomalies detected.
