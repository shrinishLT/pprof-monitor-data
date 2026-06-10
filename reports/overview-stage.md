# Overview: stage
*Last updated: 2026-06-10 15:01 IST*
*Data range: 2026-05-15T16:03 to 2026-06-10T15:01 (1268 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,139 | avg: 14,207 | max: 28,205 | trend: stable (-0.30/hr))
```
▁▁▁▁█▁▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▂▄▂▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 132.9MB | avg: 163.4MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▃▂▄▂▃▂▄▃▁▁▁▃▁▃▁▁▂▁▃▃▄▂▃▄▃▁▁▁▄█▃▂▄▃▄▄▂▃▂▂▂▃▂▂▂▁▄▃▄▁▂▂▄▁▃▂▃▃▂▃▃▂▂▂▃▃▂▂▁▁▂▂▂▂▂▃▁▃▂▂▂▃▄▃▃▁▃▁▂▂▁▂▁▇▃▁
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,139 | 14,188 | -49 | 14,207 | 28,205 | stable (-0.30/hr) |
| Heap InUse | 132.9MB | 159.9MB | -27.0MB | 163.4MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 1262.7MB | 1262.9MB | -0.2MB | 1221.7MB | 1805.8MB | |
| Heap Objects | 580,351 | 996,311 | -415960 | 884,969 | 2,707,946 | |

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
| 2026-06-10 | 31 | 14,130 | 152.0MB | 275.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.0MB |
| 6 | `compress/flate.NewWriter` | 3.53MB |
| 7 | `reflect.unsafe_NewArray` | 2.51MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `bytes.growSlice` | 1.57MB |
| 10 | `encoding/json.(*decodeState).literalStore` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 243.58GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 112.95GB |
| 3 | `reflect.unsafe_NewArray` | 105.25GB |
| 4 | `reflect.MakeSlice` | 58.82GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 44.44GB |
| 6 | `segmentio/kafka-go.makeLayout` | 25.99GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 14.16GB |
| 8 | `database/sql.convertAssignRows` | 12.6GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 12.4GB |
| 10 | `internal/reflectlite.unsafe_New` | 11.86GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.37GB | 1.36GB | 1.27GB | 0B |
| `evaluation.mergeMetadata` | 595.15MB | 593.14MB | 551.08MB | 0B |
| `local.(*Client).EvaluateV2` | 2.34GB | 2.33GB | 2.17GB | 0B |
| `local.topologicalSort` | 343.56MB | 342.02MB | 321.28MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.42GB | 2.41GB | 2.24GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 231.29MB | 229.25MB | 219.33MB | 0B |
| `localEvaluation.getMapOfValue` | 2.42GB | 2.41GB | 2.24GB | 0B |
| `utils.ParseFeatureFlag` | 2.42GB | 2.41GB | 2.25GB | 0B |

**Total FF alloc (current snapshot):** 12.10GB  |  **24h avg:** 11.24GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1266/1268 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.67MB | 49/1268 | `███████░░░░░░░░ 50%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.15MB | 31/1268 | `██████░░░░░░░░░ 44%` |
| 4 | `runtime.mallocgc` | 13.34MB | 1262/1268 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 11.57MB | 51/1268 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1268 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1268 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1268 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1263/1268 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1268 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 98.93GB | 1258/1268 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1268 | `█████████░░░░░░ 64%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1268 | `█████████░░░░░░ 63%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1268 | `█████████░░░░░░ 63%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 51.55GB | 1198/1268 | `███████░░░░░░░░ 52%` |
| 6 | `reflect.unsafe_NewArray` | 42.82GB | 1257/1268 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1268 | `█████░░░░░░░░░░ 34%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1268 | `█████░░░░░░░░░░ 34%` |
| 9 | `reflect.MakeSlice` | 24.09GB | 1248/1268 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 22.53GB | 1195/1268 | `███░░░░░░░░░░░░ 22%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
