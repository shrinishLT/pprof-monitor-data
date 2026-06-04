# Overview: stage
*Last updated: 2026-06-04 13:30 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T13:30 (978 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,418 | avg: 14,224 | max: 28,205 | trend: stable (-0.37/hr))
```
▁▃▄▁█▃▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▂▂▁▃▁▅▁▁▁▁▁▁▁▁▁▁▁▁▃▁▄▁▂▁▁▂▄▁▁▁▂▁▁▅▁▁▁▁▁▂▁▁▁▁▁▁▁▂▂▁▁▁▅▁▁▁▆▁▁▁▄▁▁▁▁▁▄
```

**Heap InUse** (current: 150.0MB | avg: 166.1MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▃▄▃▁▅▄▂▃▂▃▄▄▃▄▄▅▃▄▂▂▅▃▄▄▃▃▄▂▂▃▃▁▃▃▄▁▂▂▂▁▂▁▄▂▄▂▄▄▁▄▂▂▁▁▄▃▂▂▄▃▂▂█▄▂▄▄▃▁▁▁▃▁▂▂▃▃▂▂▂▁▇▃▁▃▅▁▃▁▅▂▁▂▂▁▃
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 51%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,418 | 14,096 | +322 | 14,224 | 28,205 | stable (-0.37/hr) |
| Heap InUse | 150.0MB | 115.0MB | +35.0MB | 166.1MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 216.7MB | 121.8MB | +94.9MB | 1283.7MB | 1805.8MB | |
| Heap Objects | 619,741 | 547,142 | +72599 | 883,351 | 2,707,946 | |

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
| 2026-06-04 | 27 | 14,166 | 139.8MB | 258.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 6.51MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `bytes.growSlice` | 3.03MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 7 | `aws/endpoints.init` | 3.0MB |
| 8 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `reflect.unsafe_NewArray` | 2.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 846.6MB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 723.55MB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 708.8MB |
| 4 | `internal/evaluation.mergeMetadata` | 663.16MB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 360.7MB |
| 6 | `experiment/local.topologicalSort` | 352.67MB |
| 7 | `reflect.unsafe_NewArray` | 343.19MB |
| 8 | `reflect.MakeSlice` | 192.5MB |
| 9 | `internal/evaluation.(*Engine).evaluateFlag` | 134.51MB |
| 10 | `segmentio/kafka-go.makeLayout` | 94.04MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.55GB | 0B | 5.84GB | 512.02kB |
| `evaluation.mergeMetadata` | 663.16MB | 0B | 2.50GB | 512.02kB |
| `local.(*Client).EvaluateV2` | 2.62GB | 0B | 9.78GB | 512.02kB |
| `local.topologicalSort` | 368.17MB | 0B | 1.34GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.97GB | 0B | 11.11GB | 512.02kB |
| `localEvaluation.GetFeatureFlagPayload` | 6.31MB | 0B | 17.76MB | 0B |
| `localEvaluation.getMapOfValue` | 2.97GB | 0B | 11.11GB | 512.02kB |
| `utils.ParseFeatureFlag` | 13.42MB | 0B | 110.08MB | 0B |

**Total FF alloc (current snapshot):** 11.14GB  |  **24h avg:** 41.81GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 976/978 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.9MB | 37/978 | `███████░░░░░░░░ 48%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.29MB | 24/978 | `███████░░░░░░░░ 47%` |
| 4 | `runtime.mallocgc` | 13.48MB | 972/978 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 12.06MB | 39/978 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/978 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/978 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/978 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 973/978 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/978 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 94.74GB | 968/978 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 64.38GB | 318/978 | `██████████░░░░░ 67%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.69GB | 319/978 | `██████████░░░░░ 67%` |
| 4 | `internal/evaluation.mergeMetadata` | 63.19GB | 313/978 | `██████████░░░░░ 66%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 50.48GB | 921/978 | `███████░░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 41.0GB | 967/978 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.55GB | 292/978 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.46GB | 298/978 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 23.1GB | 958/978 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 22.78GB | 919/978 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
