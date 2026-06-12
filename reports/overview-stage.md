# Overview: stage
*Last updated: 2026-06-12 21:32 IST*
*Data range: 2026-05-15T16:03 to 2026-06-12T21:32 (1376 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,067 | avg: 14,200 | max: 28,205 | trend: stable (-0.29/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▇▁▁▁▁▁▁▁▁▁▁▁▁▄▁▆▁▁▃▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▂▁▁▄▇▁█▇▁▁▁▁▁▂▁▁▁▁▁▃▁▂▅▃▃▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 121.4MB | avg: 161.9MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▁▅▃▂▄▃▁▁▄▂▁▄▂▄▅█▁▇▁▂▂▄▃▁▄▄▅▄▅▃▃▅▂▄▃▄▄▂▃▆▂▆▁▄▄▂▁▆▁▅▃▄▁▁▂▅▁▄▂▅▃▄▃▃▆▅▄▃▁▆▆▃▆▅▆▃▇▁▆▆▆▃▆▂▄▅▆▃▂▇▁▅▇▄▆▂
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,067 | 14,065 | +2 | 14,200 | 28,205 | stable (-0.29/hr) |
| Heap InUse | 121.4MB | 183.5MB | -62.1MB | 161.9MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 1267.8MB | 1267.8MB | +0.0MB | 1181.2MB | 1805.8MB | |
| Heap Objects | 575,750 | 1,344,009 | -768259 | 882,107 | 2,707,946 | |

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
| 2026-06-12 | 44 | 14,141 | 149.7MB | 189.5MB |

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
| 8 | `aws/endpoints.init` | 2.01MB |
| 9 | `compress/flate.NewWriter` | 1.76MB |
| 10 | `reflect.mapassign_faststr0` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 46.22GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 21.22GB |
| 3 | `reflect.unsafe_NewArray` | 19.76GB |
| 4 | `reflect.MakeSlice` | 11.01GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 8.7GB |
| 6 | `segmentio/kafka-go.makeLayout` | 4.86GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.78GB |
| 8 | `database/sql.convertAssignRows` | 2.47GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 2.44GB |
| 10 | `internal/reflectlite.unsafe_New` | 2.24GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 324.84MB | 317.10MB | 166.14MB | 0B |
| `evaluation.mergeMetadata` | 143.53MB | 140.53MB | 73.47MB | 0B |
| `local.(*Client).EvaluateV2` | 537.74MB | 526.31MB | 270.17MB | 0B |
| `local.topologicalSort` | 63.57MB | 62.04MB | 32.19MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 494.57MB | 482.10MB | 246.30MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 93.70MB | 93.70MB | 46.45MB | 0B |
| `localEvaluation.getMapOfValue` | 494.57MB | 482.10MB | 246.30MB | 0B |
| `utils.ParseFeatureFlag` | 496.07MB | 483.60MB | 247.50MB | 0B |

**Total FF alloc (current snapshot):** 2.59GB  |  **24h avg:** 1.30GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1374/1376 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.76MB | 52/1376 | `███████░░░░░░░░ 51%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 15.77MB | 32/1376 | `██████░░░░░░░░░ 43%` |
| 4 | `runtime.mallocgc` | 13.05MB | 1370/1376 | `█████░░░░░░░░░░ 35%` |
| 5 | `database/sql.convertAssignRows` | 11.45MB | 54/1376 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1376 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1376 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1376 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1371/1376 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1376 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 93.62GB | 1366/1376 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1376 | `██████████░░░░░ 68%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1376 | `██████████░░░░░ 67%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1376 | `██████████░░░░░ 66%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 50.36GB | 1257/1376 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 40.51GB | 1365/1376 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1376 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1376 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 22.78GB | 1356/1376 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.98GB | 1253/1376 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
