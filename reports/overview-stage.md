# Overview: stage
*Last updated: 2026-06-14 02:31 IST*
*Data range: 2026-05-15T16:03 to 2026-06-14T02:31 (1434 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,066 | avg: 14,196 | max: 28,205 | trend: stable (-0.28/hr))
```
▁▂▁▁▃▄▁▅▅▁▁▁▁▁▁▁▁▁▁▁▂▁▁▃▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▂▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▄▁▁▁▁▅▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 124.9MB | avg: 161.3MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▂▅▂▃▂▂▅▄▃▂▁▅▅▃▅▄▅▃▆▁▅▅▆▂▆▂▃▄▅▂▁▆▁▅▆▃▅▁▁▄▃▂▄▃▃▄▂▁▁▆▆▂▁▁▁█▅▃▄▄▄▁▁▄▃▅▃▃▄▁▆▁▅▆▂▅▄▂▅▃▁▁▅▁▂▂▁▅▃▁▅▃▄▂▅▂
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,066 | 14,069 | -3 | 14,196 | 28,205 | stable (-0.28/hr) |
| Heap InUse | 124.9MB | 174.4MB | -49.5MB | 161.3MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 1265.7MB | 1267.1MB | -1.4MB | 1184.6MB | 1805.8MB | |
| Heap Objects | 589,106 | 1,249,497 | -660391 | 880,009 | 2,707,946 | |

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
| 2026-06-14 | 6 | 14,093 | 152.2MB | 174.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 10.01MB |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 9.5MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 6 | `dotlapse-event-service/workerpool.NewWorker` | 3.0MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.85MB |
| 8 | `compress/flate.NewWriter` | 2.64MB |
| 9 | `aws/endpoints.init` | 2.01MB |
| 10 | `reflect.unsafe_New` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 99.21GB |
| 2 | `reflect.unsafe_NewArray` | 42.48GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 40.95GB |
| 4 | `reflect.MakeSlice` | 23.68GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 16.79GB |
| 6 | `segmentio/kafka-go.makeLayout` | 10.41GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 5.3GB |
| 8 | `v3/newrelic.newAnalyticsEvents` | 5.12GB |
| 9 | `internal/reflectlite.unsafe_New` | 4.86GB |
| 10 | `database/sql.convertAssignRows` | 4.76GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 504.99MB | 501.43MB | 430.32MB | 0B |
| `evaluation.mergeMetadata` | 225.05MB | 224.05MB | 190.59MB | 0B |
| `local.(*Client).EvaluateV2` | 831.58MB | 826.43MB | 709.64MB | 0B |
| `local.topologicalSort` | 106.77MB | 106.26MB | 86.28MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 806.94MB | 801.28MB | 674.35MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 113.80MB | 113.80MB | 107.88MB | 0B |
| `localEvaluation.getMapOfValue` | 806.94MB | 801.28MB | 674.35MB | 0B |
| `utils.ParseFeatureFlag` | 808.45MB | 802.78MB | 675.86MB | 0B |

**Total FF alloc (current snapshot):** 4.11GB  |  **24h avg:** 3.47GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1432/1434 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.76MB | 52/1434 | `███████░░░░░░░░ 51%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 15.77MB | 32/1434 | `██████░░░░░░░░░ 43%` |
| 4 | `runtime.mallocgc` | 12.91MB | 1428/1434 | `█████░░░░░░░░░░ 35%` |
| 5 | `database/sql.convertAssignRows` | 11.45MB | 54/1434 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1434 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1434 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1434 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1429/1434 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1434 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 92.79GB | 1424/1434 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1434 | `██████████░░░░░ 68%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1434 | `██████████░░░░░ 68%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1434 | `██████████░░░░░ 67%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 49.65GB | 1315/1434 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 40.14GB | 1423/1434 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1434 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1434 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 22.56GB | 1414/1434 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.63GB | 1311/1434 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.5x avg)
