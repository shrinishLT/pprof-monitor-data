# Overview: stage
*Last updated: 2026-06-10 18:01 IST*
*Data range: 2026-05-15T16:03 to 2026-06-10T18:01 (1274 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,069 | avg: 14,206 | max: 28,205 | trend: stable (-0.30/hr))
```
█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▁▁▁▂▆▃▁▁▁▁▁▁▁▁▁▁▁▃▁▃▁▁▁▂▁▁▁▁▂▂▂▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▂▃▁▂▁▁▁▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁
```

**Heap InUse** (current: 132.4MB | avg: 163.3MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▄▃▁▁▁▃▁▃▁▁▂▁▃▃▄▂▃▄▃▁▁▁▄█▃▂▄▃▄▄▂▃▂▂▂▃▂▂▂▁▄▃▄▁▂▂▄▁▃▂▃▃▂▃▃▂▂▂▃▃▂▂▁▁▂▂▂▂▂▃▁▃▂▂▂▃▄▃▃▁▃▁▂▂▁▂▁▇▃▁▃▃▃▁▂▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,069 | 14,219 | -150 | 14,206 | 28,205 | stable (-0.30/hr) |
| Heap InUse | 132.4MB | 148.8MB | -16.4MB | 163.3MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 1262.9MB | 1262.9MB | +0.0MB | 1221.9MB | 1805.8MB | |
| Heap Objects | 691,462 | 790,857 | -99395 | 884,856 | 2,707,946 | |

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
| 2026-06-10 | 37 | 14,130 | 151.7MB | 275.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.5MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.unsafe_NewArray` | 2.02MB |
| 9 | `compress/flate.(*compressor).initDeflate` | 1.07MB |
| 10 | `aws/endpoints.init` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 249.12GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 113.56GB |
| 3 | `reflect.unsafe_NewArray` | 107.62GB |
| 4 | `reflect.MakeSlice` | 60.11GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 44.71GB |
| 6 | `segmentio/kafka-go.makeLayout` | 26.57GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 14.26GB |
| 8 | `v3/newrelic.newAnalyticsEvents` | 12.67GB |
| 9 | `database/sql.convertAssignRows` | 12.67GB |
| 10 | `internal/reflectlite.unsafe_New` | 12.12GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.43GB | 1.42GB | 1.30GB | 0B |
| `evaluation.mergeMetadata` | 618.15MB | 614.65MB | 563.80MB | 0B |
| `local.(*Client).EvaluateV2` | 2.45GB | 2.43GB | 2.22GB | 0B |
| `local.topologicalSort` | 357.76MB | 355.22MB | 327.58MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.52GB | 2.50GB | 2.30GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 254.30MB | 247.99MB | 223.90MB | 0B |
| `localEvaluation.getMapOfValue` | 2.52GB | 2.50GB | 2.30GB | 0B |
| `utils.ParseFeatureFlag` | 2.52GB | 2.51GB | 2.30GB | 0B |

**Total FF alloc (current snapshot):** 12.63GB  |  **24h avg:** 11.50GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1272/1274 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.67MB | 49/1274 | `███████░░░░░░░░ 50%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.15MB | 31/1274 | `██████░░░░░░░░░ 44%` |
| 4 | `runtime.mallocgc` | 13.34MB | 1268/1274 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 11.57MB | 51/1274 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1274 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1274 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1274 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1269/1274 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1274 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 99.63GB | 1264/1274 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1274 | `█████████░░░░░░ 64%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1274 | `█████████░░░░░░ 63%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1274 | `█████████░░░░░░ 62%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 51.86GB | 1204/1274 | `███████░░░░░░░░ 52%` |
| 6 | `reflect.unsafe_NewArray` | 43.12GB | 1263/1274 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1274 | `█████░░░░░░░░░░ 34%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1274 | `█████░░░░░░░░░░ 34%` |
| 9 | `reflect.MakeSlice` | 24.26GB | 1254/1274 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 22.64GB | 1201/1274 | `███░░░░░░░░░░░░ 22%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
