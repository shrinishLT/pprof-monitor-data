# Overview: stage
*Last updated: 2026-06-07 06:32 IST*
*Data range: 2026-05-15T16:03 to 2026-06-07T06:32 (1108 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,636 | avg: 14,214 | max: 28,205 | trend: stable (-0.35/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▃▁▂▁▁▂▃▇▁▁▁▁▄▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▄▂▄▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▅▂▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▄█
```

**Heap InUse** (current: 298.5MB | avg: 164.4MB | max: 732.9MB | trend: stable (-0.05MB/hr))
```
▃▂▂▁▃▃▁▃▃▂▂▂▁▃▆▃▂▂▃▂▄▃▂▃▁▂▃▂▃▁▂▁▁▁▃▁▃▂▃▁▂▁▁▃▁▁▅▂▂▁▁▁▂▂▃▂▁▁▂▃▁▁▂▁▃▃▃▃▁▂▂▁▂▂▂▃▃▂▂▁▃▁▁▃▂▃▁▂▁▂▁▃▃▁▅█
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 51%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 16%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,636 | 14,360 | +276 | 14,214 | 28,205 | stable (-0.35/hr) |
| Heap InUse | 298.5MB | 243.7MB | +54.8MB | 164.4MB | 732.9MB | stable (-0.05MB/hr) |
| Heap Sys | 1096.8MB | 1096.2MB | +0.6MB | 1230.9MB | 1805.8MB | |
| Heap Objects | 992,978 | 869,887 | +123091 | 880,247 | 2,707,946 | |

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
| 2026-06-05 | 48 | 14,143 | 157.3MB | 338.5MB |
| 2026-06-06 | 48 | 14,125 | 145.8MB | 231.1MB |
| 2026-06-07 | 14 | 14,140 | 166.8MB | 298.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 32.95MB |
| 3 | `runtime.mallocgc` | 13.1MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `database/sql.convertAssignRows` | 9.0MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 7 | `bytes.growSlice` | 8.04MB |
| 8 | `http2/hpack.(*headerFieldTable).addEntry` | 2.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 2.04MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 96.9GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 52.88GB |
| 3 | `reflect.unsafe_NewArray` | 42.02GB |
| 4 | `reflect.MakeSlice` | 23.58GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 20.74GB |
| 6 | `segmentio/kafka-go.makeLayout` | 10.43GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 6.56GB |
| 8 | `database/sql.convertAssignRows` | 5.83GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 5.05GB |
| 10 | `internal/reflectlite.unsafe_New` | 4.73GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 593.32MB | 572.73MB | 495.27MB | 0B |
| `evaluation.mergeMetadata` | 250.56MB | 243.06MB | 208.90MB | 0B |
| `local.(*Client).EvaluateV2` | 1022.98MB | 991.91MB | 857.46MB | 0B |
| `local.topologicalSort` | 156.67MB | 154.11MB | 131.87MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.01GB | 1011.23MB | 868.32MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 109.21MB | 101.89MB | 93.59MB | 0B |
| `localEvaluation.getMapOfValue` | 1.01GB | 1011.23MB | 868.32MB | 0B |
| `utils.ParseFeatureFlag` | 1.01GB | 1012.73MB | 869.63MB | 0B |

**Total FF alloc (current snapshot):** 5.12GB  |  **24h avg:** 4.29GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1106/1108 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.49MB | 45/1108 | `███████░░░░░░░░ 50%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.42MB | 29/1108 | `██████░░░░░░░░░ 44%` |
| 4 | `runtime.mallocgc` | 13.38MB | 1102/1108 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 11.76MB | 47/1108 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1108 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1108 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1108 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1103/1108 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1108 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 88.42GB | 1098/1108 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1108 | `██████████░░░░░ 72%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1108 | `██████████░░░░░ 71%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1108 | `██████████░░░░░ 70%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 47.36GB | 1038/1108 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 38.27GB | 1097/1108 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1108 | `█████░░░░░░░░░░ 38%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1108 | `█████░░░░░░░░░░ 38%` |
| 9 | `reflect.MakeSlice` | 21.54GB | 1088/1108 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.24GB | 1035/1108 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
