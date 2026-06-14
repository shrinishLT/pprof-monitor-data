# Overview: stage
*Last updated: 2026-06-14 18:03 IST*
*Data range: 2026-05-15T16:03 to 2026-06-14T18:03 (1465 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,081 | avg: 14,195 | max: 28,205 | trend: stable (-0.27/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▂▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▄▁▁▁▁▅▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▄▁▁▁▃▁▂▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁
```

**Heap InUse** (current: 138.9MB | avg: 161.1MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▅▁▄▅▂▄▁▁▃▂▂▃▂▂▄▂▁▁▄▅▁▁▁▁▆▄▂▃▄▄▁▁▃▃▄▂▃▃▁▄▁▄▅▂▄▃▂▄▃▁▁▄▁▂▂▁▄▃▁▄▃▃▂▄▁▃▁▃▄▃▃█▄▄▂▂▃▁▄▁▂▁▄▂▁▄▁▄▁▁▁▃▄▄▂▂
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,081 | 14,071 | +10 | 14,195 | 28,205 | stable (-0.27/hr) |
| Heap InUse | 138.9MB | 141.3MB | -2.4MB | 161.1MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 1267.9MB | 1267.9MB | +0.0MB | 1186.4MB | 1805.8MB | |
| Heap Objects | 742,872 | 782,786 | -39914 | 878,756 | 2,707,946 | |

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
| 2026-06-14 | 37 | 14,131 | 151.0MB | 247.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 10.01MB |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 9.5MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `dotlapse-event-service/workerpool.NewWorker` | 3.0MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.85MB |
| 7 | `compress/flate.NewWriter` | 2.64MB |
| 8 | `reflect.unsafe_NewArray` | 2.01MB |
| 9 | `aws/endpoints.init` | 2.01MB |
| 10 | `segmentio/kafka-go.makePartitions` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 127.39GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 61.81GB |
| 3 | `reflect.unsafe_NewArray` | 54.74GB |
| 4 | `reflect.MakeSlice` | 30.51GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 25.35GB |
| 6 | `segmentio/kafka-go.makeLayout` | 13.31GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 7.97GB |
| 8 | `database/sql.convertAssignRows` | 7.2GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 6.55GB |
| 10 | `internal/reflectlite.unsafe_New` | 6.25GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 615.84MB | 612.30MB | 536.18MB | 0B |
| `evaluation.mergeMetadata` | 272.57MB | 270.07MB | 237.93MB | 0B |
| `local.(*Client).EvaluateV2` | 1017.03MB | 1010.87MB | 883.40MB | 0B |
| `local.topologicalSort` | 131.13MB | 130.11MB | 113.07MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1001.02MB | 994.34MB | 860.74MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 129.88MB | 129.88MB | 119.97MB | 0B |
| `localEvaluation.getMapOfValue` | 1001.02MB | 994.34MB | 860.74MB | 0B |
| `utils.ParseFeatureFlag` | 1003.02MB | 996.34MB | 862.33MB | 0B |

**Total FF alloc (current snapshot):** 5.05GB  |  **24h avg:** 4.37GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1463/1465 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.99MB | 54/1465 | `███████░░░░░░░░ 51%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 15.55MB | 34/1465 | `██████░░░░░░░░░ 42%` |
| 4 | `runtime.mallocgc` | 12.85MB | 1459/1465 | `█████░░░░░░░░░░ 35%` |
| 5 | `database/sql.convertAssignRows` | 11.56MB | 56/1465 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1465 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1465 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1465 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1460/1465 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1465 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 93.23GB | 1455/1465 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1465 | `██████████░░░░░ 68%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1465 | `██████████░░░░░ 67%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1465 | `██████████░░░░░ 67%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 49.79GB | 1346/1465 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 40.32GB | 1454/1465 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1465 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1465 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 22.66GB | 1445/1465 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.66GB | 1342/1465 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.6x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.5x avg)
