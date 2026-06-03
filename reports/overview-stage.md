# Overview: stage
*Last updated: 2026-06-04 02:30 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T02:30 (956 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,083 | avg: 14,225 | max: 28,205 | trend: stable (-0.39/hr))
```
▁▁▄▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▃▁▃▄▁█▃▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▂▂▁▃▁▅▁▁▁▁▁▁▁▁▁▁▁▁▃▁▄▁▂▁▁▂▄▁▁▁▂▁▁▅▁▁▁▁▁▂▁▁▁▁▁
```

**Heap InUse** (current: 122.9MB | avg: 166.6MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▂▃▄▁▂▄▁▄▅▃▃▃▃▁▃▄▁▂▂▂▂▄▃▄▃▁▅▄▂▃▂▃▄▄▃▄▄▅▃▄▁▂▅▃▄▄▂▃▄▂▂▃▃▁▃▃▄▁▂▂▂▁▂▁▄▂▄▂▄▄▁▄▂▂▁▁▄▃▂▂▄▃▂▂█▄▂▄▄▃▁▁▁▃▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,083 | 14,066 | +17 | 14,225 | 28,205 | stable (-0.39/hr) |
| Heap InUse | 122.9MB | 100.0MB | +22.9MB | 166.6MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 891.4MB | 895.8MB | -4.4MB | 1299.3MB | 1805.8MB | |
| Heap Objects | 567,249 | 339,658 | +227591 | 885,743 | 2,707,946 | |

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
| 2026-06-04 | 5 | 14,086 | 118.0MB | 157.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 8.5MB |
| 4 | `compress/flate.NewWriter` | 3.53MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 3.5MB |
| 7 | `reflect.unsafe_NewArray` | 2.51MB |
| 8 | `aws/endpoints.init` | 2.5MB |
| 9 | `reflect.mapassign_faststr0` | 2.5MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 13.69GB |
| 2 | `segmentio/kafka-go.makePartitions` | 12.1GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 6.62GB |
| 4 | `reflect.unsafe_NewArray` | 5.32GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 4.45GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 4.45GB |
| 7 | `internal/evaluation.mergeMetadata` | 4.36GB |
| 8 | `reflect.MakeSlice` | 2.99GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 2.31GB |
| 10 | `experiment/local.topologicalSort` | 2.2GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 10.17GB | 10.13GB | 9.60GB | 0B |
| `evaluation.mergeMetadata` | 4.36GB | 4.35GB | 4.13GB | 0B |
| `local.(*Client).EvaluateV2` | 16.96GB | 16.90GB | 16.00GB | 0B |
| `local.topologicalSort` | 2.31GB | 2.30GB | 2.18GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 19.25GB | 19.18GB | 18.16GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 41.45MB | 41.45MB | 36.10MB | 0B |
| `localEvaluation.getMapOfValue` | 19.25GB | 19.18GB | 18.16GB | 0B |
| `utils.ParseFeatureFlag` | 196.09MB | 174.20MB | 160.66MB | 0B |

**Total FF alloc (current snapshot):** 72.53GB  |  **24h avg:** 68.42GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 954/956 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.96MB | 36/956 | `███████░░░░░░░░ 49%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.29MB | 24/956 | `███████░░░░░░░░ 47%` |
| 4 | `runtime.mallocgc` | 13.57MB | 950/956 | `█████░░░░░░░░░░ 37%` |
| 5 | `database/sql.convertAssignRows` | 12.13MB | 38/956 | `████░░░░░░░░░░░ 33%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/956 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/956 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/956 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 952/956 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/956 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 96.67GB | 947/956 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 68.31GB | 299/956 | `██████████░░░░░ 70%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 68.02GB | 298/956 | `██████████░░░░░ 70%` |
| 4 | `internal/evaluation.mergeMetadata` | 67.35GB | 293/956 | `██████████░░░░░ 69%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 51.04GB | 907/956 | `███████░░░░░░░░ 52%` |
| 6 | `reflect.unsafe_NewArray` | 41.83GB | 946/956 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 35.02GB | 288/956 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.91GB | 294/956 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 23.55GB | 938/956 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 23.03GB | 905/956 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
