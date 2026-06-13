# Overview: stage
*Last updated: 2026-06-13 15:03 IST*
*Data range: 2026-05-15T16:03 to 2026-06-13T15:03 (1411 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,136 | avg: 14,198 | max: 28,205 | trend: stable (-0.28/hr))
```
▂▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▂▁▁▃▄▁▅▅▁▁▁▁▁▁▁▁▁▁▁▂▁▁▃▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▂▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▄▁▁
```

**Heap InUse** (current: 174.3MB | avg: 161.6MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▄▄▂▂▅▂▅▁▃▃▂▁▅▁▄▂▄▁▁▂▅▁▄▂▅▂▃▃▃▅▅▃▂▁▅▅▃▅▄▆▃▆▁▅▅▆▂▆▂▄▄▅▃▁▆▁▅▆▃▆▂▁▅▃▃▄▃▃▅▃▁▁▆▆▂▂▂▁█▅▃▄▅▅▁▁▄▄▅▃▄▅▁▆▂▅
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,136 | 14,068 | +68 | 14,198 | 28,205 | stable (-0.28/hr) |
| Heap InUse | 174.3MB | 119.1MB | +55.2MB | 161.6MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 1266.7MB | 1266.7MB | +0.0MB | 1183.3MB | 1805.8MB | |
| Heap Objects | 1,189,067 | 518,353 | +670714 | 880,847 | 2,707,946 | |

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
| 2026-06-12 | 48 | 14,135 | 148.8MB | 189.5MB |
| 2026-06-13 | 31 | 14,124 | 147.7MB | 214.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 9.51MB |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 9.5MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `segmentio/kafka-go.makePartitions` | 5.51MB |
| 6 | `dotlapse-event-service/workerpool.NewWorker` | 3.0MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.85MB |
| 8 | `compress/flate.NewWriter` | 2.64MB |
| 9 | `aws/endpoints.init` | 2.01MB |
| 10 | `bufio.NewWriterSize` | 1.52MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 78.27GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 39.88GB |
| 3 | `reflect.unsafe_NewArray` | 33.5GB |
| 4 | `reflect.MakeSlice` | 18.65GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 16.35GB |
| 6 | `segmentio/kafka-go.makeLayout` | 8.26GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 5.13GB |
| 8 | `database/sql.convertAssignRows` | 4.6GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 4.08GB |
| 10 | `internal/reflectlite.unsafe_New` | 3.78GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 431.88MB | 428.84MB | 351.39MB | 0B |
| `evaluation.mergeMetadata` | 191.55MB | 189.55MB | 154.71MB | 0B |
| `local.(*Client).EvaluateV2` | 709.31MB | 703.65MB | 579.52MB | 0B |
| `local.topologicalSort` | 84.39MB | 83.36MB | 68.14MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 672.27MB | 666.62MB | 537.51MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 107.63MB | 107.63MB | 97.05MB | 0B |
| `localEvaluation.getMapOfValue` | 672.27MB | 666.62MB | 537.51MB | 0B |
| `utils.ParseFeatureFlag` | 673.77MB | 668.12MB | 539.01MB | 0B |

**Total FF alloc (current snapshot):** 3.46GB  |  **24h avg:** 2.80GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1409/1411 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.76MB | 52/1411 | `███████░░░░░░░░ 51%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 15.77MB | 32/1411 | `██████░░░░░░░░░ 43%` |
| 4 | `runtime.mallocgc` | 12.97MB | 1405/1411 | `█████░░░░░░░░░░ 35%` |
| 5 | `database/sql.convertAssignRows` | 11.45MB | 54/1411 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1411 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1411 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1411 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1406/1411 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1411 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 92.85GB | 1401/1411 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1411 | `██████████░░░░░ 68%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1411 | `██████████░░░░░ 67%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1411 | `██████████░░░░░ 67%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 49.81GB | 1292/1411 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 40.17GB | 1400/1411 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1411 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1411 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 22.58GB | 1391/1411 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.72GB | 1288/1411 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
