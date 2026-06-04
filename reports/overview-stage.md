# Overview: stage
*Last updated: 2026-06-05 02:32 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T02:32 (1004 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,069 | avg: 14,222 | max: 28,205 | trend: stable (-0.37/hr))
```
▁▁▁▂▂▁▄▁▆▁▁▁▁▁▁▁▁▁▁▁▁▄▁▅▁▂▁▁▂▄▂▁▁▃▂▁▆▁▁▁▁▁▂▁▁▁▁▁▁▁▃▂▁▁▁▆▁▁▁█▁▁▁▅▁▁▁▂▁▄▆▂▄▃▁▁▁▃▁▁▁▁▃▁▁▃▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 118.2MB | avg: 165.3MB | max: 732.9MB | trend: stable (-0.05MB/hr))
```
▄▂▃▃▃▂▄▃▅▁▃▂▂▁▂▂▄▂▄▃▄▅▂▅▂▂▁▂▄▃▃▂▄▃▃▂█▄▂▄▄▄▁▁▁▃▁▂▂▃▃▃▂▃▁▇▄▁▃▅▁▃▁▅▂▁▃▂▁▃▅▁▂▄▄▃▃▃▄▃▂▁▁▂▂▁▃▃▁▃▁▁▁▃▂▂
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,069 | 14,076 | -7 | 14,222 | 28,205 | stable (-0.37/hr) |
| Heap InUse | 118.2MB | 131.3MB | -13.1MB | 165.3MB | 732.9MB | stable (-0.05MB/hr) |
| Heap Sys | 421.4MB | 193.0MB | +228.4MB | 1259.2MB | 1805.8MB | |
| Heap Objects | 541,270 | 861,828 | -320558 | 880,191 | 2,707,946 | |

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
| 2026-06-05 | 6 | 14,076 | 117.2MB | 144.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 7 | `reflect.mapassign_faststr0` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `reflect.unsafe_NewArray` | 2.0MB |
| 10 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 4.14GB |
| 2 | `reflect.unsafe_NewArray` | 1.79GB |
| 3 | `reflect.MakeSlice` | 1023.02MB |
| 4 | `segmentio/kafka-go.makeLayout` | 449.75MB |
| 5 | `v3/newrelic.newAnalyticsEvents` | 270.15MB |
| 6 | `internal/reflectlite.unsafe_New` | 195.52MB |
| 7 | `fmt.Sprintf` | 191.15MB |
| 8 | `compress/flate.NewWriter` | 171.0MB |
| 9 | `v3/newrelic.newLogEvents` | 157.01MB |
| 10 | `io.ReadAll` | 132.56MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 11.28MB | 8.74MB | 2.54GB | 0B |
| `evaluation.mergeMetadata` | 6.00MB | 4.50MB | 1.08GB | 0B |
| `local.(*Client).EvaluateV2` | 23.48MB | 17.23MB | 4.26GB | 0B |
| `local.topologicalSort` | 2.02MB | 1.52MB | 601.10MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 28.11MB | 20.84MB | 4.83GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 0B | 0B | 20.60MB | 0B |
| `localEvaluation.getMapOfValue` | 28.11MB | 20.84MB | 4.83GB | 0B |
| `utils.ParseFeatureFlag` | 28.11MB | 20.84MB | 103.25MB | 0B |

**Total FF alloc (current snapshot):** 127.11MB  |  **24h avg:** 18.25GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1002/1004 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.86MB | 38/1004 | `███████░░░░░░░░ 48%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.24MB | 25/1004 | `███████░░░░░░░░ 47%` |
| 4 | `runtime.mallocgc` | 13.41MB | 998/1004 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 11.97MB | 40/1004 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1004 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1004 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1004 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 999/1004 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1004 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 92.4GB | 994/1004 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1004 | `██████████░░░░░ 69%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1004 | `██████████░░░░░ 68%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1004 | `██████████░░░░░ 67%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 49.48GB | 940/1004 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 39.98GB | 993/1004 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1004 | `█████░░░░░░░░░░ 37%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1004 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 22.52GB | 984/1004 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 22.35GB | 937/1004 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
