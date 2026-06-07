# Overview: stage
*Last updated: 2026-06-07 20:03 IST*
*Data range: 2026-05-15T16:03 to 2026-06-07T20:02 (1134 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,078 | avg: 14,212 | max: 28,205 | trend: stable (-0.36/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▄▂▄▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▅▂▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▄█▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 116.8MB | avg: 164.1MB | max: 732.9MB | trend: stable (-0.05MB/hr))
```
▃▂▃▁▂▁▁▁▃▁▃▂▃▁▂▁▁▃▁▁▅▂▂▁▁▁▂▂▃▂▁▁▂▃▁▁▂▁▃▃▃▃▁▂▂▁▂▂▂▃▃▂▂▁▃▁▁▃▂▃▁▂▁▂▁▃▃▁▆█▁▃▄▂▃▁▂▁▂▃▃▁▃▃▁▃▃▃▂▁▃▃▃▂▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,078 | 14,069 | +9 | 14,212 | 28,205 | stable (-0.36/hr) |
| Heap InUse | 116.8MB | 107.1MB | +9.7MB | 164.1MB | 732.9MB | stable (-0.05MB/hr) |
| Heap Sys | 1097.7MB | 1098.7MB | -1.0MB | 1227.8MB | 1805.8MB | |
| Heap Objects | 499,810 | 248,581 | +251229 | 881,555 | 2,707,946 | |

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
| 2026-06-07 | 40 | 14,107 | 157.4MB | 298.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `segmentio/kafka-go.makePartitions` | 9.01MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.unsafe_NewArray` | 2.0MB |
| 9 | `reflect.mapassign_faststr0` | 2.0MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 1.07MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 121.48GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 56.39GB |
| 3 | `reflect.unsafe_NewArray` | 52.71GB |
| 4 | `reflect.MakeSlice` | 29.5GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 22.09GB |
| 6 | `segmentio/kafka-go.makeLayout` | 12.98GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 7.02GB |
| 8 | `v3/newrelic.newAnalyticsEvents` | 6.33GB |
| 9 | `database/sql.convertAssignRows` | 6.23GB |
| 10 | `internal/reflectlite.unsafe_New` | 5.94GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 713.22MB | 708.52MB | 605.21MB | 0B |
| `evaluation.mergeMetadata` | 308.58MB | 307.58MB | 258.56MB | 0B |
| `local.(*Client).EvaluateV2` | 1.20GB | 1.19GB | 1.02GB | 0B |
| `local.topologicalSort` | 183.58MB | 182.57MB | 159.04MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.23GB | 1.22GB | 1.04GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 127.91MB | 127.91MB | 109.50MB | 0B |
| `localEvaluation.getMapOfValue` | 1.23GB | 1.22GB | 1.04GB | 0B |
| `utils.ParseFeatureFlag` | 1.23GB | 1.22GB | 1.04GB | 0B |

**Total FF alloc (current snapshot):** 6.18GB  |  **24h avg:** 5.25GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1132/1134 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.49MB | 45/1134 | `███████░░░░░░░░ 50%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.42MB | 29/1134 | `██████░░░░░░░░░ 44%` |
| 4 | `runtime.mallocgc` | 13.37MB | 1128/1134 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 11.76MB | 47/1134 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1134 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1134 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1134 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1129/1134 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1134 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 88.91GB | 1124/1134 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1134 | `██████████░░░░░ 71%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1134 | `██████████░░░░░ 70%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1134 | `██████████░░░░░ 70%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 47.54GB | 1064/1134 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 38.48GB | 1123/1134 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1134 | `█████░░░░░░░░░░ 38%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1134 | `█████░░░░░░░░░░ 38%` |
| 9 | `reflect.MakeSlice` | 21.66GB | 1114/1134 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.24GB | 1061/1134 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
