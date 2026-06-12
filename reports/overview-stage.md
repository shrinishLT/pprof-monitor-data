# Overview: stage
*Last updated: 2026-06-12 06:31 IST*
*Data range: 2026-05-15T16:03 to 2026-06-12T06:31 (1346 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,569 | avg: 14,202 | max: 28,205 | trend: stable (-0.29/hr))
```
▇▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▂▂▁▁▁▃▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▇▁▁▁▁▁▁▁▁▁▁▁▁▄▁▆▁▁▃▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▂▁▁▄▇▁█
```

**Heap InUse** (current: 167.0MB | avg: 162.1MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▃▃▂▄▄▃▃▂▃▂▂▂▂▂▂█▃▂▃▃▄▁▂▂▄▃▄▁▄▃▁▃▂▁▂▂▁▁▃▂▁▃▁▃▃▄▁▄▁▁▁▂▂▁▂▃▃▂▃▂▂▃▂▃▂▃▃▁▂▄▁▄▁▂▂▁▁▃▁▃▂▂▁▁▁▃▁▃▂▃▂▂▂▂▃▃
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 51%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,569 | 14,075 | +494 | 14,202 | 28,205 | stable (-0.29/hr) |
| Heap InUse | 167.0MB | 172.1MB | -5.1MB | 162.1MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 381.7MB | 382.2MB | -0.5MB | 1179.2MB | 1805.8MB | |
| Heap Objects | 720,889 | 1,180,314 | -459425 | 880,792 | 2,707,946 | |

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
| 2026-06-12 | 14 | 14,175 | 137.6MB | 172.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 9.51MB |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 9.5MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 7 | `reflect.mapassign_faststr0` | 3.0MB |
| 8 | `dotlapse-event-service/workerpool.NewWorker` | 3.0MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.85MB |
| 10 | `bufio.NewWriterSize` | 2.52MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 18.87GB |
| 2 | `reflect.unsafe_NewArray` | 8.0GB |
| 3 | `reflect.MakeSlice` | 4.48GB |
| 4 | `segmentio/kafka-go.makeLayout` | 1.99GB |
| 5 | `v3/newrelic.newAnalyticsEvents` | 1.08GB |
| 6 | `internal/reflectlite.unsafe_New` | 965.59MB |
| 7 | `compress/flate.NewWriter` | 669.01MB |
| 8 | `fmt.Sprintf` | 638.24MB |
| 9 | `dotlapse-event-service/project.ApplyPagination` | 606.94MB |
| 10 | `v3/newrelic.newLogEvents` | 578.29MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 100.65MB | 89.76MB | 72.25MB | 0B |
| `evaluation.mergeMetadata` | 43.01MB | 38.51MB | 31.32MB | 0B |
| `local.(*Client).EvaluateV2` | 166.92MB | 149.13MB | 117.52MB | 0B |
| `local.topologicalSort` | 18.31MB | 17.81MB | 16.53MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 160.53MB | 143.28MB | 108.43MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 20.79MB | 16.65MB | 20.47MB | 0B |
| `localEvaluation.getMapOfValue` | 160.53MB | 143.28MB | 108.43MB | 0B |
| `utils.ParseFeatureFlag` | 161.54MB | 144.29MB | 108.86MB | 0B |

**Total FF alloc (current snapshot):** 832.28MB  |  **24h avg:** 583.81MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1344/1346 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.42MB | 50/1346 | `███████░░░░░░░░ 50%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.15MB | 31/1346 | `██████░░░░░░░░░ 44%` |
| 4 | `runtime.mallocgc` | 13.13MB | 1340/1346 | `█████░░░░░░░░░░ 35%` |
| 5 | `database/sql.convertAssignRows` | 11.44MB | 52/1346 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1346 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1346 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1346 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1341/1346 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1346 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 94.98GB | 1336/1346 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1346 | `██████████░░░░░ 67%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1346 | `█████████░░░░░░ 66%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1346 | `█████████░░░░░░ 65%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 51.12GB | 1227/1346 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 41.11GB | 1335/1346 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1346 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1346 | `█████░░░░░░░░░░ 35%` |
| 9 | `reflect.MakeSlice` | 23.12GB | 1326/1346 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 22.33GB | 1223/1346 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
