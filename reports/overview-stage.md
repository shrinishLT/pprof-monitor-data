# Overview: stage
*Last updated: 2026-06-07 06:00 IST*
*Data range: 2026-05-15T16:03 to 2026-06-07T06:00 (1107 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,360 | avg: 14,214 | max: 28,205 | trend: stable (-0.36/hr))
```
▅▁▁▁▁▁▁▁▁▁▁▁▁▃▁▂▁▁▂▃█▁▁▁▁▄▃▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▄▂▄▄▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▅▃▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▅
```

**Heap InUse** (current: 243.7MB | avg: 164.3MB | max: 732.9MB | trend: stable (-0.05MB/hr))
```
█▃▂▂▁▃▃▁▃▃▂▂▂▁▃▆▃▂▂▃▂▄▃▂▃▁▂▃▂▄▁▂▁▁▁▃▁▃▂▃▁▂▁▁▃▁▁▅▂▂▁▁▁▂▃▃▂▁▁▂▃▁▁▂▁▃▄▄▃▁▂▂▁▂▂▂▃▃▂▂▁▃▁▁▃▃▃▁▂▁▂▁▃▄▁▆
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 13%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,360 | 14,065 | +295 | 14,214 | 28,205 | stable (-0.36/hr) |
| Heap InUse | 243.7MB | 112.3MB | +131.4MB | 164.3MB | 732.9MB | stable (-0.05MB/hr) |
| Heap Sys | 1096.2MB | 988.7MB | +107.5MB | 1231.0MB | 1805.8MB | |
| Heap Objects | 869,887 | 418,411 | +451476 | 880,145 | 2,707,946 | |

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
| 2026-06-07 | 13 | 14,102 | 156.7MB | 243.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 16.39MB |
| 3 | `runtime.mallocgc` | 13.1MB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 10.24MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 7 | `database/sql.convertAssignRows` | 8.5MB |
| 8 | `bytes.growSlice` | 2.51MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 95.95GB |
| 2 | `reflect.unsafe_NewArray` | 41.61GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 38.9GB |
| 4 | `reflect.MakeSlice` | 23.35GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 15.29GB |
| 6 | `segmentio/kafka-go.makeLayout` | 10.34GB |
| 7 | `v3/newrelic.newAnalyticsEvents` | 5.0GB |
| 8 | `go-sql-driver/mysql.(*binaryRows).readRow` | 4.86GB |
| 9 | `internal/reflectlite.unsafe_New` | 4.69GB |
| 10 | `database/sql.convertAssignRows` | 4.28GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 572.73MB | 567.64MB | 491.09MB | 0B |
| `evaluation.mergeMetadata` | 243.06MB | 240.56MB | 207.09MB | 0B |
| `local.(*Client).EvaluateV2` | 991.91MB | 985.26MB | 850.26MB | 0B |
| `local.topologicalSort` | 154.11MB | 153.60MB | 130.71MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1011.23MB | 1004.57MB | 860.79MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 101.89MB | 101.39MB | 93.03MB | 0B |
| `localEvaluation.getMapOfValue` | 1011.23MB | 1004.57MB | 860.79MB | 0B |
| `utils.ParseFeatureFlag` | 1012.73MB | 1006.07MB | 862.09MB | 0B |

**Total FF alloc (current snapshot):** 4.98GB  |  **24h avg:** 4.25GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1105/1107 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.16MB | 44/1107 | `███████░░░░░░░░ 49%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.42MB | 29/1107 | `██████░░░░░░░░░ 44%` |
| 4 | `runtime.mallocgc` | 13.38MB | 1101/1107 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 11.82MB | 46/1107 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1107 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1107 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1107 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1102/1107 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1107 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 88.41GB | 1097/1107 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1107 | `██████████░░░░░ 72%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1107 | `██████████░░░░░ 71%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1107 | `██████████░░░░░ 70%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 47.35GB | 1037/1107 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 38.26GB | 1096/1107 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1107 | `█████░░░░░░░░░░ 38%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1107 | `█████░░░░░░░░░░ 38%` |
| 9 | `reflect.MakeSlice` | 21.54GB | 1087/1107 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.24GB | 1034/1107 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
