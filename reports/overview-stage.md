# Overview: stage
*Last updated: 2026-06-05 10:30 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T10:30 (1020 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,065 | avg: 14,222 | max: 28,205 | trend: stable (-0.36/hr))
```
▁▁▁▁▁▄▁▅▁▂▁▁▂▄▂▁▁▃▂▁▆▁▁▁▁▁▂▁▁▁▁▁▁▁▃▂▁▁▁▆▁▁▁█▁▁▁▅▁▁▁▂▁▄▆▂▄▃▁▁▁▃▁▁▁▁▃▁▁▃▁▁▁▁▁▁▁▁▁▁▂▃▂▁▂▆▄▅▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 181.4MB | avg: 165.5MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▃▂▃▂▃▃▁▃▁▂▁▁▃▂▂▂▃▂▂▂▅▃▁▃▃▃▁▁▁▂▁▁▂▂▂▂▁▂▁▅▃▁▂▃▁▂▁▄▂▁▂▂▁▂▃▁▂▃▃▂▂▂▃▂▂▁▁▁▁▁▂▂▁▂▁▁▁▂▂▁▁▂▃▂▂▃█▆▃▂▂▁▃▃▁▃
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,065 | 14,075 | -10 | 14,222 | 28,205 | stable (-0.36/hr) |
| Heap InUse | 181.4MB | 111.4MB | +70.0MB | 165.5MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 987.4MB | 987.4MB | +0.0MB | 1251.6MB | 1805.8MB | |
| Heap Objects | 1,339,484 | 437,047 | +902437 | 881,594 | 2,707,946 | |

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
| 2026-06-05 | 22 | 14,150 | 158.5MB | 338.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.01MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.unsafe_NewArray` | 2.01MB |
| 9 | `reflect.mapassign_faststr0` | 2.0MB |
| 10 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 17.66GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 16.09GB |
| 3 | `reflect.unsafe_NewArray` | 7.75GB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 6.26GB |
| 5 | `reflect.MakeSlice` | 4.27GB |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 1.93GB |
| 7 | `segmentio/kafka-go.makeLayout` | 1.91GB |
| 8 | `database/sql.convertAssignRows` | 1.7GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 1022.71MB |
| 10 | `internal/reflectlite.unsafe_New` | 874.08MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 86.27MB | 85.73MB | 1.06GB | 0B |
| `evaluation.mergeMetadata` | 35.51MB | 35.51MB | 463.31MB | 0B |
| `local.(*Client).EvaluateV2` | 159.14MB | 157.07MB | 1.79GB | 0B |
| `local.topologicalSort` | 25.95MB | 24.42MB | 252.38MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 173.47MB | 170.88MB | 2.02GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 9.90MB | 9.90MB | 19.06MB | 0B |
| `localEvaluation.getMapOfValue` | 173.47MB | 170.88MB | 2.02GB | 0B |
| `utils.ParseFeatureFlag` | 174.47MB | 171.88MB | 111.65MB | 0B |

**Total FF alloc (current snapshot):** 838.16MB  |  **24h avg:** 7.72GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1018/1020 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.43MB | 40/1020 | `███████░░░░░░░░ 50%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.36MB | 26/1020 | `███████░░░░░░░░ 47%` |
| 4 | `runtime.mallocgc` | 13.4MB | 1014/1020 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 12.04MB | 42/1020 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1020 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1020 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1020 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1015/1020 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1020 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 91.11GB | 1010/1020 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1020 | `██████████░░░░░ 70%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1020 | `██████████░░░░░ 69%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1020 | `██████████░░░░░ 68%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 49.12GB | 950/1020 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 39.42GB | 1009/1020 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1020 | `█████░░░░░░░░░░ 37%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1020 | `█████░░░░░░░░░░ 37%` |
| 9 | `reflect.MakeSlice` | 22.21GB | 1000/1020 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 22.18GB | 947/1020 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
