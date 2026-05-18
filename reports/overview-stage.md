# Overview: stage
*Last updated: 2026-05-18 06:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T06:03 (120 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,507 | avg: 14,133 | max: 14,653 | trend: decreasing (-1.25/hr))
```
▇▃▁▁▁▁▁▂▁▁▂▅▃█▁▂▁▁▂▂▃▁▁▁▂▁▁▂▁▁▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▆
```

**Heap InUse** (current: 277.6MB | avg: 148.4MB | max: 277.6MB | trend: stable (+0.31MB/hr))
```
▄▂▂▄▁▁▃▄▁▂▃▃▁▃▁▁▁▁▃▁▁▃▁▁▂▃▃▃▄▂▁▁▃▂▂▁▁▁▃▃▂▃▃▃▃▃▄▅▃▄▁▃▃▃▄▃▂▁▂▂▃▂▃▃▁▄▂▂▃▂▃▃▂▁▁▁▃▁▁▂▁▃▄▁▂▄▂▁▂▃▄▁▄▃▂█
```

## Current Status

Goroutines: `███████████████████░ 99%`
Heap InUse: `█████░░░░░░░░░░░░░░░ 27%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,507 | 14,077 | +430 | 14,133 | 14,653 | decreasing (-1.25/hr) |
| Heap InUse | 277.6MB | 136.9MB | +140.7MB | 148.4MB | 277.6MB | stable (+0.31MB/hr) |
| Heap Sys | 1012.8MB | 1012.8MB | +0.0MB | 882.7MB | 1016.6MB | |
| Heap Objects | 1,008,508 | 739,601 | +268907 | 825,871 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 13 | 14,111 | 161.2MB | 277.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 16.34MB |
| 3 | `runtime.mallocgc` | 12.1MB |
| 4 | `database/sql.convertAssignRows` | 10.0MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 7 | `bytes.growSlice` | 4.52MB |
| 8 | `segmentio/kafka-go.makePartitions` | 4.0MB |
| 9 | `bufio.NewWriterSize` | 2.52MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 95.69GB |
| 2 | `reflect.unsafe_NewArray` | 41.39GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 35.91GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 35.84GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 35.32GB |
| 6 | `internal/evaluation.mergeMetadata` | 34.37GB |
| 7 | `reflect.MakeSlice` | 22.98GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 17.62GB |
| 9 | `experiment/local.topologicalSort` | 17.59GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 15.65GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 118/120 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/120 | `██████░░░░░░░░░ 42%` |
| 3 | `runtime.mallocgc` | 11.23MB | 115/120 | `████░░░░░░░░░░░ 30%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 118/120 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.92MB | 110/120 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 8.5MB | 2/120 | `███░░░░░░░░░░░░ 23%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/120 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.25MB | 2/120 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `segmentio/kafka-go.makePartitions` | 3.08MB | 100/120 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `compress/flate.NewWriter` | 2.82MB | 100/120 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 46.33GB | 111/120 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 22.84GB | 96/120 | `███████░░░░░░░░ 49%` |
| 3 | `reflect.unsafe_NewArray` | 20.02GB | 111/120 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 19.56GB | 107/120 | `██████░░░░░░░░░ 42%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 19.29GB | 113/120 | `██████░░░░░░░░░ 41%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 19.2GB | 112/120 | `██████░░░░░░░░░ 41%` |
| 7 | `reflect.MakeSlice` | 11.35GB | 109/120 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 9.95GB | 96/120 | `███░░░░░░░░░░░░ 21%` |
| 9 | `experiment/local.topologicalSort` | 9.93GB | 108/120 | `███░░░░░░░░░░░░ 21%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 9.8GB | 109/120 | `███░░░░░░░░░░░░ 21%` |

## Alerts

No anomalies detected.
