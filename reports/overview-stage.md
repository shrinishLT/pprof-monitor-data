# Overview: stage
*Last updated: 2026-06-09 06:03 IST*
*Data range: 2026-05-15T16:03 to 2026-06-09T06:03 (1202 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,876 | avg: 14,211 | max: 28,205 | trend: stable (-0.31/hr))
```
▂▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▄▁▁▁▁▁▁▁▂▁▁▁▁▂▁▃▁▃▁▁▁▁█▁▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▂▄
```

**Heap InUse** (current: 283.6MB | avg: 163.8MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▆█▁▃▄▂▃▁▂▁▂▃▃▁▃▃▁▃▃▃▂▁▃▃▃▂▁▁▂▃▃▄▃▁▂▃▂▃▁▃▃▁▁▂▃▄▃▆▃▂▁▂▃▂▂▂▃▂▁▃▂▂▁▃▂▃▃▂▃▂▃▂▄▃▁▁▁▃▁▃▁▁▂▁▃▃▃▂▃▄▃▁▁▁▃▇
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 52%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 15%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,876 | 14,320 | +556 | 14,211 | 28,205 | stable (-0.31/hr) |
| Heap InUse | 283.6MB | 188.5MB | +95.1MB | 163.8MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 1133.8MB | 1098.2MB | +35.6MB | 1220.5MB | 1805.8MB | |
| Heap Objects | 1,190,120 | 1,217,386 | -27266 | 883,908 | 2,707,946 | |

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
| 2026-06-09 | 13 | 14,191 | 166.9MB | 283.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 16.55MB |
| 3 | `database/sql.convertAssignRows` | 15.0MB |
| 4 | `runtime.mallocgc` | 13.1MB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 11.51MB |
| 6 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 8 | `bytes.growSlice` | 7.53MB |
| 9 | `bufio.NewReaderSize` | 5.03MB |
| 10 | `aes/gcm.NewGCMForTLS13` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 183.58GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 80.83GB |
| 3 | `reflect.unsafe_NewArray` | 79.42GB |
| 4 | `reflect.MakeSlice` | 44.41GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 31.76GB |
| 6 | `segmentio/kafka-go.makeLayout` | 19.52GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 10.14GB |
| 8 | `v3/newrelic.newAnalyticsEvents` | 9.42GB |
| 9 | `database/sql.convertAssignRows` | 9.0GB |
| 10 | `internal/reflectlite.unsafe_New` | 8.92GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.05GB | 1.04GB | 948.92MB | 0B |
| `evaluation.mergeMetadata` | 460.61MB | 457.11MB | 409.00MB | 0B |
| `local.(*Client).EvaluateV2` | 1.81GB | 1.80GB | 1.59GB | 0B |
| `local.topologicalSort` | 275.56MB | 272.48MB | 243.33MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.87GB | 1.86GB | 1.64GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 181.88MB | 178.75MB | 162.83MB | 0B |
| `localEvaluation.getMapOfValue` | 1.87GB | 1.86GB | 1.64GB | 0B |
| `utils.ParseFeatureFlag` | 1.87GB | 1.86GB | 1.65GB | 0B |

**Total FF alloc (current snapshot):** 9.38GB  |  **24h avg:** 8.25GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1200/1202 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.26MB | 48/1202 | `███████░░░░░░░░ 49%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.15MB | 31/1202 | `██████░░░░░░░░░ 44%` |
| 4 | `runtime.mallocgc` | 13.36MB | 1196/1202 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 11.61MB | 50/1202 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1202 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1202 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1202 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1197/1202 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1202 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 92.56GB | 1192/1202 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1202 | `██████████░░░░░ 68%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1202 | `██████████░░░░░ 68%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1202 | `██████████░░░░░ 67%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 48.81GB | 1132/1202 | `███████░░░░░░░░ 52%` |
| 6 | `reflect.unsafe_NewArray` | 40.07GB | 1191/1202 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1202 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1202 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 22.55GB | 1182/1202 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.59GB | 1129/1202 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
