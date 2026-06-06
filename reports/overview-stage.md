# Overview: stage
*Last updated: 2026-06-06 06:00 IST*
*Data range: 2026-05-15T16:03 to 2026-06-06T06:00 (1059 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,341 | avg: 14,219 | max: 28,205 | trend: stable (-0.35/hr))
```
▆▁▁▁█▁▁▁▅▁▁▁▂▁▄▆▂▄▃▁▁▁▃▁▁▁▁▃▁▁▃▁▁▁▁▁▁▁▁▁▁▂▃▂▁▂▆▄▅▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▂▃▆▁▁▁▁▄▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▄▂▄
```

**Heap InUse** (current: 231.1MB | avg: 165.1MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▅▃▁▂▃▁▂▁▄▂▁▂▂▁▂▃▁▂▃▃▂▂▂▃▂▂▁▁▁▁▁▂▂▁▂▁▁▁▂▂▁▁▂▃▂▂▃█▆▃▂▂▁▃▃▁▃▃▂▂▂▁▃▅▃▂▂▃▂▃▃▂▃▁▂▃▂▃▂▂▁▁▁▃▁▃▂▃▂▂▁▁▃▂▁▄
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 12%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,341 | 14,189 | +152 | 14,219 | 28,205 | stable (-0.35/hr) |
| Heap InUse | 231.1MB | 117.2MB | +113.9MB | 165.1MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 987.9MB | 987.7MB | +0.2MB | 1241.9MB | 1805.8MB | |
| Heap Objects | 796,146 | 372,361 | +423785 | 881,937 | 2,707,946 | |

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
| 2026-06-06 | 13 | 14,162 | 149.3MB | 231.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 16.32MB |
| 3 | `runtime.mallocgc` | 13.1MB |
| 4 | `database/sql.convertAssignRows` | 10.0MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB |
| 8 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 9 | `reflect.unsafe_NewArray` | 2.5MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 52.71GB |
| 2 | `reflect.unsafe_NewArray` | 22.79GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 20.12GB |
| 4 | `reflect.MakeSlice` | 12.89GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 7.93GB |
| 6 | `segmentio/kafka-go.makeLayout` | 5.71GB |
| 7 | `v3/newrelic.newAnalyticsEvents` | 2.78GB |
| 8 | `internal/reflectlite.unsafe_New` | 2.61GB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.5GB |
| 10 | `database/sql.convertAssignRows` | 2.21GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 372.25MB | 370.73MB | 224.29MB | 0B |
| `evaluation.mergeMetadata` | 157.04MB | 156.54MB | 92.97MB | 0B |
| `local.(*Client).EvaluateV2` | 644.81MB | 640.07MB | 391.14MB | 0B |
| `local.topologicalSort` | 97.59MB | 97.59MB | 60.86MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 646.64MB | 642.98MB | 396.11MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 75.00MB | 73.42MB | 43.08MB | 0B |
| `localEvaluation.getMapOfValue` | 646.64MB | 642.98MB | 396.11MB | 0B |
| `utils.ParseFeatureFlag` | 647.64MB | 643.98MB | 397.11MB | 0B |

**Total FF alloc (current snapshot):** 3.21GB  |  **24h avg:** 1.95GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1057/1059 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.23MB | 42/1059 | `███████░░░░░░░░ 49%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.96MB | 27/1059 | `██████░░░░░░░░░ 46%` |
| 4 | `runtime.mallocgc` | 13.39MB | 1053/1059 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 11.91MB | 44/1059 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1059 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1059 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1059 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1054/1059 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1059 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 89.04GB | 1049/1059 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1059 | `██████████░░░░░ 71%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1059 | `██████████░░░░░ 70%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1059 | `██████████░░░░░ 70%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 47.9GB | 989/1059 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 38.53GB | 1048/1059 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1059 | `█████░░░░░░░░░░ 38%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1059 | `█████░░░░░░░░░░ 38%` |
| 9 | `reflect.MakeSlice` | 21.7GB | 1039/1059 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.58GB | 986/1059 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
