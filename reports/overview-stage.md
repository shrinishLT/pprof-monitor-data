# Overview: stage
*Last updated: 2026-06-16 20:02 IST*
*Data range: 2026-05-15T16:03 to 2026-06-16T20:02 (1564 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,094 | avg: 14,195 | max: 28,205 | trend: stable (-0.23/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▇█▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 100.0MB | avg: 160.3MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▂▃▂▅▄▂▃▃▃▂▃▂▃▆▄▄▂▃▄▂▄█▂▅▂▃▄▂▄▅▁▅▂▂▅▄▄▁▂▄▂▄▂▆▆▅▁▁▂▃▃▅▁▂▂▄▃▂▁▂▂▁▄▂▅▄▅▂▂▇▃▄▁▁▄▂▃▅▁▃▄▄▄▃▂▂▂▂▁▁▂▄▂▁▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,094 | 14,100 | -6 | 14,195 | 28,205 | stable (-0.23/hr) |
| Heap InUse | 100.0MB | 109.2MB | -9.2MB | 160.3MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 439.9MB | 439.2MB | +0.7MB | 1169.8MB | 1805.8MB | |
| Heap Objects | 296,319 | 466,746 | -170427 | 876,613 | 2,707,946 | |

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
| 2026-06-13 | 48 | 14,121 | 146.0MB | 214.7MB |
| 2026-06-14 | 48 | 14,120 | 150.8MB | 247.1MB |
| 2026-06-15 | 48 | 14,245 | 154.3MB | 238.3MB |
| 2026-06-16 | 40 | 14,148 | 141.3MB | 226.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 7.08MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 6 | `reflect.mapassign_faststr0` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 9 | `aws/endpoints.init` | 1.5MB |
| 10 | `reflect.unsafe_New` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 7.85GB |
| 2 | `reflect.unsafe_NewArray` | 3.37GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 1.94GB |
| 4 | `reflect.MakeSlice` | 1.94GB |
| 5 | `segmentio/kafka-go.makeLayout` | 862.98MB |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 798.11MB |
| 7 | `v3/newrelic.newAnalyticsEvents` | 464.38MB |
| 8 | `internal/reflectlite.unsafe_New` | 394.04MB |
| 9 | `compress/flate.NewWriter` | 283.82MB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 278.01MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 68.38MB | 61.22MB | 91.15MB | 512.03kB |
| `evaluation.mergeMetadata` | 29.01MB | 26.51MB | 35.96MB | 0B |
| `local.(*Client).EvaluateV2` | 128.09MB | 114.69MB | 153.69MB | 1.04MB |
| `local.topologicalSort` | 20.76MB | 17.72MB | 20.67MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 126.87MB | 114.01MB | 157.67MB | 1.04MB |
| `localEvaluation.GetFeatureFlagPayload` | 19.22MB | 17.67MB | 16.15MB | 0B |
| `localEvaluation.getMapOfValue` | 126.87MB | 114.01MB | 157.67MB | 1.04MB |
| `utils.ParseFeatureFlag` | 127.37MB | 114.51MB | 157.77MB | 1.04MB |

**Total FF alloc (current snapshot):** 646.57MB  |  **24h avg:** 790.71MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1562/1564 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.77MB | 56/1564 | `███████░░░░░░░░ 51%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 15.47MB | 35/1564 | `██████░░░░░░░░░ 42%` |
| 4 | `runtime.mallocgc` | 12.61MB | 1558/1564 | `█████░░░░░░░░░░ 34%` |
| 5 | `database/sql.convertAssignRows` | 11.44MB | 58/1564 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1564 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1564 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1564 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.21MB | 1559/1564 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1564 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 91.29GB | 1554/1564 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1564 | `██████████░░░░░ 69%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1564 | `██████████░░░░░ 69%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1564 | `██████████░░░░░ 68%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 49.15GB | 1421/1564 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 39.47GB | 1553/1564 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1564 | `█████░░░░░░░░░░ 37%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1564 | `█████░░░░░░░░░░ 37%` |
| 9 | `reflect.MakeSlice` | 22.17GB | 1544/1564 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.33GB | 1417/1564 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (4.0x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.6x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.5x avg)
