# Overview: stage
*Last updated: 2026-06-04 09:03 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T09:02 (969 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,079 | avg: 14,225 | max: 28,205 | trend: stable (-0.38/hr))
```
▁▁▁▁▁▁▁▁▃▁▃▄▁█▃▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▂▂▁▃▁▅▁▁▁▁▁▁▁▁▁▁▁▁▃▁▄▁▂▁▁▂▄▁▁▁▂▁▁▅▁▁▁▁▁▂▁▁▁▁▁▁▁▂▂▁▁▁▅▁▁▁▆▁
```

**Heap InUse** (current: 115.0MB | avg: 166.4MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▁▃▄▁▂▂▂▂▄▃▄▃▁▅▄▂▃▂▃▄▄▃▄▄▅▃▄▁▂▅▃▄▄▂▃▄▂▂▃▃▁▃▃▄▁▂▂▂▁▂▁▄▂▄▂▄▄▁▄▂▂▁▁▄▃▂▂▄▃▂▂█▄▂▄▄▃▁▁▁▃▁▁▂▃▃▂▂▂▁▇▃▁▃▅▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,079 | 14,693 | -614 | 14,225 | 28,205 | stable (-0.38/hr) |
| Heap InUse | 115.0MB | 192.8MB | -77.8MB | 166.4MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 835.5MB | 835.2MB | +0.3MB | 1289.2MB | 1805.8MB | |
| Heap Objects | 557,340 | 956,673 | -399333 | 884,825 | 2,707,946 | |

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
| 2026-06-04 | 18 | 14,163 | 141.8MB | 258.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 10.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `reflect.unsafe_NewArray` | 1.5MB |
| 10 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 14.08GB |
| 2 | `segmentio/kafka-go.makePartitions` | 9.43GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 6.9GB |
| 4 | `reflect.unsafe_NewArray` | 4.14GB |
| 5 | `experiment/local.(*Client).EvaluateV2` | 3.28GB |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 3.27GB |
| 7 | `internal/evaluation.mergeMetadata` | 3.16GB |
| 8 | `reflect.MakeSlice` | 2.25GB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.12GB |
| 10 | `database/sql.convertAssignRows` | 1.93GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 7.42GB | 6.70GB | 5.62GB | 0B |
| `evaluation.mergeMetadata` | 3.16GB | 2.85GB | 2.41GB | 0B |
| `local.(*Client).EvaluateV2` | 12.44GB | 11.26GB | 9.39GB | 0B |
| `local.topologicalSort` | 1.72GB | 1.56GB | 1.29GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 14.18GB | 12.82GB | 10.67GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 17.06MB | 14.47MB | 16.95MB | 0B |
| `localEvaluation.getMapOfValue` | 14.18GB | 12.82GB | 10.67GB | 0B |
| `utils.ParseFeatureFlag` | 123.75MB | 113.30MB | 98.72MB | 0B |

**Total FF alloc (current snapshot):** 53.23GB  |  **24h avg:** 40.14GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 967/969 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.9MB | 37/969 | `███████░░░░░░░░ 48%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.29MB | 24/969 | `███████░░░░░░░░ 47%` |
| 4 | `runtime.mallocgc` | 13.52MB | 963/969 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 12.06MB | 39/969 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/969 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/969 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/969 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 965/969 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/969 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 95.44GB | 960/969 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 65.96GB | 310/969 | `██████████░░░░░ 69%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 65.25GB | 311/969 | `██████████░░░░░ 68%` |
| 4 | `internal/evaluation.mergeMetadata` | 64.77GB | 305/969 | `██████████░░░░░ 67%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 50.75GB | 914/969 | `███████░░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 41.3GB | 959/969 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.67GB | 291/969 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.57GB | 297/969 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 23.27GB | 950/969 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 22.9GB | 912/969 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
