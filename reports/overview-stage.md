# Overview: stage
*Last updated: 2026-06-10 05:01 IST*
*Data range: 2026-05-15T16:03 to 2026-06-10T05:01 (1248 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,088 | avg: 14,208 | max: 28,205 | trend: stable (-0.30/hr))
```
▁▂▄▁▁▁▁▁▁▁▂▁▁▁▁▂▁▃▁▃▁▁▁▁█▁▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▂▄▂▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁
```

**Heap InUse** (current: 161.9MB | avg: 163.5MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▃▇▃▂▁▂▃▂▂▂▃▂▁▄▂▂▁▄▂▃▃▂▄▂▃▂▄▃▁▁▁▃▁▃▁▁▂▁▃▃▄▂▃▄▃▁▁▁▄█▃▂▄▃▄▄▂▃▂▂▂▃▂▂▂▁▄▃▄▁▂▂▄▁▃▂▃▃▂▃▃▂▂▂▃▃▂▂▁▁▂▂▂▂▂▃
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,088 | 14,210 | -122 | 14,208 | 28,205 | stable (-0.30/hr) |
| Heap InUse | 161.9MB | 148.0MB | +13.9MB | 163.5MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 1238.8MB | 1238.8MB | +0.0MB | 1221.1MB | 1805.8MB | |
| Heap Objects | 1,045,086 | 807,462 | +237624 | 885,182 | 2,707,946 | |

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
| 2026-06-10 | 11 | 14,153 | 145.0MB | 175.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.unsafe_NewArray` | 1.51MB |
| 9 | `compress/flate.(*compressor).initDeflate` | 1.07MB |
| 10 | `bufio.NewReaderSize` | 1.02MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 225.26GB |
| 2 | `reflect.unsafe_NewArray` | 97.38GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 94.92GB |
| 4 | `reflect.MakeSlice` | 54.45GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 37.33GB |
| 6 | `segmentio/kafka-go.makeLayout` | 24.02GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 11.94GB |
| 8 | `v3/newrelic.newAnalyticsEvents` | 11.53GB |
| 9 | `internal/reflectlite.unsafe_New` | 10.94GB |
| 10 | `database/sql.convertAssignRows` | 10.6GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.28GB | 1.28GB | 1.17GB | 0B |
| `evaluation.mergeMetadata` | 553.13MB | 553.13MB | 510.07MB | 0B |
| `local.(*Client).EvaluateV2` | 2.19GB | 2.18GB | 2.01GB | 0B |
| `local.topologicalSort` | 322.23MB | 321.72MB | 301.65MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.26GB | 2.26GB | 2.08GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 217.78MB | 217.78MB | 204.34MB | 0B |
| `localEvaluation.getMapOfValue` | 2.26GB | 2.26GB | 2.08GB | 0B |
| `utils.ParseFeatureFlag` | 2.27GB | 2.26GB | 2.08GB | 0B |

**Total FF alloc (current snapshot):** 11.33GB  |  **24h avg:** 10.41GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1246/1248 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.26MB | 48/1248 | `███████░░░░░░░░ 49%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.15MB | 31/1248 | `██████░░░░░░░░░ 44%` |
| 4 | `runtime.mallocgc` | 13.35MB | 1242/1248 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 11.61MB | 50/1248 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1248 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1248 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1248 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1243/1248 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1248 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 96.73GB | 1238/1248 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1248 | `█████████░░░░░░ 65%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1248 | `█████████░░░░░░ 65%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1248 | `█████████░░░░░░ 64%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 50.56GB | 1178/1248 | `███████░░░░░░░░ 52%` |
| 6 | `reflect.unsafe_NewArray` | 41.87GB | 1237/1248 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1248 | `█████░░░░░░░░░░ 35%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1248 | `█████░░░░░░░░░░ 35%` |
| 9 | `reflect.MakeSlice` | 23.56GB | 1228/1248 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 22.18GB | 1175/1248 | `███░░░░░░░░░░░░ 22%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
