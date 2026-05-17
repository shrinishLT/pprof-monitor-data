# Overview: stage
*Last updated: 2026-05-17 07:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T07:31 (75 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,083 | avg: 14,155 | max: 14,653 | trend: stable (+0.29/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁
```

**Heap InUse** (current: 124.4MB | avg: 145.9MB | max: 213.6MB | trend: INCREASING (+0.56MB/hr))
```
▂▄▁▅▃▃▂▃▅▆▁▂▅▄▁▅▁▁▅▅▁▁▆▆▇▃▃▆▂▃▅▆▁▃▅▅▂▄▂▂▂▂▅▂▂▄▂▂▄▄▄▅▆▃▂▂▄▄▃▁▂▁▅▅▄▅▅▅▅▅▆█▄▆▂
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 12%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,083 | 14,185 | -102 | 14,155 | 14,653 | stable (+0.29/hr) |
| Heap InUse | 124.4MB | 185.7MB | -61.3MB | 145.9MB | 213.6MB | INCREASING (+0.56MB/hr) |
| Heap Sys | 1013.0MB | 1013.0MB | +0.0MB | 804.4MB | 1016.6MB | |
| Heap Objects | 532,210 | 1,293,781 | -761571 | 794,818 | 1,343,690 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 16 | 14,149 | 158.6MB | 213.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 5.0MB |
| 6 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `reflect.unsafe_New` | 2.0MB |
| 10 | `compress/flate.NewWriter` | 1.76MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 55.34GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 28.27GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 26.65GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 26.31GB |
| 5 | `internal/evaluation.mergeMetadata` | 25.65GB |
| 6 | `reflect.unsafe_NewArray` | 23.87GB |
| 7 | `reflect.MakeSlice` | 13.27GB |
| 8 | `experiment/local.topologicalSort` | 13.13GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 13.01GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 12.3GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 73/75 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/75 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 10.67MB | 70/75 | `████░░░░░░░░░░░ 29%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 73/75 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.86MB | 65/75 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/75 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/75 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/75 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.92MB | 58/75 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.76MB | 2/75 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 26.17GB | 66/75 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 16.03GB | 51/75 | `█████████░░░░░░ 61%` |
| 3 | `internal/evaluation.mergeMetadata` | 12.57GB | 62/75 | `███████░░░░░░░░ 48%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 11.95GB | 67/75 | `██████░░░░░░░░░ 45%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 11.94GB | 68/75 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 11.32GB | 66/75 | `██████░░░░░░░░░ 43%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 7.0GB | 51/75 | `████░░░░░░░░░░░ 26%` |
| 8 | `reflect.MakeSlice` | 6.5GB | 64/75 | `███░░░░░░░░░░░░ 24%` |
| 9 | `experiment/local.topologicalSort` | 6.33GB | 63/75 | `███░░░░░░░░░░░░ 24%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 6.24GB | 64/75 | `███░░░░░░░░░░░░ 23%` |

## Alerts

No anomalies detected.
