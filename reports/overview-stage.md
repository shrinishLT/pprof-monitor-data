# Overview: stage
*Last updated: 2026-05-17 06:33 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T06:33 (73 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,300 | avg: 14,156 | max: 14,653 | trend: stable (+0.41/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃
```

**Heap InUse** (current: 159.3MB | avg: 145.7MB | max: 213.6MB | trend: INCREASING (+0.57MB/hr))
```
▂▄▁▅▃▃▂▃▅▆▁▂▅▄▁▅▁▁▅▅▁▁▆▆▇▃▃▆▂▃▅▆▁▃▅▅▂▄▂▂▂▂▅▂▂▄▂▂▄▄▄▅▆▃▂▂▄▄▃▁▂▁▅▅▄▅▅▅▅▅▆█▄
```

## Current Status

Goroutines: `███████████████████░ 97%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 15%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,300 | 14,607 | -307 | 14,156 | 14,653 | stable (+0.41/hr) |
| Heap InUse | 159.3MB | 213.6MB | -54.3MB | 145.7MB | 213.6MB | INCREASING (+0.57MB/hr) |
| Heap Sys | 1012.9MB | 1012.6MB | +0.3MB | 798.7MB | 1016.6MB | |
| Heap Objects | 684,090 | 1,002,970 | -318880 | 791,580 | 1,343,690 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 14 | 14,151 | 159.1MB | 213.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `bytes.growSlice` | 2.51MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `bufio.NewWriterSize` | 2.02MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 53.59GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 28.2GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 26.48GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 26.15GB |
| 5 | `internal/evaluation.mergeMetadata` | 25.48GB |
| 6 | `reflect.unsafe_NewArray` | 23.11GB |
| 7 | `experiment/local.topologicalSort` | 13.03GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 12.92GB |
| 9 | `reflect.MakeSlice` | 12.86GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 12.27GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 71/73 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/73 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 10.63MB | 68/73 | `████░░░░░░░░░░░ 29%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 71/73 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.86MB | 63/73 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/73 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/73 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/73 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.89MB | 56/73 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.76MB | 2/73 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 25.27GB | 64/73 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 15.53GB | 49/73 | `█████████░░░░░░ 61%` |
| 3 | `internal/evaluation.mergeMetadata` | 12.14GB | 60/73 | `███████░░░░░░░░ 48%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 11.5GB | 65/73 | `██████░░░░░░░░░ 45%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 11.49GB | 66/73 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 10.93GB | 64/73 | `██████░░░░░░░░░ 43%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 6.78GB | 49/73 | `████░░░░░░░░░░░ 26%` |
| 8 | `reflect.MakeSlice` | 6.28GB | 62/73 | `███░░░░░░░░░░░░ 24%` |
| 9 | `experiment/local.topologicalSort` | 6.11GB | 61/73 | `███░░░░░░░░░░░░ 24%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 6.02GB | 62/73 | `███░░░░░░░░░░░░ 23%` |

## Alerts

No anomalies detected.
