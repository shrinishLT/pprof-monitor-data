# Overview: stage
*Last updated: 2026-06-10 19:32 IST*
*Data range: 2026-05-15T16:03 to 2026-06-10T19:32 (1277 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,170 | avg: 14,206 | max: 28,205 | trend: stable (-0.30/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▁▁▁▃█▃▁▁▁▁▁▁▁▁▁▁▁▄▁▄▁▁▁▂▁▁▁▁▃▂▂▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▃▃▁▂▁▁▁▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▂▁▁▁▁
```

**Heap InUse** (current: 175.7MB | avg: 163.3MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▁▁▃▁▃▁▁▂▁▃▃▄▂▃▄▃▁▁▁▄█▃▂▄▃▄▄▂▃▂▂▂▃▂▂▂▁▄▃▄▁▂▂▄▁▃▂▃▃▂▃▃▂▂▂▃▃▂▂▁▁▂▂▂▂▂▃▁▃▂▂▂▃▄▃▃▁▃▁▂▂▁▂▁▇▃▁▃▃▃▁▂▁▄▃▃
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,170 | 14,073 | +97 | 14,206 | 28,205 | stable (-0.30/hr) |
| Heap InUse | 175.7MB | 160.8MB | +14.9MB | 163.3MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 192.6MB | 189.5MB | +3.1MB | 1220.3MB | 1805.8MB | |
| Heap Objects | 1,289,110 | 1,118,876 | +170234 | 885,701 | 2,707,946 | |

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
| 2026-06-10 | 40 | 14,128 | 153.4MB | 275.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 9.01MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `compress/flate.NewWriter` | 1.76MB |
| 8 | `reflect.mapassign_faststr0` | 1.5MB |
| 9 | `dotlapse-event-service/workerpool.NewWorker` | 1.5MB |
| 10 | `kafka-go/protocol.newPage` | 1.06MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 321.93MB |
| 2 | `reflect.unsafe_NewArray` | 130.0MB |
| 3 | `reflect.MakeSlice` | 87.5MB |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 5 | `segmentio/kafka-go.makeLayout` | 35.15MB |
| 6 | `v3/newrelic.newAnalyticsEvents` | 24.7MB |
| 7 | `internal/reflectlite.unsafe_New` | 20.5MB |
| 8 | `compress/flate.NewWriter` | 10.58MB |
| 9 | `kafka-go/protocol.(*decoder).read` | 10.5MB |
| 10 | `v3/newrelic.newLogEvents` | 9.65MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 5.13MB | 3.60MB | 1.26GB | 0B |
| `evaluation.mergeMetadata` | 2.00MB | 1.00MB | 544.21MB | 0B |
| `local.(*Client).EvaluateV2` | 7.22MB | 4.65MB | 2.14GB | 0B |
| `local.topologicalSort` | 1.00MB | 516.64kB | 315.97MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 6.70MB | 2.62MB | 2.22GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.04MB | 2.55MB | 216.09MB | 0B |
| `localEvaluation.getMapOfValue` | 6.70MB | 2.62MB | 2.22GB | 0B |
| `utils.ParseFeatureFlag` | 6.70MB | 2.62MB | 2.22GB | 0B |

**Total FF alloc (current snapshot):** 36.49MB  |  **24h avg:** 11.10GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1275/1277 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.67MB | 49/1277 | `███████░░░░░░░░ 50%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.15MB | 31/1277 | `██████░░░░░░░░░ 44%` |
| 4 | `runtime.mallocgc` | 13.34MB | 1271/1277 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 11.57MB | 51/1277 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1277 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1277 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1277 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1272/1277 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1277 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 99.59GB | 1267/1277 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1277 | `█████████░░░░░░ 64%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1277 | `█████████░░░░░░ 63%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1277 | `█████████░░░░░░ 62%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 51.91GB | 1205/1277 | `███████░░░░░░░░ 52%` |
| 6 | `reflect.unsafe_NewArray` | 43.11GB | 1266/1277 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1277 | `█████░░░░░░░░░░ 34%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1277 | `█████░░░░░░░░░░ 34%` |
| 9 | `reflect.MakeSlice` | 24.25GB | 1257/1277 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 22.66GB | 1202/1277 | `███░░░░░░░░░░░░ 22%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
