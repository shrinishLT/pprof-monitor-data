# Overview: stage
*Last updated: 2026-06-07 05:02 IST*
*Data range: 2026-05-15T16:03 to 2026-06-07T05:02 (1105 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,077 | avg: 14,214 | max: 28,205 | trend: stable (-0.36/hr))
```
▇▄▅▁▁▁▁▁▁▁▁▁▁▁▁▃▁▂▁▁▂▃█▁▁▁▁▄▃▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▄▂▄▄▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▅▃▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁
```

**Heap InUse** (current: 187.1MB | avg: 164.3MB | max: 732.9MB | trend: stable (-0.05MB/hr))
```
▂█▆▃▂▂▁▂▃▁▃▃▂▂▂▁▃▅▂▂▂▃▂▃▃▂▂▁▂▃▂▃▁▂▁▁▁▂▁▂▁▂▁▂▁▁▃▁▁▄▂▂▁▁▁▂▂▃▂▁▁▂▂▁▁▂▁▂▃▃▂▁▂▂▁▂▁▂▃▂▂▂▁▂▁▁▂▂▃▁▂▁▂▁▃▃
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,077 | 14,091 | -14 | 14,214 | 28,205 | stable (-0.36/hr) |
| Heap InUse | 187.1MB | 173.5MB | +13.6MB | 164.3MB | 732.9MB | stable (-0.05MB/hr) |
| Heap Sys | 988.7MB | 988.5MB | +0.2MB | 1231.3MB | 1805.8MB | |
| Heap Objects | 1,407,014 | 1,192,562 | +214452 | 880,572 | 2,707,946 | |

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
| 2026-06-07 | 11 | 14,082 | 152.8MB | 187.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `reflect.unsafe_NewArray` | 2.51MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `compress/flate.NewWriter` | 1.76MB |
| 9 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 1.5MB |
| 10 | `reflect.unsafe_New` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 94.16GB |
| 2 | `reflect.unsafe_NewArray` | 40.81GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 36.99GB |
| 4 | `reflect.MakeSlice` | 22.9GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 14.53GB |
| 6 | `segmentio/kafka-go.makeLayout` | 10.16GB |
| 7 | `v3/newrelic.newAnalyticsEvents` | 4.9GB |
| 8 | `go-sql-driver/mysql.(*binaryRows).readRow` | 4.64GB |
| 9 | `internal/reflectlite.unsafe_New` | 4.6GB |
| 10 | `database/sql.convertAssignRows` | 4.07GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 567.14MB | 562.42MB | 482.81MB | 0B |
| `evaluation.mergeMetadata` | 240.06MB | 239.56MB | 203.55MB | 0B |
| `local.(*Client).EvaluateV2` | 983.17MB | 977.43MB | 835.84MB | 0B |
| `local.topologicalSort` | 153.08MB | 152.07MB | 128.37MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1001.96MB | 995.71MB | 845.66MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 101.39MB | 101.39MB | 91.89MB | 0B |
| `localEvaluation.getMapOfValue` | 1001.96MB | 995.71MB | 845.66MB | 0B |
| `utils.ParseFeatureFlag` | 1003.46MB | 997.21MB | 846.94MB | 0B |

**Total FF alloc (current snapshot):** 4.93GB  |  **24h avg:** 4.18GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1103/1105 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.2MB | 43/1105 | `███████░░░░░░░░ 49%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.64MB | 28/1105 | `██████░░░░░░░░░ 45%` |
| 4 | `runtime.mallocgc` | 13.38MB | 1099/1105 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 11.89MB | 45/1105 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1105 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1105 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1105 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1100/1105 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1105 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 88.4GB | 1095/1105 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1105 | `██████████░░░░░ 72%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1105 | `██████████░░░░░ 71%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1105 | `██████████░░░░░ 70%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 47.37GB | 1035/1105 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 38.26GB | 1094/1105 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1105 | `█████░░░░░░░░░░ 38%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1105 | `█████░░░░░░░░░░ 38%` |
| 9 | `reflect.MakeSlice` | 21.54GB | 1085/1105 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.25GB | 1032/1105 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
