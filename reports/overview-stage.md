# Overview: stage
*Last updated: 2026-06-11 06:32 IST*
*Data range: 2026-05-15T16:03 to 2026-06-11T06:32 (1298 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,499 | avg: 14,204 | max: 28,205 | trend: stable (-0.30/hr))
```
▆▁▁▁▁▂▁▁▁▁▁▁▆▂▆▂▁▁▃▁▁▁▁▄▃▃▃▁▁▁▃▁▁▁▁▁▁▁▁▂▂▄▅▂▃▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▂▂▃▁▁▁▃▁▁▁▂▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▃▁▇
```

**Heap InUse** (current: 193.6MB | avg: 163.0MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▄▃▄▃▄▄▂▃▂▂▂▃▃▂▃▁▄▃▅▂▃▂▄▂▄▂▃▃▂▃▃▂▂▃▃▃▃▂▂▁▃▂▂▂▂▃▂▃▃▃▂▄▄▃▃▂▃▂▂▂▂▂▂█▃▂▃▃▄▁▂▂▄▃▄▁▄▃▁▃▂▁▂▂▁▁▃▂▁▃▁▃▃▄▁▄
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 51%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,499 | 14,110 | +389 | 14,204 | 28,205 | stable (-0.30/hr) |
| Heap InUse | 193.6MB | 109.4MB | +84.2MB | 163.0MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 911.9MB | 379.2MB | +532.7MB | 1205.9MB | 1805.8MB | |
| Heap Objects | 1,099,856 | 285,727 | +814129 | 884,452 | 2,707,946 | |

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
| 2026-06-11 | 14 | 14,122 | 141.7MB | 199.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `bytes.growSlice` | 4.52MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.02MB |
| 7 | `compress/flate.NewWriter` | 2.64MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.51MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `bufio.NewReaderSize` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 17.81GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 13.87GB |
| 3 | `reflect.unsafe_NewArray` | 7.77GB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 5.46GB |
| 5 | `reflect.MakeSlice` | 4.35GB |
| 6 | `segmentio/kafka-go.makeLayout` | 1.93GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 1.71GB |
| 8 | `database/sql.convertAssignRows` | 1.58GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 1.04GB |
| 10 | `internal/reflectlite.unsafe_New` | 909.58MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 106.02MB | 83.58MB | 749.66MB | 0B |
| `evaluation.mergeMetadata` | 51.01MB | 38.51MB | 317.92MB | 0B |
| `local.(*Client).EvaluateV2` | 184.80MB | 146.07MB | 1.25GB | 0B |
| `local.topologicalSort` | 26.96MB | 22.38MB | 183.88MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 187.37MB | 155.27MB | 1.29GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 22.24MB | 9.94MB | 125.04MB | 0B |
| `localEvaluation.getMapOfValue` | 187.37MB | 155.27MB | 1.29GB | 0B |
| `utils.ParseFeatureFlag` | 187.37MB | 155.27MB | 1.29GB | 0B |

**Total FF alloc (current snapshot):** 953.12MB  |  **24h avg:** 6.46GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1296/1298 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.67MB | 49/1298 | `███████░░░░░░░░ 50%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.15MB | 31/1298 | `██████░░░░░░░░░ 44%` |
| 4 | `runtime.mallocgc` | 13.3MB | 1292/1298 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 11.57MB | 51/1298 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1298 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1298 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1298 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1293/1298 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1298 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 98.13GB | 1288/1298 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1298 | `█████████░░░░░░ 65%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1298 | `█████████░░░░░░ 64%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1298 | `█████████░░░░░░ 63%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 51.88GB | 1206/1298 | `███████░░░░░░░░ 52%` |
| 6 | `reflect.unsafe_NewArray` | 42.47GB | 1287/1298 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1298 | `█████░░░░░░░░░░ 34%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1298 | `█████░░░░░░░░░░ 34%` |
| 9 | `reflect.MakeSlice` | 23.89GB | 1278/1298 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 22.65GB | 1203/1298 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
