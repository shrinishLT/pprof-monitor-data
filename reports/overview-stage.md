# Overview: stage
*Last updated: 2026-05-16 13:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T13:31 (39 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,074 | avg: 14,165 | max: 14,653 | trend: INCREASING (+5.61/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁
```

**Heap InUse** (current: 117.9MB | avg: 144.1MB | max: 201.6MB | trend: INCREASING (+0.92MB/hr))
```
▃▄▁▆▃▃▂▄▅▆▁▂▅▅▁▅▁▁▅▅▂▁▆▆█▄▄▆▃▃▆▆▁▄▅▆▂▅▂
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 11%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,074 | 14,653 | -579 | 14,165 | 14,653 | INCREASING (+5.61/hr) |
| Heap InUse | 117.9MB | 159.7MB | -41.8MB | 144.1MB | 201.6MB | INCREASING (+0.92MB/hr) |
| Heap Sys | 1012.0MB | 1011.5MB | +0.5MB | 612.3MB | 1016.6MB | |
| Heap Objects | 535,059 | 758,392 | -223333 | 802,517 | 1,341,103 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 29 | 14,162 | 144.6MB | 201.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.5MB |
| 6 | `compress/flate.NewWriter` | 4.41MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 1.07MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 22.87GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 14.56GB |
| 3 | `reflect.unsafe_NewArray` | 9.97GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 9.64GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 9.5GB |
| 6 | `internal/evaluation.mergeMetadata` | 9.28GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 6.36GB |
| 8 | `reflect.MakeSlice` | 5.56GB |
| 9 | `experiment/local.topologicalSort` | 4.78GB |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 4.76GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 37/39 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/39 | `█████░░░░░░░░░░ 39%` |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.23MB | 37/39 | `███░░░░░░░░░░░░ 25%` |
| 4 | `runtime.mallocgc` | 9.16MB | 34/39 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.69MB | 29/39 | `███░░░░░░░░░░░░ 23%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/39 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/39 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `reflect.unsafe_New` | 3.0MB | 1/39 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.77MB | 24/39 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `compress/flate.NewWriter` | 2.6MB | 32/39 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 13.05GB | 15/39 | `███████████████ 100%` |
| 2 | `segmentio/kafka-go.makePartitions` | 10.05GB | 30/39 | `███████████░░░░ 77%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 5.71GB | 15/39 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 5.08GB | 26/39 | `█████░░░░░░░░░░ 38%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 4.4GB | 31/39 | `█████░░░░░░░░░░ 33%` |
| 6 | `reflect.unsafe_NewArray` | 4.39GB | 30/39 | `█████░░░░░░░░░░ 33%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 4.32GB | 32/39 | `████░░░░░░░░░░░ 33%` |
| 8 | `reflect.MakeSlice` | 2.62GB | 28/39 | `███░░░░░░░░░░░░ 20%` |
| 9 | `experiment/local.topologicalSort` | 2.51GB | 27/39 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 2.44GB | 28/39 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

No anomalies detected.
