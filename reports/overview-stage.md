# Overview: stage
*Last updated: 2026-06-08 06:37 IST*
*Data range: 2026-05-15T16:03 to 2026-06-08T06:37 (1155 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,879 | avg: 14,211 | max: 28,205 | trend: stable (-0.35/hr))
```
▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▄▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▃▅▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▄▁▂▄█
```

**Heap InUse** (current: 163.8MB | avg: 164.1MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▂▂▁▁▁▂▂▃▂▁▁▂▃▁▁▂▁▃▃▃▃▁▂▂▁▂▂▂▃▃▂▂▁▃▁▁▃▂▃▁▂▁▂▁▃▃▁▆█▁▃▄▂▃▁▂▁▂▃▃▁▃▃▁▃▃▃▂▁▃▃▃▂▁▁▂▃▃▄▃▁▂▃▂▃▁▃▃▁▁▂▃▄▃▆▃
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 52%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,879 | 14,426 | +453 | 14,211 | 28,205 | stable (-0.35/hr) |
| Heap InUse | 163.8MB | 265.6MB | -101.8MB | 164.1MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 1097.5MB | 1097.6MB | -0.1MB | 1225.4MB | 1805.8MB | |
| Heap Objects | 702,276 | 1,849,396 | -1147120 | 884,320 | 2,707,946 | |

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
| 2026-06-08 | 14 | 14,197 | 164.7MB | 265.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `bytes.growSlice` | 4.02MB |
| 6 | `compress/flate.NewWriter` | 3.53MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `bufio.NewReaderSize` | 2.01MB |
| 9 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 140.71GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 71.24GB |
| 3 | `reflect.unsafe_NewArray` | 61.08GB |
| 4 | `reflect.MakeSlice` | 34.12GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 27.92GB |
| 6 | `segmentio/kafka-go.makeLayout` | 15.0GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 8.88GB |
| 8 | `database/sql.convertAssignRows` | 7.85GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 7.3GB |
| 10 | `internal/reflectlite.unsafe_New` | 6.89GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 787.95MB | 770.55MB | 691.87MB | 0B |
| `evaluation.mergeMetadata` | 341.08MB | 331.58MB | 296.78MB | 0B |
| `local.(*Client).EvaluateV2` | 1.33GB | 1.30GB | 1.16GB | 0B |
| `local.topologicalSort` | 205.96MB | 200.87MB | 179.02MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.37GB | 1.34GB | 1.19GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 135.75MB | 128.42MB | 121.27MB | 0B |
| `localEvaluation.getMapOfValue` | 1.37GB | 1.34GB | 1.19GB | 0B |
| `utils.ParseFeatureFlag` | 1.38GB | 1.35GB | 1.20GB | 0B |

**Total FF alloc (current snapshot):** 6.89GB  |  **24h avg:** 6.01GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1153/1155 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.33MB | 46/1155 | `███████░░░░░░░░ 50%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.42MB | 29/1155 | `██████░░░░░░░░░ 44%` |
| 4 | `runtime.mallocgc` | 13.37MB | 1149/1155 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 11.65MB | 48/1155 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1155 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1155 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1155 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1150/1155 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1155 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 89.69GB | 1145/1155 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1155 | `██████████░░░░░ 71%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1155 | `██████████░░░░░ 70%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1155 | `██████████░░░░░ 69%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 47.72GB | 1085/1155 | `███████░░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 38.82GB | 1144/1155 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1155 | `█████░░░░░░░░░░ 38%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1155 | `█████░░░░░░░░░░ 38%` |
| 9 | `reflect.MakeSlice` | 21.85GB | 1135/1155 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.27GB | 1082/1155 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
