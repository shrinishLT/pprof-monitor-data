# Overview: stage
*Last updated: 2026-06-06 17:33 IST*
*Data range: 2026-05-15T16:03 to 2026-06-06T17:32 (1082 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,080 | avg: 14,217 | max: 28,205 | trend: stable (-0.35/hr))
```
▁▁▁▁▄▁▁▃▁▁▁▁▁▁▁▁▁▁▂▃▃▁▃▇▄▆▁▁▁▁▁▁▁▁▁▁▁▁▃▁▂▁▂▃▃█▁▁▁▁▄▃▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▄▂▄▄▁▁▁▁▁▁▂▁▁▁▁▁▂▂▂▁▅▃▃▁▁▁
```

**Heap InUse** (current: 156.1MB | avg: 164.6MB | max: 732.9MB | trend: stable (-0.05MB/hr))
```
▃▂▂▁▁▁▁▁▂▂▁▂▁▁▁▂▂▁▁▂▃▂▂▃█▆▃▂▂▁▃▃▁▃▃▂▂▂▁▃▅▃▂▂▃▂▃▃▂▃▁▂▃▂▃▂▂▁▁▁▃▁▃▂▃▂▂▁▁▃▂▁▄▂▂▁▁▁▂▂▃▂▁▁▂▃▁▁▂▁▃▃▃▃▁▂
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,080 | 14,091 | -11 | 14,217 | 28,205 | stable (-0.35/hr) |
| Heap InUse | 156.1MB | 125.5MB | +30.6MB | 164.6MB | 732.9MB | stable (-0.05MB/hr) |
| Heap Sys | 988.6MB | 988.6MB | +0.0MB | 1236.5MB | 1805.8MB | |
| Heap Objects | 1,029,493 | 596,355 | +433138 | 880,291 | 2,707,946 | |

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
| 2026-06-06 | 36 | 14,142 | 146.4MB | 231.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.0MB |
| 8 | `segmentio/kafka-go.makePartitions` | 1.5MB |
| 9 | `aws/endpoints.init` | 1.0MB |
| 10 | `encoding/json.typeFields` | 514.63kB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 73.25GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 36.98GB |
| 3 | `reflect.unsafe_NewArray` | 31.76GB |
| 4 | `reflect.MakeSlice` | 17.79GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 14.52GB |
| 6 | `segmentio/kafka-go.makeLayout` | 7.89GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 4.6GB |
| 8 | `database/sql.convertAssignRows` | 4.04GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 3.84GB |
| 10 | `internal/reflectlite.unsafe_New` | 3.59GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 495.45MB | 491.84MB | 376.47MB | 0B |
| `evaluation.mergeMetadata` | 208.55MB | 207.55MB | 156.74MB | 0B |
| `local.(*Client).EvaluateV2` | 859.71MB | 850.41MB | 650.67MB | 0B |
| `local.topologicalSort` | 132.21MB | 129.15MB | 99.49MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 871.80MB | 863.57MB | 651.88MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 93.12MB | 91.01MB | 76.10MB | 0B |
| `localEvaluation.getMapOfValue` | 871.80MB | 863.57MB | 651.88MB | 0B |
| `utils.ParseFeatureFlag` | 873.30MB | 865.07MB | 652.92MB | 0B |

**Total FF alloc (current snapshot):** 4.30GB  |  **24h avg:** 3.24GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1080/1082 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.2MB | 43/1082 | `███████░░░░░░░░ 49%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.64MB | 28/1082 | `██████░░░░░░░░░ 45%` |
| 4 | `runtime.mallocgc` | 13.39MB | 1076/1082 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 11.89MB | 45/1082 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1082 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1082 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1082 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1077/1082 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1082 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 88.49GB | 1072/1082 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1082 | `██████████░░░░░ 72%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1082 | `██████████░░░░░ 71%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1082 | `██████████░░░░░ 70%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 47.61GB | 1012/1082 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 38.29GB | 1071/1082 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1082 | `█████░░░░░░░░░░ 38%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1082 | `█████░░░░░░░░░░ 38%` |
| 9 | `reflect.MakeSlice` | 21.56GB | 1062/1082 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.41GB | 1009/1082 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
