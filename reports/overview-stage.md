# Overview: stage
*Last updated: 2026-06-05 01:30 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T01:30 (1002 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,063 | avg: 14,223 | max: 28,205 | trend: stable (-0.37/hr))
```
▁▃▁▁▁▂▂▁▄▁▆▁▁▁▁▁▁▁▁▁▁▁▁▄▁▅▁▂▁▁▂▄▂▁▁▃▂▁▆▁▁▁▁▁▂▁▁▁▁▁▁▁▃▂▁▁▁▆▁▁▁█▁▁▁▅▁▁▁▂▁▄▆▂▄▃▁▁▁▃▁▁▁▁▃▁▁▃▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 144.8MB | avg: 165.4MB | max: 732.9MB | trend: stable (-0.05MB/hr))
```
▃▃▄▂▃▃▃▂▄▃▅▁▃▂▂▁▂▂▄▂▄▃▄▅▂▅▂▂▁▂▄▃▃▂▄▃▃▂█▄▂▄▄▄▁▁▁▃▁▂▂▃▃▃▂▃▁▇▄▁▃▅▁▃▁▅▂▁▃▂▁▃▅▁▂▄▄▃▃▃▄▃▂▁▁▂▂▁▃▃▁▃▁▁▁▃
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,063 | 14,072 | -9 | 14,223 | 28,205 | stable (-0.37/hr) |
| Heap InUse | 144.8MB | 92.8MB | +52.0MB | 165.4MB | 732.9MB | stable (-0.05MB/hr) |
| Heap Sys | 192.9MB | 194.0MB | -1.1MB | 1261.1MB | 1805.8MB | |
| Heap Objects | 977,194 | 278,782 | +698412 | 880,548 | 2,707,946 | |

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
| 2026-06-05 | 4 | 14,078 | 113.5MB | 144.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 9.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.51MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.unsafe_NewArray` | 2.03MB |
| 9 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.0MB |
| 10 | `kafka-go/protocol.newPage` | 1.6MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 2.53GB |
| 2 | `reflect.unsafe_NewArray` | 1.09GB |
| 3 | `reflect.MakeSlice` | 624.01MB |
| 4 | `segmentio/kafka-go.makeLayout` | 267.07MB |
| 5 | `v3/newrelic.newAnalyticsEvents` | 179.67MB |
| 6 | `internal/reflectlite.unsafe_New` | 108.51MB |
| 7 | `v3/newrelic.newLogEvents` | 101.84MB |
| 8 | `compress/flate.NewWriter` | 90.79MB |
| 9 | `io.ReadAll` | 80.44MB |
| 10 | `reflect.mapassign_faststr0` | 70.02MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 8.74MB | 6.16MB | 2.96GB | 0B |
| `evaluation.mergeMetadata` | 4.50MB | 3.00MB | 1.26GB | 0B |
| `local.(*Client).EvaluateV2` | 17.23MB | 9.34MB | 4.96GB | 0B |
| `local.topologicalSort` | 1.52MB | 518.65kB | 699.24MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 20.84MB | 12.43MB | 5.63GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 0B | 0B | 22.33MB | 0B |
| `localEvaluation.getMapOfValue` | 20.84MB | 12.43MB | 5.63GB | 0B |
| `utils.ParseFeatureFlag` | 20.84MB | 12.43MB | 109.95MB | 0B |

**Total FF alloc (current snapshot):** 94.52MB  |  **24h avg:** 21.26GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1000/1002 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.86MB | 38/1002 | `███████░░░░░░░░ 48%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.24MB | 25/1002 | `███████░░░░░░░░ 47%` |
| 4 | `runtime.mallocgc` | 13.41MB | 996/1002 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 11.97MB | 40/1002 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1002 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1002 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1002 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 997/1002 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1002 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 92.57GB | 992/1002 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1002 | `██████████░░░░░ 68%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1002 | `██████████░░░░░ 68%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1002 | `██████████░░░░░ 67%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 49.48GB | 940/1002 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 40.06GB | 991/1002 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1002 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1002 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 22.57GB | 982/1002 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 22.35GB | 937/1002 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
