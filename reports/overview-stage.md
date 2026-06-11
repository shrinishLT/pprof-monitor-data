# Overview: stage
*Last updated: 2026-06-11 17:31 IST*
*Data range: 2026-05-15T16:03 to 2026-06-11T17:31 (1320 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,077 | avg: 14,203 | max: 28,205 | trend: stable (-0.30/hr))
```
▁▄▃▃▃▁▁▁▃▁▁▁▁▁▁▁▁▂▂▄▅▂▃▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▂▂▃▁▁▁▃▁▁▁▂▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▃▁▇▁▁▁▁▁▁▁▁▁▁▁▁▄▁▆▁▁▃▁▃▁▁
```

**Heap InUse** (current: 180.9MB | avg: 162.6MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▄▂▄▂▃▃▂▃▃▂▂▃▃▃▃▂▂▁▃▂▂▂▂▃▂▃▃▃▂▄▄▃▃▂▃▂▂▂▂▂▂█▃▂▃▃▄▁▂▂▄▃▄▁▄▃▁▃▂▁▂▂▁▁▃▂▁▃▁▃▃▄▁▄▁▁▁▂▂▁▂▃▃▂▃▂▂▃▁▃▂▃▃▁▂▄
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,077 | 14,083 | -6 | 14,203 | 28,205 | stable (-0.30/hr) |
| Heap InUse | 180.9MB | 129.7MB | +51.2MB | 162.6MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 511.0MB | 511.5MB | -0.5MB | 1196.3MB | 1805.8MB | |
| Heap Objects | 1,014,619 | 789,159 | +225460 | 883,044 | 2,707,946 | |

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
| 2026-06-11 | 36 | 14,121 | 140.7MB | 199.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 8.08MB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 6.0MB |
| 5 | `database/sql.convertAssignRows` | 5.0MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 4.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `segmentio/kafka-go.makePartitions` | 1.5MB |
| 9 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 1.01MB |
| 10 | `internal/sync.newIndirectNode[go.shape.interface {},go.shape.interface {}]` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 10.7GB |
| 2 | `reflect.unsafe_NewArray` | 4.5GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 3.14GB |
| 4 | `reflect.MakeSlice` | 2.57GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 1.28GB |
| 6 | `segmentio/kafka-go.makeLayout` | 1.09GB |
| 7 | `v3/newrelic.newAnalyticsEvents` | 633.81MB |
| 8 | `internal/reflectlite.unsafe_New` | 505.05MB |
| 9 | `compress/flate.NewWriter` | 436.31MB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 416.51MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 110.91MB | 107.37MB | 154.57MB | 0B |
| `evaluation.mergeMetadata` | 45.01MB | 43.01MB | 66.46MB | 0B |
| `local.(*Client).EvaluateV2` | 178.17MB | 171.49MB | 260.64MB | 0B |
| `local.topologicalSort` | 28.96MB | 27.44MB | 37.81MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 143.94MB | 137.24MB | 262.35MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 52.27MB | 51.77MB | 31.22MB | 0B |
| `localEvaluation.getMapOfValue` | 143.94MB | 137.24MB | 262.35MB | 0B |
| `utils.ParseFeatureFlag` | 144.44MB | 137.74MB | 262.55MB | 0B |

**Total FF alloc (current snapshot):** 847.64MB  |  **24h avg:** 1.31GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1318/1320 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.42MB | 50/1320 | `███████░░░░░░░░ 50%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.15MB | 31/1320 | `██████░░░░░░░░░ 44%` |
| 4 | `runtime.mallocgc` | 13.23MB | 1314/1320 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 11.44MB | 52/1320 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1320 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1320 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1320 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1315/1320 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1320 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 96.67GB | 1310/1320 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1320 | `█████████░░░░░░ 65%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1320 | `█████████░░░░░░ 65%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1320 | `█████████░░░░░░ 64%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 51.24GB | 1224/1320 | `███████░░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 41.84GB | 1309/1320 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1320 | `█████░░░░░░░░░░ 35%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1320 | `█████░░░░░░░░░░ 35%` |
| 9 | `reflect.MakeSlice` | 23.54GB | 1300/1320 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 22.36GB | 1221/1320 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
