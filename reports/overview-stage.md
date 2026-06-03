# Overview: stage
*Last updated: 2026-06-04 01:03 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T01:02 (954 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,076 | avg: 14,226 | max: 28,205 | trend: stable (-0.39/hr))
```
▁▅▁▁▄▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▃▁▃▄▁█▃▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▂▂▁▃▁▅▁▁▁▁▁▁▁▁▁▁▁▁▃▁▄▁▂▁▁▂▄▁▁▁▂▁▁▅▁▁▁▁▁▂▁▁▁
```

**Heap InUse** (current: 157.0MB | avg: 166.7MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▃▂▂▃▄▁▂▄▁▄▄▃▃▃▃▁▃▄▁▂▂▂▂▃▃▄▃▁▅▃▂▃▂▃▄▃▃▄▄▄▃▄▁▂▅▃▄▄▂▃▄▂▂▃▃▁▃▃▄▁▂▂▁▁▂▁▃▂▄▂▃▄▁▄▁▂▁▁▄▃▂▂▄▃▂▂█▄▁▄▄▃▁▁▁▃
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,076 | 14,099 | -23 | 14,226 | 28,205 | stable (-0.39/hr) |
| Heap InUse | 157.0MB | 103.8MB | +53.2MB | 166.7MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 895.6MB | 899.0MB | -3.4MB | 1300.1MB | 1805.8MB | |
| Heap Objects | 1,055,270 | 333,666 | +721604 | 886,649 | 2,707,946 | |

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
| 2026-06-04 | 3 | 14,094 | 122.3MB | 157.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 6.58MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 3.5MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 6 | `aws/endpoints.init` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.unsafe_NewArray` | 2.0MB |
| 9 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 10 | `reflect.mapassign_faststr0` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 13.69GB |
| 2 | `segmentio/kafka-go.makePartitions` | 9.46GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 6.62GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 4.42GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 4.41GB |
| 6 | `internal/evaluation.mergeMetadata` | 4.34GB |
| 7 | `reflect.unsafe_NewArray` | 4.2GB |
| 8 | `reflect.MakeSlice` | 2.33GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 2.3GB |
| 10 | `experiment/local.topologicalSort` | 2.19GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 10.11GB | 9.59GB | 9.32GB | 0B |
| `evaluation.mergeMetadata` | 4.34GB | 4.13GB | 4.01GB | 0B |
| `local.(*Client).EvaluateV2` | 16.86GB | 15.98GB | 15.54GB | 0B |
| `local.topologicalSort` | 2.29GB | 2.18GB | 2.11GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 19.13GB | 18.14GB | 17.64GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 39.90MB | 34.70MB | 33.43MB | 0B |
| `localEvaluation.getMapOfValue` | 19.13GB | 18.14GB | 17.64GB | 0B |
| `utils.ParseFeatureFlag` | 170.04MB | 151.90MB | 148.41MB | 0B |

**Total FF alloc (current snapshot):** 72.06GB  |  **24h avg:** 66.44GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 952/954 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.96MB | 36/954 | `███████░░░░░░░░ 49%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.29MB | 24/954 | `███████░░░░░░░░ 47%` |
| 4 | `runtime.mallocgc` | 13.58MB | 948/954 | `█████░░░░░░░░░░ 37%` |
| 5 | `database/sql.convertAssignRows` | 12.13MB | 38/954 | `████░░░░░░░░░░░ 33%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/954 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/954 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/954 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 950/954 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/954 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 96.85GB | 945/954 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 68.74GB | 297/954 | `██████████░░░░░ 70%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 68.45GB | 296/954 | `██████████░░░░░ 70%` |
| 4 | `internal/evaluation.mergeMetadata` | 67.78GB | 291/954 | `██████████░░░░░ 69%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 51.13GB | 905/954 | `███████░░░░░░░░ 52%` |
| 6 | `reflect.unsafe_NewArray` | 41.91GB | 944/954 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 35.25GB | 286/954 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 35.14GB | 292/954 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 23.6GB | 936/954 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 23.07GB | 903/954 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
