# Overview: stage
*Last updated: 2026-05-18 18:49 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T18:48 (147 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,078 | avg: 14,181 | max: 17,149 | trend: INCREASING (+3.04/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▆▄▁▁
```

**Heap InUse** (current: 163.9MB | avg: 151.3MB | max: 290.3MB | trend: stable (+0.39MB/hr))
```
▃▃▂▁▁▂▂▂▁▁▁▃▃▂▃▃▃▃▃▃▅▃▄▁▃▃▂▄▃▂▁▂▂▃▂▃▃▁▃▂▂▃▂▂▃▂▁▁▁▃▁▁▁▁▃▄▁▂▄▂▁▁▃▃▁▃▃▂▇▄▂▂▁▁▃▂▁▁▂▃▃▄▁▂▄▂▁▃▄▃▄█▅▅▁▃
```

## Current Status

Goroutines: `████████████████░░░░ 82%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 12%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,078 | 14,097 | -19 | 14,181 | 17,149 | INCREASING (+3.04/hr) |
| Heap InUse | 163.9MB | 127.4MB | +36.5MB | 151.3MB | 290.3MB | stable (+0.39MB/hr) |
| Heap Sys | 1334.6MB | 1334.5MB | +0.1MB | 913.1MB | 1334.6MB | |
| Heap Objects | 956,273 | 594,564 | +361709 | 827,164 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 40 | 14,303 | 163.4MB | 290.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 8 | `reflect.mapassign_faststr0` | 2.0MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 118.59GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 72.33GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.58GB |
| 4 | `internal/evaluation.mergeMetadata` | 69.63GB |
| 5 | `reflect.unsafe_NewArray` | 51.33GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 46.99GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.29GB |
| 8 | `experiment/local.topologicalSort` | 35.56GB |
| 9 | `reflect.MakeSlice` | 28.44GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.44GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 145/147 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/147 | `██████░░░░░░░░░ 42%` |
| 3 | `runtime.mallocgc` | 11.44MB | 142/147 | `████░░░░░░░░░░░ 31%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 145/147 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.93MB | 137/147 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 8.5MB | 2/147 | `███░░░░░░░░░░░░ 23%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/147 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `bytes.growSlice` | 3.69MB | 21/147 | `█░░░░░░░░░░░░░░ 10%` |
| 9 | `segmentio/kafka-go.makePartitions` | 3.14MB | 125/147 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.01MB | 7/147 | `█░░░░░░░░░░░░░░ 8%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 58.42GB | 138/147 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 27.69GB | 123/147 | `███████░░░░░░░░ 47%` |
| 3 | `reflect.unsafe_NewArray` | 25.25GB | 138/147 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 24.37GB | 134/147 | `██████░░░░░░░░░ 41%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 24.28GB | 140/147 | `██████░░░░░░░░░ 41%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 24.13GB | 139/147 | `██████░░░░░░░░░ 41%` |
| 7 | `reflect.MakeSlice` | 14.25GB | 136/147 | `███░░░░░░░░░░░░ 24%` |
| 8 | `experiment/local.topologicalSort` | 12.37GB | 135/147 | `███░░░░░░░░░░░░ 21%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 12.27GB | 136/147 | `███░░░░░░░░░░░░ 21%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 12.06GB | 123/147 | `███░░░░░░░░░░░░ 20%` |

## Alerts

No anomalies detected.
