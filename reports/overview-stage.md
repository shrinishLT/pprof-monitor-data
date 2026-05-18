# Overview: stage
*Last updated: 2026-05-18 05:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T05:31 (119 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,077 | avg: 14,130 | max: 14,653 | trend: decreasing (-1.60/hr))
```
▁▇▃▁▁▁▁▁▂▁▁▂▅▃█▁▂▁▁▂▂▃▁▁▁▂▁▁▂▁▁▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁
```

**Heap InUse** (current: 136.9MB | avg: 147.3MB | max: 213.6MB | trend: stable (+0.20MB/hr))
```
▅▇▃▃▅▂▂▅▆▁▃▄▅▁▄▁▂▂▁▄▁▂▄▁▁▄▄▄▄▅▃▁▁▄▃▃▁▂▁▄▅▄▅▄▅▅▄▆█▄▆▂▅▅▄▆▄▃▁▃▄▅▃▄▄▁▅▃▃▅▃▄▅▂▁▂▁▅▁▁▂▁▅▆▁▄▆▃▂▂▅▅▁▆▅▃
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 13%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,077 | 14,071 | +6 | 14,130 | 14,653 | decreasing (-1.60/hr) |
| Heap InUse | 136.9MB | 178.4MB | -41.5MB | 147.3MB | 213.6MB | stable (+0.20MB/hr) |
| Heap Sys | 1012.8MB | 1012.8MB | +0.0MB | 881.6MB | 1016.6MB | |
| Heap Objects | 739,601 | 1,225,819 | -486218 | 824,337 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 12 | 14,078 | 151.5MB | 186.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `bufio.NewWriterSize` | 1.02MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 94.66GB |
| 2 | `reflect.unsafe_NewArray` | 40.93GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 35.03GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 34.48GB |
| 5 | `internal/evaluation.mergeMetadata` | 33.56GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 31.26GB |
| 7 | `reflect.MakeSlice` | 22.73GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 17.24GB |
| 9 | `experiment/local.topologicalSort` | 17.15GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 13.61GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 117/119 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/119 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 11.22MB | 114/119 | `████░░░░░░░░░░░ 30%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 117/119 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.92MB | 109/119 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/119 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/119 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.25MB | 2/119 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `segmentio/kafka-go.makePartitions` | 3.07MB | 99/119 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `compress/flate.NewWriter` | 2.82MB | 100/119 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 45.89GB | 110/119 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 22.7GB | 95/119 | `███████░░░░░░░░ 49%` |
| 3 | `reflect.unsafe_NewArray` | 19.83GB | 110/119 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 19.42GB | 106/119 | `██████░░░░░░░░░ 42%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 19.15GB | 112/119 | `██████░░░░░░░░░ 41%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 19.06GB | 111/119 | `██████░░░░░░░░░ 41%` |
| 7 | `reflect.MakeSlice` | 11.24GB | 108/119 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 9.89GB | 95/119 | `███░░░░░░░░░░░░ 21%` |
| 9 | `experiment/local.topologicalSort` | 9.86GB | 107/119 | `███░░░░░░░░░░░░ 21%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 9.73GB | 108/119 | `███░░░░░░░░░░░░ 21%` |

## Alerts

No anomalies detected.
