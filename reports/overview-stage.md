# Overview: stage
*Last updated: 2026-05-18 03:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T03:01 (114 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,087 | avg: 14,132 | max: 14,653 | trend: decreasing (-1.62/hr))
```
▃▁▁▁▁▁▇▃▁▁▁▁▁▂▁▁▂▅▃█▁▂▁▁▂▂▃▁▁▁▂▁▁▂▁▁▁▃▃▁▁▁▁▁▁▁▁▅▁▁▁▁▁▇▃▂▁▁▁▁▁▁▁▁▂▁▁▂▁▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 169.5MB | avg: 146.8MB | max: 213.6MB | trend: stable (+0.18MB/hr))
```
▅▅▁▁▆▅▇▃▃▅▂▂▅▆▁▃▄▅▁▄▁▂▂▁▄▁▂▄▁▁▄▄▄▄▅▃▁▁▄▃▃▁▂▁▄▅▄▅▄▅▅▄▆█▄▆▂▅▅▄▆▄▃▁▃▄▅▃▄▄▁▅▃▃▅▃▄▅▂▁▂▁▅▁▁▂▁▅▆▁▄▆▃▂▂▅
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 16%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,087 | 14,066 | +21 | 14,132 | 14,653 | decreasing (-1.62/hr) |
| Heap InUse | 169.5MB | 131.6MB | +37.9MB | 146.8MB | 213.6MB | stable (+0.18MB/hr) |
| Heap Sys | 1012.6MB | 1011.1MB | +1.5MB | 875.8MB | 1016.6MB | |
| Heap Objects | 1,077,758 | 657,392 | +420366 | 817,252 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 7 | 14,071 | 146.5MB | 186.8MB |

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
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 90.2GB |
| 2 | `reflect.unsafe_NewArray` | 39.01GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 34.32GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 33.83GB |
| 5 | `internal/evaluation.mergeMetadata` | 32.88GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 31.26GB |
| 7 | `reflect.MakeSlice` | 21.69GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.89GB |
| 9 | `experiment/local.topologicalSort` | 16.81GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 13.61GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 112/114 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.44MB | 1/114 | `█████░░░░░░░░░░ 39%` |
| 3 | `runtime.mallocgc` | 11.18MB | 109/114 | `████░░░░░░░░░░░ 30%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 112/114 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.91MB | 104/114 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 7.0MB | 1/114 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/114 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `internal/evaluation.mergeMetadata` | 3.25MB | 2/114 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `segmentio/kafka-go.makePartitions` | 3.04MB | 94/114 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `compress/flate.NewWriter` | 2.8MB | 95/114 | `█░░░░░░░░░░░░░░ 7%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 43.65GB | 105/114 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 22.22GB | 90/114 | `███████░░░░░░░░ 50%` |
| 3 | `reflect.unsafe_NewArray` | 18.86GB | 105/114 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 18.73GB | 101/114 | `██████░░░░░░░░░ 42%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 18.42GB | 107/114 | `██████░░░░░░░░░ 42%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 18.34GB | 106/114 | `██████░░░░░░░░░ 42%` |
| 7 | `reflect.MakeSlice` | 10.7GB | 103/114 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 9.69GB | 90/114 | `███░░░░░░░░░░░░ 22%` |
| 9 | `experiment/local.topologicalSort` | 9.51GB | 102/114 | `███░░░░░░░░░░░░ 21%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 9.37GB | 103/114 | `███░░░░░░░░░░░░ 21%` |

## Alerts

No anomalies detected.
