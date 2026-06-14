# Overview: stage
*Last updated: 2026-06-14 19:03 IST*
*Data range: 2026-05-15T16:03 to 2026-06-14T19:03 (1467 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,181 | avg: 14,195 | max: 28,205 | trend: stable (-0.27/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▂▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▄▁▁▁▁▅▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▄▁▁▁▃▁▂▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▂
```

**Heap InUse** (current: 162.1MB | avg: 161.1MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▄▅▂▄▁▁▃▂▂▃▂▂▄▂▁▁▄▅▁▁▁▁▆▄▂▃▄▄▁▁▃▃▄▂▃▃▁▄▁▄▅▂▄▃▂▄▃▁▁▄▁▂▂▁▄▃▁▄▃▃▂▄▁▃▁▃▄▃▃█▄▄▂▂▃▁▄▁▂▁▄▂▁▄▁▄▁▁▁▃▄▄▂▂▄▃
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,181 | 14,071 | +110 | 14,195 | 28,205 | stable (-0.27/hr) |
| Heap InUse | 162.1MB | 178.6MB | -16.5MB | 161.1MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 1267.6MB | 1268.0MB | -0.4MB | 1186.5MB | 1805.8MB | |
| Heap Objects | 1,038,173 | 1,211,406 | -173233 | 879,091 | 2,707,946 | |

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
| 2026-06-14 | 39 | 14,131 | 152.0MB | 247.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 10.01MB |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 9.5MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `dotlapse-event-service/workerpool.NewWorker` | 3.0MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.85MB |
| 7 | `aws/endpoints.init` | 2.01MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.01MB |
| 9 | `compress/flate.NewWriter` | 1.76MB |
| 10 | `regexp.(*bitState).reset` | 1.03MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 129.25GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 61.81GB |
| 3 | `reflect.unsafe_NewArray` | 55.51GB |
| 4 | `reflect.MakeSlice` | 30.95GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 25.35GB |
| 6 | `segmentio/kafka-go.makeLayout` | 13.51GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 7.97GB |
| 8 | `database/sql.convertAssignRows` | 7.2GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 6.64GB |
| 10 | `internal/reflectlite.unsafe_New` | 6.35GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 626.18MB | 622.10MB | 542.96MB | 0B |
| `evaluation.mergeMetadata` | 277.07MB | 274.57MB | 240.84MB | 0B |
| `local.(*Client).EvaluateV2` | 1.01GB | 1.00GB | 894.60MB | 0B |
| `local.topologicalSort` | 132.14MB | 132.14MB | 114.60MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1022.86MB | 1012.45MB | 872.77MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 129.88MB | 129.88MB | 120.64MB | 0B |
| `localEvaluation.getMapOfValue` | 1022.86MB | 1012.45MB | 872.77MB | 0B |
| `utils.ParseFeatureFlag` | 1.00GB | 1014.46MB | 874.38MB | 0B |

**Total FF alloc (current snapshot):** 5.15GB  |  **24h avg:** 4.43GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1465/1467 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.99MB | 54/1467 | `███████░░░░░░░░ 51%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 15.55MB | 34/1467 | `██████░░░░░░░░░ 42%` |
| 4 | `runtime.mallocgc` | 12.84MB | 1461/1467 | `█████░░░░░░░░░░ 35%` |
| 5 | `database/sql.convertAssignRows` | 11.56MB | 56/1467 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1467 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1467 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1467 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1462/1467 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1467 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 93.28GB | 1457/1467 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1467 | `██████████░░░░░ 68%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1467 | `██████████░░░░░ 67%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1467 | `██████████░░░░░ 67%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 49.8GB | 1348/1467 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 40.35GB | 1456/1467 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1467 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1467 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 22.67GB | 1447/1467 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.67GB | 1344/1467 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.5x avg)
