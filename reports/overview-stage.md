# Overview: stage
*Last updated: 2026-06-08 23:31 IST*
*Data range: 2026-05-15T16:03 to 2026-06-08T23:31 (1189 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,076 | avg: 14,211 | max: 28,205 | trend: stable (-0.32/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▄▁▁▁▁▁▁▁▂▁▁▁▁▂▁▃▁▃▁▁▁▁█▁▅▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 153.3MB | avg: 163.8MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▁▁▃▂▃▁▂▁▂▁▃▃▁▆█▁▃▄▂▃▁▂▁▂▃▃▁▃▃▁▃▃▃▂▁▃▃▃▂▁▁▂▃▃▄▃▁▂▃▂▃▁▃▃▁▁▂▃▄▃▆▃▂▁▂▃▂▂▂▃▂▁▃▂▂▁▃▂▃▃▂▃▂▃▂▄▃▁▁▁▃▁▃▁▁▂
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,076 | 14,067 | +9 | 14,211 | 28,205 | stable (-0.32/hr) |
| Heap InUse | 153.3MB | 128.5MB | +24.8MB | 163.8MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 1098.3MB | 1098.2MB | +0.1MB | 1221.8MB | 1805.8MB | |
| Heap Objects | 966,968 | 635,513 | +331455 | 883,115 | 2,707,946 | |

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
| 2026-06-07 | 47 | 14,103 | 158.2MB | 298.5MB |
| 2026-06-08 | 48 | 14,210 | 154.6MB | 265.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 7 | `compress/flate.NewWriter` | 1.76MB |
| 8 | `reflect.unsafe_NewArray` | 1.5MB |
| 9 | `compress/flate.(*compressor).initDeflate` | 1.07MB |
| 10 | `kafka-go/protocol.newPage` | 1.06MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 171.53GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 75.07GB |
| 3 | `reflect.unsafe_NewArray` | 74.19GB |
| 4 | `reflect.MakeSlice` | 41.58GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 29.45GB |
| 6 | `segmentio/kafka-go.makeLayout` | 18.26GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 9.4GB |
| 8 | `v3/newrelic.newAnalyticsEvents` | 8.84GB |
| 9 | `internal/reflectlite.unsafe_New` | 8.39GB |
| 10 | `database/sql.convertAssignRows` | 8.37GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.02GB | 1.01GB | 867.63MB | 0B |
| `evaluation.mergeMetadata` | 447.61MB | 445.11MB | 374.32MB | 0B |
| `local.(*Client).EvaluateV2` | 1.75GB | 1.74GB | 1.46GB | 0B |
| `local.topologicalSort` | 263.86MB | 262.85MB | 223.47MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.81GB | 1.80GB | 1.50GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 175.17MB | 175.17MB | 149.08MB | 0B |
| `localEvaluation.getMapOfValue` | 1.81GB | 1.80GB | 1.50GB | 0B |
| `utils.ParseFeatureFlag` | 1.81GB | 1.80GB | 1.51GB | 0B |

**Total FF alloc (current snapshot):** 9.05GB  |  **24h avg:** 7.55GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1187/1189 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.29MB | 47/1189 | `███████░░░░░░░░ 49%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.3MB | 30/1189 | `██████░░░░░░░░░ 44%` |
| 4 | `runtime.mallocgc` | 13.36MB | 1183/1189 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 11.54MB | 49/1189 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1189 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1189 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1189 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1184/1189 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1189 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 91.62GB | 1179/1189 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1189 | `██████████░░░░░ 69%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1189 | `██████████░░░░░ 68%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1189 | `██████████░░░░░ 68%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 48.5GB | 1119/1189 | `███████░░░░░░░░ 52%` |
| 6 | `reflect.unsafe_NewArray` | 39.66GB | 1178/1189 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1189 | `█████░░░░░░░░░░ 37%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1189 | `█████░░░░░░░░░░ 37%` |
| 9 | `reflect.MakeSlice` | 22.32GB | 1169/1189 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.49GB | 1116/1189 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
