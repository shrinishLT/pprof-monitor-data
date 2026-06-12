# Overview: stage
*Last updated: 2026-06-13 03:32 IST*
*Data range: 2026-05-15T16:03 to 2026-06-13T03:32 (1388 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,212 | avg: 14,199 | max: 28,205 | trend: stable (-0.29/hr))
```
▁▁▁▃▁▇▁▁▁▁▁▁▁▁▁▁▁▁▄▁▆▁▁▃▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▂▁▁▄▇▁█▇▁▁▁▁▁▂▁▁▁▁▁▃▁▂▅▃▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▃
```

**Heap InUse** (current: 185.5MB | avg: 161.8MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▂▄▅█▁▇▁▂▂▄▃▁▄▄▅▄▅▃▃▅▂▄▃▄▄▂▃▆▂▆▁▄▄▂▁▆▁▅▃▄▁▁▂▅▁▄▂▅▃▄▃▃▆▅▄▃▁▆▆▃▆▅▆▃▇▁▆▆▆▃▆▂▄▅▆▃▂▇▁▅▇▄▆▂▁▅▄▃▅▃▄▅▃▁▁▇
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,212 | 14,082 | +130 | 14,199 | 28,205 | stable (-0.29/hr) |
| Heap InUse | 185.5MB | 112.2MB | +73.3MB | 161.8MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 1267.2MB | 1267.1MB | +0.1MB | 1181.9MB | 1805.8MB | |
| Heap Objects | 1,176,709 | 416,558 | +760151 | 881,317 | 2,707,946 | |

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
| 2026-06-13 | 8 | 14,096 | 143.8MB | 185.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 9.51MB |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 9.5MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 7 | `bytes.growSlice` | 3.03MB |
| 8 | `reflect.unsafe_NewArray` | 3.01MB |
| 9 | `dotlapse-event-service/workerpool.NewWorker` | 3.0MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.85MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 57.24GB |
| 2 | `reflect.unsafe_NewArray` | 24.51GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 21.22GB |
| 4 | `reflect.MakeSlice` | 13.67GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 8.7GB |
| 6 | `segmentio/kafka-go.makeLayout` | 6.02GB |
| 7 | `v3/newrelic.newAnalyticsEvents` | 3.02GB |
| 8 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.8GB |
| 9 | `internal/reflectlite.unsafe_New` | 2.78GB |
| 10 | `database/sql.convertAssignRows` | 2.49GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 346.69MB | 342.61MB | 234.20MB | 0B |
| `evaluation.mergeMetadata` | 151.04MB | 149.04MB | 102.92MB | 0B |
| `local.(*Client).EvaluateV2` | 573.28MB | 566.05MB | 383.31MB | 0B |
| `local.topologicalSort` | 66.10MB | 65.59MB | 45.04MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 533.71MB | 525.43MB | 351.24MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 93.70MB | 93.70MB | 66.10MB | 0B |
| `localEvaluation.getMapOfValue` | 533.71MB | 525.43MB | 351.24MB | 0B |
| `utils.ParseFeatureFlag` | 535.21MB | 526.94MB | 352.66MB | 0B |

**Total FF alloc (current snapshot):** 2.77GB  |  **24h avg:** 1.84GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1386/1388 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.76MB | 52/1388 | `███████░░░░░░░░ 51%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 15.77MB | 32/1388 | `██████░░░░░░░░░ 43%` |
| 4 | `runtime.mallocgc` | 13.02MB | 1382/1388 | `█████░░░░░░░░░░ 35%` |
| 5 | `database/sql.convertAssignRows` | 11.45MB | 54/1388 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1388 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1388 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1388 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1383/1388 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1388 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 93.26GB | 1378/1388 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1388 | `██████████░░░░░ 68%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1388 | `██████████░░░░░ 67%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1388 | `██████████░░░░░ 67%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 50.08GB | 1269/1388 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 40.35GB | 1377/1388 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1388 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1388 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 22.69GB | 1368/1388 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.86GB | 1265/1388 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
