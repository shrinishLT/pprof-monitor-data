# Overview: stage
*Last updated: 2026-06-07 09:30 IST*
*Data range: 2026-05-15T16:03 to 2026-06-07T09:30 (1114 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,070 | avg: 14,214 | max: 28,205 | trend: stable (-0.35/hr))
```
▁▁▁▁▁▁▃▁▂▁▁▂▃▇▁▁▁▁▄▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▄▂▄▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▅▂▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▄█▁▁▁▁▁▁
```

**Heap InUse** (current: 106.6MB | avg: 164.4MB | max: 732.9MB | trend: stable (-0.05MB/hr))
```
▁▃▃▂▂▂▁▃▆▃▂▂▃▂▄▃▂▃▁▂▃▂▃▁▂▁▁▁▃▁▃▂▃▁▂▁▁▃▁▁▅▂▂▁▁▁▂▂▃▂▁▁▂▃▁▁▂▁▃▃▃▃▁▂▂▁▂▂▂▃▃▂▂▁▃▁▁▃▂▃▁▂▁▂▁▃▃▁▆█▁▃▄▂▃▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,070 | 14,078 | -8 | 14,214 | 28,205 | stable (-0.35/hr) |
| Heap InUse | 106.6MB | 182.8MB | -76.2MB | 164.4MB | 732.9MB | stable (-0.05MB/hr) |
| Heap Sys | 1097.1MB | 1097.1MB | +0.0MB | 1230.1MB | 1805.8MB | |
| Heap Objects | 345,061 | 1,348,964 | -1003903 | 880,606 | 2,707,946 | |

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
| 2026-06-07 | 20 | 14,121 | 162.9MB | 298.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 7 | `reflect.mapassign_faststr0` | 1.5MB |
| 8 | `kafka-go/protocol.newPage` | 1.06MB |
| 9 | `regexp.(*bitState).reset` | 1.03MB |
| 10 | `aws/endpoints.init` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 102.22GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 53.07GB |
| 3 | `reflect.unsafe_NewArray` | 44.41GB |
| 4 | `reflect.MakeSlice` | 24.94GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 20.78GB |
| 6 | `segmentio/kafka-go.makeLayout` | 10.99GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 6.58GB |
| 8 | `database/sql.convertAssignRows` | 5.85GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 5.32GB |
| 10 | `internal/reflectlite.unsafe_New` | 4.99GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 618.88MB | 615.83MB | 521.17MB | 0B |
| `evaluation.mergeMetadata` | 264.56MB | 263.06MB | 220.66MB | 0B |
| `local.(*Client).EvaluateV2` | 1.04GB | 1.04GB | 901.82MB | 0B |
| `local.topologicalSort` | 161.22MB | 161.22MB | 138.71MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.06GB | 1.06GB | 914.93MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 109.71MB | 109.71MB | 97.03MB | 0B |
| `localEvaluation.getMapOfValue` | 1.06GB | 1.06GB | 914.93MB | 0B |
| `utils.ParseFeatureFlag` | 1.06GB | 1.06GB | 916.31MB | 0B |

**Total FF alloc (current snapshot):** 5.36GB  |  **24h avg:** 4.52GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1112/1114 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.49MB | 45/1114 | `███████░░░░░░░░ 50%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.42MB | 29/1114 | `██████░░░░░░░░░ 44%` |
| 4 | `runtime.mallocgc` | 13.38MB | 1108/1114 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 11.76MB | 47/1114 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1114 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1114 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1114 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1109/1114 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1114 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 88.48GB | 1104/1114 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1114 | `██████████░░░░░ 72%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1114 | `██████████░░░░░ 71%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1114 | `██████████░░░░░ 70%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 47.39GB | 1044/1114 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 38.29GB | 1103/1114 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1114 | `█████░░░░░░░░░░ 38%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1114 | `█████░░░░░░░░░░ 38%` |
| 9 | `reflect.MakeSlice` | 21.56GB | 1094/1114 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.24GB | 1041/1114 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
