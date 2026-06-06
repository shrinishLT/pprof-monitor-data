# Overview: stage
*Last updated: 2026-06-06 20:03 IST*
*Data range: 2026-05-15T16:03 to 2026-06-06T20:03 (1087 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,094 | avg: 14,216 | max: 28,205 | trend: stable (-0.35/hr))
```
▁▁▃▁▁▁▁▁▁▁▁▁▁▂▃▃▁▃▇▄▆▁▁▁▁▁▁▁▁▁▁▁▁▃▁▂▁▂▃▃█▁▁▁▁▄▃▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▄▂▄▄▁▁▁▁▁▁▂▁▁▁▁▁▂▂▂▁▅▃▃▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 152.7MB | avg: 164.5MB | max: 732.9MB | trend: stable (-0.05MB/hr))
```
▁▁▁▂▂▁▂▁▁▁▂▂▁▁▂▃▂▂▃█▆▃▂▂▁▃▃▁▃▃▂▂▂▁▃▅▃▂▂▃▂▃▃▂▃▁▂▃▂▃▂▂▁▁▁▃▁▃▂▃▂▂▁▁▃▂▁▄▂▂▁▁▁▂▂▃▂▁▁▂▃▁▁▂▁▃▃▃▃▁▂▂▁▂▂▂
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,094 | 14,068 | +26 | 14,216 | 28,205 | stable (-0.35/hr) |
| Heap InUse | 152.7MB | 135.6MB | +17.1MB | 164.5MB | 732.9MB | stable (-0.05MB/hr) |
| Heap Sys | 988.5MB | 988.6MB | -0.1MB | 1235.3MB | 1805.8MB | |
| Heap Objects | 958,645 | 705,143 | +253502 | 879,777 | 2,707,946 | |

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
| 2026-06-06 | 41 | 14,135 | 145.5MB | 231.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.0MB |
| 8 | `compress/flate.NewWriter` | 1.76MB |
| 9 | `bufio.NewReaderSize` | 1.53MB |
| 10 | `reflect.mapassign_faststr0` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 77.77GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 36.99GB |
| 3 | `reflect.unsafe_NewArray` | 33.73GB |
| 4 | `reflect.MakeSlice` | 18.9GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 14.53GB |
| 6 | `segmentio/kafka-go.makeLayout` | 8.38GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 4.61GB |
| 8 | `v3/newrelic.newAnalyticsEvents` | 4.07GB |
| 9 | `database/sql.convertAssignRows` | 4.04GB |
| 10 | `internal/reflectlite.unsafe_New` | 3.8GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 527.37MB | 523.19MB | 403.25MB | 0B |
| `evaluation.mergeMetadata` | 223.56MB | 222.05MB | 168.63MB | 0B |
| `local.(*Client).EvaluateV2` | 912.57MB | 905.20MB | 697.26MB | 0B |
| `local.topologicalSort` | 141.89MB | 140.86MB | 106.89MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 923.65MB | 915.25MB | 699.15MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 101.39MB | 101.39MB | 81.21MB | 0B |
| `localEvaluation.getMapOfValue` | 923.65MB | 915.25MB | 699.15MB | 0B |
| `utils.ParseFeatureFlag` | 925.15MB | 916.75MB | 700.24MB | 0B |

**Total FF alloc (current snapshot):** 4.57GB  |  **24h avg:** 3.47GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1085/1087 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.2MB | 43/1087 | `███████░░░░░░░░ 49%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.64MB | 28/1087 | `██████░░░░░░░░░ 45%` |
| 4 | `runtime.mallocgc` | 13.39MB | 1081/1087 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 11.89MB | 45/1087 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1087 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1087 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1087 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1082/1087 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1087 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 88.43GB | 1077/1087 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1087 | `██████████░░░░░ 72%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1087 | `██████████░░░░░ 71%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1087 | `██████████░░░░░ 70%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 47.56GB | 1017/1087 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 38.27GB | 1076/1087 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1087 | `█████░░░░░░░░░░ 38%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1087 | `█████░░░░░░░░░░ 38%` |
| 9 | `reflect.MakeSlice` | 21.55GB | 1067/1087 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.37GB | 1014/1087 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
