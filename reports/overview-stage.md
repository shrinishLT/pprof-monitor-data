# Overview: stage
*Last updated: 2026-06-09 14:02 IST*
*Data range: 2026-05-15T16:03 to 2026-06-09T14:02 (1218 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,138 | avg: 14,210 | max: 28,205 | trend: stable (-0.31/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▄▁▁▁▁▁▁▁▂▁▁▁▁▂▁▃▁▃▁▁▁▁█▁▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▂▄▂▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁
```

**Heap InUse** (current: 121.0MB | avg: 163.7MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▁▃▃▃▂▁▃▄▄▂▁▁▂▃▄▄▃▁▂▃▃▃▁▃▃▁▁▂▃▄▃▇▃▂▁▂▃▂▂▂▃▂▁▄▂▂▁▄▂▃▃▂▄▂▃▂▄▃▁▁▁▃▁▄▁▁▂▁▃▃▄▂▃▄▃▁▁▁▄█▃▂▄▃▄▄▂▃▂▂▂▃▂▂▂▁
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,138 | 14,448 | -310 | 14,210 | 28,205 | stable (-0.31/hr) |
| Heap InUse | 121.0MB | 153.9MB | -32.9MB | 163.7MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 1238.2MB | 1237.6MB | +0.6MB | 1220.7MB | 1805.8MB | |
| Heap Objects | 480,590 | 732,411 | -251821 | 884,847 | 2,707,946 | |

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
| 2026-06-09 | 29 | 14,170 | 162.2MB | 283.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 6 | `reflect.mapassign_faststr0` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.unsafe_NewArray` | 2.0MB |
| 9 | `compress/flate.NewWriter` | 1.76MB |
| 10 | `encoding/json.(*decodeState).literalStore` | 1.54MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 197.96GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 92.92GB |
| 3 | `reflect.unsafe_NewArray` | 85.64GB |
| 4 | `reflect.MakeSlice` | 47.87GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 36.5GB |
| 6 | `segmentio/kafka-go.makeLayout` | 21.09GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 11.64GB |
| 8 | `database/sql.convertAssignRows` | 10.34GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 10.13GB |
| 10 | `internal/reflectlite.unsafe_New` | 9.61GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.13GB | 1.12GB | 1.02GB | 0B |
| `evaluation.mergeMetadata` | 492.62MB | 488.62MB | 448.00MB | 0B |
| `local.(*Client).EvaluateV2` | 1.95GB | 1.93GB | 1.76GB | 0B |
| `local.topologicalSort` | 295.83MB | 292.78MB | 267.92MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.01GB | 2.00GB | 1.82GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 193.36MB | 192.86MB | 179.13MB | 0B |
| `localEvaluation.getMapOfValue` | 2.01GB | 2.00GB | 1.82GB | 0B |
| `utils.ParseFeatureFlag` | 2.02GB | 2.00GB | 1.82GB | 0B |

**Total FF alloc (current snapshot):** 10.08GB  |  **24h avg:** 9.11GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1216/1218 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.26MB | 48/1218 | `███████░░░░░░░░ 49%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.15MB | 31/1218 | `██████░░░░░░░░░ 44%` |
| 4 | `runtime.mallocgc` | 13.35MB | 1212/1218 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 11.61MB | 50/1218 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1218 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1218 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1218 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1213/1218 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1218 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 93.87GB | 1208/1218 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1218 | `██████████░░░░░ 67%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1218 | `██████████░░░░░ 67%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1218 | `██████████░░░░░ 66%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 49.41GB | 1148/1218 | `███████░░░░░░░░ 52%` |
| 6 | `reflect.unsafe_NewArray` | 40.63GB | 1207/1218 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1218 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1218 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 22.87GB | 1198/1218 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.79GB | 1145/1218 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
