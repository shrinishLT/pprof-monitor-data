# Overview: stage
*Last updated: 2026-06-17 17:31 IST*
*Data range: 2026-05-15T16:03 to 2026-06-17T17:31 (1607 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,079 | avg: 14,193 | max: 28,205 | trend: stable (-0.22/hr))
```
▇█▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 98.9MB | avg: 159.8MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▅▅▄▁▁▂▃▂▄▁▁▂▃▃▂▁▂▂▁▄▁▄▄▅▂▂▆▃▃▁▁▃▂▂▄▁▂▃▄▄▃▁▂▂▁▁▁▁▄▁▁▁▁▃▃▂▄▄▃▁▃▁▁▄▃▂▁▂▁▃▃▁▃█▃▃▂▂▁▃▂▁▂▃▁▁▃▄▃▁▁▂▂▁▄▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,079 | 14,067 | +12 | 14,193 | 28,205 | stable (-0.22/hr) |
| Heap InUse | 98.9MB | 178.8MB | -79.9MB | 159.8MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 397.4MB | 378.0MB | +19.4MB | 1155.9MB | 1805.8MB | |
| Heap Objects | 374,837 | 1,351,994 | -977157 | 875,180 | 2,707,946 | |

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
| 2026-06-13 | 48 | 14,121 | 146.0MB | 214.7MB |
| 2026-06-14 | 48 | 14,120 | 150.8MB | 247.1MB |
| 2026-06-15 | 48 | 14,245 | 154.3MB | 238.3MB |
| 2026-06-16 | 47 | 14,139 | 142.5MB | 226.4MB |
| 2026-06-17 | 36 | 14,131 | 139.1MB | 267.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 8.51MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 1.5MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 4.21GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 1.93GB |
| 3 | `reflect.unsafe_NewArray` | 1.8GB |
| 4 | `reflect.MakeSlice` | 1020.52MB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 832.35MB |
| 6 | `segmentio/kafka-go.makeLayout` | 460.7MB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 261.51MB |
| 8 | `v3/newrelic.newAnalyticsEvents` | 252.67MB |
| 9 | `database/sql.convertAssignRows` | 234.51MB |
| 10 | `internal/reflectlite.unsafe_New` | 207.52MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 57.63MB | 46.39MB | 137.05MB | 0B |
| `evaluation.mergeMetadata` | 23.01MB | 18.00MB | 64.01MB | 0B |
| `local.(*Client).EvaluateV2` | 85.93MB | 71.05MB | 231.06MB | 0B |
| `local.topologicalSort` | 9.12MB | 7.59MB | 32.20MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 72.91MB | 58.55MB | 226.10MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 23.31MB | 21.75MB | 32.96MB | 0B |
| `localEvaluation.getMapOfValue` | 72.91MB | 58.55MB | 226.10MB | 0B |
| `utils.ParseFeatureFlag` | 73.41MB | 59.05MB | 226.94MB | 0B |

**Total FF alloc (current snapshot):** 418.21MB  |  **24h avg:** 1.15GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1605/1607 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.66MB | 57/1607 | `███████░░░░░░░░ 50%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 15.47MB | 35/1607 | `██████░░░░░░░░░ 42%` |
| 4 | `runtime.mallocgc` | 12.49MB | 1601/1607 | `█████░░░░░░░░░░ 34%` |
| 5 | `database/sql.convertAssignRows` | 11.42MB | 59/1607 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1607 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1607 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1607 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.21MB | 1602/1607 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1607 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 89.38GB | 1597/1607 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1607 | `██████████░░░░░ 71%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1607 | `██████████░░░░░ 70%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1607 | `██████████░░░░░ 70%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 47.96GB | 1464/1607 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 38.65GB | 1596/1607 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1607 | `█████░░░░░░░░░░ 38%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1607 | `█████░░░░░░░░░░ 38%` |
| 9 | `reflect.MakeSlice` | 21.71GB | 1587/1607 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.81GB | 1460/1607 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (4.0x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.6x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.4x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.5x avg)
