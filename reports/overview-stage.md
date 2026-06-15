# Overview: stage
*Last updated: 2026-06-15 16:31 IST*
*Data range: 2026-05-15T16:03 to 2026-06-15T16:31 (1510 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,067 | avg: 14,193 | max: 28,205 | trend: stable (-0.27/hr))
```
▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▃▁▂▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▂▁█▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▂▄▁▂▁
```

**Heap InUse** (current: 171.1MB | avg: 160.9MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▃▂▄▃▁▁▄▁▂▂▁▄▃▁▄▃▃▂▄▁▃▁▃▄▃▃█▄▄▂▂▂▁▄▁▂▁▄▂▁▃▁▄▁▁▁▃▄▄▂▂▄▃▁▁▃▂▅▄▂▂▂▂▂▃▂▃▅▃▄▁▂▄▂▄▇▂▅▂▂▃▁▃▄▁▅▁▂▅▄▄▁▂▄▂▄
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,067 | 14,215 | -148 | 14,193 | 28,205 | stable (-0.27/hr) |
| Heap InUse | 171.1MB | 131.5MB | +39.6MB | 160.9MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 546.9MB | 548.5MB | -1.6MB | 1186.1MB | 1805.8MB | |
| Heap Objects | 1,259,671 | 667,140 | +592531 | 879,701 | 2,707,946 | |

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
| 2026-06-15 | 34 | 14,140 | 155.9MB | 238.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 15.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 8 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 9 | `reflect.unsafe_NewArray` | 1.5MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 1.07MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 5.12GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 3.18GB |
| 3 | `reflect.unsafe_NewArray` | 2.27GB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 1.3GB |
| 5 | `reflect.MakeSlice` | 1.22GB |
| 6 | `segmentio/kafka-go.makeLayout` | 568.36MB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 436.51MB |
| 8 | `database/sql.convertAssignRows` | 382.52MB |
| 9 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 339.58MB |
| 10 | `v3/newrelic.newAnalyticsEvents` | 288.77MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 67.32MB | 62.16MB | 591.77MB | 0B |
| `evaluation.mergeMetadata` | 28.51MB | 27.01MB | 260.87MB | 0B |
| `local.(*Client).EvaluateV2` | 107.72MB | 99.98MB | 978.33MB | 0B |
| `local.topologicalSort` | 12.19MB | 10.67MB | 123.45MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 108.27MB | 98.99MB | 974.35MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 8.73MB | 8.73MB | 116.07MB | 0B |
| `localEvaluation.getMapOfValue` | 108.27MB | 98.99MB | 974.35MB | 0B |
| `utils.ParseFeatureFlag` | 108.27MB | 98.99MB | 976.20MB | 0B |

**Total FF alloc (current snapshot):** 549.28MB  |  **24h avg:** 4.88GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1508/1510 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.77MB | 56/1510 | `███████░░░░░░░░ 51%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 15.47MB | 35/1510 | `██████░░░░░░░░░ 42%` |
| 4 | `runtime.mallocgc` | 12.78MB | 1504/1510 | `█████░░░░░░░░░░ 34%` |
| 5 | `database/sql.convertAssignRows` | 11.44MB | 58/1510 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1510 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1510 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1510 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1505/1510 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1510 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 94.12GB | 1500/1510 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1510 | `██████████░░░░░ 67%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1510 | `██████████░░░░░ 67%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1510 | `█████████░░░░░░ 66%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 50.05GB | 1391/1510 | `███████░░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 40.7GB | 1499/1510 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1510 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1510 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 22.87GB | 1490/1510 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.73GB | 1387/1510 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.6x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.5x avg)
