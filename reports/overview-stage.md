# Overview: stage
*Last updated: 2026-06-03 23:30 IST*
*Data range: 2026-05-15T16:03 to 2026-06-03T23:30 (951 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,179 | avg: 14,226 | max: 28,205 | trend: stable (-0.38/hr))
```
▁▁▁▁▅▁▁▄▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▃▁▃▄▁█▃▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▂▂▁▃▁▅▁▁▁▁▁▁▁▁▁▁▁▁▃▁▄▁▂▁▁▂▄▁▁▁▂▁▁▅▁▁▁▁▁▂
```

**Heap InUse** (current: 116.5MB | avg: 166.9MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▂▃▃▃▂▂▃▄▁▂▃▁▄▄▂▃▃▃▁▃▄▁▁▁▁▂▃▃▄▃▁▅▃▂▃▂▃▄▃▂▃▄▄▃▄▁▂▄▃▄▄▂▃▄▂▂▃▃▁▃▃▄▁▂▂▁▁▂▁▃▁▄▂▃▄▁▄▁▁▁▁▄▃▂▂▄▃▂▂█▃▁▃▄▃▁
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,179 | 14,068 | +111 | 14,226 | 28,205 | stable (-0.38/hr) |
| Heap InUse | 116.5MB | 166.8MB | -50.3MB | 166.9MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 898.7MB | 899.7MB | -1.0MB | 1301.4MB | 1805.8MB | |
| Heap Objects | 457,730 | 1,193,651 | -735921 | 887,634 | 2,707,946 | |

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

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 6.58MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 3.5MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `aws/endpoints.init` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 10 | `reflect.mapassign_faststr0` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 12.63GB |
| 2 | `segmentio/kafka-go.makePartitions` | 6.74GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 6.1GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 3.6GB |
| 5 | `experiment/local.(*Client).EvaluateV2` | 3.58GB |
| 6 | `internal/evaluation.mergeMetadata` | 3.55GB |
| 7 | `reflect.unsafe_NewArray` | 3.03GB |
| 8 | `go-sql-driver/mysql.(*binaryRows).readRow` | 1.9GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 1.86GB |
| 10 | `experiment/local.topologicalSort` | 1.77GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 8.25GB | 0B | 8.25GB | 0B |
| `evaluation.mergeMetadata` | 3.55GB | 0B | 3.55GB | 0B |
| `local.(*Client).EvaluateV2` | 13.72GB | 0B | 13.72GB | 553.04kB |
| `local.topologicalSort` | 1.85GB | 0B | 1.85GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 15.57GB | 0B | 15.57GB | 553.04kB |
| `localEvaluation.GetFeatureFlagPayload` | 26.45MB | 0B | 26.45MB | 0B |
| `localEvaluation.getMapOfValue` | 15.57GB | 0B | 15.57GB | 553.04kB |
| `utils.ParseFeatureFlag` | 129.09MB | 0B | 129.09MB | 0B |

**Total FF alloc (current snapshot):** 58.65GB  |  **24h avg:** 58.65GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 949/951 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.96MB | 36/951 | `███████░░░░░░░░ 49%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.29MB | 24/951 | `███████░░░░░░░░ 47%` |
| 4 | `runtime.mallocgc` | 13.6MB | 945/951 | `█████░░░░░░░░░░ 37%` |
| 5 | `database/sql.convertAssignRows` | 12.13MB | 38/951 | `████░░░░░░░░░░░ 33%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/951 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/951 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/951 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 947/951 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/951 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 97.13GB | 942/951 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 69.4GB | 294/951 | `██████████░░░░░ 71%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 69.11GB | 293/951 | `██████████░░░░░ 71%` |
| 4 | `internal/evaluation.mergeMetadata` | 68.45GB | 288/951 | `██████████░░░░░ 70%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 51.25GB | 902/951 | `███████░░░░░░░░ 52%` |
| 6 | `reflect.unsafe_NewArray` | 42.03GB | 941/951 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 35.6GB | 283/951 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 35.48GB | 289/951 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 23.67GB | 933/951 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 23.12GB | 900/951 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
