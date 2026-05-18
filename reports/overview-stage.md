# Overview: stage
*Last updated: 2026-05-18 17:33 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T17:33 (143 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 17,149 | avg: 14,157 | max: 17,149 | trend: INCREASING (+1.25/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█
```

**Heap InUse** (current: 290.3MB | avg: 150.4MB | max: 290.3MB | trend: stable (+0.35MB/hr))
```
▁▂▃▂▃▃▂▁▁▂▂▂▁▁▁▃▃▂▃▃▃▃▃▃▅▃▄▁▃▃▂▄▃▂▁▂▂▃▂▃▃▁▃▂▂▃▂▂▃▂▁▁▁▃▁▁▁▁▃▄▁▂▄▂▁▁▃▃▁▃▃▂▇▄▂▂▁▁▃▂▁▁▂▃▃▄▁▂▄▂▁▃▄▃▄█
```

## Current Status

Goroutines: `████████████████████ 100%`
Heap InUse: `█████░░░░░░░░░░░░░░░ 28%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 17,149 | 14,253 | +2896 | 14,157 | 17,149 | INCREASING (+1.25/hr) |
| Heap InUse | 290.3MB | 194.2MB | +96.1MB | 150.4MB | 290.3MB | stable (+0.35MB/hr) |
| Heap Sys | 1002.8MB | 1012.9MB | -10.1MB | 903.6MB | 1016.6MB | |
| Heap Objects | 1,191,656 | 1,160,702 | +30954 | 826,916 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 36 | 14,220 | 161.0MB | 290.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 14.07MB |
| 3 | `runtime.mallocgc` | 12.1MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `bufio.NewReaderSize` | 9.04MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 7 | `bufio.NewWriterSize` | 5.54MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 5.53MB |
| 9 | `segmentio/kafka-go.makePartitions` | 5.01MB |
| 10 | `crypto/tls.Client` | 3.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 116.33GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 53.71GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 53.15GB |
| 4 | `internal/evaluation.mergeMetadata` | 51.72GB |
| 5 | `reflect.unsafe_NewArray` | 50.37GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 46.99GB |
| 7 | `reflect.MakeSlice` | 27.9GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 26.7GB |
| 9 | `experiment/local.topologicalSort` | 26.4GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.44GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 141/143 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/143 | `██████░░░░░░░░░ 42%` |
| 3 | `runtime.mallocgc` | 11.38MB | 138/143 | `████░░░░░░░░░░░ 31%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 141/143 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.93MB | 133/143 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 8.5MB | 2/143 | `███░░░░░░░░░░░░ 23%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/143 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `segmentio/kafka-go.makePartitions` | 3.14MB | 121/143 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.01MB | 5/143 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `internal/evaluation.mergeMetadata` | 3.0MB | 3/143 | `█░░░░░░░░░░░░░░ 8%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 56.64GB | 134/143 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 27.05GB | 119/143 | `███████░░░░░░░░ 47%` |
| 3 | `reflect.unsafe_NewArray` | 24.48GB | 134/143 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 23.08GB | 130/143 | `██████░░░░░░░░░ 40%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 22.96GB | 136/143 | `██████░░░░░░░░░ 40%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 22.82GB | 135/143 | `██████░░░░░░░░░ 40%` |
| 7 | `reflect.MakeSlice` | 13.82GB | 132/143 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 11.78GB | 119/143 | `███░░░░░░░░░░░░ 20%` |
| 9 | `experiment/local.topologicalSort` | 11.71GB | 131/143 | `███░░░░░░░░░░░░ 20%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 11.59GB | 132/143 | `███░░░░░░░░░░░░ 20%` |

## Alerts

No anomalies detected.
