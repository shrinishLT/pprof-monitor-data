# Overview: stage
*Last updated: 2026-06-05 19:02 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T19:02 (1037 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,353 | avg: 14,221 | max: 28,205 | trend: stable (-0.35/hr))
```
▃▂▁▆▁▁▁▁▁▂▁▁▁▁▁▁▁▃▂▁▁▁▆▁▁▁█▁▁▁▅▁▁▁▂▁▄▆▂▄▃▁▁▁▃▁▁▁▁▃▁▁▃▁▁▁▁▁▁▁▁▁▁▂▃▂▁▂▆▄▅▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▂▃▆▁▁▁▁▄
```

**Heap InUse** (current: 119.4MB | avg: 165.4MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▂▂▂▅▃▁▃▃▃▁▁▁▂▁▁▂▂▂▂▁▂▁▅▃▁▂▃▁▂▁▄▂▁▂▂▁▂▃▁▂▃▃▂▂▂▃▂▂▁▁▁▁▁▂▂▁▂▁▁▁▂▂▁▁▂▃▂▂▃█▆▃▂▂▁▃▃▁▃▃▂▂▂▁▃▅▃▂▂▃▂▃▃▂▃▁
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,353 | 14,083 | +270 | 14,221 | 28,205 | stable (-0.35/hr) |
| Heap InUse | 119.4MB | 169.8MB | -50.4MB | 165.4MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 987.9MB | 987.9MB | +0.0MB | 1247.3MB | 1805.8MB | |
| Heap Objects | 403,718 | 1,197,627 | -793909 | 883,956 | 2,707,946 | |

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
| 2026-06-05 | 39 | 14,154 | 160.5MB | 338.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.0MB |
| 6 | `compress/flate.NewWriter` | 3.53MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `segmentio/kafka-go.makeLayout` | 2.05MB |
| 9 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.0MB |
| 10 | `reflect.unsafe_NewArray` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 32.84GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 18.65GB |
| 3 | `reflect.unsafe_NewArray` | 14.31GB |
| 4 | `reflect.MakeSlice` | 8.05GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 7.33GB |
| 6 | `segmentio/kafka-go.makeLayout` | 3.57GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.3GB |
| 8 | `database/sql.convertAssignRows` | 2.0GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 1.76GB |
| 10 | `internal/reflectlite.unsafe_New` | 1.59GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 257.97MB | 244.10MB | 102.49MB | 0B |
| `evaluation.mergeMetadata` | 104.53MB | 98.52MB | 42.99MB | 0B |
| `local.(*Client).EvaluateV2` | 440.60MB | 421.44MB | 181.40MB | 0B |
| `local.topologicalSort` | 65.11MB | 63.58MB | 27.04MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 446.04MB | 425.86MB | 183.71MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 47.68MB | 46.66MB | 19.92MB | 0B |
| `localEvaluation.getMapOfValue` | 446.04MB | 425.86MB | 183.71MB | 0B |
| `utils.ParseFeatureFlag` | 447.04MB | 426.86MB | 184.36MB | 0B |

**Total FF alloc (current snapshot):** 2.20GB  |  **24h avg:** 925.60MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1035/1037 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.27MB | 41/1037 | `███████░░░░░░░░ 49%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.36MB | 26/1037 | `███████░░░░░░░░ 47%` |
| 4 | `runtime.mallocgc` | 13.4MB | 1031/1037 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 11.95MB | 43/1037 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1037 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1037 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1037 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1032/1037 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1037 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 90.03GB | 1027/1037 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1037 | `██████████░░░░░ 70%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1037 | `██████████░░░░░ 70%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1037 | `██████████░░░░░ 69%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 48.56GB | 967/1037 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 38.96GB | 1026/1037 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1037 | `█████░░░░░░░░░░ 37%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1037 | `█████░░░░░░░░░░ 37%` |
| 9 | `reflect.MakeSlice` | 21.94GB | 1017/1037 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.91GB | 964/1037 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
