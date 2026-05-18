# Overview: stage
*Last updated: 2026-05-18 15:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T15:03 (138 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,316 | avg: 14,133 | max: 14,653 | trend: decreasing (-0.87/hr))
```
▂▂▄▁▁▁▂▁▁▃▁▂▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁█▄▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▆▆▁▁▁▁▁▁▁▁▁▁▁▃▁▂▁▂▄
```

**Heap InUse** (current: 129.1MB | avg: 148.4MB | max: 277.6MB | trend: stable (+0.21MB/hr))
```
▃▁▁▃▁▁▂▃▃▃▄▂▁▁▃▂▂▁▁▁▃▃▂▃▃▃▃▃▄▅▃▄▁▃▃▃▄▃▂▁▂▂▃▂▃▃▁▄▂▂▃▂▃▃▂▁▁▁▃▁▁▂▁▃▄▁▂▄▂▁▂▃▄▁▄▃▂█▄▂▂▁▁▄▂▁▁▂▃▃▄▁▃▄▂▁
```

## Current Status

Goroutines: `███████████████████░ 97%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 12%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,316 | 14,140 | +176 | 14,133 | 14,653 | decreasing (-0.87/hr) |
| Heap InUse | 129.1MB | 138.5MB | -9.4MB | 148.4MB | 277.6MB | stable (+0.21MB/hr) |
| Heap Sys | 1013.1MB | 1013.4MB | -0.3MB | 899.7MB | 1016.6MB | |
| Heap Objects | 461,518 | 605,948 | -144430 | 820,439 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 31 | 14,121 | 154.0MB | 277.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.51MB |
| 6 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `bufio.NewWriterSize` | 2.02MB |
| 9 | `bytes.growSlice` | 2.01MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 111.89GB |
| 2 | `reflect.unsafe_NewArray` | 48.38GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 45.69GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 42.25GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 41.71GB |
| 6 | `internal/evaluation.mergeMetadata` | 40.61GB |
| 7 | `reflect.MakeSlice` | 26.84GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 20.69GB |
| 9 | `experiment/local.topologicalSort` | 20.68GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 19.87GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 136/138 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/138 | `██████░░░░░░░░░ 42%` |
| 3 | `runtime.mallocgc` | 11.35MB | 133/138 | `████░░░░░░░░░░░ 30%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 136/138 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.93MB | 128/138 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 8.5MB | 2/138 | `███░░░░░░░░░░░░ 23%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/138 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `segmentio/kafka-go.makePartitions` | 3.12MB | 116/138 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `internal/evaluation.mergeMetadata` | 3.0MB | 3/138 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `compress/flate.NewWriter` | 2.84MB | 113/138 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 54.4GB | 129/138 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 26.2GB | 114/138 | `███████░░░░░░░░ 48%` |
| 3 | `reflect.unsafe_NewArray` | 23.51GB | 129/138 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 22.21GB | 125/138 | `██████░░░░░░░░░ 40%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 22.07GB | 131/138 | `██████░░░░░░░░░ 40%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 21.94GB | 130/138 | `██████░░░░░░░░░ 40%` |
| 7 | `reflect.MakeSlice` | 13.28GB | 127/138 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 11.41GB | 114/138 | `███░░░░░░░░░░░░ 20%` |
| 9 | `experiment/local.topologicalSort` | 11.27GB | 126/138 | `███░░░░░░░░░░░░ 20%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 11.15GB | 127/138 | `███░░░░░░░░░░░░ 20%` |

## Alerts

No anomalies detected.
