# Overview: stage
*Last updated: 2026-06-04 18:31 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T18:31 (988 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,095 | avg: 14,224 | max: 28,205 | trend: stable (-0.36/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▂▂▁▄▁▆▁▁▁▁▁▁▁▁▁▁▁▁▄▁▅▁▂▁▁▂▄▁▁▁▃▂▁▆▁▁▁▁▁▂▁▁▁▁▁▁▁▃▂▁▁▁▆▁▁▁█▁▁▁▅▁▁▁▂▁▄▆▂▄▃▁▁▁▃▁▁
```

**Heap InUse** (current: 160.8MB | avg: 166.0MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▄▄▃▄▄▅▃▄▂▂▅▃▄▄▃▃▄▂▂▃▃▁▃▃▄▁▂▂▂▁▂▁▄▂▄▂▄▄▁▄▂▂▁▁▄▃▂▂▄▃▂▂█▄▂▄▄▃▁▁▁▃▁▂▂▃▃▂▂▂▁▇▃▁▃▅▁▃▁▅▂▁▂▂▁▃▅▁▂▃▄▃▃▃▄▃
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,095 | 14,105 | -10 | 14,224 | 28,205 | stable (-0.36/hr) |
| Heap InUse | 160.8MB | 184.1MB | -23.3MB | 166.0MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 386.3MB | 389.5MB | -3.2MB | 1274.3MB | 1805.8MB | |
| Heap Objects | 1,071,682 | 1,357,803 | -286121 | 883,970 | 2,707,946 | |

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
| 2026-06-04 | 37 | 14,179 | 144.7MB | 258.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 8 | `segmentio/kafka-go.makePartitions` | 1.5MB |
| 9 | `jasonlvhit/gocron.NewScheduler` | 1.08MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 1.07MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 4.91GB |
| 2 | `reflect.unsafe_NewArray` | 2.2GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 1.47GB |
| 4 | `reflect.MakeSlice` | 1.21GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 609.32MB |
| 6 | `segmentio/kafka-go.makeLayout` | 570.29MB |
| 7 | `v3/newrelic.newAnalyticsEvents` | 302.7MB |
| 8 | `internal/reflectlite.unsafe_New` | 257.52MB |
| 9 | `compress/flate.NewWriter` | 238.87MB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 199.5MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 96.55MB | 77.44MB | 4.68GB | 0B |
| `evaluation.mergeMetadata` | 44.01MB | 38.01MB | 2.00GB | 0B |
| `local.(*Client).EvaluateV2` | 169.18MB | 137.40MB | 7.84GB | 0B |
| `local.topologicalSort` | 19.84MB | 16.29MB | 1.08GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 141.78MB | 118.30MB | 8.91GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 41.30MB | 30.93MB | 18.24MB | 0B |
| `localEvaluation.getMapOfValue` | 141.78MB | 118.30MB | 8.91GB | 0B |
| `utils.ParseFeatureFlag` | 141.78MB | 118.30MB | 97.97MB | 0B |

**Total FF alloc (current snapshot):** 796.21MB  |  **24h avg:** 33.54GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 986/988 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.86MB | 38/988 | `███████░░░░░░░░ 48%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.24MB | 25/988 | `███████░░░░░░░░ 47%` |
| 4 | `runtime.mallocgc` | 13.44MB | 982/988 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 11.97MB | 40/988 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/988 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/988 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/988 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 983/988 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/988 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 93.8GB | 978/988 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/988 | `██████████░░░░░ 68%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/988 | `██████████░░░░░ 67%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/988 | `██████████░░░░░ 66%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 50.0GB | 930/988 | `███████░░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 40.59GB | 977/988 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/988 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/988 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 22.87GB | 968/988 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 22.59GB | 927/988 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
