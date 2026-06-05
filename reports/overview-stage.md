# Overview: stage
*Last updated: 2026-06-06 04:32 IST*
*Data range: 2026-05-15T16:03 to 2026-06-06T04:32 (1056 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,097 | avg: 14,219 | max: 28,205 | trend: stable (-0.36/hr))
```
▁▁▁▆▁▁▁█▁▁▁▅▁▁▁▂▁▄▆▂▄▃▁▁▁▃▁▁▁▁▃▁▁▃▁▁▁▁▁▁▁▁▁▁▂▃▂▁▂▆▄▅▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▂▃▆▁▁▁▁▄▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁
```

**Heap InUse** (current: 174.7MB | avg: 165.1MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▁▂▁▅▃▁▂▃▁▂▁▄▂▁▂▂▁▂▃▁▂▃▃▂▂▂▃▂▂▁▁▁▁▁▂▂▁▂▁▁▁▂▂▁▁▂▃▂▂▃█▆▃▂▂▁▃▃▁▃▃▂▂▂▁▃▅▃▂▂▃▂▃▃▂▃▁▂▃▂▃▂▂▁▁▁▃▁▃▂▃▂▂▁▁▃
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,097 | 14,353 | -256 | 14,219 | 28,205 | stable (-0.36/hr) |
| Heap InUse | 174.7MB | 125.4MB | +49.3MB | 165.1MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 987.9MB | 988.9MB | -1.0MB | 1242.6MB | 1805.8MB | |
| Heap Objects | 1,196,807 | 360,298 | +836509 | 882,861 | 2,707,946 | |

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
| 2026-06-06 | 10 | 14,123 | 146.2MB | 174.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `segmentio/kafka-go.makePartitions` | 6.51MB |
| 6 | `reflect.unsafe_NewArray` | 3.01MB |
| 7 | `compress/flate.NewWriter` | 2.64MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.0MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 1.07MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 49.96GB |
| 2 | `reflect.unsafe_NewArray` | 21.63GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 18.88GB |
| 4 | `reflect.MakeSlice` | 12.24GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 7.42GB |
| 6 | `segmentio/kafka-go.makeLayout` | 5.42GB |
| 7 | `v3/newrelic.newAnalyticsEvents` | 2.64GB |
| 8 | `internal/reflectlite.unsafe_New` | 2.46GB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.36GB |
| 10 | `database/sql.convertAssignRows` | 2.07GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 363.59MB | 362.59MB | 203.24MB | 0B |
| `evaluation.mergeMetadata` | 153.04MB | 153.04MB | 84.04MB | 0B |
| `local.(*Client).EvaluateV2` | 626.64MB | 623.08MB | 354.81MB | 0B |
| `local.topologicalSort` | 96.59MB | 95.07MB | 55.26MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 627.48MB | 623.40MB | 360.11MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 73.42MB | 73.42MB | 38.46MB | 0B |
| `localEvaluation.getMapOfValue` | 627.48MB | 623.40MB | 360.11MB | 0B |
| `utils.ParseFeatureFlag` | 628.48MB | 624.40MB | 361.12MB | 0B |

**Total FF alloc (current snapshot):** 3.12GB  |  **24h avg:** 1.77GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1054/1056 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.27MB | 41/1056 | `███████░░░░░░░░ 49%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.36MB | 26/1056 | `███████░░░░░░░░ 47%` |
| 4 | `runtime.mallocgc` | 13.39MB | 1050/1056 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 11.95MB | 43/1056 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1056 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1056 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1056 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1051/1056 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1056 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 89.15GB | 1046/1056 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1056 | `██████████░░░░░ 71%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1056 | `██████████░░░░░ 70%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1056 | `██████████░░░░░ 70%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 47.99GB | 986/1056 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 38.58GB | 1045/1056 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1056 | `█████░░░░░░░░░░ 38%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1056 | `█████░░░░░░░░░░ 38%` |
| 9 | `reflect.MakeSlice` | 21.72GB | 1036/1056 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.63GB | 983/1056 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
