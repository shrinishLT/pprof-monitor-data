# Overview: stage
*Last updated: 2026-06-05 04:30 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T04:30 (1008 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,065 | avg: 14,222 | max: 28,205 | trend: stable (-0.37/hr))
```
▂▁▄▁▆▁▁▁▁▁▁▁▁▁▁▁▁▄▁▅▁▂▁▁▂▄▂▁▁▃▂▁▆▁▁▁▁▁▂▁▁▁▁▁▁▁▃▂▁▁▁▆▁▁▁█▁▁▁▅▁▁▁▂▁▄▆▂▄▃▁▁▁▃▁▁▁▁▃▁▁▃▁▁▁▁▁▁▁▁▁▁▂▃▂▁
```

**Heap InUse** (current: 142.4MB | avg: 165.3MB | max: 732.9MB | trend: stable (-0.05MB/hr))
```
▃▂▄▃▅▁▃▂▂▁▂▂▄▂▄▃▄▅▂▅▂▂▁▂▄▃▃▂▄▃▃▂█▄▂▄▄▄▁▁▁▃▁▂▂▃▃▃▂▃▁▇▄▁▃▅▁▃▁▅▂▁▃▂▁▃▅▁▂▄▄▃▃▃▄▃▂▁▁▂▂▁▃▃▁▃▁▁▁▃▂▂▂▂▅▃
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,065 | 14,210 | -145 | 14,222 | 28,205 | stable (-0.37/hr) |
| Heap InUse | 142.4MB | 198.0MB | -55.6MB | 165.3MB | 732.9MB | stable (-0.05MB/hr) |
| Heap Sys | 417.7MB | 417.9MB | -0.2MB | 1255.9MB | 1805.8MB | |
| Heap Objects | 875,020 | 1,406,233 | -531213 | 880,052 | 2,707,946 | |

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
| 2026-06-05 | 10 | 14,119 | 130.1MB | 198.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 6 | `reflect.unsafe_NewArray` | 2.52MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.0MB |
| 9 | `compress/flate.NewWriter` | 1.76MB |
| 10 | `reflect.mapassign_faststr0` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 7.23GB |
| 2 | `reflect.unsafe_NewArray` | 3.16GB |
| 3 | `reflect.MakeSlice` | 1.75GB |
| 4 | `segmentio/kafka-go.makeLayout` | 797.62MB |
| 5 | `v3/newrelic.newAnalyticsEvents` | 454.22MB |
| 6 | `internal/reflectlite.unsafe_New` | 349.53MB |
| 7 | `v3/newrelic.newLogEvents` | 259.91MB |
| 8 | `compress/flate.NewWriter` | 257.38MB |
| 9 | `fmt.Sprintf` | 255.86MB |
| 10 | `io.ReadAll` | 215.73MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 24.75MB | 22.65MB | 2.32GB | 0B |
| `evaluation.mergeMetadata` | 10.50MB | 10.00MB | 1010.35MB | 0B |
| `local.(*Client).EvaluateV2` | 45.28MB | 41.61MB | 3.89GB | 0B |
| `local.topologicalSort` | 6.61MB | 5.58MB | 549.39MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 51.47MB | 47.80MB | 4.41GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 0B | 0B | 19.74MB | 0B |
| `localEvaluation.getMapOfValue` | 51.47MB | 47.80MB | 4.41GB | 0B |
| `utils.ParseFeatureFlag` | 52.47MB | 48.80MB | 102.03MB | 0B |

**Total FF alloc (current snapshot):** 242.55MB  |  **24h avg:** 16.67GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1006/1008 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.86MB | 38/1008 | `███████░░░░░░░░ 48%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.24MB | 25/1008 | `███████░░░░░░░░ 47%` |
| 4 | `runtime.mallocgc` | 13.41MB | 1002/1008 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 11.97MB | 40/1008 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1008 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1008 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1008 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1003/1008 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1008 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 92.05GB | 998/1008 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1008 | `██████████░░░░░ 69%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1008 | `██████████░░░░░ 68%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1008 | `██████████░░░░░ 68%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 49.48GB | 940/1008 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 39.83GB | 997/1008 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1008 | `█████░░░░░░░░░░ 37%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1008 | `█████░░░░░░░░░░ 37%` |
| 9 | `reflect.MakeSlice` | 22.44GB | 988/1008 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 22.35GB | 937/1008 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
