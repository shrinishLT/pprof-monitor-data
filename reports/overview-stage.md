# Overview: stage
*Last updated: 2026-06-11 16:02 IST*
*Data range: 2026-05-15T16:03 to 2026-06-11T16:02 (1317 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,082 | avg: 14,203 | max: 28,205 | trend: stable (-0.30/hr))
```
▁▁▁▁▄▃▃▃▁▁▁▃▁▁▁▁▁▁▁▁▂▂▄▅▂▃▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▂▂▃▁▁▁▃▁▁▁▂▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▃▁▇▁▁▁▁▁▁▁▁▁▁▁▁▄▁▆▁▁▃▁
```

**Heap InUse** (current: 151.2MB | avg: 162.6MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▂▃▂▄▂▄▂▃▃▂▃▃▂▂▃▃▃▃▂▂▁▃▂▂▂▂▃▂▃▃▃▂▄▄▃▃▂▃▂▂▂▂▂▂█▃▂▃▃▄▁▂▂▄▃▄▁▄▃▁▃▂▁▂▂▁▁▃▂▁▃▁▃▃▄▁▄▁▁▁▂▂▁▂▃▃▂▃▂▂▃▁▃▂▃▃
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,082 | 14,222 | -140 | 14,203 | 28,205 | stable (-0.30/hr) |
| Heap InUse | 151.2MB | 154.6MB | -3.4MB | 162.6MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 513.8MB | 516.2MB | -2.4MB | 1197.9MB | 1805.8MB | |
| Heap Objects | 893,152 | 954,656 | -61504 | 883,308 | 2,707,946 | |

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
| 2026-06-11 | 33 | 14,121 | 140.5MB | 199.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 8.08MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 4.5MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.unsafe_NewArray` | 1.0MB |
| 9 | `internal/sync.newIndirectNode[go.shape.interface {},go.shape.interface {}]` | 1.0MB |
| 10 | `aws/endpoints.init` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 8.36GB |
| 2 | `reflect.unsafe_NewArray` | 3.53GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 2.75GB |
| 4 | `reflect.MakeSlice` | 2.02GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 1.11GB |
| 6 | `segmentio/kafka-go.makeLayout` | 859.63MB |
| 7 | `v3/newrelic.newAnalyticsEvents` | 493.54MB |
| 8 | `internal/reflectlite.unsafe_New` | 395.54MB |
| 9 | `database/sql.convertAssignRows` | 356.52MB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 353.51MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 81.16MB | 64.72MB | 237.04MB | 0B |
| `evaluation.mergeMetadata` | 34.01MB | 26.51MB | 101.65MB | 0B |
| `local.(*Client).EvaluateV2` | 129.08MB | 101.18MB | 402.34MB | 0B |
| `local.topologicalSort` | 21.85MB | 15.75MB | 57.87MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 107.78MB | 86.10MB | 411.26MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 35.19MB | 25.34MB | 42.90MB | 0B |
| `localEvaluation.getMapOfValue` | 107.78MB | 86.10MB | 411.26MB | 0B |
| `utils.ParseFeatureFlag` | 108.28MB | 86.60MB | 411.55MB | 0B |

**Total FF alloc (current snapshot):** 625.11MB  |  **24h avg:** 2.03GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1315/1317 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.67MB | 49/1317 | `███████░░░░░░░░ 50%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.15MB | 31/1317 | `██████░░░░░░░░░ 44%` |
| 4 | `runtime.mallocgc` | 13.24MB | 1311/1317 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 11.57MB | 51/1317 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1317 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1317 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1317 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1312/1317 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1317 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 96.87GB | 1307/1317 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1317 | `█████████░░░░░░ 65%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1317 | `█████████░░░░░░ 65%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1317 | `█████████░░░░░░ 64%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 51.36GB | 1221/1317 | `███████░░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 41.93GB | 1306/1317 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1317 | `█████░░░░░░░░░░ 35%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1317 | `█████░░░░░░░░░░ 35%` |
| 9 | `reflect.MakeSlice` | 23.59GB | 1297/1317 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 22.42GB | 1218/1317 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
