# Overview: stage
*Last updated: 2026-06-12 07:01 IST*
*Data range: 2026-05-15T16:03 to 2026-06-12T07:01 (1347 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,567 | avg: 14,202 | max: 28,205 | trend: stable (-0.29/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▂▂▁▁▁▃▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▇▁▁▁▁▁▁▁▁▁▁▁▁▄▁▆▁▁▃▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▂▁▁▄▇▁█▇
```

**Heap InUse** (current: 143.3MB | avg: 162.1MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▃▂▄▄▃▃▂▃▂▂▂▂▂▂█▃▂▃▃▄▁▂▂▄▃▄▁▄▃▁▃▂▁▂▂▁▁▃▂▁▃▁▃▃▄▁▄▁▁▁▂▂▁▂▃▃▂▃▂▂▃▂▃▂▃▃▁▂▄▁▄▁▂▂▁▁▃▁▃▂▂▁▁▁▃▁▃▂▃▂▂▂▂▃▃▂
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 51%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,567 | 14,569 | -2 | 14,202 | 28,205 | stable (-0.29/hr) |
| Heap InUse | 143.3MB | 167.0MB | -23.7MB | 162.1MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 1267.2MB | 381.7MB | +885.5MB | 1179.3MB | 1805.8MB | |
| Heap Objects | 410,465 | 720,889 | -310424 | 880,443 | 2,707,946 | |

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
| 2026-06-12 | 15 | 14,201 | 138.0MB | 172.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 37.78MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `database/sql.convertAssignRows` | 14.0MB |
| 4 | `runtime.mallocgc` | 9.51MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 9.5MB |
| 6 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 7 | `bytes.growSlice` | 8.55MB |
| 8 | `segmentio/kafka-go.makePartitions` | 6.01MB |
| 9 | `dotlapse-event-service/workerpool.NewWorker` | 3.0MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.85MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 19.72GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 14.55GB |
| 3 | `reflect.unsafe_NewArray` | 8.38GB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 6.02GB |
| 5 | `reflect.MakeSlice` | 4.66GB |
| 6 | `segmentio/kafka-go.makeLayout` | 2.09GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 1.91GB |
| 8 | `database/sql.convertAssignRows` | 1.69GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 1.13GB |
| 10 | `internal/reflectlite.unsafe_New` | 1003.59MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 129.90MB | 100.65MB | 72.40MB | 0B |
| `evaluation.mergeMetadata` | 58.01MB | 43.01MB | 31.36MB | 0B |
| `local.(*Client).EvaluateV2` | 207.68MB | 166.92MB | 117.51MB | 0B |
| `local.topologicalSort` | 22.38MB | 18.31MB | 16.37MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 194.61MB | 160.53MB | 108.17MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 30.58MB | 20.79MB | 20.53MB | 0B |
| `localEvaluation.getMapOfValue` | 194.61MB | 160.53MB | 108.17MB | 0B |
| `utils.ParseFeatureFlag` | 195.61MB | 161.54MB | 108.62MB | 0B |

**Total FF alloc (current snapshot):** 1.01GB  |  **24h avg:** 583.14MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1345/1347 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.8MB | 51/1347 | `███████░░░░░░░░ 51%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.15MB | 31/1347 | `██████░░░░░░░░░ 44%` |
| 4 | `runtime.mallocgc` | 13.13MB | 1341/1347 | `█████░░░░░░░░░░ 35%` |
| 5 | `database/sql.convertAssignRows` | 11.49MB | 53/1347 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1347 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1347 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1347 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1342/1347 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1347 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 94.92GB | 1337/1347 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1347 | `██████████░░░░░ 67%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1347 | `█████████░░░░░░ 66%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1347 | `█████████░░░░░░ 65%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 51.09GB | 1228/1347 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 41.08GB | 1336/1347 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1347 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1347 | `█████░░░░░░░░░░ 35%` |
| 9 | `reflect.MakeSlice` | 23.11GB | 1327/1347 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 22.32GB | 1224/1347 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
