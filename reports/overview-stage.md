# Overview: stage
*Last updated: 2026-06-07 03:30 IST*
*Data range: 2026-05-15T16:03 to 2026-06-07T03:30 (1102 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,068 | avg: 14,214 | max: 28,205 | trend: stable (-0.36/hr))
```
▂▁▂▇▄▅▁▁▁▁▁▁▁▁▁▁▁▁▃▁▂▁▁▂▃█▁▁▁▁▄▃▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▄▂▄▄▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▅▃▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 152.5MB | avg: 164.3MB | max: 732.9MB | trend: stable (-0.05MB/hr))
```
▃▂▂▂█▆▃▂▂▁▂▃▁▃▃▂▂▂▁▃▅▂▂▂▃▂▃▃▂▂▁▂▃▂▃▁▂▁▁▁▂▁▂▁▂▁▂▁▁▃▁▁▄▂▂▁▁▁▂▂▃▂▁▁▂▂▁▁▂▁▂▃▃▂▁▂▂▁▂▁▂▃▂▂▂▁▂▁▁▂▂▃▁▂▁▂
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,068 | 14,075 | -7 | 14,214 | 28,205 | stable (-0.36/hr) |
| Heap InUse | 152.5MB | 116.8MB | +35.7MB | 164.3MB | 732.9MB | stable (-0.05MB/hr) |
| Heap Sys | 988.1MB | 987.4MB | +0.7MB | 1232.0MB | 1805.8MB | |
| Heap Objects | 988,457 | 494,337 | +494120 | 880,143 | 2,707,946 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 48 | 14,138 | 178.7MB | 369.4MB |
| 2026-05-21 | 72 | 14,362 | 180.0MB | 556.9MB |
| 2026-05-22 | 50 | 14,165 | 186.1MB | 277.6MB |
| 2026-05-23 | 48 | 14,133 | 181.2MB | 368.1MB |
| 2026-05-24 | 48 | 14,127 | 179.7MB | 263.6MB |
| 2026-05-25 | 48 | 14,341 | 196.2MB | 338.8MB |
| 2026-05-26 | 46 | 14,155 | 171.1MB | 299.9MB |
| 2026-05-27 | 47 | 14,177 | 151.2MB | 232.3MB |
| 2026-05-28 | 48 | 14,161 | 148.6MB | 218.1MB |
| 2026-05-29 | 48 | 14,166 | 148.6MB | 258.2MB |
| 2026-05-30 | 48 | 14,205 | 164.1MB | 277.7MB |
| 2026-05-31 | 48 | 14,126 | 149.1MB | 213.6MB |
| 2026-06-01 | 48 | 14,226 | 160.1MB | 355.0MB |
| 2026-06-02 | 48 | 14,148 | 157.1MB | 206.0MB |
| 2026-06-03 | 48 | 14,147 | 154.2MB | 260.4MB |
| 2026-06-04 | 47 | 14,166 | 140.9MB | 258.6MB |
| 2026-06-05 | 48 | 14,143 | 157.3MB | 338.5MB |
| 2026-06-06 | 48 | 14,125 | 145.8MB | 231.1MB |
| 2026-06-07 | 8 | 14,068 | 149.6MB | 183.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `segmentio/kafka-go.makePartitions` | 6.51MB |
| 6 | `compress/flate.NewWriter` | 3.53MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.mapassign_faststr0` | 2.0MB |
| 9 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.0MB |
| 10 | `reflect.unsafe_NewArray` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 91.34GB |
| 2 | `reflect.unsafe_NewArray` | 39.58GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 36.99GB |
| 4 | `reflect.MakeSlice` | 22.22GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 14.53GB |
| 6 | `segmentio/kafka-go.makeLayout` | 9.84GB |
| 7 | `v3/newrelic.newAnalyticsEvents` | 4.76GB |
| 8 | `go-sql-driver/mysql.(*binaryRows).readRow` | 4.63GB |
| 9 | `internal/reflectlite.unsafe_New` | 4.47GB |
| 10 | `database/sql.convertAssignRows` | 4.07GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 558.72MB | 556.68MB | 470.38MB | 0B |
| `evaluation.mergeMetadata` | 239.06MB | 237.56MB | 198.18MB | 0B |
| `local.(*Client).EvaluateV2` | 968.49MB | 964.35MB | 813.97MB | 0B |
| `local.topologicalSort` | 150.56MB | 150.05MB | 124.89MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 986.24MB | 981.59MB | 822.70MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 101.39MB | 101.39MB | 90.14MB | 0B |
| `localEvaluation.getMapOfValue` | 986.24MB | 981.59MB | 822.70MB | 0B |
| `utils.ParseFeatureFlag` | 987.74MB | 983.09MB | 823.95MB | 0B |

**Total FF alloc (current snapshot):** 4.86GB  |  **24h avg:** 4.07GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1100/1102 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.2MB | 43/1102 | `███████░░░░░░░░ 49%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.64MB | 28/1102 | `██████░░░░░░░░░ 45%` |
| 4 | `runtime.mallocgc` | 13.38MB | 1096/1102 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 11.89MB | 45/1102 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1102 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1102 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1102 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1097/1102 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1102 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 88.39GB | 1092/1102 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1102 | `██████████░░░░░ 72%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1102 | `██████████░░░░░ 71%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1102 | `██████████░░░░░ 70%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 47.4GB | 1032/1102 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 38.25GB | 1091/1102 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1102 | `█████░░░░░░░░░░ 38%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1102 | `█████░░░░░░░░░░ 38%` |
| 9 | `reflect.MakeSlice` | 21.54GB | 1082/1102 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.27GB | 1029/1102 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
