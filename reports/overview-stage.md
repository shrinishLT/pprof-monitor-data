# Overview: stage
*Last updated: 2026-06-14 16:33 IST*
*Data range: 2026-05-15T16:03 to 2026-06-14T16:33 (1462 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,164 | avg: 14,195 | max: 28,205 | trend: stable (-0.27/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▂▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▄▁▁▁▁▅▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▄▁▁▁▃▁▂▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁
```

**Heap InUse** (current: 178.8MB | avg: 161.1MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▄▂▁▅▁▄▅▂▄▁▁▃▂▂▃▂▂▄▂▁▁▄▅▁▁▁▁▆▄▂▃▄▄▁▁▃▃▄▂▃▃▁▄▁▄▅▂▄▃▂▄▃▁▁▄▁▂▂▁▄▃▁▄▃▃▂▄▁▃▁▃▄▃▃█▄▄▂▂▃▁▄▁▂▁▄▂▁▄▁▄▁▁▁▃▄
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,164 | 14,065 | +99 | 14,195 | 28,205 | stable (-0.27/hr) |
| Heap InUse | 178.8MB | 153.2MB | +25.6MB | 161.1MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 1267.8MB | 1267.8MB | +0.0MB | 1186.2MB | 1805.8MB | |
| Heap Objects | 1,126,656 | 952,157 | +174499 | 878,699 | 2,707,946 | |

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
| 2026-06-14 | 34 | 14,136 | 150.9MB | 247.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 10.01MB |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 9.5MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 3.0MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.85MB |
| 9 | `reflect.unsafe_NewArray` | 2.51MB |
| 10 | `aws/endpoints.init` | 2.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 124.61GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 61.44GB |
| 3 | `reflect.unsafe_NewArray` | 53.53GB |
| 4 | `reflect.MakeSlice` | 29.83GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 25.21GB |
| 6 | `segmentio/kafka-go.makeLayout` | 13.02GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 7.92GB |
| 8 | `database/sql.convertAssignRows` | 7.16GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 6.41GB |
| 10 | `internal/reflectlite.unsafe_New` | 6.1GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 607.72MB | 604.06MB | 526.03MB | 0B |
| `evaluation.mergeMetadata` | 267.56MB | 266.06MB | 233.55MB | 0B |
| `local.(*Client).EvaluateV2` | 1003.11MB | 996.84MB | 866.68MB | 0B |
| `local.topologicalSort` | 129.59MB | 128.06MB | 110.70MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 986.58MB | 979.81MB | 842.69MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 129.38MB | 129.38MB | 118.96MB | 0B |
| `localEvaluation.getMapOfValue` | 986.58MB | 979.81MB | 842.69MB | 0B |
| `utils.ParseFeatureFlag` | 988.58MB | 981.81MB | 844.24MB | 0B |

**Total FF alloc (current snapshot):** 4.98GB  |  **24h avg:** 4.28GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1460/1462 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.99MB | 54/1462 | `███████░░░░░░░░ 51%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 15.55MB | 34/1462 | `██████░░░░░░░░░ 42%` |
| 4 | `runtime.mallocgc` | 12.85MB | 1456/1462 | `█████░░░░░░░░░░ 35%` |
| 5 | `database/sql.convertAssignRows` | 11.56MB | 56/1462 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1462 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1462 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1462 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1457/1462 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1462 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 93.17GB | 1452/1462 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1462 | `██████████░░░░░ 68%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1462 | `██████████░░░░░ 67%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1462 | `██████████░░░░░ 67%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 49.76GB | 1343/1462 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 40.3GB | 1451/1462 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1462 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1462 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 22.65GB | 1442/1462 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.65GB | 1339/1462 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.5x avg)
