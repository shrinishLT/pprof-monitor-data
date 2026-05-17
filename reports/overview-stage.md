# Overview: stage
*Last updated: 2026-05-17 14:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T14:01 (88 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,190 | avg: 14,148 | max: 14,653 | trend: decreasing (-0.60/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂
```

**Heap InUse** (current: 165.8MB | avg: 147.9MB | max: 213.6MB | trend: INCREASING (+0.57MB/hr))
```
▂▄▁▅▃▃▂▃▅▆▁▂▅▄▁▅▁▁▅▅▁▁▆▆▇▃▃▆▂▃▅▆▁▃▅▅▂▄▂▂▂▂▅▂▂▄▂▂▄▄▄▅▆▃▂▂▄▄▃▁▂▁▅▅▄▅▅▅▅▅▆█▄▆▂▅▅▄▆▅▄▁▄▄▅▃▅▅
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 16%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,190 | 14,076 | +114 | 14,148 | 14,653 | decreasing (-0.60/hr) |
| Heap InUse | 165.8MB | 167.3MB | -1.5MB | 147.9MB | 213.6MB | INCREASING (+0.57MB/hr) |
| Heap Sys | 1013.2MB | 1013.2MB | +0.0MB | 835.3MB | 1016.6MB | |
| Heap Objects | 1,066,296 | 1,070,126 | -3830 | 820,836 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 29 | 14,130 | 158.8MB | 213.6MB |

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
| 9 | `compress/flate.NewWriter` | 1.76MB |
| 10 | `bytes.growSlice` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 66.91GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 29.64GB |
| 3 | `reflect.unsafe_NewArray` | 28.88GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 28.85GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 28.5GB |
| 6 | `internal/evaluation.mergeMetadata` | 27.73GB |
| 7 | `reflect.MakeSlice` | 16.07GB |
| 8 | `experiment/local.topologicalSort` | 14.22GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 14.07GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 12.89GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 86/88 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/88 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 10.89MB | 83/88 | `████░░░░░░░░░░░ 29%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 86/88 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.88MB | 78/88 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/88 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/88 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/88 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.99MB | 70/88 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.76MB | 2/88 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 32.0GB | 79/88 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 18.58GB | 64/88 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.mergeMetadata` | 14.95GB | 75/88 | `███████░░░░░░░░ 46%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 14.41GB | 81/88 | `██████░░░░░░░░░ 45%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 14.39GB | 80/88 | `██████░░░░░░░░░ 44%` |
| 6 | `reflect.unsafe_NewArray` | 13.83GB | 79/88 | `██████░░░░░░░░░ 43%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 8.11GB | 64/88 | `███░░░░░░░░░░░░ 25%` |
| 8 | `reflect.MakeSlice` | 7.9GB | 77/88 | `███░░░░░░░░░░░░ 24%` |
| 9 | `experiment/local.topologicalSort` | 7.56GB | 76/88 | `███░░░░░░░░░░░░ 23%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 7.44GB | 77/88 | `███░░░░░░░░░░░░ 23%` |

## Alerts

No anomalies detected.
