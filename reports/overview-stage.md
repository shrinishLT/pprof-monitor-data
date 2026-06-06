# Overview: stage
*Last updated: 2026-06-06 13:03 IST*
*Data range: 2026-05-15T16:03 to 2026-06-06T13:02 (1073 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,129 | avg: 14,217 | max: 28,205 | trend: stable (-0.35/hr))
```
▅█▂▅▃▁▁▁▃▁▁▁▁▄▁▁▃▁▁▁▁▁▁▁▁▁▁▂▃▃▁▃▇▄▅▁▁▁▁▁▁▁▁▁▁▁▁▃▁▂▁▂▂▃▇▁▁▁▁▄▃▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▄▂▄▄▁▁▁▁▁▁▂▁▁▁▁▁▁
```

**Heap InUse** (current: 117.5MB | avg: 164.7MB | max: 732.9MB | trend: stable (-0.05MB/hr))
```
▂▃▁▂▃▃▂▂▂▃▂▂▁▁▁▁▁▂▂▁▂▁▁▁▂▂▁▁▂▃▂▂▃█▆▃▂▂▁▃▃▁▃▃▂▂▂▁▃▅▃▂▂▃▂▃▃▂▃▁▂▃▂▃▂▂▁▁▁▃▁▃▂▃▂▂▁▁▃▂▁▄▂▂▁▁▁▂▂▃▂▁▁▂▃▁
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,129 | 14,105 | +24 | 14,217 | 28,205 | stable (-0.35/hr) |
| Heap InUse | 117.5MB | 171.4MB | -53.9MB | 164.7MB | 732.9MB | stable (-0.05MB/hr) |
| Heap Sys | 988.4MB | 988.3MB | +0.1MB | 1238.6MB | 1805.8MB | |
| Heap Objects | 498,039 | 1,179,646 | -681607 | 880,237 | 2,707,946 | |

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
| 2026-06-06 | 27 | 14,132 | 144.0MB | 231.1MB |

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
| 9 | `segmentio/kafka-go.makePartitions` | 1.5MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 1.07MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 65.19GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 34.4GB |
| 3 | `reflect.unsafe_NewArray` | 28.28GB |
| 4 | `reflect.MakeSlice` | 15.89GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 13.49GB |
| 6 | `segmentio/kafka-go.makeLayout` | 7.05GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 4.27GB |
| 8 | `database/sql.convertAssignRows` | 3.73GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 3.43GB |
| 10 | `internal/reflectlite.unsafe_New` | 3.2GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 427.84MB | 424.30MB | 320.18MB | 0B |
| `evaluation.mergeMetadata` | 177.04MB | 174.54MB | 132.49MB | 0B |
| `local.(*Client).EvaluateV2` | 742.38MB | 737.29MB | 554.39MB | 0B |
| `local.topologicalSort` | 112.88MB | 111.86MB | 85.14MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 750.89MB | 744.79MB | 556.46MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 82.24MB | 82.24MB | 64.17MB | 0B |
| `localEvaluation.getMapOfValue` | 750.89MB | 744.79MB | 556.46MB | 0B |
| `utils.ParseFeatureFlag` | 751.90MB | 745.79MB | 557.46MB | 0B |

**Total FF alloc (current snapshot):** 3.71GB  |  **24h avg:** 2.76GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1071/1073 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.23MB | 42/1073 | `███████░░░░░░░░ 49%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.96MB | 27/1073 | `██████░░░░░░░░░ 46%` |
| 4 | `runtime.mallocgc` | 13.39MB | 1067/1073 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 11.91MB | 44/1073 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1073 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1073 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1073 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1068/1073 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1073 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 88.65GB | 1063/1073 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1073 | `██████████░░░░░ 71%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1073 | `██████████░░░░░ 71%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1073 | `██████████░░░░░ 70%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 47.71GB | 1003/1073 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 38.36GB | 1062/1073 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1073 | `█████░░░░░░░░░░ 38%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1073 | `█████░░░░░░░░░░ 38%` |
| 9 | `reflect.MakeSlice` | 21.6GB | 1053/1073 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.47GB | 1000/1073 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
