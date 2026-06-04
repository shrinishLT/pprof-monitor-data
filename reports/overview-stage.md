# Overview: stage
*Last updated: 2026-06-04 06:00 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T06:00 (963 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,104 | avg: 14,225 | max: 28,205 | trend: stable (-0.39/hr))
```
▁▃▁▁▁▁▁▁▁▁▁▁▁▁▃▁▃▄▁█▃▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▂▂▁▃▁▅▁▁▁▁▁▁▁▁▁▁▁▁▃▁▄▁▂▁▁▂▄▁▁▁▂▁▁▅▁▁▁▁▁▂▁▁▁▁▁▁▁▂▂▁▁▁
```

**Heap InUse** (current: 104.0MB | avg: 166.4MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▄▅▃▃▃▃▁▃▄▁▂▂▂▂▄▃▄▃▁▅▄▂▃▂▃▄▄▃▄▄▅▃▄▁▂▅▃▄▄▂▃▄▂▂▃▃▁▃▃▄▁▂▂▂▁▂▁▄▂▄▂▄▄▁▄▂▂▁▁▄▃▂▂▄▃▂▂█▄▂▄▄▃▁▁▁▃▁▁▂▃▃▂▂▂▁
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,104 | 14,075 | +29 | 14,225 | 28,205 | stable (-0.39/hr) |
| Heap InUse | 104.0MB | 140.8MB | -36.8MB | 166.4MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 215.5MB | 211.6MB | +3.9MB | 1292.1MB | 1805.8MB | |
| Heap Objects | 440,147 | 861,853 | -421706 | 885,050 | 2,707,946 | |

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
| 2026-06-04 | 12 | 14,114 | 130.2MB | 161.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 9.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `reflect.growslice` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `reflect.unsafe_NewArray` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 4.07GB |
| 2 | `reflect.unsafe_NewArray` | 1.76GB |
| 3 | `reflect.MakeSlice` | 969.52MB |
| 4 | `segmentio/kafka-go.makeLayout` | 443.47MB |
| 5 | `v3/newrelic.newAnalyticsEvents` | 232.71MB |
| 6 | `internal/reflectlite.unsafe_New` | 201.52MB |
| 7 | `compress/flate.NewWriter` | 175.4MB |
| 8 | `v3/newrelic.newLogEvents` | 136.64MB |
| 9 | `io.ReadAll` | 115.81MB |
| 10 | `internal/evaluation.(*Engine).Evaluate` | 113.59MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 250.11MB | 244.49MB | 5.31GB | 0B |
| `evaluation.mergeMetadata` | 105.03MB | 101.52MB | 2.28GB | 0B |
| `local.(*Client).EvaluateV2` | 415.59MB | 404.74MB | 8.85GB | 0B |
| `local.topologicalSort` | 62.00MB | 59.46MB | 1.21GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 465.64MB | 452.71MB | 10.04GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 0B | 0B | 19.85MB | 0B |
| `localEvaluation.getMapOfValue` | 465.64MB | 452.71MB | 10.04GB | 0B |
| `utils.ParseFeatureFlag` | 39.20MB | 28.32MB | 98.68MB | 0B |

**Total FF alloc (current snapshot):** 1.76GB  |  **24h avg:** 37.85GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 961/963 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.96MB | 36/963 | `███████░░░░░░░░ 49%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.29MB | 24/963 | `███████░░░░░░░░ 47%` |
| 4 | `runtime.mallocgc` | 13.53MB | 957/963 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 12.13MB | 38/963 | `████░░░░░░░░░░░ 33%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/963 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/963 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/963 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 959/963 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/963 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 95.99GB | 954/963 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 67.2GB | 304/963 | `██████████░░░░░ 70%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 66.48GB | 305/963 | `██████████░░░░░ 69%` |
| 4 | `internal/evaluation.mergeMetadata` | 66.01GB | 299/963 | `██████████░░░░░ 68%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 51.0GB | 908/963 | `███████░░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 41.54GB | 953/963 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.68GB | 296/963 | `█████░░░░░░░░░░ 36%` |
| 8 | `experiment/local.topologicalSort` | 34.67GB | 291/963 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 23.39GB | 945/963 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 23.01GB | 906/963 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
