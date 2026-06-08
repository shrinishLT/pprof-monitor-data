# Overview: stage
*Last updated: 2026-06-08 16:01 IST*
*Data range: 2026-05-15T16:03 to 2026-06-08T16:01 (1174 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,136 | avg: 14,210 | max: 28,205 | trend: stable (-0.34/hr))
```
▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▃▅▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▄▁▂▄█▁▁▁▁▁▁▁▃▁▁▁▁▃▁▅▂▅▁▁
```

**Heap InUse** (current: 140.9MB | avg: 163.9MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▃▃▁▂▂▁▂▂▂▃▃▂▂▁▃▁▁▃▂▃▁▂▁▂▁▃▃▁▆█▁▃▄▂▃▁▂▁▂▃▃▁▃▃▁▃▃▃▂▁▃▃▃▂▁▁▂▃▃▄▃▁▂▃▂▃▁▃▃▁▁▂▃▄▃▆▃▂▁▂▃▂▂▂▃▂▁▃▂▂▁▃▂▃▃▂
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,136 | 14,068 | +68 | 14,210 | 28,205 | stable (-0.34/hr) |
| Heap InUse | 140.9MB | 171.8MB | -30.9MB | 163.9MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 1097.8MB | 1097.5MB | +0.3MB | 1223.4MB | 1805.8MB | |
| Heap Objects | 766,446 | 1,187,747 | -421301 | 883,928 | 2,707,946 | |

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
| 2026-06-08 | 33 | 14,189 | 156.5MB | 265.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `segmentio/kafka-go.makePartitions` | 5.0MB |
| 6 | `reflect.unsafe_NewArray` | 3.01MB |
| 7 | `reflect.mapassign_faststr0` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `compress/flate.NewWriter` | 1.76MB |
| 10 | `aws/endpoints.init` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 157.8GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 74.1GB |
| 3 | `reflect.unsafe_NewArray` | 68.36GB |
| 4 | `reflect.MakeSlice` | 38.24GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 29.05GB |
| 6 | `segmentio/kafka-go.makeLayout` | 16.76GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 9.24GB |
| 8 | `database/sql.convertAssignRows` | 8.21GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 8.16GB |
| 10 | `internal/reflectlite.unsafe_New` | 7.74GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 917.50MB | 903.57MB | 777.83MB | 0B |
| `evaluation.mergeMetadata` | 394.60MB | 390.60MB | 336.26MB | 0B |
| `local.(*Client).EvaluateV2` | 1.54GB | 1.52GB | 1.31GB | 0B |
| `local.topologicalSort` | 234.46MB | 231.42MB | 200.88MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.58GB | 1.56GB | 1.35GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 162.72MB | 158.62MB | 134.71MB | 0B |
| `localEvaluation.getMapOfValue` | 1.58GB | 1.56GB | 1.35GB | 0B |
| `utils.ParseFeatureFlag` | 1.59GB | 1.57GB | 1.35GB | 0B |

**Total FF alloc (current snapshot):** 7.97GB  |  **24h avg:** 6.77GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1172/1174 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.29MB | 47/1174 | `███████░░░░░░░░ 49%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.3MB | 30/1174 | `██████░░░░░░░░░ 44%` |
| 4 | `runtime.mallocgc` | 13.36MB | 1168/1174 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 11.54MB | 49/1174 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1174 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1174 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1174 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1169/1174 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1174 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 90.67GB | 1164/1174 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1174 | `██████████░░░░░ 70%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1174 | `██████████░░░░░ 69%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1174 | `██████████░░░░░ 69%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 48.14GB | 1104/1174 | `███████░░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 39.25GB | 1163/1174 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1174 | `█████░░░░░░░░░░ 37%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1174 | `█████░░░░░░░░░░ 37%` |
| 9 | `reflect.MakeSlice` | 22.09GB | 1154/1174 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.38GB | 1101/1174 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
