# Overview: stage
*Last updated: 2026-06-06 08:01 IST*
*Data range: 2026-05-15T16:03 to 2026-06-06T08:00 (1063 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,070 | avg: 14,219 | max: 28,205 | trend: stable (-0.35/hr))
```
█▁▁▁▅▁▁▁▂▁▄▆▂▄▃▁▁▁▃▁▁▁▁▃▁▁▃▁▁▁▁▁▁▁▁▁▁▂▃▂▁▂▆▄▅▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▂▃▆▁▁▁▁▄▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▄▂▄▄▁▁▁
```

**Heap InUse** (current: 109.0MB | avg: 164.9MB | max: 732.9MB | trend: stable (-0.05MB/hr))
```
▃▁▂▁▄▂▁▂▂▁▂▃▁▂▃▃▂▂▂▃▂▂▁▁▁▁▁▂▂▁▂▁▁▁▂▂▁▁▂▃▂▂▃█▆▃▂▂▁▃▃▁▃▃▂▂▂▁▃▅▃▂▂▃▂▃▃▂▃▁▂▃▂▃▂▂▁▁▁▃▁▃▂▃▂▂▁▁▃▂▁▄▂▂▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,070 | 14,080 | -10 | 14,219 | 28,205 | stable (-0.35/hr) |
| Heap InUse | 109.0MB | 107.6MB | +1.4MB | 164.9MB | 732.9MB | stable (-0.05MB/hr) |
| Heap Sys | 988.3MB | 989.2MB | -0.9MB | 1240.9MB | 1805.8MB | |
| Heap Objects | 399,157 | 265,916 | +133241 | 880,612 | 2,707,946 | |

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
| 2026-06-06 | 17 | 14,158 | 144.1MB | 231.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.0MB |
| 9 | `aws/endpoints.init` | 1.0MB |
| 10 | `reflect.growslice` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 56.18GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 34.4GB |
| 3 | `reflect.unsafe_NewArray` | 24.3GB |
| 4 | `reflect.MakeSlice` | 13.74GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 13.49GB |
| 6 | `segmentio/kafka-go.makeLayout` | 6.11GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 4.27GB |
| 8 | `database/sql.convertAssignRows` | 3.72GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 2.96GB |
| 10 | `internal/reflectlite.unsafe_New` | 2.77GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 403.76MB | 400.14MB | 251.88MB | 0B |
| `evaluation.mergeMetadata` | 167.54MB | 166.54MB | 104.41MB | 0B |
| `local.(*Client).EvaluateV2` | 698.92MB | 692.66MB | 437.98MB | 0B |
| `local.topologicalSort` | 105.24MB | 104.22MB | 67.80MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 700.21MB | 692.93MB | 442.21MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 82.24MB | 82.24MB | 49.14MB | 0B |
| `localEvaluation.getMapOfValue` | 700.21MB | 692.93MB | 442.21MB | 0B |
| `utils.ParseFeatureFlag` | 701.21MB | 693.93MB | 443.21MB | 0B |

**Total FF alloc (current snapshot):** 3.48GB  |  **24h avg:** 2.19GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1061/1063 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.23MB | 42/1063 | `███████░░░░░░░░ 49%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.96MB | 27/1063 | `██████░░░░░░░░░ 46%` |
| 4 | `runtime.mallocgc` | 13.39MB | 1057/1063 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 11.91MB | 44/1063 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1063 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1063 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1063 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1058/1063 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1063 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 88.91GB | 1053/1063 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1063 | `██████████░░░░░ 71%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1063 | `██████████░░░░░ 70%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1063 | `██████████░░░░░ 70%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 47.85GB | 993/1063 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 38.48GB | 1052/1063 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1063 | `█████░░░░░░░░░░ 38%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1063 | `█████░░░░░░░░░░ 38%` |
| 9 | `reflect.MakeSlice` | 21.67GB | 1043/1063 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.55GB | 990/1063 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
