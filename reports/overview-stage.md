# Overview: stage
*Last updated: 2026-06-17 12:02 IST*
*Data range: 2026-05-15T16:03 to 2026-06-17T12:02 (1596 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,067 | avg: 14,193 | max: 28,205 | trend: stable (-0.23/hr))
```
▁▁▁▁▁▁▂▁▁▁▁▇█▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 105.6MB | avg: 159.9MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▂▂▄▃▄▁▂▄▂▃▂▅▅▄▁▁▂▃▂▄▁▁▂▃▃▂▁▂▂▁▄▁▄▄▅▂▂▆▃▃▁▁▃▂▂▄▁▂▃▄▄▃▁▂▁▁▁▁▁▄▁▁▁▁▃▂▂▄▄▃▁▃▁▁▄▃▂▁▂▁▃▃▁▃█▃▃▂▁▁▃▂▁▂▃▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,067 | 14,067 | +0 | 14,193 | 28,205 | stable (-0.23/hr) |
| Heap InUse | 105.6MB | 149.9MB | -44.3MB | 159.9MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 1003.6MB | 1003.6MB | +0.0MB | 1159.3MB | 1805.8MB | |
| Heap Objects | 422,042 | 937,432 | -515390 | 876,036 | 2,707,946 | |

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
| 2026-06-16 | 47 | 14,139 | 142.5MB | 226.4MB |
| 2026-06-17 | 25 | 14,131 | 140.7MB | 267.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 8.58MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.51MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `reflect.mapassign_faststr0` | 2.0MB |
| 8 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 9 | `reflect.unsafe_NewArray` | 2.0MB |
| 10 | `compress/flate.NewWriter` | 1.76MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 34.62GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 19.22GB |
| 3 | `reflect.unsafe_NewArray` | 14.9GB |
| 4 | `reflect.MakeSlice` | 8.41GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 7.85GB |
| 6 | `segmentio/kafka-go.makeLayout` | 3.78GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.54GB |
| 8 | `database/sql.convertAssignRows` | 2.29GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 1.92GB |
| 10 | `internal/reflectlite.unsafe_New` | 1.67GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 212.68MB | 211.60MB | 121.90MB | 0B |
| `evaluation.mergeMetadata` | 99.02MB | 99.02MB | 56.24MB | 0B |
| `local.(*Client).EvaluateV2` | 353.61MB | 351.99MB | 207.39MB | 0B |
| `local.topologicalSort` | 49.19MB | 49.19MB | 28.96MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 349.30MB | 347.16MB | 204.48MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 44.00MB | 44.00MB | 28.37MB | 0B |
| `localEvaluation.getMapOfValue` | 349.30MB | 347.16MB | 204.48MB | 0B |
| `utils.ParseFeatureFlag` | 350.80MB | 348.66MB | 205.17MB | 0B |

**Total FF alloc (current snapshot):** 1.77GB  |  **24h avg:** 1.03GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1594/1596 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.66MB | 57/1596 | `███████░░░░░░░░ 50%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 15.47MB | 35/1596 | `██████░░░░░░░░░ 42%` |
| 4 | `runtime.mallocgc` | 12.52MB | 1590/1596 | `█████░░░░░░░░░░ 34%` |
| 5 | `database/sql.convertAssignRows` | 11.42MB | 59/1596 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1596 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1596 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1596 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.21MB | 1591/1596 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1596 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 89.87GB | 1586/1596 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1596 | `██████████░░░░░ 70%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1596 | `██████████░░░░░ 70%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1596 | `██████████░░░░░ 69%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 48.25GB | 1453/1596 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 38.86GB | 1585/1596 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1596 | `█████░░░░░░░░░░ 38%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1596 | `█████░░░░░░░░░░ 37%` |
| 9 | `reflect.MakeSlice` | 21.83GB | 1576/1596 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.94GB | 1449/1596 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (4.0x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.6x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.4x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.5x avg)
