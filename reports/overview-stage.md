# Overview: stage
*Last updated: 2026-05-17 06:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T06:02 (72 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,607 | avg: 14,154 | max: 14,653 | trend: stable (+0.09/hr))
```
▁▁▁▁▁▅▄▃▁▂▁▁▁▁▁▁▄▁▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▃▅▃█▁▂▁▁▂▂▄▁▁▁▂▁▁▂▁▂▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇
```

**Heap InUse** (current: 213.6MB | avg: 145.5MB | max: 213.6MB | trend: INCREASING (+0.56MB/hr))
```
▂▄▁▅▃▃▂▃▅▆▁▂▅▄▁▅▁▁▅▅▁▁▆▆▇▃▃▆▂▃▅▆▁▃▅▅▂▄▂▂▂▂▅▂▂▄▂▂▄▄▄▅▆▃▂▂▄▄▃▁▂▁▅▅▄▅▅▅▅▅▆█
```

## Current Status

Goroutines: `███████████████████░ 99%`
Heap InUse: `████░░░░░░░░░░░░░░░░ 21%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,607 | 14,067 | +540 | 14,154 | 14,653 | stable (+0.09/hr) |
| Heap InUse | 213.6MB | 183.6MB | +30.0MB | 145.5MB | 213.6MB | INCREASING (+0.56MB/hr) |
| Heap Sys | 1012.6MB | 1012.9MB | -0.3MB | 795.8MB | 1016.6MB | |
| Heap Objects | 1,002,970 | 1,343,690 | -340720 | 793,073 | 1,343,690 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 13 | 14,139 | 159.1MB | 213.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `bytes.growSlice` | 3.52MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.01MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `bufio.NewWriterSize` | 2.02MB |
| 10 | `bufio.NewReaderSize` | 2.02MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 52.68GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 23.97GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 23.62GB |
| 4 | `internal/evaluation.mergeMetadata` | 23.0GB |
| 5 | `reflect.unsafe_NewArray` | 22.74GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 20.73GB |
| 7 | `reflect.MakeSlice` | 12.66GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 11.81GB |
| 9 | `experiment/local.topologicalSort` | 11.76GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 9.04GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 70/72 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/72 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 10.61MB | 67/72 | `████░░░░░░░░░░░ 28%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 70/72 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.85MB | 62/72 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/72 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/72 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB | 1/72 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `segmentio/kafka-go.makePartitions` | 2.9MB | 55/72 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.76MB | 2/72 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 24.83GB | 63/72 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 15.26GB | 48/72 | `█████████░░░░░░ 61%` |
| 3 | `internal/evaluation.mergeMetadata` | 11.91GB | 59/72 | `███████░░░░░░░░ 47%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 11.28GB | 64/72 | `██████░░░░░░░░░ 45%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 11.26GB | 65/72 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 10.74GB | 63/72 | `██████░░░░░░░░░ 43%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 6.67GB | 48/72 | `████░░░░░░░░░░░ 26%` |
| 8 | `reflect.MakeSlice` | 6.18GB | 61/72 | `███░░░░░░░░░░░░ 24%` |
| 9 | `experiment/local.topologicalSort` | 6.0GB | 60/72 | `███░░░░░░░░░░░░ 24%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 5.91GB | 61/72 | `███░░░░░░░░░░░░ 23%` |

## Alerts

No anomalies detected.
