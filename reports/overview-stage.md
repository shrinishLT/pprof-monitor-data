# Overview: stage
*Last updated: 2026-06-12 01:31 IST*
*Data range: 2026-05-15T16:03 to 2026-06-12T01:31 (1336 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,063 | avg: 14,202 | max: 28,205 | trend: stable (-0.30/hr))
```
▁▂▂▄▅▂▃▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▂▂▃▁▁▁▃▁▁▁▂▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▃▁▇▁▁▁▁▁▁▁▁▁▁▁▁▄▁▆▁▁▃▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁
```

**Heap InUse** (current: 168.6MB | avg: 162.2MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▂▁▃▂▂▂▂▃▂▃▃▃▂▄▄▃▃▂▃▂▂▂▂▂▂█▃▂▃▃▄▁▂▂▄▃▄▁▄▃▁▃▂▁▂▂▁▁▃▂▁▃▁▃▃▄▁▄▁▁▁▂▂▁▂▃▃▂▃▂▂▃▂▃▂▃▃▁▂▄▁▄▁▂▂▁▁▃▁▃▂▂▁▁▁▃
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,063 | 14,245 | -182 | 14,202 | 28,205 | stable (-0.30/hr) |
| Heap InUse | 168.6MB | 122.8MB | +45.8MB | 162.2MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 250.2MB | 250.1MB | +0.1MB | 1185.3MB | 1805.8MB | |
| Heap Objects | 1,198,825 | 560,540 | +638285 | 881,714 | 2,707,946 | |

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
| 2026-06-12 | 4 | 14,111 | 123.4MB | 168.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `sirupsen/logrus.(*Entry).WithFields` | 9.5MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `runtime.mallocgc` | 8.01MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 6 | `dotlapse-event-service/workerpool.NewWorker` | 3.0MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.85MB |
| 8 | `aws/endpoints.init` | 2.01MB |
| 9 | `compress/flate.NewWriter` | 1.76MB |
| 10 | `reflect.unsafe_NewArray` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 10.78GB |
| 2 | `reflect.unsafe_NewArray` | 4.5GB |
| 3 | `reflect.MakeSlice` | 2.54GB |
| 4 | `segmentio/kafka-go.makeLayout` | 1.12GB |
| 5 | `v3/newrelic.newAnalyticsEvents` | 623.11MB |
| 6 | `internal/reflectlite.unsafe_New` | 537.55MB |
| 7 | `compress/flate.NewWriter` | 356.1MB |
| 8 | `v3/newrelic.newLogEvents` | 328.56MB |
| 9 | `kafka-go/protocol.bytesToString` | 290.01MB |
| 10 | `kafka-go/protocol.(*decoder).read` | 288.51MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 66.53MB | 65.49MB | 70.85MB | 0B |
| `evaluation.mergeMetadata` | 31.51MB | 31.01MB | 31.05MB | 0B |
| `local.(*Client).EvaluateV2` | 108.46MB | 106.34MB | 116.30MB | 0B |
| `local.topologicalSort` | 14.76MB | 14.76MB | 17.20MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 98.53MB | 96.41MB | 109.91MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 16.65MB | 16.65MB | 19.24MB | 0B |
| `localEvaluation.getMapOfValue` | 98.53MB | 96.41MB | 109.91MB | 0B |
| `utils.ParseFeatureFlag` | 99.03MB | 96.91MB | 110.14MB | 0B |

**Total FF alloc (current snapshot):** 533.99MB  |  **24h avg:** 584.59MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1334/1336 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.42MB | 50/1336 | `███████░░░░░░░░ 50%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.15MB | 31/1336 | `██████░░░░░░░░░ 44%` |
| 4 | `runtime.mallocgc` | 13.16MB | 1330/1336 | `█████░░░░░░░░░░ 35%` |
| 5 | `database/sql.convertAssignRows` | 11.44MB | 52/1336 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1336 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1336 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1336 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1331/1336 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1336 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 95.58GB | 1326/1336 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1336 | `██████████░░░░░ 66%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1336 | `█████████░░░░░░ 66%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1336 | `█████████░░░░░░ 65%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 51.16GB | 1226/1336 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 41.37GB | 1325/1336 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1336 | `█████░░░░░░░░░░ 35%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1336 | `█████░░░░░░░░░░ 35%` |
| 9 | `reflect.MakeSlice` | 23.27GB | 1316/1336 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 22.33GB | 1223/1336 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
