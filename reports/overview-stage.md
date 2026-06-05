# Overview: stage
*Last updated: 2026-06-05 06:32 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T06:32 (1012 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,430 | avg: 14,223 | max: 28,205 | trend: stable (-0.35/hr))
```
▆▁▁▁▁▁▁▁▁▁▁▁▁▄▁▅▁▂▁▁▂▄▂▁▁▃▂▁▆▁▁▁▁▁▂▁▁▁▁▁▁▁▃▂▁▁▁▆▁▁▁█▁▁▁▅▁▁▁▂▁▄▆▂▄▃▁▁▁▃▁▁▁▁▃▁▁▃▁▁▁▁▁▁▁▁▁▁▂▃▂▁▂▆▄▅
```

**Heap InUse** (current: 288.2MB | avg: 165.6MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▃▁▂▂▁▁▂▁▃▂▃▂▃▃▁▃▁▂▁▁▃▂▂▂▃▂▂▂▅▃▁▃▃▃▁▁▁▂▁▁▂▂▂▂▁▂▁▅▃▁▂▃▁▂▁▄▂▁▂▂▁▂▃▁▂▃▃▂▂▂▃▂▂▁▁▁▁▁▂▂▁▂▁▁▁▂▂▁▁▂▃▂▂▃█▆
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 51%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 15%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,430 | 14,334 | +96 | 14,223 | 28,205 | stable (-0.35/hr) |
| Heap InUse | 288.2MB | 338.5MB | -50.3MB | 165.6MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 987.0MB | 993.2MB | -6.2MB | 1253.7MB | 1805.8MB | |
| Heap Objects | 859,373 | 1,643,188 | -783815 | 880,677 | 2,707,946 | |

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
| 2026-06-05 | 14 | 14,193 | 159.9MB | 338.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 19.95MB |
| 3 | `runtime.mallocgc` | 13.1MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 6 | `database/sql.convertAssignRows` | 5.5MB |
| 7 | `compress/flate.NewWriter` | 4.41MB |
| 8 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 4.08MB |
| 9 | `bytes.growSlice` | 3.52MB |
| 10 | `bufio.NewReaderSize` | 3.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 15.63GB |
| 2 | `segmentio/kafka-go.makePartitions` | 10.56GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 6.1GB |
| 4 | `reflect.unsafe_NewArray` | 4.64GB |
| 5 | `reflect.MakeSlice` | 2.52GB |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 1.89GB |
| 7 | `database/sql.convertAssignRows` | 1.65GB |
| 8 | `segmentio/kafka-go.makeLayout` | 1.15GB |
| 9 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 728.39MB |
| 10 | `v3/newrelic.newAnalyticsEvents` | 650.71MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 58.30MB | 37.69MB | 2.21GB | 0B |
| `evaluation.mergeMetadata` | 25.01MB | 15.00MB | 962.98MB | 0B |
| `local.(*Client).EvaluateV2` | 110.82MB | 66.63MB | 3.71GB | 0B |
| `local.topologicalSort` | 17.30MB | 8.64MB | 523.43MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 116.94MB | 74.88MB | 4.20GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 8.30MB | 0B | 19.78MB | 0B |
| `localEvaluation.getMapOfValue` | 116.94MB | 74.88MB | 4.20GB | 0B |
| `utils.ParseFeatureFlag` | 117.94MB | 75.88MB | 105.36MB | 0B |

**Total FF alloc (current snapshot):** 571.56MB  |  **24h avg:** 15.90GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1010/1012 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.43MB | 40/1012 | `███████░░░░░░░░ 50%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.36MB | 26/1012 | `███████░░░░░░░░ 47%` |
| 4 | `runtime.mallocgc` | 13.41MB | 1006/1012 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 12.04MB | 42/1012 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1012 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1012 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1012 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1007/1012 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1012 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 91.72GB | 1002/1012 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1012 | `██████████░░░░░ 69%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1012 | `██████████░░░░░ 68%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1012 | `██████████░░░░░ 68%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 49.4GB | 942/1012 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 39.69GB | 1001/1012 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1012 | `█████░░░░░░░░░░ 37%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1012 | `█████░░░░░░░░░░ 37%` |
| 9 | `reflect.MakeSlice` | 22.36GB | 992/1012 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 22.31GB | 939/1012 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
