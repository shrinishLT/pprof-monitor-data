# Overview: stage
*Last updated: 2026-06-11 11:32 IST*
*Data range: 2026-05-15T16:03 to 2026-06-11T11:32 (1308 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,083 | avg: 14,203 | max: 28,205 | trend: stable (-0.30/hr))
```
▁▁▆▂▆▂▁▁▃▁▁▁▁▄▃▃▃▁▁▁▃▁▁▁▁▁▁▁▁▂▂▄▅▂▃▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▂▂▃▁▁▁▃▁▁▁▂▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▃▁▇▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 147.3MB | avg: 162.7MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▂▃▃▂▃▁▄▃▅▂▃▂▄▂▄▂▃▃▂▃▃▂▂▃▃▃▃▂▂▁▃▂▂▂▂▃▂▃▃▃▂▄▄▃▃▂▃▂▂▂▂▂▂█▃▂▃▃▄▁▂▂▄▃▄▁▄▃▁▃▂▁▂▂▁▁▃▂▁▃▁▃▃▄▁▄▁▁▁▂▂▁▂▃▃▂
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,083 | 14,094 | -11 | 14,203 | 28,205 | stable (-0.30/hr) |
| Heap InUse | 147.3MB | 170.2MB | -22.9MB | 162.7MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 200.3MB | 193.1MB | +7.2MB | 1203.1MB | 1805.8MB | |
| Heap Objects | 987,489 | 1,268,840 | -281351 | 883,389 | 2,707,946 | |

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
| 2026-06-11 | 24 | 14,106 | 138.9MB | 199.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 8.08MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 4.5MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.51MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 1.0MB |
| 9 | `encoding/json.(*decodeState).literalStore` | 1.0MB |
| 10 | `fmt.(*pp).handleMethods` | 532.26kB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 1.05GB |
| 2 | `reflect.unsafe_NewArray` | 456.95MB |
| 3 | `reflect.MakeSlice` | 298.51MB |
| 4 | `segmentio/kafka-go.makeLayout` | 103.23MB |
| 5 | `v3/newrelic.newAnalyticsEvents` | 64.55MB |
| 6 | `internal/reflectlite.unsafe_New` | 53.0MB |
| 7 | `compress/flate.NewWriter` | 44.95MB |
| 8 | `v3/newrelic.newLogEvents` | 38.52MB |
| 9 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 10 | `internal/reflectlite.Swapper` | 35.0MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 11.23MB | 3.58MB | 488.98MB | 0B |
| `evaluation.mergeMetadata` | 4.00MB | 2.00MB | 208.69MB | 0B |
| `local.(*Client).EvaluateV2` | 16.46MB | 4.12MB | 833.26MB | 0B |
| `local.topologicalSort` | 2.03MB | 0B | 119.74MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 14.38MB | 3.08MB | 859.77MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 4.11MB | 1.54MB | 82.43MB | 0B |
| `localEvaluation.getMapOfValue` | 14.38MB | 3.08MB | 859.77MB | 0B |
| `utils.ParseFeatureFlag` | 14.38MB | 3.08MB | 860.39MB | 0B |

**Total FF alloc (current snapshot):** 80.97MB  |  **24h avg:** 4.21GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1306/1308 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.67MB | 49/1308 | `███████░░░░░░░░ 50%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.15MB | 31/1308 | `██████░░░░░░░░░ 44%` |
| 4 | `runtime.mallocgc` | 13.28MB | 1302/1308 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 11.57MB | 51/1308 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1308 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1308 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1308 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1303/1308 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1308 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 97.51GB | 1298/1308 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1308 | `█████████░░░░░░ 65%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1308 | `█████████░░░░░░ 64%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1308 | `█████████░░░░░░ 64%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 51.65GB | 1214/1308 | `███████░░░░░░░░ 52%` |
| 6 | `reflect.unsafe_NewArray` | 42.2GB | 1297/1308 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1308 | `█████░░░░░░░░░░ 35%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1308 | `█████░░░░░░░░░░ 35%` |
| 9 | `reflect.MakeSlice` | 23.74GB | 1288/1308 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 22.54GB | 1211/1308 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
