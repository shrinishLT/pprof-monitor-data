# Overview: stage
*Last updated: 2026-06-13 20:03 IST*
*Data range: 2026-05-15T16:03 to 2026-06-13T20:03 (1421 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,246 | avg: 14,198 | max: 28,205 | trend: stable (-0.28/hr))
```
▁▁▁▁▁▁▁▁▁▂▁▁▁▁▂▁▁▃▄▁▅▅▁▁▁▁▁▁▁▁▁▁▁▂▁▁▃▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▂▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▄▁▁▁▁▅▁▁▁▁▁▁▂
```

**Heap InUse** (current: 182.5MB | avg: 161.5MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▂▁▅▁▄▂▄▁▁▂▅▁▄▂▅▂▃▃▃▅▅▃▂▁▅▅▃▅▄▆▃▆▁▅▅▆▂▆▂▄▄▅▃▁▆▁▅▆▃▆▂▁▅▃▃▄▃▃▅▃▁▁▆▆▂▂▂▁█▅▃▄▅▅▁▁▄▄▅▃▄▅▁▆▂▅▆▂▅▄▃▅▄▁▁▆
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,246 | 14,065 | +181 | 14,198 | 28,205 | stable (-0.28/hr) |
| Heap InUse | 182.5MB | 107.6MB | +74.9MB | 161.5MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 1266.5MB | 1267.9MB | -1.4MB | 1183.9MB | 1805.8MB | |
| Heap Objects | 1,174,902 | 347,168 | +827734 | 880,810 | 2,707,946 | |

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
| 2026-06-13 | 41 | 14,129 | 148.5MB | 214.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 9.51MB |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 9.5MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `segmentio/kafka-go.makePartitions` | 5.51MB |
| 6 | `reflect.unsafe_NewArray` | 3.53MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 3.0MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.85MB |
| 9 | `compress/flate.NewWriter` | 2.64MB |
| 10 | `aws/endpoints.init` | 2.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 87.46GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 40.95GB |
| 3 | `reflect.unsafe_NewArray` | 37.5GB |
| 4 | `reflect.MakeSlice` | 20.85GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 16.79GB |
| 6 | `segmentio/kafka-go.makeLayout` | 9.22GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 5.28GB |
| 8 | `database/sql.convertAssignRows` | 4.73GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 4.55GB |
| 10 | `internal/reflectlite.unsafe_New` | 4.25GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 471.19MB | 469.11MB | 386.92MB | 0B |
| `evaluation.mergeMetadata` | 210.55MB | 209.55MB | 170.64MB | 0B |
| `local.(*Client).EvaluateV2` | 777.96MB | 775.34MB | 638.42MB | 0B |
| `local.topologicalSort` | 97.60MB | 97.60MB | 76.01MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 747.10MB | 743.46MB | 598.77MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 113.80MB | 113.80MB | 102.44MB | 0B |
| `localEvaluation.getMapOfValue` | 747.10MB | 743.46MB | 598.77MB | 0B |
| `utils.ParseFeatureFlag` | 748.60MB | 744.96MB | 600.27MB | 0B |

**Total FF alloc (current snapshot):** 3.82GB  |  **24h avg:** 3.10GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1419/1421 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.76MB | 52/1421 | `███████░░░░░░░░ 51%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 15.77MB | 32/1421 | `██████░░░░░░░░░ 43%` |
| 4 | `runtime.mallocgc` | 12.94MB | 1415/1421 | `█████░░░░░░░░░░ 35%` |
| 5 | `database/sql.convertAssignRows` | 11.45MB | 54/1421 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1421 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1421 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1421 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1416/1421 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1421 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 92.78GB | 1411/1421 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1421 | `██████████░░░░░ 68%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1421 | `██████████░░░░░ 68%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1421 | `██████████░░░░░ 67%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 49.74GB | 1302/1421 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 40.14GB | 1410/1421 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1421 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1421 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 22.57GB | 1401/1421 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.68GB | 1298/1421 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
