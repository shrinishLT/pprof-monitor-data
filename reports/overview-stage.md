# Overview: stage
*Last updated: 2026-06-04 14:00 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T14:00 (979 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,581 | avg: 14,225 | max: 28,205 | trend: stable (-0.37/hr))
```
▃▄▁█▃▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▂▂▁▃▁▅▁▁▁▁▁▁▁▁▁▁▁▁▃▁▄▁▂▁▁▂▄▁▁▁▂▁▁▅▁▁▁▁▁▂▁▁▁▁▁▁▁▂▂▁▁▁▅▁▁▁▆▁▁▁▄▁▁▁▁▁▄▅
```

**Heap InUse** (current: 192.6MB | avg: 166.1MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▄▃▁▅▄▂▃▂▃▄▄▃▄▄▅▃▄▂▂▅▃▄▄▃▃▄▂▂▃▃▁▃▃▄▁▂▂▂▁▂▁▄▂▄▂▄▄▁▄▂▂▁▁▄▃▂▂▄▃▂▂█▄▂▄▄▃▁▁▁▃▁▂▂▃▃▂▂▂▁▇▃▁▃▅▁▃▁▅▂▁▂▂▁▃▅
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 51%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,581 | 14,418 | +163 | 14,225 | 28,205 | stable (-0.37/hr) |
| Heap InUse | 192.6MB | 150.0MB | +42.6MB | 166.1MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 313.4MB | 216.7MB | +96.7MB | 1282.7MB | 1805.8MB | |
| Heap Objects | 920,288 | 619,741 | +300547 | 883,389 | 2,707,946 | |

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
| 2026-06-04 | 28 | 14,181 | 141.7MB | 258.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 6.51MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `bytes.growSlice` | 4.65MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.01MB |
| 7 | `aws/endpoints.init` | 3.0MB |
| 8 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `regexp.(*bitState).reset` | 2.05MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 1.58GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 1.49GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 1.46GB |
| 4 | `internal/evaluation.mergeMetadata` | 1.37GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 775.87MB |
| 6 | `experiment/local.topologicalSort` | 744.36MB |
| 7 | `reflect.unsafe_NewArray` | 689.56MB |
| 8 | `reflect.MakeSlice` | 389.01MB |
| 9 | `dotlapse-event-service/project.ApplyPagination` | 310.85MB |
| 10 | `internal/evaluation.(*Engine).evaluateFlag` | 260.52MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 3.25GB | 1.55GB | 5.75GB | 512.14kB |
| `evaluation.mergeMetadata` | 1.37GB | 663.16MB | 2.46GB | 512.14kB |
| `local.(*Client).EvaluateV2` | 5.51GB | 2.62GB | 9.63GB | 1.04MB |
| `local.topologicalSort` | 781.86MB | 368.17MB | 1.32GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 6.26GB | 2.97GB | 10.95GB | 1.56MB |
| `localEvaluation.GetFeatureFlagPayload` | 14.69MB | 6.31MB | 17.65MB | 0B |
| `localEvaluation.getMapOfValue` | 6.26GB | 2.97GB | 10.95GB | 1.56MB |
| `utils.ParseFeatureFlag` | 37.25MB | 13.42MB | 107.57MB | 0B |

**Total FF alloc (current snapshot):** 23.46GB  |  **24h avg:** 41.17GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 977/979 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.9MB | 37/979 | `███████░░░░░░░░ 48%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.29MB | 24/979 | `███████░░░░░░░░ 47%` |
| 4 | `runtime.mallocgc` | 13.47MB | 973/979 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 12.06MB | 39/979 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/979 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/979 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/979 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 974/979 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/979 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 94.65GB | 969/979 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 64.18GB | 319/979 | `██████████░░░░░ 67%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.49GB | 320/979 | `██████████░░░░░ 67%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.99GB | 314/979 | `█████████░░░░░░ 66%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 50.42GB | 922/979 | `███████░░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 40.95GB | 968/979 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.43GB | 293/979 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.35GB | 299/979 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 23.08GB | 959/979 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 22.78GB | 919/979 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
