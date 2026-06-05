# Overview: stage
*Last updated: 2026-06-05 08:00 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T08:00 (1015 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,065 | avg: 14,222 | max: 28,205 | trend: stable (-0.36/hr))
```
▁▁▁▁▁▁▁▁▁▁▄▁▅▁▂▁▁▂▄▂▁▁▃▂▁▆▁▁▁▁▁▂▁▁▁▁▁▁▁▃▂▁▁▁▆▁▁▁█▁▁▁▅▁▁▁▂▁▄▆▂▄▃▁▁▁▃▁▁▁▁▃▁▁▃▁▁▁▁▁▁▁▁▁▁▂▃▂▁▂▆▄▅▁▁▁
```

**Heap InUse** (current: 146.9MB | avg: 165.5MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▂▁▁▂▁▃▂▃▂▃▃▁▃▁▂▁▁▃▂▂▂▃▂▂▂▅▃▁▃▃▃▁▁▁▂▁▁▂▂▂▂▁▂▁▅▃▁▂▃▁▂▁▄▂▁▂▂▁▂▃▁▂▃▃▂▂▂▃▂▂▁▁▁▁▁▂▂▁▂▁▁▁▂▂▁▁▂▃▂▂▃█▆▃▂▂
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,065 | 14,076 | -11 | 14,222 | 28,205 | stable (-0.36/hr) |
| Heap InUse | 146.9MB | 158.1MB | -11.2MB | 165.5MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 987.3MB | 987.3MB | +0.0MB | 1252.9MB | 1805.8MB | |
| Heap Objects | 894,206 | 1,033,697 | -139491 | 881,259 | 2,707,946 | |

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
| 2026-06-05 | 17 | 14,174 | 160.2MB | 338.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `reflect.mapassign_faststr0` | 2.0MB |
| 8 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.0MB |
| 9 | `encoding/json.(*decodeState).literalStore` | 1.54MB |
| 10 | `segmentio/kafka-go.makePartitions` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 16.09GB |
| 2 | `segmentio/kafka-go.makePartitions` | 13.14GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 6.26GB |
| 4 | `reflect.unsafe_NewArray` | 5.77GB |
| 5 | `reflect.MakeSlice` | 3.15GB |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 1.93GB |
| 7 | `database/sql.convertAssignRows` | 1.69GB |
| 8 | `segmentio/kafka-go.makeLayout` | 1.42GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 784.6MB |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 743.73MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 74.37MB | 71.23MB | 1.82GB | 0B |
| `evaluation.mergeMetadata` | 31.51MB | 31.01MB | 792.31MB | 0B |
| `local.(*Client).EvaluateV2` | 138.37MB | 133.66MB | 3.06GB | 0B |
| `local.topologicalSort` | 21.88MB | 21.37MB | 430.97MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 149.59MB | 144.38MB | 3.46GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 9.90MB | 9.90MB | 19.85MB | 0B |
| `localEvaluation.getMapOfValue` | 149.59MB | 144.38MB | 3.46GB | 0B |
| `utils.ParseFeatureFlag` | 150.60MB | 145.38MB | 108.31MB | 0B |

**Total FF alloc (current snapshot):** 725.81MB  |  **24h avg:** 13.11GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1013/1015 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.43MB | 40/1015 | `███████░░░░░░░░ 50%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.36MB | 26/1015 | `███████░░░░░░░░ 47%` |
| 4 | `runtime.mallocgc` | 13.41MB | 1009/1015 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 12.04MB | 42/1015 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1015 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1015 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1015 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1010/1015 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1015 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 91.48GB | 1005/1015 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1015 | `██████████░░░░░ 69%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1015 | `██████████░░░░░ 68%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1015 | `██████████░░░░░ 68%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 49.29GB | 945/1015 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 39.59GB | 1004/1015 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1015 | `█████░░░░░░░░░░ 37%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1015 | `█████░░░░░░░░░░ 37%` |
| 9 | `reflect.MakeSlice` | 22.3GB | 995/1015 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 22.26GB | 942/1015 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
