# Overview: stage
*Last updated: 2026-06-06 18:03 IST*
*Data range: 2026-05-15T16:03 to 2026-06-06T18:03 (1083 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,091 | avg: 14,217 | max: 28,205 | trend: stable (-0.35/hr))
```
▁▁▁▄▁▁▃▁▁▁▁▁▁▁▁▁▁▂▃▃▁▃▇▄▆▁▁▁▁▁▁▁▁▁▁▁▁▃▁▂▁▂▃▃█▁▁▁▁▄▃▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▄▂▄▄▁▁▁▁▁▁▂▁▁▁▁▁▂▂▂▁▅▃▃▁▁▁▁
```

**Heap InUse** (current: 143.4MB | avg: 164.6MB | max: 732.9MB | trend: stable (-0.05MB/hr))
```
▂▂▁▁▁▁▁▂▂▁▂▁▁▁▂▂▁▁▂▃▂▂▃█▆▃▂▂▁▃▃▁▃▃▂▂▂▁▃▅▃▂▂▃▂▃▃▂▃▁▂▃▂▃▂▂▁▁▁▃▁▃▂▃▂▂▁▁▃▂▁▄▂▂▁▁▁▂▂▃▂▁▁▂▃▁▁▂▁▃▃▃▃▁▂▂
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,091 | 14,080 | +11 | 14,217 | 28,205 | stable (-0.35/hr) |
| Heap InUse | 143.4MB | 156.1MB | -12.7MB | 164.6MB | 732.9MB | stable (-0.05MB/hr) |
| Heap Sys | 988.6MB | 988.6MB | +0.0MB | 1236.3MB | 1805.8MB | |
| Heap Objects | 823,681 | 1,029,493 | -205812 | 880,239 | 2,707,946 | |

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
| 2026-06-06 | 37 | 14,141 | 146.3MB | 231.1MB |

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
| 9 | `compress/flate.(*compressor).initDeflate` | 1.07MB |
| 10 | `aws/endpoints.init` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 74.15GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 36.98GB |
| 3 | `reflect.unsafe_NewArray` | 32.16GB |
| 4 | `reflect.MakeSlice` | 18.0GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 14.53GB |
| 6 | `segmentio/kafka-go.makeLayout` | 7.99GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 4.6GB |
| 8 | `database/sql.convertAssignRows` | 4.04GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 3.89GB |
| 10 | `internal/reflectlite.unsafe_New` | 3.64GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 498.03MB | 495.45MB | 381.97MB | 0B |
| `evaluation.mergeMetadata` | 209.05MB | 208.55MB | 159.13MB | 0B |
| `local.(*Client).EvaluateV2` | 865.88MB | 859.71MB | 660.26MB | 0B |
| `local.topologicalSort` | 134.75MB | 132.21MB | 101.05MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 874.87MB | 871.80MB | 661.55MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 96.21MB | 93.12MB | 77.18MB | 0B |
| `localEvaluation.getMapOfValue` | 874.87MB | 871.80MB | 661.55MB | 0B |
| `utils.ParseFeatureFlag` | 876.37MB | 873.30MB | 662.61MB | 0B |

**Total FF alloc (current snapshot):** 4.33GB  |  **24h avg:** 3.29GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1081/1083 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.2MB | 43/1083 | `███████░░░░░░░░ 49%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.64MB | 28/1083 | `██████░░░░░░░░░ 45%` |
| 4 | `runtime.mallocgc` | 13.39MB | 1077/1083 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 11.89MB | 45/1083 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1083 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1083 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1083 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1078/1083 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1083 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 88.48GB | 1073/1083 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1083 | `██████████░░░░░ 72%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1083 | `██████████░░░░░ 71%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1083 | `██████████░░░░░ 70%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 47.6GB | 1013/1083 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 38.29GB | 1072/1083 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1083 | `█████░░░░░░░░░░ 38%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1083 | `█████░░░░░░░░░░ 38%` |
| 9 | `reflect.MakeSlice` | 21.56GB | 1063/1083 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.4GB | 1010/1083 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
