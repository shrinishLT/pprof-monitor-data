# Overview: stage
*Last updated: 2026-06-04 22:31 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T22:31 (996 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,093 | avg: 14,223 | max: 28,205 | trend: stable (-0.36/hr))
```
▁▁▁▁▁▁▁▃▁▁▁▂▂▁▄▁▆▁▁▁▁▁▁▁▁▁▁▁▁▄▁▅▁▂▁▁▂▄▁▁▁▃▂▁▆▁▁▁▁▁▂▁▁▁▁▁▁▁▃▂▁▁▁▆▁▁▁█▁▁▁▅▁▁▁▂▁▄▆▂▄▃▁▁▁▃▁▁▁▁▃▁▁▃▁▁
```

**Heap InUse** (current: 157.2MB | avg: 165.7MB | max: 732.9MB | trend: stable (-0.05MB/hr))
```
▂▂▅▃▄▄▃▃▄▂▂▃▃▁▃▃▄▁▂▂▂▁▂▁▄▂▄▂▄▄▁▄▂▂▁▁▄▃▂▂▄▃▂▂█▄▂▄▄▃▁▁▁▃▁▂▂▃▃▂▂▂▁▇▃▁▃▅▁▃▁▅▂▁▂▂▁▃▅▁▂▃▄▃▃▃▄▃▂▁▁▂▁▁▃▃
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,093 | 14,065 | +28 | 14,223 | 28,205 | stable (-0.36/hr) |
| Heap InUse | 157.2MB | 146.0MB | +11.2MB | 165.7MB | 732.9MB | stable (-0.05MB/hr) |
| Heap Sys | 382.2MB | 382.2MB | +0.0MB | 1267.2MB | 1805.8MB | |
| Heap Objects | 1,091,934 | 937,375 | +154559 | 882,163 | 2,707,946 | |

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
| 2026-06-04 | 45 | 14,170 | 141.5MB | 258.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `reflect.mapassign_faststr0` | 3.0MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 10 | `jasonlvhit/gocron.NewScheduler` | 1.08MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 11.3GB |
| 2 | `reflect.unsafe_NewArray` | 4.91GB |
| 3 | `reflect.MakeSlice` | 2.77GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 1.5GB |
| 5 | `segmentio/kafka-go.makeLayout` | 1.24GB |
| 6 | `v3/newrelic.newAnalyticsEvents` | 676.7MB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 629.89MB |
| 8 | `internal/reflectlite.unsafe_New` | 578.05MB |
| 9 | `compress/flate.NewWriter` | 429.26MB |
| 10 | `v3/newrelic.newLogEvents` | 375.08MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 156.85MB | 154.79MB | 3.89GB | 0B |
| `evaluation.mergeMetadata` | 71.02MB | 70.02MB | 1.66GB | 0B |
| `local.(*Client).EvaluateV2` | 267.59MB | 262.98MB | 6.52GB | 0B |
| `local.topologicalSort` | 37.12MB | 35.07MB | 916.01MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 235.99MB | 230.85MB | 7.40GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 51.69MB | 51.69MB | 23.96MB | 0B |
| `localEvaluation.getMapOfValue` | 235.99MB | 230.85MB | 7.40GB | 0B |
| `utils.ParseFeatureFlag` | 235.99MB | 230.85MB | 116.44MB | 0B |

**Total FF alloc (current snapshot):** 1.26GB  |  **24h avg:** 27.90GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 994/996 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.86MB | 38/996 | `███████░░░░░░░░ 48%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.24MB | 25/996 | `███████░░░░░░░░ 47%` |
| 4 | `runtime.mallocgc` | 13.43MB | 990/996 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 11.97MB | 40/996 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/996 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/996 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/996 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 991/996 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/996 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 93.11GB | 986/996 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/996 | `██████████░░░░░ 68%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/996 | `██████████░░░░░ 67%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/996 | `██████████░░░░░ 67%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 49.58GB | 938/996 | `███████░░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 40.29GB | 985/996 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/996 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/996 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 22.7GB | 976/996 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 22.4GB | 935/996 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
