# Overview: stage
*Last updated: 2026-06-06 13:31 IST*
*Data range: 2026-05-15T16:03 to 2026-06-06T13:31 (1074 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,139 | avg: 14,217 | max: 28,205 | trend: stable (-0.35/hr))
```
█▂▅▃▁▁▁▃▁▁▁▁▄▁▁▃▁▁▁▁▁▁▁▁▁▁▂▃▃▁▃▇▄▅▁▁▁▁▁▁▁▁▁▁▁▁▃▁▂▁▂▂▃▇▁▁▁▁▄▃▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▄▂▄▄▁▁▁▁▁▁▂▁▁▁▁▁▁▂
```

**Heap InUse** (current: 125.0MB | avg: 164.7MB | max: 732.9MB | trend: stable (-0.05MB/hr))
```
▃▁▂▃▃▂▂▂▃▂▂▁▁▁▁▁▂▂▁▂▁▁▁▂▂▁▁▂▃▂▂▃█▆▃▂▂▁▃▃▁▃▃▂▂▂▁▃▅▃▂▂▃▂▃▃▂▃▁▂▃▂▃▂▂▁▁▁▃▁▃▂▃▂▂▁▁▃▂▁▄▂▂▁▁▁▂▂▃▂▁▁▂▃▁▁
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,139 | 14,129 | +10 | 14,217 | 28,205 | stable (-0.35/hr) |
| Heap InUse | 125.0MB | 117.5MB | +7.5MB | 164.7MB | 732.9MB | stable (-0.05MB/hr) |
| Heap Sys | 988.4MB | 988.4MB | +0.0MB | 1238.3MB | 1805.8MB | |
| Heap Objects | 549,291 | 498,039 | +51252 | 879,929 | 2,707,946 | |

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
| 2026-06-06 | 28 | 14,132 | 143.4MB | 231.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.13MB |
| 3 | `runtime.mallocgc` | 13.1MB |
| 4 | `database/sql.convertAssignRows` | 11.0MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 8.12MB |
| 8 | `segmentio/kafka-go.makePartitions` | 4.51MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 66.12GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 34.79GB |
| 3 | `reflect.unsafe_NewArray` | 28.66GB |
| 4 | `reflect.MakeSlice` | 16.09GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 13.66GB |
| 6 | `segmentio/kafka-go.makeLayout` | 7.13GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 4.34GB |
| 8 | `database/sql.convertAssignRows` | 3.78GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 3.47GB |
| 10 | `internal/reflectlite.unsafe_New` | 3.23GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 437.66MB | 427.84MB | 326.89MB | 0B |
| `evaluation.mergeMetadata` | 182.05MB | 177.04MB | 135.35MB | 0B |
| `local.(*Client).EvaluateV2` | 761.17MB | 742.38MB | 565.83MB | 0B |
| `local.topologicalSort` | 115.43MB | 112.88MB | 86.80MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 769.66MB | 750.89MB | 567.71MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 82.78MB | 82.24MB | 65.62MB | 0B |
| `localEvaluation.getMapOfValue` | 769.66MB | 750.89MB | 567.71MB | 0B |
| `utils.ParseFeatureFlag` | 770.66MB | 751.90MB | 568.71MB | 0B |

**Total FF alloc (current snapshot):** 3.80GB  |  **24h avg:** 2.82GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1072/1074 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.2MB | 43/1074 | `███████░░░░░░░░ 49%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.64MB | 28/1074 | `██████░░░░░░░░░ 45%` |
| 4 | `runtime.mallocgc` | 13.39MB | 1068/1074 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 11.89MB | 45/1074 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1074 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1074 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1074 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1069/1074 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1074 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 88.63GB | 1064/1074 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1074 | `██████████░░░░░ 71%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1074 | `██████████░░░░░ 71%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1074 | `██████████░░░░░ 70%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 47.7GB | 1004/1074 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 38.35GB | 1063/1074 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1074 | `█████░░░░░░░░░░ 38%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1074 | `█████░░░░░░░░░░ 38%` |
| 9 | `reflect.MakeSlice` | 21.6GB | 1054/1074 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.46GB | 1001/1074 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
