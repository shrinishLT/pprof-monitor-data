# Overview: stage
*Last updated: 2026-06-12 09:03 IST*
*Data range: 2026-05-15T16:03 to 2026-06-12T09:03 (1351 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,090 | avg: 14,202 | max: 28,205 | trend: stable (-0.29/hr))
```
▁▁▁▁▁▁▁▁▂▁▁▂▂▂▁▁▁▃▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▇▁▁▁▁▁▁▁▁▁▁▁▁▄▁▆▁▁▃▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▂▁▁▄▇▁█▇▁▁▁▁
```

**Heap InUse** (current: 176.5MB | avg: 162.0MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▃▃▂▃▂▂▂▂▂▂█▃▂▃▃▄▁▂▂▄▃▄▁▄▃▁▃▂▁▂▂▁▁▃▂▁▃▁▃▃▄▁▄▁▁▁▂▂▁▂▃▃▂▃▂▂▃▂▃▂▃▃▁▂▄▁▄▁▂▂▁▁▃▁▃▂▂▁▁▁▃▁▃▂▃▂▂▂▂▃▃▂▂▁▄▄
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,090 | 14,067 | +23 | 14,202 | 28,205 | stable (-0.29/hr) |
| Heap InUse | 176.5MB | 181.5MB | -5.0MB | 162.0MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 1267.3MB | 1267.4MB | -0.1MB | 1179.6MB | 1805.8MB | |
| Heap Objects | 1,230,240 | 1,341,000 | -110760 | 880,496 | 2,707,946 | |

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
| 2026-06-12 | 19 | 14,177 | 140.4MB | 181.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 9.51MB |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 9.5MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `reflect.unsafe_NewArray` | 4.02MB |
| 6 | `dotlapse-event-service/workerpool.NewWorker` | 3.0MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.85MB |
| 8 | `compress/flate.NewWriter` | 2.64MB |
| 9 | `aws/endpoints.init` | 2.01MB |
| 10 | `segmentio/kafka-go.makePartitions` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 23.34GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 17.26GB |
| 3 | `reflect.unsafe_NewArray` | 9.94GB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 7.05GB |
| 5 | `reflect.MakeSlice` | 5.52GB |
| 6 | `segmentio/kafka-go.makeLayout` | 2.46GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.26GB |
| 8 | `database/sql.convertAssignRows` | 1.99GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 1.32GB |
| 10 | `internal/reflectlite.unsafe_New` | 1.15GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 144.44MB | 143.44MB | 73.18MB | 0B |
| `evaluation.mergeMetadata` | 62.01MB | 61.51MB | 31.49MB | 0B |
| `local.(*Client).EvaluateV2` | 229.04MB | 226.44MB | 117.75MB | 0B |
| `local.topologicalSort` | 25.43MB | 25.43MB | 15.85MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 213.81MB | 211.21MB | 107.07MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 35.32MB | 35.32MB | 21.19MB | 0B |
| `localEvaluation.getMapOfValue` | 213.81MB | 211.21MB | 107.07MB | 0B |
| `utils.ParseFeatureFlag` | 215.31MB | 212.71MB | 107.64MB | 0B |

**Total FF alloc (current snapshot):** 1.11GB  |  **24h avg:** 581.25MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1349/1351 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.8MB | 51/1351 | `███████░░░░░░░░ 51%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.15MB | 31/1351 | `██████░░░░░░░░░ 44%` |
| 4 | `runtime.mallocgc` | 13.12MB | 1345/1351 | `█████░░░░░░░░░░ 35%` |
| 5 | `database/sql.convertAssignRows` | 11.49MB | 53/1351 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1351 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1351 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1351 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1346/1351 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1351 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 94.71GB | 1341/1351 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1351 | `██████████░░░░░ 67%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1351 | `█████████░░░░░░ 66%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1351 | `█████████░░░░░░ 66%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 50.98GB | 1232/1351 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 40.99GB | 1340/1351 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1351 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1351 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 23.05GB | 1331/1351 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 22.27GB | 1228/1351 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
