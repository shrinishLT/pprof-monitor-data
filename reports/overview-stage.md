# Overview: stage
*Last updated: 2026-06-06 21:02 IST*
*Data range: 2026-05-15T16:03 to 2026-06-06T21:02 (1089 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,075 | avg: 14,216 | max: 28,205 | trend: stable (-0.35/hr))
```
▃▁▁▁▁▁▁▁▁▁▁▂▃▃▁▃▇▄▆▁▁▁▁▁▁▁▁▁▁▁▁▃▁▂▁▂▃▃█▁▁▁▁▄▃▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▄▂▄▄▁▁▁▁▁▁▂▁▁▁▁▁▂▂▂▁▅▃▃▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 172.1MB | avg: 164.5MB | max: 732.9MB | trend: stable (-0.05MB/hr))
```
▁▂▂▁▂▁▁▁▂▂▁▁▂▃▂▂▃█▆▃▂▂▁▃▃▁▃▃▂▂▂▁▃▅▃▂▂▃▂▃▃▂▃▁▂▃▂▃▂▂▁▁▁▃▁▃▂▃▂▂▁▁▃▂▁▄▂▂▁▁▁▂▂▃▂▁▁▂▃▁▁▂▁▃▃▃▃▁▂▂▁▂▂▂▃▃
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,075 | 14,065 | +10 | 14,216 | 28,205 | stable (-0.35/hr) |
| Heap InUse | 172.1MB | 176.9MB | -4.8MB | 164.5MB | 732.9MB | stable (-0.05MB/hr) |
| Heap Sys | 988.6MB | 988.6MB | +0.0MB | 1234.9MB | 1805.8MB | |
| Heap Objects | 1,220,285 | 1,256,776 | -36491 | 880,435 | 2,707,946 | |

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
| 2026-06-06 | 43 | 14,132 | 146.9MB | 231.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `segmentio/kafka-go.makePartitions` | 2.51MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `reflect.unsafe_NewArray` | 2.01MB |
| 8 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.0MB |
| 9 | `compress/flate.NewWriter` | 1.76MB |
| 10 | `bufio.NewReaderSize` | 1.53MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 79.58GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 36.99GB |
| 3 | `reflect.unsafe_NewArray` | 34.51GB |
| 4 | `reflect.MakeSlice` | 19.33GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 14.53GB |
| 6 | `segmentio/kafka-go.makeLayout` | 8.58GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 4.61GB |
| 8 | `v3/newrelic.newAnalyticsEvents` | 4.17GB |
| 9 | `database/sql.convertAssignRows` | 4.05GB |
| 10 | `internal/reflectlite.unsafe_New` | 3.88GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 531.49MB | 530.45MB | 412.91MB | 0B |
| `evaluation.mergeMetadata` | 226.06MB | 225.56MB | 172.98MB | 0B |
| `local.(*Client).EvaluateV2` | 918.82MB | 917.78MB | 713.87MB | 0B |
| `local.topologicalSort` | 141.89MB | 141.89MB | 109.38MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 931.44MB | 930.40MB | 716.67MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 101.39MB | 101.39MB | 82.54MB | 0B |
| `localEvaluation.getMapOfValue` | 931.44MB | 930.40MB | 716.67MB | 0B |
| `utils.ParseFeatureFlag` | 932.94MB | 931.90MB | 717.79MB | 0B |

**Total FF alloc (current snapshot):** 4.60GB  |  **24h avg:** 3.56GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1087/1089 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.2MB | 43/1089 | `███████░░░░░░░░ 49%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.64MB | 28/1089 | `██████░░░░░░░░░ 45%` |
| 4 | `runtime.mallocgc` | 13.38MB | 1083/1089 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 11.89MB | 45/1089 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1089 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1089 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1089 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1084/1089 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1089 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 88.42GB | 1079/1089 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1089 | `██████████░░░░░ 72%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1089 | `██████████░░░░░ 71%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1089 | `██████████░░░░░ 70%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 47.54GB | 1019/1089 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 38.26GB | 1078/1089 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1089 | `█████░░░░░░░░░░ 38%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1089 | `█████░░░░░░░░░░ 38%` |
| 9 | `reflect.MakeSlice` | 21.54GB | 1069/1089 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.36GB | 1016/1089 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
