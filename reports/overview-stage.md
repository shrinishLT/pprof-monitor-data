# Overview: stage
*Last updated: 2026-06-05 13:32 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T13:32 (1026 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,097 | avg: 14,221 | max: 28,205 | trend: stable (-0.36/hr))
```
▁▅▁▂▁▁▂▄▂▁▁▃▂▁▆▁▁▁▁▁▂▁▁▁▁▁▁▁▃▂▁▁▁▆▁▁▁█▁▁▁▅▁▁▁▂▁▄▆▂▄▃▁▁▁▃▁▁▁▁▃▁▁▃▁▁▁▁▁▁▁▁▁▁▂▃▂▁▂▆▄▅▁▁▁▁▁▁▁▁▁▁▁▁▂▁
```

**Heap InUse** (current: 180.1MB | avg: 165.4MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▁▃▁▂▁▁▃▂▂▂▃▂▂▂▅▃▁▃▃▃▁▁▁▂▁▁▂▂▂▂▁▂▁▅▃▁▂▃▁▂▁▄▂▁▂▂▁▂▃▁▂▃▃▂▂▂▃▂▂▁▁▁▁▁▂▂▁▂▁▁▁▂▂▁▁▂▃▂▂▃█▆▃▂▂▁▃▃▁▃▃▂▂▂▁▃
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,097 | 14,231 | -134 | 14,221 | 28,205 | stable (-0.36/hr) |
| Heap InUse | 180.1MB | 118.5MB | +61.6MB | 165.4MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 987.5MB | 987.3MB | +0.2MB | 1250.0MB | 1805.8MB | |
| Heap Objects | 1,229,061 | 452,334 | +776727 | 881,817 | 2,707,946 | |

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
| 2026-06-05 | 28 | 14,140 | 157.0MB | 338.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 8 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.0MB |
| 9 | `reflect.mapassign_faststr0` | 1.5MB |
| 10 | `reflect.unsafe_NewArray` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 23.08GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 16.83GB |
| 3 | `reflect.unsafe_NewArray` | 10.09GB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 6.55GB |
| 5 | `reflect.MakeSlice` | 5.63GB |
| 6 | `segmentio/kafka-go.makeLayout` | 2.48GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.04GB |
| 8 | `database/sql.convertAssignRows` | 1.78GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 1.27GB |
| 10 | `internal/reflectlite.unsafe_New` | 1.11GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 115.82MB | 106.38MB | 368.90MB | 0B |
| `evaluation.mergeMetadata` | 45.01MB | 42.51MB | 157.40MB | 0B |
| `local.(*Client).EvaluateV2` | 212.23MB | 194.85MB | 626.87MB | 0B |
| `local.topologicalSort` | 36.10MB | 33.57MB | 87.06MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 229.70MB | 212.28MB | 692.60MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 13.50MB | 11.99MB | 17.93MB | 0B |
| `localEvaluation.getMapOfValue` | 229.70MB | 212.28MB | 692.60MB | 0B |
| `utils.ParseFeatureFlag` | 230.70MB | 213.28MB | 120.37MB | 0B |

**Total FF alloc (current snapshot):** 1.09GB  |  **24h avg:** 2.70GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1024/1026 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.43MB | 40/1026 | `███████░░░░░░░░ 50%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.36MB | 26/1026 | `███████░░░░░░░░ 47%` |
| 4 | `runtime.mallocgc` | 13.4MB | 1020/1026 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 12.04MB | 42/1026 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1026 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1026 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1026 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1021/1026 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1026 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 90.69GB | 1016/1026 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1026 | `██████████░░░░░ 70%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1026 | `██████████░░░░░ 69%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1026 | `██████████░░░░░ 69%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 48.91GB | 956/1026 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 39.24GB | 1015/1026 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1026 | `█████░░░░░░░░░░ 37%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1026 | `█████░░░░░░░░░░ 37%` |
| 9 | `reflect.MakeSlice` | 22.1GB | 1006/1026 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 22.08GB | 953/1026 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
