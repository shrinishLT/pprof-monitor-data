# Overview: stage
*Last updated: 2026-05-17 10:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T10:31 (81 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,067 | avg: 14,150 | max: 14,653 | trend: stable (-0.48/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁
```

**Heap InUse** (current: 151.3MB | avg: 147.7MB | max: 213.6MB | trend: INCREASING (+0.68MB/hr))
```
▂▄▁▅▃▃▂▃▅▆▁▂▅▄▁▅▁▁▅▅▁▁▆▆▇▃▃▆▂▃▅▆▁▃▅▅▂▄▂▂▂▂▅▂▂▄▂▂▄▄▄▅▆▃▂▂▄▄▃▁▂▁▅▅▄▅▅▅▅▅▆█▄▆▂▅▅▄▆▅▄
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 14%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,067 | 14,127 | -60 | 14,150 | 14,653 | stable (-0.48/hr) |
| Heap InUse | 151.3MB | 163.6MB | -12.3MB | 147.7MB | 213.6MB | INCREASING (+0.68MB/hr) |
| Heap Sys | 1013.0MB | 1013.0MB | +0.0MB | 819.9MB | 1016.6MB | |
| Heap Objects | 920,541 | 1,069,013 | -148472 | 821,304 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 22 | 14,131 | 161.6MB | 213.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.0MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `reflect.unsafe_NewArray` | 2.0MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 60.73GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 28.27GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 27.01GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 26.68GB |
| 5 | `reflect.unsafe_NewArray` | 26.23GB |
| 6 | `internal/evaluation.mergeMetadata` | 25.98GB |
| 7 | `reflect.MakeSlice` | 14.57GB |
| 8 | `experiment/local.topologicalSort` | 13.32GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 13.2GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 12.3GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 79/81 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/81 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 10.78MB | 76/81 | `████░░░░░░░░░░░ 29%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 79/81 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.87MB | 71/81 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/81 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/81 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/81 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.99MB | 63/81 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.76MB | 2/81 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 28.87GB | 72/81 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 17.32GB | 57/81 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.mergeMetadata` | 13.75GB | 68/81 | `███████░░░░░░░░ 47%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 13.15GB | 74/81 | `██████░░░░░░░░░ 45%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 13.15GB | 73/81 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 12.48GB | 72/81 | `██████░░░░░░░░░ 43%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 7.56GB | 57/81 | `███░░░░░░░░░░░░ 26%` |
| 8 | `reflect.MakeSlice` | 7.15GB | 70/81 | `███░░░░░░░░░░░░ 24%` |
| 9 | `experiment/local.topologicalSort` | 6.94GB | 69/81 | `███░░░░░░░░░░░░ 24%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 6.83GB | 70/81 | `███░░░░░░░░░░░░ 23%` |

## Alerts

No anomalies detected.
