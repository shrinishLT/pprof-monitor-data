# Overview: stage
*Last updated: 2026-06-12 14:02 IST*
*Data range: 2026-05-15T16:03 to 2026-06-12T14:02 (1361 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,155 | avg: 14,201 | max: 28,205 | trend: stable (-0.29/hr))
```
▁▂▂▂▁▁▁▃▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▇▁▁▁▁▁▁▁▁▁▁▁▁▄▁▆▁▁▃▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▂▁▁▄▇▁█▇▁▁▁▁▁▂▁▁▁▁▁▃▁▂
```

**Heap InUse** (current: 184.6MB | avg: 162.0MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
█▃▂▃▃▄▁▂▂▄▃▄▁▄▃▁▃▂▁▂▂▁▁▃▂▁▃▁▃▃▄▁▄▁▁▁▂▂▁▂▃▃▂▃▂▂▃▂▃▂▃▃▁▂▄▁▄▁▂▂▁▁▃▁▃▂▂▁▁▁▃▁▃▂▃▂▂▂▂▃▃▂▂▁▄▄▂▄▃▄▂▄▁▃▄▄
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,155 | 14,071 | +84 | 14,201 | 28,205 | stable (-0.29/hr) |
| Heap InUse | 184.6MB | 181.0MB | +3.6MB | 162.0MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 1267.4MB | 1267.4MB | +0.0MB | 1180.2MB | 1805.8MB | |
| Heap Objects | 1,311,108 | 1,270,696 | +40412 | 881,890 | 2,707,946 | |

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
| 2026-06-09 | 48 | 14,154 | 161.0MB | 283.6MB |
| 2026-06-10 | 47 | 14,121 | 151.2MB | 275.7MB |
| 2026-06-11 | 48 | 14,109 | 139.5MB | 199.7MB |
| 2026-06-12 | 29 | 14,151 | 148.6MB | 187.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 9.51MB |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 9.5MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `compress/flate.NewWriter` | 5.29MB |
| 6 | `dotlapse-event-service/workerpool.NewWorker` | 3.0MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.85MB |
| 8 | `reflect.unsafe_NewArray` | 2.02MB |
| 9 | `aws/endpoints.init` | 2.01MB |
| 10 | `segmentio/kafka-go.makePartitions` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 32.46GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 19.03GB |
| 3 | `reflect.unsafe_NewArray` | 13.85GB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 7.77GB |
| 5 | `reflect.MakeSlice` | 7.73GB |
| 6 | `segmentio/kafka-go.makeLayout` | 3.41GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.48GB |
| 8 | `database/sql.convertAssignRows` | 2.19GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 1.79GB |
| 10 | `internal/reflectlite.unsafe_New` | 1.59GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 208.48MB | 200.73MB | 97.92MB | 0B |
| `evaluation.mergeMetadata` | 94.02MB | 90.52MB | 42.50MB | 0B |
| `local.(*Client).EvaluateV2` | 333.08MB | 321.12MB | 156.92MB | 0B |
| `local.topologicalSort` | 38.16MB | 36.64MB | 20.09MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 302.03MB | 287.99MB | 141.65MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 58.86MB | 58.35MB | 28.25MB | 0B |
| `localEvaluation.getMapOfValue` | 302.03MB | 287.99MB | 141.65MB | 0B |
| `utils.ParseFeatureFlag` | 303.53MB | 289.49MB | 142.53MB | 0B |

**Total FF alloc (current snapshot):** 1.60GB  |  **24h avg:** 771.50MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1359/1361 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.76MB | 52/1361 | `███████░░░░░░░░ 51%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 15.77MB | 32/1361 | `██████░░░░░░░░░ 43%` |
| 4 | `runtime.mallocgc` | 13.09MB | 1355/1361 | `█████░░░░░░░░░░ 35%` |
| 5 | `database/sql.convertAssignRows` | 11.45MB | 54/1361 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1361 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1361 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1361 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1356/1361 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1361 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 94.21GB | 1351/1361 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1361 | `██████████░░░░░ 67%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1361 | `██████████░░░░░ 66%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1361 | `█████████░░░░░░ 66%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 50.71GB | 1242/1361 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 40.77GB | 1350/1361 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1361 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1361 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 22.93GB | 1341/1361 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 22.15GB | 1238/1361 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
