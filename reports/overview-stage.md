# Overview: stage
*Last updated: 2026-06-05 06:00 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T06:00 (1011 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,334 | avg: 14,223 | max: 28,205 | trend: stable (-0.36/hr))
```
▁▆▁▁▁▁▁▁▁▁▁▁▁▁▄▁▅▁▂▁▁▂▄▂▁▁▃▂▁▆▁▁▁▁▁▂▁▁▁▁▁▁▁▃▂▁▁▁▆▁▁▁█▁▁▁▅▁▁▁▂▁▄▆▂▄▃▁▁▁▃▁▁▁▁▃▁▁▃▁▁▁▁▁▁▁▁▁▁▂▃▂▁▂▆▄
```

**Heap InUse** (current: 338.5MB | avg: 165.4MB | max: 732.9MB | trend: stable (-0.05MB/hr))
```
▂▃▁▂▂▁▁▂▁▃▂▃▂▃▃▁▃▁▂▁▁▃▂▂▂▃▂▂▂▅▃▁▃▃▃▁▁▁▂▁▁▂▂▂▂▁▂▁▅▃▁▂▃▁▂▁▄▂▁▂▂▁▂▃▁▂▃▃▂▂▂▃▂▂▁▁▁▁▁▂▂▁▂▁▁▁▂▂▁▁▂▃▂▂▃█
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 18%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,334 | 14,540 | -206 | 14,223 | 28,205 | stable (-0.36/hr) |
| Heap InUse | 338.5MB | 167.1MB | +171.4MB | 165.4MB | 732.9MB | stable (-0.05MB/hr) |
| Heap Sys | 993.2MB | 413.7MB | +579.5MB | 1253.9MB | 1805.8MB | |
| Heap Objects | 1,643,188 | 914,088 | +729100 | 880,698 | 2,707,946 | |

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
| 2026-06-05 | 13 | 14,175 | 150.1MB | 338.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 38.56MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `database/sql.convertAssignRows` | 21.0MB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 20.33MB |
| 5 | `runtime.mallocgc` | 13.1MB |
| 6 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 8 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 5.05MB |
| 9 | `bytes.growSlice` | 2.51MB |
| 10 | `reflect.mapassign_faststr0` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 9.63GB |
| 2 | `reflect.unsafe_NewArray` | 4.22GB |
| 3 | `reflect.MakeSlice` | 2.31GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 1.97GB |
| 5 | `segmentio/kafka-go.makeLayout` | 1.04GB |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 810.26MB |
| 7 | `v3/newrelic.newAnalyticsEvents` | 601.94MB |
| 8 | `internal/reflectlite.unsafe_New` | 468.54MB |
| 9 | `v3/newrelic.newLogEvents` | 351.0MB |
| 10 | `compress/flate.NewWriter` | 348.17MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 37.69MB | 35.11MB | 2.30GB | 0B |
| `evaluation.mergeMetadata` | 15.00MB | 13.50MB | 1004.91MB | 0B |
| `local.(*Client).EvaluateV2` | 66.63MB | 59.80MB | 3.87GB | 0B |
| `local.topologicalSort` | 8.64MB | 8.13MB | 546.18MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 74.88MB | 67.53MB | 4.39GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 0B | 0B | 19.74MB | 0B |
| `localEvaluation.getMapOfValue` | 74.88MB | 67.53MB | 4.39GB | 0B |
| `utils.ParseFeatureFlag` | 75.88MB | 68.54MB | 104.40MB | 0B |

**Total FF alloc (current snapshot):** 353.61MB  |  **24h avg:** 16.58GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1009/1011 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.39MB | 39/1011 | `███████░░░░░░░░ 50%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.36MB | 26/1011 | `███████░░░░░░░░ 47%` |
| 4 | `runtime.mallocgc` | 13.41MB | 1005/1011 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 12.2MB | 41/1011 | `████░░░░░░░░░░░ 33%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1011 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1011 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1011 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1006/1011 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1011 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 91.8GB | 1001/1011 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1011 | `██████████░░░░░ 69%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1011 | `██████████░░░░░ 68%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1011 | `██████████░░░░░ 68%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 49.43GB | 941/1011 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 39.72GB | 1000/1011 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1011 | `█████░░░░░░░░░░ 37%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1011 | `█████░░░░░░░░░░ 37%` |
| 9 | `reflect.MakeSlice` | 22.38GB | 991/1011 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 22.33GB | 938/1011 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
