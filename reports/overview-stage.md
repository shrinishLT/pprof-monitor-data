# Overview: stage
*Last updated: 2026-06-13 08:01 IST*
*Data range: 2026-05-15T16:03 to 2026-06-13T08:01 (1397 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,065 | avg: 14,199 | max: 28,205 | trend: stable (-0.28/hr))
```
▁▁▁▁▁▁▁▁▁▃▁▄▁▁▂▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▂▁▁▃▄▁▅▅▁▁▁▁▁▁▁▁▁▁▁▂▁▁▃▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▂▁█▁▁▁
```

**Heap InUse** (current: 161.2MB | avg: 161.7MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▃▂▁▃▄▅▃▄▂▂▄▂▄▃▄▄▂▂▅▂▅▁▃▃▂▁▅▁▄▂▄▁▁▂▅▁▄▂▅▂▃▃▃▅▅▃▂▁▅▅▃▅▄▆▃▆▁▅▅▆▂▆▂▄▄▅▃▁▆▁▅▆▃▆▂▁▅▃▃▄▃▃▅▃▁▁▆▆▂▂▂▁█▅▃▄
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,065 | 14,073 | -8 | 14,199 | 28,205 | stable (-0.28/hr) |
| Heap InUse | 161.2MB | 145.9MB | +15.3MB | 161.7MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 1266.7MB | 1266.7MB | +0.0MB | 1182.5MB | 1805.8MB | |
| Heap Objects | 1,051,348 | 871,227 | +180121 | 880,978 | 2,707,946 | |

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
| 2026-06-13 | 17 | 14,137 | 146.7MB | 214.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 9.51MB |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 9.5MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 6 | `dotlapse-event-service/workerpool.NewWorker` | 3.0MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.85MB |
| 8 | `aws/endpoints.init` | 2.01MB |
| 9 | `bufio.NewWriterSize` | 1.02MB |
| 10 | `reflect.mapassign_faststr0` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 65.36GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 38.48GB |
| 3 | `reflect.unsafe_NewArray` | 28.04GB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 15.77GB |
| 5 | `reflect.MakeSlice` | 15.56GB |
| 6 | `segmentio/kafka-go.makeLayout` | 6.88GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 4.96GB |
| 8 | `database/sql.convertAssignRows` | 4.43GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 3.44GB |
| 10 | `internal/reflectlite.unsafe_New` | 3.17GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 398.98MB | 395.90MB | 283.85MB | 0B |
| `evaluation.mergeMetadata` | 176.04MB | 174.04MB | 124.79MB | 0B |
| `local.(*Client).EvaluateV2` | 656.98MB | 651.83MB | 465.93MB | 0B |
| `local.topologicalSort` | 77.26MB | 76.25MB | 54.70MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 614.38MB | 609.23MB | 428.07MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 106.01MB | 106.01MB | 80.36MB | 0B |
| `localEvaluation.getMapOfValue` | 614.38MB | 609.23MB | 428.07MB | 0B |
| `utils.ParseFeatureFlag` | 615.88MB | 610.73MB | 429.57MB | 0B |

**Total FF alloc (current snapshot):** 3.18GB  |  **24h avg:** 2.24GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1395/1397 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.76MB | 52/1397 | `███████░░░░░░░░ 51%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 15.77MB | 32/1397 | `██████░░░░░░░░░ 43%` |
| 4 | `runtime.mallocgc` | 13.0MB | 1391/1397 | `█████░░░░░░░░░░ 35%` |
| 5 | `database/sql.convertAssignRows` | 11.45MB | 54/1397 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1397 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1397 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1397 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1392/1397 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1397 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 93.05GB | 1387/1397 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1397 | `██████████░░░░░ 68%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1397 | `██████████░░░░░ 67%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1397 | `██████████░░░░░ 67%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 49.93GB | 1278/1397 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 40.26GB | 1386/1397 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1397 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1397 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 22.64GB | 1377/1397 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.79GB | 1274/1397 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
