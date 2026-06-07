# Overview: stage
*Last updated: 2026-06-07 10:30 IST*
*Data range: 2026-05-15T16:03 to 2026-06-07T10:30 (1116 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,065 | avg: 14,213 | max: 28,205 | trend: stable (-0.36/hr))
```
▁▁▁▁▃▁▂▁▁▂▃▇▁▁▁▁▄▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▄▂▄▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▅▂▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▄█▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 114.6MB | avg: 164.3MB | max: 732.9MB | trend: stable (-0.05MB/hr))
```
▃▂▂▂▁▃▆▃▂▂▃▂▄▃▂▃▁▂▃▂▃▁▂▁▁▁▃▁▃▂▃▁▂▁▁▃▁▁▅▂▂▁▁▁▂▂▃▂▁▁▂▃▁▁▂▁▃▃▃▃▁▂▂▁▂▂▂▃▃▂▂▁▃▁▁▃▂▃▁▂▁▂▁▃▃▁▆█▁▃▄▂▃▁▂▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,065 | 14,066 | -1 | 14,213 | 28,205 | stable (-0.36/hr) |
| Heap InUse | 114.6MB | 139.0MB | -24.4MB | 164.3MB | 732.9MB | stable (-0.05MB/hr) |
| Heap Sys | 1097.1MB | 1097.1MB | +0.0MB | 1229.9MB | 1805.8MB | |
| Heap Objects | 482,106 | 768,546 | -286440 | 880,148 | 2,707,946 | |

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
| 2026-06-07 | 22 | 14,116 | 159.6MB | 298.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `reflect.unsafe_NewArray` | 3.01MB |
| 7 | `segmentio/kafka-go.makePartitions` | 3.01MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `reflect.mapassign_faststr0` | 2.0MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 1.07MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 104.05GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 53.07GB |
| 3 | `reflect.unsafe_NewArray` | 45.17GB |
| 4 | `reflect.MakeSlice` | 25.36GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 20.78GB |
| 6 | `segmentio/kafka-go.makeLayout` | 11.17GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 6.58GB |
| 8 | `database/sql.convertAssignRows` | 5.85GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 5.41GB |
| 10 | `internal/reflectlite.unsafe_New` | 5.07GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 619.88MB | 618.88MB | 529.70MB | 0B |
| `evaluation.mergeMetadata` | 265.06MB | 264.56MB | 224.58MB | 0B |
| `local.(*Client).EvaluateV2` | 1.04GB | 1.04GB | 916.41MB | 0B |
| `local.topologicalSort` | 161.22MB | 161.22MB | 140.86MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.06GB | 1.06GB | 930.28MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 109.71MB | 109.71MB | 98.17MB | 0B |
| `localEvaluation.getMapOfValue` | 1.06GB | 1.06GB | 930.28MB | 0B |
| `utils.ParseFeatureFlag` | 1.07GB | 1.06GB | 931.68MB | 0B |

**Total FF alloc (current snapshot):** 5.37GB  |  **24h avg:** 4.59GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1114/1116 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.49MB | 45/1116 | `███████░░░░░░░░ 50%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.42MB | 29/1116 | `██████░░░░░░░░░ 44%` |
| 4 | `runtime.mallocgc` | 13.38MB | 1110/1116 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 11.76MB | 47/1116 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1116 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1116 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1116 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1111/1116 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1116 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 88.51GB | 1106/1116 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1116 | `██████████░░░░░ 72%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1116 | `██████████░░░░░ 71%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1116 | `██████████░░░░░ 70%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 47.4GB | 1046/1116 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 38.31GB | 1105/1116 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1116 | `█████░░░░░░░░░░ 38%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1116 | `█████░░░░░░░░░░ 38%` |
| 9 | `reflect.MakeSlice` | 21.57GB | 1096/1116 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.24GB | 1043/1116 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
