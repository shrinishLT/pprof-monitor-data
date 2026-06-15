# Overview: stage
*Last updated: 2026-06-15 14:33 IST*
*Data range: 2026-05-15T16:03 to 2026-06-15T14:33 (1506 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,192 | avg: 14,193 | max: 28,205 | trend: stable (-0.27/hr))
```
▁▁▁▅▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▃▁▂▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▂▁█▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▂
```

**Heap InUse** (current: 116.4MB | avg: 160.9MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▄▅▁▄▃▂▄▃▁▁▄▁▂▂▁▄▃▁▄▃▃▂▄▁▃▁▃▄▃▃█▄▄▂▂▂▁▄▁▂▁▄▂▁▃▁▄▁▁▁▃▄▄▂▂▄▃▁▁▃▂▅▄▂▂▂▂▂▃▂▃▅▃▄▁▂▄▂▄▇▂▅▂▂▃▁▃▄▁▅▁▂▅▄▄▁
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,192 | 14,132 | +60 | 14,193 | 28,205 | stable (-0.27/hr) |
| Heap InUse | 116.4MB | 173.6MB | -57.2MB | 160.9MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 556.0MB | 557.3MB | -1.3MB | 1187.7MB | 1805.8MB | |
| Heap Objects | 265,008 | 1,252,028 | -987020 | 879,665 | 2,707,946 | |

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
| 2026-06-15 | 30 | 14,131 | 156.6MB | 238.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.51MB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 12.89MB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 11.18MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 7 | `database/sql.convertAssignRows` | 6.0MB |
| 8 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `reflect.unsafe_New` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 2.04GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 1.96GB |
| 3 | `reflect.unsafe_NewArray` | 919.38MB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 817.71MB |
| 5 | `reflect.MakeSlice` | 487.01MB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 321.8MB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 279.01MB |
| 8 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 256.95MB |
| 9 | `segmentio/kafka-go.makeLayout` | 238.18MB |
| 10 | `database/sql.convertAssignRows` | 226.51MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 33.88MB | 19.97MB | 637.08MB | 0B |
| `evaluation.mergeMetadata` | 15.50MB | 9.00MB | 280.91MB | 0B |
| `local.(*Client).EvaluateV2` | 56.02MB | 32.13MB | 1.03GB | 0B |
| `local.topologicalSort` | 4.55MB | 1.50MB | 133.26MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 54.02MB | 30.60MB | 1.02GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 4.59MB | 3.08MB | 126.08MB | 0B |
| `localEvaluation.getMapOfValue` | 54.02MB | 30.60MB | 1.02GB | 0B |
| `utils.ParseFeatureFlag` | 54.02MB | 30.60MB | 1.03GB | 0B |

**Total FF alloc (current snapshot):** 276.60MB  |  **24h avg:** 5.25GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1504/1506 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.77MB | 56/1506 | `███████░░░░░░░░ 51%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 15.47MB | 35/1506 | `██████░░░░░░░░░ 42%` |
| 4 | `runtime.mallocgc` | 12.78MB | 1500/1506 | `█████░░░░░░░░░░ 34%` |
| 5 | `database/sql.convertAssignRows` | 11.44MB | 58/1506 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1506 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1506 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1506 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1501/1506 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1506 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 94.37GB | 1496/1506 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1506 | `██████████░░░░░ 67%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1506 | `██████████░░░░░ 66%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1506 | `█████████░░░░░░ 66%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 50.18GB | 1387/1506 | `███████░░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 40.8GB | 1495/1506 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1506 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1506 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 22.93GB | 1486/1506 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.79GB | 1383/1506 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.6x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.5x avg)
