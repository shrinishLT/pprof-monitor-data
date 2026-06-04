# Overview: stage
*Last updated: 2026-06-04 11:00 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T11:00 (973 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,089 | avg: 14,225 | max: 28,205 | trend: stable (-0.37/hr))
```
▁▁▁▁▃▁▃▄▁█▃▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▂▂▁▃▁▅▁▁▁▁▁▁▁▁▁▁▁▁▃▁▄▁▂▁▁▂▄▁▁▁▂▁▁▅▁▁▁▁▁▂▁▁▁▁▁▁▁▂▂▁▁▁▅▁▁▁▆▁▁▁▄▁
```

**Heap InUse** (current: 135.8MB | avg: 166.3MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▂▂▂▂▄▃▄▃▁▅▄▂▃▂▃▄▄▃▄▄▅▃▄▂▂▅▃▄▄▃▃▄▂▂▃▃▁▃▃▄▁▂▂▂▁▂▁▄▂▄▂▄▄▁▄▂▂▁▁▄▃▂▂▄▃▂▂█▄▂▄▄▃▁▁▁▃▁▂▂▃▃▂▂▂▁▇▃▁▃▅▁▃▁▅▂
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,089 | 14,482 | -393 | 14,225 | 28,205 | stable (-0.37/hr) |
| Heap InUse | 135.8MB | 203.7MB | -67.9MB | 166.3MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 834.9MB | 834.6MB | +0.3MB | 1287.4MB | 1805.8MB | |
| Heap Objects | 798,205 | 1,434,130 | -635925 | 884,839 | 2,707,946 | |

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
| 2026-06-04 | 22 | 14,166 | 142.7MB | 258.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 10.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 5 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.01MB |
| 7 | `aws/endpoints.init` | 2.0MB |
| 8 | `compress/flate.NewWriter` | 1.76MB |
| 9 | `kafka-go/protocol.newPage` | 1.6MB |
| 10 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 14.9GB |
| 2 | `segmentio/kafka-go.makePartitions` | 12.96GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 7.28GB |
| 4 | `reflect.unsafe_NewArray` | 5.68GB |
| 5 | `experiment/local.(*Client).EvaluateV2` | 3.6GB |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 3.59GB |
| 7 | `internal/evaluation.mergeMetadata` | 3.45GB |
| 8 | `reflect.MakeSlice` | 3.1GB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.23GB |
| 10 | `database/sql.convertAssignRows` | 2.05GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 8.13GB | 7.65GB | 5.97GB | 0B |
| `evaluation.mergeMetadata` | 3.45GB | 3.25GB | 2.55GB | 0B |
| `local.(*Client).EvaluateV2` | 13.64GB | 12.83GB | 9.99GB | 0B |
| `local.topologicalSort` | 1.88GB | 1.77GB | 1.37GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 15.52GB | 14.61GB | 11.36GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 25.41MB | 21.75MB | 17.54MB | 0B |
| `localEvaluation.getMapOfValue` | 15.52GB | 14.61GB | 11.36GB | 0B |
| `utils.ParseFeatureFlag` | 170.11MB | 158.30MB | 107.91MB | 0B |

**Total FF alloc (current snapshot):** 58.33GB  |  **24h avg:** 42.72GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 971/973 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.9MB | 37/973 | `███████░░░░░░░░ 48%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.29MB | 24/973 | `███████░░░░░░░░ 47%` |
| 4 | `runtime.mallocgc` | 13.5MB | 967/973 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 12.06MB | 39/973 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/973 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/973 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/973 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 969/973 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/973 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 95.09GB | 964/973 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 65.16GB | 314/973 | `██████████░░░░░ 68%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 64.46GB | 315/973 | `██████████░░░░░ 67%` |
| 4 | `internal/evaluation.mergeMetadata` | 63.97GB | 309/973 | `██████████░░░░░ 67%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 50.59GB | 918/973 | `███████░░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 41.15GB | 963/973 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.67GB | 291/973 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.57GB | 297/973 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 23.19GB | 954/973 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 22.83GB | 916/973 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
