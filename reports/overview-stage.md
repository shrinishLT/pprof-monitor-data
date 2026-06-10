# Overview: stage
*Last updated: 2026-06-10 23:03 IST*
*Data range: 2026-05-15T16:03 to 2026-06-10T23:03 (1283 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,067 | avg: 14,205 | max: 28,205 | trend: stable (-0.30/hr))
```
▁▁▁▁▁▁▁▁▂▃▁▁▁▃█▃▁▁▁▁▁▁▁▁▁▁▁▄▁▄▁▁▁▂▁▁▁▁▃▂▂▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▃▃▁▂▁▁▁▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 133.1MB | avg: 163.2MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▂▃▁▃▃▄▂▃▄▃▁▂▂▄█▄▂▄▃▄▄▂▃▂▂▂▃▃▂▃▁▄▃▄▂▂▂▄▁▃▂▃▃▂▃▃▂▂▃▃▃▃▂▂▁▃▂▂▂▂▃▁▃▃▃▂▄▄▃▃▂▃▂▂▂▂▂▂▇▃▂▃▃▃▁▂▂▄▃▃▁▃▃▁▃▂
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,067 | 14,067 | +0 | 14,205 | 28,205 | stable (-0.30/hr) |
| Heap InUse | 133.1MB | 164.1MB | -31.0MB | 163.2MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 256.0MB | 255.9MB | +0.1MB | 1215.7MB | 1805.8MB | |
| Heap Objects | 785,884 | 1,172,929 | -387045 | 885,697 | 2,707,946 | |

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
| 2026-06-10 | 46 | 14,122 | 152.0MB | 275.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 10.08MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.0MB |
| 6 | `compress/flate.NewWriter` | 3.53MB |
| 7 | `reflect.mapassign_faststr0` | 3.5MB |
| 8 | `reflect.unsafe_NewArray` | 3.04MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 5.88GB |
| 2 | `reflect.unsafe_NewArray` | 2.52GB |
| 3 | `reflect.MakeSlice` | 1.44GB |
| 4 | `segmentio/kafka-go.makeLayout` | 631.77MB |
| 5 | `v3/newrelic.newAnalyticsEvents` | 339.98MB |
| 6 | `internal/reflectlite.unsafe_New` | 291.53MB |
| 7 | `v3/newrelic.newLogEvents` | 204.17MB |
| 8 | `compress/flate.NewWriter` | 194.8MB |
| 9 | `kafka-go/protocol.bytesToString` | 162.01MB |
| 10 | `io.ReadAll` | 150.83MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 46.53MB | 44.99MB | 1.11GB | 0B |
| `evaluation.mergeMetadata` | 22.51MB | 21.50MB | 479.27MB | 0B |
| `local.(*Client).EvaluateV2` | 78.04MB | 75.96MB | 1.89GB | 0B |
| `local.topologicalSort` | 11.68MB | 11.68MB | 278.00MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 77.41MB | 75.33MB | 1.95GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 9.94MB | 9.94MB | 189.74MB | 0B |
| `localEvaluation.getMapOfValue` | 77.41MB | 75.33MB | 1.95GB | 0B |
| `utils.ParseFeatureFlag` | 77.41MB | 75.33MB | 1.95GB | 0B |

**Total FF alloc (current snapshot):** 400.94MB  |  **24h avg:** 9.78GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1281/1283 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.67MB | 49/1283 | `███████░░░░░░░░ 50%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.15MB | 31/1283 | `██████░░░░░░░░░ 44%` |
| 4 | `runtime.mallocgc` | 13.32MB | 1277/1283 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 11.57MB | 51/1283 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1283 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1283 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1283 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1278/1283 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1283 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 99.14GB | 1273/1283 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1283 | `█████████░░░░░░ 64%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1283 | `█████████░░░░░░ 63%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1283 | `█████████░░░░░░ 63%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 51.91GB | 1205/1283 | `███████░░░░░░░░ 52%` |
| 6 | `reflect.unsafe_NewArray` | 42.91GB | 1272/1283 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1283 | `█████░░░░░░░░░░ 34%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1283 | `█████░░░░░░░░░░ 34%` |
| 9 | `reflect.MakeSlice` | 24.14GB | 1263/1283 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 22.66GB | 1202/1283 | `███░░░░░░░░░░░░ 22%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
