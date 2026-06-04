# Overview: stage
*Last updated: 2026-06-04 16:03 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T16:03 (983 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,075 | avg: 14,225 | max: 28,205 | trend: stable (-0.36/hr))
```
▄▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▂▂▁▄▁▆▁▁▁▁▁▁▁▁▁▁▁▁▄▁▅▁▂▁▁▂▄▁▁▁▃▂▁▆▁▁▁▁▁▂▁▁▁▁▁▁▁▃▂▁▁▁▆▁▁▁█▁▁▁▅▁▁▁▂▁▄▆▂▄▃▁
```

**Heap InUse** (current: 173.9MB | avg: 166.1MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▄▂▃▂▃▄▄▃▄▄▅▃▄▂▂▅▃▄▄▃▃▄▂▂▃▃▁▃▃▄▁▂▂▂▁▂▁▄▂▄▂▄▄▁▄▂▂▁▁▄▃▂▂▄▃▂▂█▄▂▄▄▃▁▁▁▃▁▂▂▃▃▂▂▂▁▇▃▁▃▅▁▃▁▅▂▁▂▂▁▃▅▁▂▃▄
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,075 | 14,266 | -191 | 14,225 | 28,205 | stable (-0.36/hr) |
| Heap InUse | 173.9MB | 167.6MB | +6.3MB | 166.1MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 338.1MB | 228.8MB | +109.3MB | 1278.9MB | 1805.8MB | |
| Heap Objects | 1,280,166 | 968,404 | +311762 | 883,113 | 2,707,946 | |

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
| 2026-06-04 | 32 | 14,186 | 142.3MB | 258.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 16.24MB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB |
| 4 | `runtime.mallocgc` | 12.01MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `database/sql.convertAssignRows` | 8.5MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.51MB |
| 9 | `reflect.unsafe_NewArray` | 2.5MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 1.04GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 705.79MB |
| 3 | `reflect.unsafe_NewArray` | 534.71MB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 294.3MB |
| 5 | `reflect.MakeSlice` | 286.01MB |
| 6 | `segmentio/kafka-go.makeLayout` | 118.55MB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 98.5MB |
| 8 | `database/sql.convertAssignRows` | 77.5MB |
| 9 | `compress/flate.NewWriter` | 62.58MB |
| 10 | `v3/newrelic.newAnalyticsEvents` | 60.97MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 23.08MB | 6.16MB | 5.39GB | 0B |
| `evaluation.mergeMetadata` | 11.00MB | 3.50MB | 2.30GB | 0B |
| `local.(*Client).EvaluateV2` | 36.20MB | 11.91MB | 9.02GB | 0B |
| `local.topologicalSort` | 4.57MB | 2.04MB | 1.24GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 30.57MB | 12.90MB | 10.25GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 8.71MB | 1.05MB | 17.45MB | 0B |
| `localEvaluation.getMapOfValue` | 30.57MB | 12.90MB | 10.25GB | 0B |
| `utils.ParseFeatureFlag` | 30.57MB | 12.90MB | 99.62MB | 0B |

**Total FF alloc (current snapshot):** 175.28MB  |  **24h avg:** 38.55GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 981/983 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.86MB | 38/983 | `███████░░░░░░░░ 48%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.24MB | 25/983 | `███████░░░░░░░░ 47%` |
| 4 | `runtime.mallocgc` | 13.45MB | 977/983 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 11.97MB | 40/983 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/983 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/983 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/983 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 978/983 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/983 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 94.26GB | 973/983 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/983 | `██████████░░░░░ 67%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/983 | `██████████░░░░░ 66%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/983 | `█████████░░░░░░ 66%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 50.26GB | 925/983 | `███████░░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 40.79GB | 972/983 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/983 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/983 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 22.98GB | 963/983 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 22.71GB | 922/983 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
