# Overview: stage
*Last updated: 2026-06-04 03:02 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T03:02 (957 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,072 | avg: 14,225 | max: 28,205 | trend: stable (-0.39/hr))
```
▁▄▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▃▁▃▄▁█▃▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▂▂▁▃▁▅▁▁▁▁▁▁▁▁▁▁▁▁▃▁▄▁▂▁▁▂▄▁▁▁▂▁▁▅▁▁▁▁▁▂▁▁▁▁▁▁
```

**Heap InUse** (current: 136.2MB | avg: 166.6MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▃▄▁▂▄▁▄▅▃▃▃▃▁▃▄▁▂▂▂▂▄▃▄▃▁▅▄▂▃▂▃▄▄▃▄▄▅▃▄▁▂▅▃▄▄▂▃▄▂▂▃▃▁▃▃▄▁▂▂▂▁▂▁▄▂▄▂▄▄▁▄▂▂▁▁▄▃▂▂▄▃▂▂█▄▂▄▄▃▁▁▁▃▁▁▂
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,072 | 14,083 | -11 | 14,225 | 28,205 | stable (-0.39/hr) |
| Heap InUse | 136.2MB | 122.9MB | +13.3MB | 166.6MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 892.6MB | 891.4MB | +1.2MB | 1298.9MB | 1805.8MB | |
| Heap Objects | 714,791 | 567,249 | +147542 | 885,564 | 2,707,946 | |

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
| 2026-06-04 | 6 | 14,084 | 121.0MB | 157.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 8.5MB |
| 4 | `segmentio/kafka-go.makePartitions` | 4.51MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 3.5MB |
| 6 | `reflect.unsafe_NewArray` | 3.0MB |
| 7 | `aws/endpoints.init` | 2.5MB |
| 8 | `reflect.mapassign_faststr0` | 2.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 13.69GB |
| 2 | `segmentio/kafka-go.makePartitions` | 13.02GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 6.62GB |
| 4 | `reflect.unsafe_NewArray` | 5.73GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 4.46GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 4.46GB |
| 7 | `internal/evaluation.mergeMetadata` | 4.38GB |
| 8 | `reflect.MakeSlice` | 3.22GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 2.32GB |
| 10 | `experiment/local.topologicalSort` | 2.21GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 10.19GB | 10.17GB | 9.69GB | 0B |
| `evaluation.mergeMetadata` | 4.38GB | 4.36GB | 4.16GB | 0B |
| `local.(*Client).EvaluateV2` | 17.00GB | 16.96GB | 16.15GB | 0B |
| `local.topologicalSort` | 2.31GB | 2.31GB | 2.19GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 19.29GB | 19.25GB | 18.32GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 41.45MB | 41.45MB | 36.87MB | 0B |
| `localEvaluation.getMapOfValue` | 19.29GB | 19.25GB | 18.32GB | 0B |
| `utils.ParseFeatureFlag` | 202.31MB | 196.09MB | 166.61MB | 0B |

**Total FF alloc (current snapshot):** 72.71GB  |  **24h avg:** 69.03GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 955/957 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.96MB | 36/957 | `███████░░░░░░░░ 49%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.29MB | 24/957 | `███████░░░░░░░░ 47%` |
| 4 | `runtime.mallocgc` | 13.56MB | 951/957 | `█████░░░░░░░░░░ 37%` |
| 5 | `database/sql.convertAssignRows` | 12.13MB | 38/957 | `████░░░░░░░░░░░ 33%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/957 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/957 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/957 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 953/957 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/957 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 96.59GB | 948/957 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 68.1GB | 300/957 | `██████████░░░░░ 70%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 67.81GB | 299/957 | `██████████░░░░░ 70%` |
| 4 | `internal/evaluation.mergeMetadata` | 67.14GB | 294/957 | `██████████░░░░░ 69%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 51.0GB | 908/957 | `███████░░░░░░░░ 52%` |
| 6 | `reflect.unsafe_NewArray` | 41.79GB | 947/957 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.9GB | 289/957 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.8GB | 295/957 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 23.53GB | 939/957 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 23.01GB | 906/957 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
