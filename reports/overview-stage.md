# Overview: stage
*Last updated: 2026-06-08 09:01 IST*
*Data range: 2026-05-15T16:03 to 2026-06-08T09:01 (1160 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,082 | avg: 14,210 | max: 28,205 | trend: stable (-0.35/hr))
```
▁▁▁▁▁▁▁▁▁▁▂▁▄▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▃▅▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▄▁▂▄█▁▁▁▁▁
```

**Heap InUse** (current: 149.0MB | avg: 164.1MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▂▂▃▂▁▁▂▃▁▁▂▁▃▃▃▃▁▂▂▁▂▂▂▃▃▂▂▁▃▁▁▃▂▃▁▂▁▂▁▃▃▁▆█▁▃▄▂▃▁▂▁▂▃▃▁▃▃▁▃▃▃▂▁▃▃▃▂▁▁▂▃▃▄▃▁▂▃▂▃▁▃▃▁▁▂▃▄▃▆▃▂▁▂▃▂
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,082 | 14,075 | +7 | 14,210 | 28,205 | stable (-0.35/hr) |
| Heap InUse | 149.0MB | 166.4MB | -17.4MB | 164.1MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 1098.1MB | 1098.1MB | +0.0MB | 1224.9MB | 1805.8MB | |
| Heap Objects | 913,677 | 1,109,147 | -195470 | 884,249 | 2,707,946 | |

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
| 2026-06-08 | 19 | 14,171 | 159.9MB | 265.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.unsafe_NewArray` | 1.5MB |
| 9 | `kafka-go/protocol.newPage` | 1.06MB |
| 10 | `reflect.growslice` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 144.89GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 71.34GB |
| 3 | `reflect.unsafe_NewArray` | 62.9GB |
| 4 | `reflect.MakeSlice` | 35.13GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 27.96GB |
| 6 | `segmentio/kafka-go.makeLayout` | 15.44GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 8.89GB |
| 8 | `database/sql.convertAssignRows` | 7.87GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 7.52GB |
| 10 | `internal/reflectlite.unsafe_New` | 7.09GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 815.08MB | 813.54MB | 713.11MB | 0B |
| `evaluation.mergeMetadata` | 356.59MB | 355.59MB | 306.64MB | 0B |
| `local.(*Client).EvaluateV2` | 1.37GB | 1.37GB | 1.20GB | 0B |
| `local.topologicalSort` | 211.58MB | 210.55MB | 184.32MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.42GB | 1.41GB | 1.23GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 138.36MB | 138.36MB | 124.26MB | 0B |
| `localEvaluation.getMapOfValue` | 1.42GB | 1.41GB | 1.23GB | 0B |
| `utils.ParseFeatureFlag` | 1.42GB | 1.41GB | 1.23GB | 0B |

**Total FF alloc (current snapshot):** 7.11GB  |  **24h avg:** 6.20GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1158/1160 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.33MB | 46/1160 | `███████░░░░░░░░ 50%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.42MB | 29/1160 | `██████░░░░░░░░░ 44%` |
| 4 | `runtime.mallocgc` | 13.37MB | 1154/1160 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 11.65MB | 48/1160 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1160 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1160 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1160 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1155/1160 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1160 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 89.93GB | 1150/1160 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1160 | `██████████░░░░░ 70%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1160 | `██████████░░░░░ 70%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1160 | `██████████░░░░░ 69%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 47.83GB | 1090/1160 | `███████░░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 38.92GB | 1149/1160 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1160 | `█████░░░░░░░░░░ 38%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1160 | `█████░░░░░░░░░░ 37%` |
| 9 | `reflect.MakeSlice` | 21.91GB | 1140/1160 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.3GB | 1087/1160 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
