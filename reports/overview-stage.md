# Overview: stage
*Last updated: 2026-06-04 03:32 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T03:32 (958 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,109 | avg: 14,225 | max: 28,205 | trend: stable (-0.39/hr))
```
▄▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▃▁▃▄▁█▃▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▂▂▁▃▁▅▁▁▁▁▁▁▁▁▁▁▁▁▃▁▄▁▂▁▁▂▄▁▁▁▂▁▁▅▁▁▁▁▁▂▁▁▁▁▁▁▁
```

**Heap InUse** (current: 161.6MB | avg: 166.6MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▄▁▂▄▁▄▅▃▃▃▃▁▃▄▁▂▂▂▂▄▃▄▃▁▅▄▂▃▂▃▄▄▃▄▄▅▃▄▁▂▅▃▄▄▂▃▄▂▂▃▃▁▃▃▄▁▂▂▂▁▂▁▄▂▄▂▄▄▁▄▂▂▁▁▄▃▂▂▄▃▂▂█▄▂▄▄▃▁▁▁▃▁▁▂▃
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,109 | 14,072 | +37 | 14,225 | 28,205 | stable (-0.39/hr) |
| Heap InUse | 161.6MB | 136.2MB | +25.4MB | 166.6MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 185.7MB | 892.6MB | -706.9MB | 1297.7MB | 1805.8MB | |
| Heap Objects | 920,181 | 714,791 | +205390 | 885,600 | 2,707,946 | |

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
| 2026-06-04 | 7 | 14,087 | 126.8MB | 161.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 9.01MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `aws/endpoints.init` | 2.0MB |
| 8 | `reflect.unsafe_NewArray` | 1.5MB |
| 9 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 1.5MB |
| 10 | `experiment/local.(*Client).EvaluateV2` | 553.04kB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 134.17MB |
| 2 | `reflect.unsafe_NewArray` | 62.8MB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 43.82MB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 38.44MB |
| 5 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 6 | `internal/evaluation.mergeMetadata` | 30.51MB |
| 7 | `reflect.MakeSlice` | 29.5MB |
| 8 | `experiment/local.topologicalSort` | 22.4MB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 21.63MB |
| 10 | `compress/flate.NewWriter` | 14.1MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 83.83MB | 10.19GB | 8.48GB | 512.14kB |
| `evaluation.mergeMetadata` | 30.51MB | 4.38GB | 3.65GB | 512.14kB |
| `local.(*Client).EvaluateV2` | 146.67MB | 17.00GB | 14.15GB | 1.04MB |
| `local.topologicalSort` | 24.40MB | 2.31GB | 1.92GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 168.30MB | 19.29GB | 16.05GB | 1.04MB |
| `localEvaluation.GetFeatureFlagPayload` | 0B | 41.45MB | 32.26MB | 0B |
| `localEvaluation.getMapOfValue` | 168.30MB | 19.29GB | 16.05GB | 1.04MB |
| `utils.ParseFeatureFlag` | 3.13MB | 202.31MB | 146.17MB | 0B |

**Total FF alloc (current snapshot):** 625.14MB  |  **24h avg:** 60.48GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 956/958 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.96MB | 36/958 | `███████░░░░░░░░ 49%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.29MB | 24/958 | `███████░░░░░░░░ 47%` |
| 4 | `runtime.mallocgc` | 13.56MB | 952/958 | `█████░░░░░░░░░░ 37%` |
| 5 | `database/sql.convertAssignRows` | 12.13MB | 38/958 | `████░░░░░░░░░░░ 33%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/958 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/958 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/958 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 954/958 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/958 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 96.48GB | 949/958 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 67.87GB | 301/958 | `██████████░░░░░ 70%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 67.58GB | 300/958 | `██████████░░░░░ 70%` |
| 4 | `internal/evaluation.mergeMetadata` | 66.91GB | 295/958 | `██████████░░░░░ 69%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 51.0GB | 908/958 | `███████░░░░░░░░ 52%` |
| 6 | `reflect.unsafe_NewArray` | 41.75GB | 948/958 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.78GB | 290/958 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.68GB | 296/958 | `█████░░░░░░░░░░ 35%` |
| 9 | `reflect.MakeSlice` | 23.51GB | 940/958 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 23.01GB | 906/958 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
