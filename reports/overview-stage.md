# Overview: stage
*Last updated: 2026-06-07 22:02 IST*
*Data range: 2026-05-15T16:03 to 2026-06-07T22:02 (1138 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,127 | avg: 14,211 | max: 28,205 | trend: stable (-0.36/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▃▄▁▄▂▄▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▅▂▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▄█▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 193.4MB | avg: 164.2MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▂▁▁▁▃▁▃▂▃▁▂▁▁▃▁▁▅▂▂▁▁▁▂▂▃▂▁▁▂▃▁▁▂▁▃▃▃▃▁▂▂▁▂▂▂▃▃▂▂▁▃▁▁▃▂▃▁▂▁▂▁▃▃▁▆█▁▃▄▂▃▁▂▁▂▃▃▁▃▃▁▃▃▃▂▁▃▃▃▂▁▁▂▃▃▄
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,127 | 14,074 | +53 | 14,211 | 28,205 | stable (-0.36/hr) |
| Heap InUse | 193.4MB | 187.6MB | +5.8MB | 164.2MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 1097.5MB | 1097.3MB | +0.2MB | 1227.3MB | 1805.8MB | |
| Heap Objects | 1,428,554 | 1,419,466 | +9088 | 882,844 | 2,707,946 | |

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
| 2026-06-07 | 44 | 14,105 | 159.1MB | 298.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.51MB |
| 6 | `compress/flate.NewWriter` | 4.41MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.mapassign_faststr0` | 1.5MB |
| 9 | `aws/endpoints.init` | 1.0MB |
| 10 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 125.13GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 56.39GB |
| 3 | `reflect.unsafe_NewArray` | 54.32GB |
| 4 | `reflect.MakeSlice` | 30.36GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 22.09GB |
| 6 | `segmentio/kafka-go.makeLayout` | 13.37GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 7.03GB |
| 8 | `v3/newrelic.newAnalyticsEvents` | 6.51GB |
| 9 | `database/sql.convertAssignRows` | 6.24GB |
| 10 | `internal/reflectlite.unsafe_New` | 6.12GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 728.22MB | 723.56MB | 621.05MB | 0B |
| `evaluation.mergeMetadata` | 315.08MB | 313.08MB | 265.72MB | 0B |
| `local.(*Client).EvaluateV2` | 1.22GB | 1.21GB | 1.05GB | 0B |
| `local.topologicalSort` | 186.64MB | 186.13MB | 162.63MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.26GB | 1.25GB | 1.07GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 127.91MB | 127.91MB | 111.71MB | 0B |
| `localEvaluation.getMapOfValue` | 1.26GB | 1.25GB | 1.07GB | 0B |
| `utils.ParseFeatureFlag` | 1.26GB | 1.25GB | 1.07GB | 0B |

**Total FF alloc (current snapshot):** 6.32GB  |  **24h avg:** 5.38GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1136/1138 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.49MB | 45/1138 | `███████░░░░░░░░ 50%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.42MB | 29/1138 | `██████░░░░░░░░░ 44%` |
| 4 | `runtime.mallocgc` | 13.37MB | 1132/1138 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 11.76MB | 47/1138 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1138 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1138 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1138 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1133/1138 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1138 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 89.04GB | 1128/1138 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1138 | `██████████░░░░░ 71%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1138 | `██████████░░░░░ 70%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1138 | `██████████░░░░░ 70%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 47.57GB | 1068/1138 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 38.54GB | 1127/1138 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1138 | `█████░░░░░░░░░░ 38%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1138 | `█████░░░░░░░░░░ 38%` |
| 9 | `reflect.MakeSlice` | 21.69GB | 1118/1138 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.25GB | 1065/1138 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
