# Overview: stage
*Last updated: 2026-06-04 00:02 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T00:02 (952 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,106 | avg: 14,226 | max: 28,205 | trend: stable (-0.38/hr))
```
▁▁▁▅▁▁▄▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▃▁▃▄▁█▃▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▂▂▁▃▁▅▁▁▁▁▁▁▁▁▁▁▁▁▃▁▄▁▂▁▁▂▄▁▁▁▂▁▁▅▁▁▁▁▁▂▁
```

**Heap InUse** (current: 106.1MB | avg: 166.8MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▃▃▃▂▂▃▄▁▂▄▁▄▄▃▃▃▃▁▃▄▁▂▁▂▂▃▃▄▃▁▅▃▂▃▂▃▄▃▃▃▄▄▃▄▁▂▄▃▄▄▂▃▄▂▂▃▃▁▃▃▄▁▂▂▁▁▂▁▃▂▄▂▃▄▁▄▁▂▁▁▄▃▂▂▄▃▂▂█▄▁▄▄▃▁▁
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,106 | 14,179 | -73 | 14,226 | 28,205 | stable (-0.38/hr) |
| Heap InUse | 106.1MB | 116.5MB | -10.4MB | 166.8MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 899.0MB | 898.7MB | +0.3MB | 1301.0MB | 1805.8MB | |
| Heap Objects | 334,137 | 457,730 | -123593 | 887,053 | 2,707,946 | |

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
| 2026-06-04 | 1 | 14,106 | 106.1MB | 106.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 6.58MB |
| 4 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 3.5MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `aws/endpoints.init` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `reflect.unsafe_NewArray` | 2.0MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 12.66GB |
| 2 | `segmentio/kafka-go.makePartitions` | 7.73GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 6.13GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 4.08GB |
| 5 | `experiment/local.(*Client).EvaluateV2` | 4.08GB |
| 6 | `internal/evaluation.mergeMetadata` | 4.02GB |
| 7 | `reflect.unsafe_NewArray` | 3.44GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 2.13GB |
| 9 | `experiment/local.topologicalSort` | 2.03GB |
| 10 | `reflect.MakeSlice` | 1.91GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 9.36GB | 8.25GB | 8.80GB | 0B |
| `evaluation.mergeMetadata` | 4.02GB | 3.55GB | 3.79GB | 0B |
| `local.(*Client).EvaluateV2` | 15.60GB | 13.72GB | 14.66GB | 0B |
| `local.topologicalSort` | 2.12GB | 1.85GB | 1.99GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 17.71GB | 15.57GB | 16.64GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 32.66MB | 26.45MB | 29.55MB | 0B |
| `localEvaluation.getMapOfValue` | 17.71GB | 15.57GB | 16.64GB | 0B |
| `utils.ParseFeatureFlag` | 142.62MB | 129.09MB | 135.86MB | 0B |

**Total FF alloc (current snapshot):** 66.69GB  |  **24h avg:** 62.67GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 950/952 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.96MB | 36/952 | `███████░░░░░░░░ 49%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.29MB | 24/952 | `███████░░░░░░░░ 47%` |
| 4 | `runtime.mallocgc` | 13.59MB | 946/952 | `█████░░░░░░░░░░ 37%` |
| 5 | `database/sql.convertAssignRows` | 12.13MB | 38/952 | `████░░░░░░░░░░░ 33%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/952 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/952 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/952 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 948/952 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/952 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 97.04GB | 943/952 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 69.18GB | 295/952 | `██████████░░░░░ 71%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 68.89GB | 294/952 | `██████████░░░░░ 70%` |
| 4 | `internal/evaluation.mergeMetadata` | 68.22GB | 289/952 | `██████████░░░░░ 70%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 51.21GB | 903/952 | `███████░░░░░░░░ 52%` |
| 6 | `reflect.unsafe_NewArray` | 41.99GB | 942/952 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 35.48GB | 284/952 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 35.36GB | 290/952 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 23.64GB | 934/952 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 23.1GB | 901/952 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
