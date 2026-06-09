# Overview: stage
*Last updated: 2026-06-09 20:04 IST*
*Data range: 2026-05-15T16:03 to 2026-06-09T20:04 (1230 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,076 | avg: 14,209 | max: 28,205 | trend: stable (-0.30/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▄▁▁▁▁▁▁▁▂▁▁▁▁▂▁▃▁▃▁▁▁▁█▁▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▂▄▂▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▁▁▁▁▁▂▁▁▁▁
```

**Heap InUse** (current: 175.1MB | avg: 163.7MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▂▃▄▄▃▁▂▃▃▃▁▃▃▁▁▂▃▄▃▇▃▂▁▂▃▂▂▂▃▂▁▄▂▂▁▄▂▃▃▂▄▂▃▂▄▃▁▁▁▃▁▃▁▁▂▁▃▃▄▂▃▄▃▁▁▁▄█▃▂▄▃▄▄▂▃▂▂▂▃▂▂▂▁▄▃▄▁▂▂▄▁▃▂▃▃
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,076 | 14,215 | -139 | 14,209 | 28,205 | stable (-0.30/hr) |
| Heap InUse | 175.1MB | 160.1MB | +15.0MB | 163.7MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 1238.6MB | 1238.5MB | +0.1MB | 1220.9MB | 1805.8MB | |
| Heap Objects | 1,226,153 | 928,758 | +297395 | 885,734 | 2,707,946 | |

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
| 2026-06-09 | 41 | 14,165 | 161.9MB | 283.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 8 | `kafka-go/protocol.newPage` | 1.06MB |
| 9 | `aws/endpoints.init` | 1.0MB |
| 10 | `net.(*Resolver).lookupIPAddr` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 208.93GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 94.92GB |
| 3 | `reflect.unsafe_NewArray` | 90.37GB |
| 4 | `reflect.MakeSlice` | 50.51GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 37.33GB |
| 6 | `segmentio/kafka-go.makeLayout` | 22.26GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 11.92GB |
| 8 | `v3/newrelic.newAnalyticsEvents` | 10.7GB |
| 9 | `database/sql.convertAssignRows` | 10.57GB |
| 10 | `internal/reflectlite.unsafe_New` | 10.13GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.22GB | 1.21GB | 1.08GB | 0B |
| `evaluation.mergeMetadata` | 531.63MB | 528.63MB | 474.17MB | 0B |
| `local.(*Client).EvaluateV2` | 2.08GB | 2.07GB | 1.86GB | 0B |
| `local.topologicalSort` | 309.56MB | 307.52MB | 282.81MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.14GB | 2.13GB | 1.93GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 217.78MB | 213.12MB | 189.07MB | 0B |
| `localEvaluation.getMapOfValue` | 2.14GB | 2.13GB | 1.93GB | 0B |
| `utils.ParseFeatureFlag` | 2.15GB | 2.13GB | 1.93GB | 0B |

**Total FF alloc (current snapshot):** 10.77GB  |  **24h avg:** 9.65GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1228/1230 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.26MB | 48/1230 | `███████░░░░░░░░ 49%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.15MB | 31/1230 | `██████░░░░░░░░░ 44%` |
| 4 | `runtime.mallocgc` | 13.35MB | 1224/1230 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 11.61MB | 50/1230 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1230 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1230 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1230 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1225/1230 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1230 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 94.95GB | 1220/1230 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1230 | `██████████░░░░░ 67%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1230 | `█████████░░░░░░ 66%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1230 | `█████████░░░░░░ 65%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 49.87GB | 1160/1230 | `███████░░░░░░░░ 52%` |
| 6 | `reflect.unsafe_NewArray` | 41.1GB | 1219/1230 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1230 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1230 | `█████░░░░░░░░░░ 35%` |
| 9 | `reflect.MakeSlice` | 23.13GB | 1210/1230 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.95GB | 1157/1230 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
