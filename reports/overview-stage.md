# Overview: stage
*Last updated: 2026-06-16 09:01 IST*
*Data range: 2026-05-15T16:03 to 2026-06-16T09:00 (1542 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,065 | avg: 14,196 | max: 28,205 | trend: stable (-0.23/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▇█▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▇▁▁▁▁
```

**Heap InUse** (current: 111.6MB | avg: 160.6MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▁▄▁▂▂▄▃▁▄▁▄▁▂▂▃▄▄▃▂▄▄▁▂▃▂▅▄▂▃▃▃▂▃▂▃▆▄▄▂▃▄▂▄█▂▅▂▃▄▂▄▅▁▅▂▂▅▄▄▁▂▄▂▄▂▆▆▅▁▁▂▃▃▅▁▂▂▄▃▂▁▂▂▁▄▂▅▄▅▂▂▇▃▄▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,065 | 14,065 | +0 | 14,196 | 28,205 | stable (-0.23/hr) |
| Heap InUse | 111.6MB | 110.2MB | +1.4MB | 160.6MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 1649.9MB | 1649.9MB | +0.0MB | 1173.1MB | 1805.8MB | |
| Heap Objects | 435,159 | 411,405 | +23754 | 878,082 | 2,707,946 | |

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
| 2026-06-16 | 18 | 14,191 | 146.8MB | 226.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 7.64MB |
| 3 | `runtime.mallocgc` | 7.6MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `dotlapse-event-service/workerpool.NewWorker` | 3.0MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `compress/flate.NewWriter` | 1.76MB |
| 8 | `compress/flate.(*compressor).initDeflate` | 1.6MB |
| 9 | `segmentio/kafka-go.makePartitions` | 1.5MB |
| 10 | `aws/endpoints.init` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 24.35GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 14.07GB |
| 3 | `reflect.unsafe_NewArray` | 10.53GB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 5.81GB |
| 5 | `reflect.MakeSlice` | 5.78GB |
| 6 | `segmentio/kafka-go.makeLayout` | 2.58GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 1.83GB |
| 8 | `database/sql.convertAssignRows` | 1.71GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 1.34GB |
| 10 | `internal/reflectlite.unsafe_New` | 1.21GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 156.42MB | 156.42MB | 204.70MB | 0B |
| `evaluation.mergeMetadata` | 61.51MB | 61.51MB | 87.67MB | 0B |
| `local.(*Client).EvaluateV2` | 256.51MB | 256.51MB | 338.84MB | 0B |
| `local.topologicalSort` | 32.06MB | 32.06MB | 43.65MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 259.65MB | 259.65MB | 342.80MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 27.34MB | 27.34MB | 36.89MB | 0B |
| `localEvaluation.getMapOfValue` | 259.65MB | 259.65MB | 342.80MB | 0B |
| `utils.ParseFeatureFlag` | 259.65MB | 259.65MB | 343.27MB | 0B |

**Total FF alloc (current snapshot):** 1.28GB  |  **24h avg:** 1.70GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1540/1542 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.77MB | 56/1542 | `███████░░░░░░░░ 51%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 15.47MB | 35/1542 | `██████░░░░░░░░░ 42%` |
| 4 | `runtime.mallocgc` | 12.68MB | 1536/1542 | `█████░░░░░░░░░░ 34%` |
| 5 | `database/sql.convertAssignRows` | 11.44MB | 58/1542 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1542 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1542 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1542 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.22MB | 1537/1542 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1542 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 92.4GB | 1532/1542 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1542 | `██████████░░░░░ 69%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1542 | `██████████░░░░░ 68%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1542 | `██████████░░░░░ 67%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 49.82GB | 1399/1542 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 39.95GB | 1531/1542 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1542 | `█████░░░░░░░░░░ 37%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1542 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 22.44GB | 1522/1542 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.62GB | 1395/1542 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.6x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.5x avg)
