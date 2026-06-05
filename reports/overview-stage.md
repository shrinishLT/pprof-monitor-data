# Overview: stage
*Last updated: 2026-06-05 07:32 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T07:32 (1014 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,076 | avg: 14,223 | max: 28,205 | trend: stable (-0.36/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▄▁▅▁▂▁▁▂▄▂▁▁▃▂▁▆▁▁▁▁▁▂▁▁▁▁▁▁▁▃▂▁▁▁▆▁▁▁█▁▁▁▅▁▁▁▂▁▄▆▂▄▃▁▁▁▃▁▁▁▁▃▁▁▃▁▁▁▁▁▁▁▁▁▁▂▃▂▁▂▆▄▅▁▁
```

**Heap InUse** (current: 158.1MB | avg: 165.6MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▂▂▁▁▂▁▃▂▃▂▃▃▁▃▁▂▁▁▃▂▂▂▃▂▂▂▅▃▁▃▃▃▁▁▁▂▁▁▂▂▂▂▁▂▁▅▃▁▂▃▁▂▁▄▂▁▂▂▁▂▃▁▂▃▃▂▂▂▃▂▂▁▁▁▁▁▂▂▁▂▁▁▁▂▂▁▁▂▃▂▂▃█▆▃▂
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,076 | 14,116 | -40 | 14,223 | 28,205 | stable (-0.36/hr) |
| Heap InUse | 158.1MB | 179.9MB | -21.8MB | 165.6MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 987.3MB | 987.2MB | +0.1MB | 1253.1MB | 1805.8MB | |
| Heap Objects | 1,033,697 | 1,304,161 | -270464 | 881,246 | 2,707,946 | |

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
| 2026-06-04 | 47 | 14,166 | 140.9MB | 258.6MB |
| 2026-06-05 | 16 | 14,181 | 161.1MB | 338.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.51MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.0MB |
| 9 | `reflect.mapassign_faststr0` | 1.5MB |
| 10 | `encoding/json.(*decodeState).objectInterface` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 16.09GB |
| 2 | `segmentio/kafka-go.makePartitions` | 12.27GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 6.26GB |
| 4 | `reflect.unsafe_NewArray` | 5.38GB |
| 5 | `reflect.MakeSlice` | 2.95GB |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 1.93GB |
| 7 | `database/sql.convertAssignRows` | 1.69GB |
| 8 | `segmentio/kafka-go.makeLayout` | 1.32GB |
| 9 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 743.73MB |
| 10 | `v3/newrelic.newAnalyticsEvents` | 739.47MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 71.23MB | 63.01MB | 1.95GB | 0B |
| `evaluation.mergeMetadata` | 31.01MB | 26.51MB | 849.20MB | 0B |
| `local.(*Client).EvaluateV2` | 133.66MB | 121.79MB | 3.27GB | 0B |
| `local.topologicalSort` | 21.37MB | 19.85MB | 461.80MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 144.38MB | 128.39MB | 3.71GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 9.90MB | 9.90MB | 19.83MB | 0B |
| `localEvaluation.getMapOfValue` | 144.38MB | 128.39MB | 3.71GB | 0B |
| `utils.ParseFeatureFlag` | 145.38MB | 129.39MB | 107.27MB | 0B |

**Total FF alloc (current snapshot):** 701.30MB  |  **24h avg:** 14.04GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1012/1014 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.43MB | 40/1014 | `███████░░░░░░░░ 50%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.36MB | 26/1014 | `███████░░░░░░░░ 47%` |
| 4 | `runtime.mallocgc` | 13.41MB | 1008/1014 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 12.04MB | 42/1014 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1014 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1014 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1014 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1009/1014 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1014 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 91.56GB | 1004/1014 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1014 | `██████████░░░░░ 69%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1014 | `██████████░░░░░ 68%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1014 | `██████████░░░░░ 68%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 49.33GB | 944/1014 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 39.62GB | 1003/1014 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1014 | `█████░░░░░░░░░░ 37%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1014 | `█████░░░░░░░░░░ 37%` |
| 9 | `reflect.MakeSlice` | 22.32GB | 994/1014 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 22.28GB | 941/1014 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
