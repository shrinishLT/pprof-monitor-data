# Overview: stage
*Last updated: 2026-06-16 15:25 IST*
*Data range: 2026-05-15T16:03 to 2026-06-16T15:25 (1553 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,073 | avg: 14,195 | max: 28,205 | trend: stable (-0.23/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▇█▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 121.0MB | avg: 160.5MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▁▂▂▃▄▄▃▂▄▄▁▂▃▂▅▄▂▃▃▃▂▃▂▃▆▄▄▂▃▄▂▄█▂▅▂▃▄▂▄▅▁▅▂▂▅▄▄▁▂▄▂▄▂▆▆▅▁▁▂▃▃▅▁▂▂▄▃▂▁▂▂▁▄▂▅▄▅▂▂▇▃▄▁▁▄▂▃▅▁▃▃▄▄▃▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,073 | 14,085 | -12 | 14,195 | 28,205 | stable (-0.23/hr) |
| Heap InUse | 121.0MB | 149.5MB | -28.5MB | 160.5MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 449.0MB | 449.0MB | +0.0MB | 1174.9MB | 1805.8MB | |
| Heap Objects | 642,335 | 1,019,751 | -377416 | 878,337 | 2,707,946 | |

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
| 2026-06-16 | 29 | 14,159 | 148.5MB | 226.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 6.58MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.5MB |
| 6 | `compress/flate.NewWriter` | 4.41MB |
| 7 | `reflect.unsafe_NewArray` | 2.51MB |
| 8 | `reflect.mapassign_faststr0` | 2.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 854.58MB |
| 2 | `segmentio/kafka-go.makePartitions` | 402.03MB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 338.87MB |
| 4 | `reflect.unsafe_NewArray` | 157.65MB |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 113.0MB |
| 6 | `reflect.MakeSlice` | 108.0MB |
| 7 | `database/sql.convertAssignRows` | 86.5MB |
| 8 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 44.85MB |
| 9 | `segmentio/kafka-go.makeLayout` | 39.69MB |
| 10 | `compress/flate.NewWriter` | 39.66MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 2.04MB | 512.02kB | 95.43MB | 0B |
| `evaluation.mergeMetadata` | 1.50MB | 512.02kB | 37.82MB | 0B |
| `local.(*Client).EvaluateV2` | 5.24MB | 2.62MB | 158.30MB | 0B |
| `local.topologicalSort` | 513.69kB | 513.69kB | 20.69MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 4.72MB | 2.10MB | 162.58MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.04MB | 1.04MB | 15.52MB | 0B |
| `localEvaluation.getMapOfValue` | 4.72MB | 2.10MB | 162.58MB | 0B |
| `utils.ParseFeatureFlag` | 4.72MB | 2.10MB | 162.58MB | 0B |

**Total FF alloc (current snapshot):** 24.49MB  |  **24h avg:** 815.50MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1551/1553 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.77MB | 56/1553 | `███████░░░░░░░░ 51%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 15.47MB | 35/1553 | `██████░░░░░░░░░ 42%` |
| 4 | `runtime.mallocgc` | 12.65MB | 1547/1553 | `█████░░░░░░░░░░ 34%` |
| 5 | `database/sql.convertAssignRows` | 11.44MB | 58/1553 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1553 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1553 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1553 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.21MB | 1548/1553 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1553 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 91.91GB | 1543/1553 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1553 | `██████████░░░░░ 69%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1553 | `██████████░░░░░ 68%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1553 | `██████████░░░░░ 68%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 49.52GB | 1410/1553 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 39.74GB | 1542/1553 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1553 | `█████░░░░░░░░░░ 37%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1553 | `█████░░░░░░░░░░ 37%` |
| 9 | `reflect.MakeSlice` | 22.32GB | 1533/1553 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.49GB | 1406/1553 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.6x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.5x avg)
