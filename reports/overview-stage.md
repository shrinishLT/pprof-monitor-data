# Overview: stage
*Last updated: 2026-06-09 04:31 IST*
*Data range: 2026-05-15T16:03 to 2026-06-09T04:31 (1199 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,068 | avg: 14,210 | max: 28,205 | trend: stable (-0.32/hr))
```
▁▁▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▄▁▁▁▁▁▁▁▂▁▁▁▁▂▁▃▁▃▁▁▁▁█▁▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁
```

**Heap InUse** (current: 127.7MB | avg: 163.7MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▃▃▁▆█▁▃▄▂▃▁▂▁▂▃▃▁▃▃▁▃▃▃▂▁▃▃▃▂▁▁▂▃▃▄▃▁▂▃▂▃▁▃▃▁▁▂▃▄▃▆▃▂▁▂▃▂▂▂▃▂▁▃▂▂▁▃▂▃▃▂▃▂▃▂▄▃▁▁▁▃▁▃▁▁▂▁▃▃▃▂▃▄▃▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,068 | 14,083 | -15 | 14,210 | 28,205 | stable (-0.32/hr) |
| Heap InUse | 127.7MB | 122.4MB | +5.3MB | 163.7MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 1098.1MB | 1098.1MB | +0.0MB | 1220.7MB | 1805.8MB | |
| Heap Objects | 614,124 | 532,422 | +81702 | 883,655 | 2,707,946 | |

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
| 2026-06-09 | 10 | 14,116 | 157.1MB | 196.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.mapassign_faststr0` | 1.5MB |
| 9 | `encoding/json.(*decodeState).literalStore` | 1.04MB |
| 10 | `reflect.unsafe_NewArray` | 1.03MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 180.72GB |
| 2 | `reflect.unsafe_NewArray` | 78.12GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 75.08GB |
| 4 | `reflect.MakeSlice` | 43.75GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 29.46GB |
| 6 | `segmentio/kafka-go.makeLayout` | 19.23GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 9.42GB |
| 8 | `v3/newrelic.newAnalyticsEvents` | 9.3GB |
| 9 | `internal/reflectlite.unsafe_New` | 8.79GB |
| 10 | `database/sql.convertAssignRows` | 8.4GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.04GB | 1.03GB | 930.04MB | 0B |
| `evaluation.mergeMetadata` | 453.11MB | 452.11MB | 401.08MB | 0B |
| `local.(*Client).EvaluateV2` | 1.78GB | 1.78GB | 1.56GB | 0B |
| `local.topologicalSort` | 271.97MB | 271.47MB | 238.75MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.85GB | 1.84GB | 1.61GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 178.75MB | 178.75MB | 159.60MB | 0B |
| `localEvaluation.getMapOfValue` | 1.85GB | 1.84GB | 1.61GB | 0B |
| `utils.ParseFeatureFlag` | 1.85GB | 1.84GB | 1.61GB | 0B |

**Total FF alloc (current snapshot):** 9.24GB  |  **24h avg:** 8.09GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1197/1199 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.29MB | 47/1199 | `███████░░░░░░░░ 49%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.3MB | 30/1199 | `██████░░░░░░░░░ 44%` |
| 4 | `runtime.mallocgc` | 13.36MB | 1193/1199 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 11.54MB | 49/1199 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1199 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1199 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1199 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1194/1199 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1199 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 92.33GB | 1189/1199 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1199 | `██████████░░░░░ 69%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1199 | `██████████░░░░░ 68%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1199 | `██████████░░░░░ 67%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 48.73GB | 1129/1199 | `███████░░░░░░░░ 52%` |
| 6 | `reflect.unsafe_NewArray` | 39.97GB | 1188/1199 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1199 | `█████░░░░░░░░░░ 37%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1199 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 22.5GB | 1179/1199 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.56GB | 1126/1199 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
