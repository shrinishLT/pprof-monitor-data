# Overview: stage
*Last updated: 2026-06-04 12:32 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T12:32 (976 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,165 | avg: 14,224 | max: 28,205 | trend: stable (-0.38/hr))
```
▁▃▁▃▄▁█▃▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▂▂▁▃▁▅▁▁▁▁▁▁▁▁▁▁▁▁▃▁▄▁▂▁▁▂▄▁▁▁▂▁▁▅▁▁▁▁▁▂▁▁▁▁▁▁▁▂▂▁▁▁▅▁▁▁▆▁▁▁▄▁▁▁▁
```

**Heap InUse** (current: 128.3MB | avg: 166.2MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▂▄▃▄▃▁▅▄▂▃▂▃▄▄▃▄▄▅▃▄▂▂▅▃▄▄▃▃▄▂▂▃▃▁▃▃▄▁▂▂▂▁▂▁▄▂▄▂▄▄▁▄▂▂▁▁▄▃▂▂▄▃▂▂█▄▂▄▄▃▁▁▁▃▁▂▂▃▃▂▂▂▁▇▃▁▃▅▁▃▁▅▂▁▂▂
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,165 | 14,066 | +99 | 14,224 | 28,205 | stable (-0.38/hr) |
| Heap InUse | 128.3MB | 143.0MB | -14.7MB | 166.2MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 834.8MB | 834.9MB | -0.1MB | 1286.0MB | 1805.8MB | |
| Heap Objects | 627,638 | 896,933 | -269295 | 883,966 | 2,707,946 | |

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
| 2026-06-04 | 25 | 14,158 | 140.4MB | 258.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 10.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `segmentio/kafka-go.makePartitions` | 4.0MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 6 | `compress/flate.NewWriter` | 3.53MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `bytes.growSlice` | 1.51MB |
| 10 | `bufio.NewReaderSize` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 15.75GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 14.9GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 7.28GB |
| 4 | `reflect.unsafe_NewArray` | 6.87GB |
| 5 | `reflect.MakeSlice` | 3.75GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 3.68GB |
| 7 | `internal/evaluation.(*Engine).Evaluate` | 3.65GB |
| 8 | `internal/evaluation.mergeMetadata` | 3.52GB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.23GB |
| 10 | `database/sql.convertAssignRows` | 2.05GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 8.28GB | 8.18GB | 6.23GB | 0B |
| `evaluation.mergeMetadata` | 3.52GB | 3.48GB | 2.66GB | 0B |
| `local.(*Client).EvaluateV2` | 13.90GB | 13.73GB | 10.43GB | 0B |
| `local.topologicalSort` | 1.91GB | 1.89GB | 1.43GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 15.81GB | 15.61GB | 11.85GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 31.64MB | 28.00MB | 18.88MB | 0B |
| `localEvaluation.getMapOfValue` | 15.81GB | 15.61GB | 11.85GB | 0B |
| `utils.ParseFeatureFlag` | 203.07MB | 192.73MB | 118.03MB | 0B |

**Total FF alloc (current snapshot):** 59.47GB  |  **24h avg:** 44.59GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 974/976 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.9MB | 37/976 | `███████░░░░░░░░ 48%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.29MB | 24/976 | `███████░░░░░░░░ 47%` |
| 4 | `runtime.mallocgc` | 13.49MB | 970/976 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 12.06MB | 39/976 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/976 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/976 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/976 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 972/976 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/976 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 94.84GB | 967/976 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 64.58GB | 317/976 | `██████████░░░░░ 68%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.89GB | 318/976 | `██████████░░░░░ 67%` |
| 4 | `internal/evaluation.mergeMetadata` | 63.39GB | 312/976 | `██████████░░░░░ 66%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 50.48GB | 921/976 | `███████░░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 41.04GB | 966/976 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.67GB | 291/976 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.57GB | 297/976 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 23.12GB | 957/976 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 22.78GB | 919/976 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
