# Overview: stage
*Last updated: 2026-06-04 11:31 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T11:31 (974 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,075 | avg: 14,224 | max: 28,205 | trend: stable (-0.38/hr))
```
▁▁▁▃▁▃▄▁█▃▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▂▂▁▃▁▅▁▁▁▁▁▁▁▁▁▁▁▁▃▁▄▁▂▁▁▂▄▁▁▁▂▁▁▅▁▁▁▁▁▂▁▁▁▁▁▁▁▂▂▁▁▁▅▁▁▁▆▁▁▁▄▁▁
```

**Heap InUse** (current: 99.6MB | avg: 166.2MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▂▂▂▄▃▄▃▁▅▄▂▃▂▃▄▄▃▄▄▅▃▄▂▂▅▃▄▄▃▃▄▂▂▃▃▁▃▃▄▁▂▂▂▁▂▁▄▂▄▂▄▄▁▄▂▂▁▁▄▃▂▂▄▃▂▂█▄▂▄▄▃▁▁▁▃▁▂▂▃▃▂▂▂▁▇▃▁▃▅▁▃▁▅▂▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,075 | 14,089 | -14 | 14,224 | 28,205 | stable (-0.38/hr) |
| Heap InUse | 99.6MB | 135.8MB | -36.2MB | 166.2MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 835.8MB | 834.9MB | +0.9MB | 1286.9MB | 1805.8MB | |
| Heap Objects | 277,493 | 798,205 | -520712 | 884,216 | 2,707,946 | |

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
| 2026-06-04 | 23 | 14,162 | 140.8MB | 258.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 10.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `segmentio/kafka-go.makePartitions` | 7.01MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 6 | `compress/flate.NewWriter` | 3.53MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.unsafe_NewArray` | 2.01MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `reflect.makemap` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 14.9GB |
| 2 | `segmentio/kafka-go.makePartitions` | 13.88GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 7.28GB |
| 4 | `reflect.unsafe_NewArray` | 6.09GB |
| 5 | `experiment/local.(*Client).EvaluateV2` | 3.63GB |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 3.61GB |
| 7 | `internal/evaluation.mergeMetadata` | 3.48GB |
| 8 | `reflect.MakeSlice` | 3.32GB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.23GB |
| 10 | `database/sql.convertAssignRows` | 2.05GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 8.18GB | 8.13GB | 6.06GB | 0B |
| `evaluation.mergeMetadata` | 3.48GB | 3.45GB | 2.59GB | 0B |
| `local.(*Client).EvaluateV2` | 13.73GB | 13.64GB | 10.14GB | 0B |
| `local.topologicalSort` | 1.89GB | 1.88GB | 1.39GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 15.61GB | 15.52GB | 11.53GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 28.00MB | 25.41MB | 17.97MB | 0B |
| `localEvaluation.getMapOfValue` | 15.61GB | 15.52GB | 11.53GB | 0B |
| `utils.ParseFeatureFlag` | 191.19MB | 170.11MB | 111.38MB | 0B |

**Total FF alloc (current snapshot):** 58.71GB  |  **24h avg:** 43.39GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 972/974 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.9MB | 37/974 | `███████░░░░░░░░ 48%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.29MB | 24/974 | `███████░░░░░░░░ 47%` |
| 4 | `runtime.mallocgc` | 13.5MB | 968/974 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 12.06MB | 39/974 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/974 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/974 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/974 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 970/974 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/974 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 95.0GB | 965/974 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 64.96GB | 315/974 | `██████████░░░░░ 68%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 64.27GB | 316/974 | `██████████░░░░░ 67%` |
| 4 | `internal/evaluation.mergeMetadata` | 63.78GB | 310/974 | `██████████░░░░░ 67%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 50.55GB | 919/974 | `███████░░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 41.11GB | 964/974 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.67GB | 291/974 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.57GB | 297/974 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 23.17GB | 955/974 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 22.81GB | 917/974 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
