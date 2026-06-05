# Overview: stage
*Last updated: 2026-06-06 03:01 IST*
*Data range: 2026-05-15T16:03 to 2026-06-06T03:01 (1053 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,081 | avg: 14,219 | max: 28,205 | trend: stable (-0.36/hr))
```
▁▃▂▁▁▁▆▁▁▁█▁▁▁▅▁▁▁▂▁▄▆▂▄▃▁▁▁▃▁▁▁▁▃▁▁▃▁▁▁▁▁▁▁▁▁▁▂▃▂▁▂▆▄▅▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▂▃▆▁▁▁▁▄▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 141.8MB | avg: 165.1MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▂▂▂▁▂▁▅▃▁▂▃▁▂▁▄▂▁▂▂▁▂▃▁▂▃▃▂▂▂▃▂▂▁▁▁▁▁▂▂▁▂▁▁▁▂▂▁▁▂▃▂▂▃█▆▃▂▂▁▃▃▁▃▃▂▂▂▁▃▅▃▂▂▃▂▃▃▂▃▁▂▃▂▃▂▂▁▁▁▃▁▃▂▃▂▂
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,081 | 14,069 | +12 | 14,219 | 28,205 | stable (-0.36/hr) |
| Heap InUse | 141.8MB | 132.6MB | +9.2MB | 165.1MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 987.9MB | 987.5MB | +0.4MB | 1243.3MB | 1805.8MB | |
| Heap Objects | 789,171 | 681,068 | +108103 | 883,413 | 2,707,946 | |

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
| 2026-06-06 | 7 | 14,077 | 147.8MB | 171.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `reflect.unsafe_NewArray` | 3.01MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 9 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.0MB |
| 10 | `reflect.unsafe_New` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 47.19GB |
| 2 | `reflect.unsafe_NewArray` | 20.48GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 18.88GB |
| 4 | `reflect.MakeSlice` | 11.58GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 7.42GB |
| 6 | `segmentio/kafka-go.makeLayout` | 5.12GB |
| 7 | `v3/newrelic.newAnalyticsEvents` | 2.5GB |
| 8 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.35GB |
| 9 | `internal/reflectlite.unsafe_New` | 2.33GB |
| 10 | `database/sql.convertAssignRows` | 2.06GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 352.91MB | 348.75MB | 181.96MB | 0B |
| `evaluation.mergeMetadata` | 147.54MB | 146.04MB | 75.10MB | 0B |
| `local.(*Client).EvaluateV2` | 606.51MB | 598.72MB | 318.39MB | 0B |
| `local.topologicalSort` | 93.55MB | 92.03MB | 49.63MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 603.71MB | 594.40MB | 324.08MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 73.42MB | 73.42MB | 33.87MB | 0B |
| `localEvaluation.getMapOfValue` | 603.71MB | 594.40MB | 324.08MB | 0B |
| `utils.ParseFeatureFlag` | 604.71MB | 595.40MB | 325.07MB | 0B |

**Total FF alloc (current snapshot):** 3.01GB  |  **24h avg:** 1.59GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1051/1053 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.27MB | 41/1053 | `███████░░░░░░░░ 49%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.36MB | 26/1053 | `███████░░░░░░░░ 47%` |
| 4 | `runtime.mallocgc` | 13.39MB | 1047/1053 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 11.95MB | 43/1053 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1053 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1053 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1053 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1048/1053 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1053 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 89.26GB | 1043/1053 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1053 | `██████████░░░░░ 71%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1053 | `██████████░░░░░ 70%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1053 | `██████████░░░░░ 70%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 48.08GB | 983/1053 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 38.63GB | 1042/1053 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1053 | `█████░░░░░░░░░░ 38%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1053 | `█████░░░░░░░░░░ 38%` |
| 9 | `reflect.MakeSlice` | 21.75GB | 1033/1053 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.67GB | 980/1053 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
