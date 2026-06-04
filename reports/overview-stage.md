# Overview: stage
*Last updated: 2026-06-04 09:31 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T09:31 (970 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,075 | avg: 14,225 | max: 28,205 | trend: stable (-0.38/hr))
```
▁▁▁▁▁▁▁▃▁▃▄▁█▃▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▂▂▁▃▁▅▁▁▁▁▁▁▁▁▁▁▁▁▃▁▄▁▂▁▁▂▄▁▁▁▂▁▁▅▁▁▁▁▁▂▁▁▁▁▁▁▁▂▂▁▁▁▅▁▁▁▆▁▁
```

**Heap InUse** (current: 147.7MB | avg: 166.4MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▃▄▁▂▂▂▂▄▃▄▃▁▅▄▂▃▂▃▄▄▃▄▄▅▃▄▁▂▅▃▄▄▂▃▄▂▂▃▃▁▃▃▄▁▂▂▂▁▂▁▄▂▄▂▄▄▁▄▂▂▁▁▄▃▂▂▄▃▂▂█▄▂▄▄▃▁▁▁▃▁▁▂▃▃▂▂▂▁▇▃▁▃▅▁▃
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,075 | 14,079 | -4 | 14,225 | 28,205 | stable (-0.38/hr) |
| Heap InUse | 147.7MB | 115.0MB | +32.7MB | 166.4MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 835.5MB | 835.5MB | +0.0MB | 1288.8MB | 1805.8MB | |
| Heap Objects | 986,870 | 557,340 | +429530 | 884,930 | 2,707,946 | |

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
| 2026-06-04 | 19 | 14,158 | 142.1MB | 258.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 10.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `compress/flate.NewWriter` | 4.41MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `reflect.unsafe_NewArray` | 1.5MB |
| 10 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 14.08GB |
| 2 | `segmentio/kafka-go.makePartitions` | 10.3GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 6.9GB |
| 4 | `reflect.unsafe_NewArray` | 4.51GB |
| 5 | `experiment/local.(*Client).EvaluateV2` | 3.28GB |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 3.28GB |
| 7 | `internal/evaluation.mergeMetadata` | 3.16GB |
| 8 | `reflect.MakeSlice` | 2.47GB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.12GB |
| 10 | `database/sql.convertAssignRows` | 1.94GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 7.42GB | 7.42GB | 5.71GB | 0B |
| `evaluation.mergeMetadata` | 3.16GB | 3.16GB | 2.44GB | 0B |
| `local.(*Client).EvaluateV2` | 12.46GB | 12.44GB | 9.54GB | 0B |
| `local.topologicalSort` | 1.72GB | 1.72GB | 1.31GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 14.19GB | 14.18GB | 10.84GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 17.06MB | 17.06MB | 16.96MB | 0B |
| `localEvaluation.getMapOfValue` | 14.19GB | 14.18GB | 10.84GB | 0B |
| `utils.ParseFeatureFlag` | 136.26MB | 123.75MB | 100.60MB | 0B |

**Total FF alloc (current snapshot):** 53.29GB  |  **24h avg:** 40.80GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 968/970 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.9MB | 37/970 | `███████░░░░░░░░ 48%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.29MB | 24/970 | `███████░░░░░░░░ 47%` |
| 4 | `runtime.mallocgc` | 13.51MB | 964/970 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 12.06MB | 39/970 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/970 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/970 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/970 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 966/970 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/970 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 95.35GB | 961/970 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 65.76GB | 311/970 | `██████████░░░░░ 68%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 65.05GB | 312/970 | `██████████░░░░░ 68%` |
| 4 | `internal/evaluation.mergeMetadata` | 64.57GB | 306/970 | `██████████░░░░░ 67%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 50.71GB | 915/970 | `███████░░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 41.26GB | 960/970 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.67GB | 291/970 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.57GB | 297/970 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 23.25GB | 951/970 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 22.88GB | 913/970 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
