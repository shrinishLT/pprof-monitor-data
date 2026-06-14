# Overview: stage
*Last updated: 2026-06-14 14:03 IST*
*Data range: 2026-05-15T16:03 to 2026-06-14T14:03 (1457 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,152 | avg: 14,196 | max: 28,205 | trend: stable (-0.27/hr))
```
▃▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▂▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▄▁▁▁▁▅▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▄▁▁▁▃▁▂▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 170.3MB | avg: 161.2MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▂▄▁▃▃▄▂▁▅▁▄▅▂▄▁▁▃▂▂▃▂▂▄▂▁▁▄▅▁▁▁▁▆▄▂▃▄▄▁▁▃▃▄▂▃▃▁▄▁▄▅▂▄▃▂▄▃▁▁▄▁▂▂▁▄▃▁▄▃▃▂▄▁▃▁▃▄▃▃█▄▄▂▂▃▁▄▁▂▁▄▂▁▄▁▄
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,152 | 14,065 | +87 | 14,196 | 28,205 | stable (-0.27/hr) |
| Heap InUse | 170.3MB | 112.8MB | +57.5MB | 161.2MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 1267.7MB | 1267.7MB | +0.0MB | 1185.9MB | 1805.8MB | |
| Heap Objects | 1,122,025 | 400,130 | +721895 | 879,234 | 2,707,946 | |

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
| 2026-06-07 | 47 | 14,103 | 158.2MB | 298.5MB |
| 2026-06-08 | 48 | 14,210 | 154.6MB | 265.6MB |
| 2026-06-09 | 48 | 14,154 | 161.0MB | 283.6MB |
| 2026-06-10 | 47 | 14,121 | 151.2MB | 275.7MB |
| 2026-06-11 | 48 | 14,109 | 139.5MB | 199.7MB |
| 2026-06-12 | 48 | 14,135 | 148.8MB | 189.5MB |
| 2026-06-13 | 48 | 14,121 | 146.0MB | 214.7MB |
| 2026-06-14 | 29 | 14,137 | 152.8MB | 247.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 16.94MB |
| 3 | `database/sql.convertAssignRows` | 11.0MB |
| 4 | `runtime.mallocgc` | 10.01MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 9.5MB |
| 6 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 3.74MB |
| 8 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 9 | `dotlapse-event-service/workerpool.NewWorker` | 3.0MB |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 3.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 120.18GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 59.9GB |
| 3 | `reflect.unsafe_NewArray` | 51.58GB |
| 4 | `reflect.MakeSlice` | 28.74GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 24.6GB |
| 6 | `segmentio/kafka-go.makeLayout` | 12.56GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 7.74GB |
| 8 | `database/sql.convertAssignRows` | 6.97GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 6.2GB |
| 10 | `internal/reflectlite.unsafe_New` | 5.88GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 588.13MB | 579.90MB | 509.01MB | 0B |
| `evaluation.mergeMetadata` | 260.56MB | 256.56MB | 226.17MB | 0B |
| `local.(*Client).EvaluateV2` | 967.29MB | 954.22MB | 838.44MB | 0B |
| `local.topologicalSort` | 123.49MB | 123.49MB | 106.50MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 949.86MB | 936.77MB | 812.26MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 126.71MB | 126.21MB | 117.07MB | 0B |
| `localEvaluation.getMapOfValue` | 949.86MB | 936.77MB | 812.26MB | 0B |
| `utils.ParseFeatureFlag` | 951.36MB | 938.27MB | 813.76MB | 0B |

**Total FF alloc (current snapshot):** 4.80GB  |  **24h avg:** 4.14GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1455/1457 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.99MB | 54/1457 | `███████░░░░░░░░ 51%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 15.55MB | 34/1457 | `██████░░░░░░░░░ 42%` |
| 4 | `runtime.mallocgc` | 12.86MB | 1451/1457 | `█████░░░░░░░░░░ 35%` |
| 5 | `database/sql.convertAssignRows` | 11.56MB | 56/1457 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1457 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1457 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1457 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1452/1457 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1457 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 93.06GB | 1447/1457 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1457 | `██████████░░░░░ 68%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1457 | `██████████░░░░░ 67%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1457 | `██████████░░░░░ 67%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 49.72GB | 1338/1457 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 40.25GB | 1446/1457 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1457 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1457 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 22.62GB | 1437/1457 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.64GB | 1334/1457 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.5x avg)
