# Overview: stage
*Last updated: 2026-06-15 11:32 IST*
*Data range: 2026-05-15T16:03 to 2026-06-15T11:32 (1500 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,068 | avg: 14,193 | max: 28,205 | trend: stable (-0.27/hr))
```
▁▁▁▁▃▁▁▁▁▅▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▃▁▂▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▂▁█▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 188.1MB | avg: 160.9MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▂▃▃▁▄▁▄▅▁▄▃▂▄▃▁▁▄▁▂▂▁▄▃▁▄▃▃▂▄▁▃▁▃▄▃▃█▄▄▂▂▂▁▄▁▂▁▄▂▁▃▁▄▁▁▁▃▄▄▂▂▄▃▁▁▃▂▅▄▂▂▂▂▂▃▂▃▅▃▄▁▂▄▂▄▇▂▅▂▂▃▁▃▄▁▅
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,068 | 14,065 | +3 | 14,193 | 28,205 | stable (-0.27/hr) |
| Heap InUse | 188.1MB | 113.0MB | +75.1MB | 160.9MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 1327.4MB | 1327.4MB | +0.0MB | 1188.7MB | 1805.8MB | |
| Heap Objects | 1,376,517 | 389,133 | +987384 | 879,779 | 2,707,946 | |

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
| 2026-06-14 | 48 | 14,120 | 150.8MB | 247.1MB |
| 2026-06-15 | 24 | 14,125 | 158.1MB | 238.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 10.01MB |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 9.5MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.0MB |
| 6 | `dotlapse-event-service/workerpool.NewWorker` | 3.0MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.85MB |
| 8 | `bufio.NewWriterSize` | 2.05MB |
| 9 | `reflect.unsafe_NewArray` | 2.01MB |
| 10 | `aws/endpoints.init` | 2.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 159.2GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 78.93GB |
| 3 | `reflect.unsafe_NewArray` | 68.43GB |
| 4 | `reflect.MakeSlice` | 38.15GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 32.29GB |
| 6 | `segmentio/kafka-go.makeLayout` | 16.72GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 10.18GB |
| 8 | `database/sql.convertAssignRows` | 9.09GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 8.16GB |
| 10 | `internal/reflectlite.unsafe_New` | 7.79GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 751.86MB | 749.32MB | 661.15MB | 0B |
| `evaluation.mergeMetadata` | 332.08MB | 330.08MB | 291.53MB | 0B |
| `local.(*Client).EvaluateV2` | 1.21GB | 1.21GB | 1.07GB | 0B |
| `local.topologicalSort` | 157.55MB | 157.55MB | 138.57MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.22GB | 1.21GB | 1.06GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 144.54MB | 144.54MB | 132.56MB | 0B |
| `localEvaluation.getMapOfValue` | 1.22GB | 1.21GB | 1.06GB | 0B |
| `utils.ParseFeatureFlag` | 1.22GB | 1.21GB | 1.06GB | 0B |

**Total FF alloc (current snapshot):** 6.21GB  |  **24h avg:** 5.44GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1498/1500 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.91MB | 55/1500 | `███████░░░░░░░░ 51%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 15.55MB | 34/1500 | `██████░░░░░░░░░ 42%` |
| 4 | `runtime.mallocgc` | 12.78MB | 1494/1500 | `█████░░░░░░░░░░ 34%` |
| 5 | `database/sql.convertAssignRows` | 11.54MB | 57/1500 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1500 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1500 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1500 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1495/1500 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1500 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 94.42GB | 1490/1500 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1500 | `██████████░░░░░ 67%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1500 | `██████████░░░░░ 66%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1500 | `█████████░░░░░░ 66%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 50.23GB | 1381/1500 | `███████░░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 40.83GB | 1489/1500 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1500 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1500 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 22.94GB | 1480/1500 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.81GB | 1377/1500 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.6x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.5x avg)
