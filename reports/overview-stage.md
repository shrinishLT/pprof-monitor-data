# Overview: stage
*Last updated: 2026-06-04 08:32 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T08:32 (968 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,693 | avg: 14,225 | max: 28,205 | trend: stable (-0.38/hr))
```
▁▁▁▁▁▁▁▁▁▃▁▃▄▁█▃▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▂▂▁▃▁▅▁▁▁▁▁▁▁▁▁▁▁▁▃▁▄▁▂▁▁▂▄▁▁▁▂▁▁▅▁▁▁▁▁▂▁▁▁▁▁▁▁▂▂▁▁▁▅▁▁▁▆
```

**Heap InUse** (current: 192.8MB | avg: 166.4MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▃▁▃▄▁▂▂▂▂▄▃▄▃▁▅▄▂▃▂▃▄▄▃▄▄▅▃▄▁▂▅▃▄▄▂▃▄▂▂▃▃▁▃▃▄▁▂▂▂▁▂▁▄▂▄▂▄▄▁▄▂▂▁▁▄▃▂▂▄▃▂▂█▄▂▄▄▃▁▁▁▃▁▁▂▃▃▂▂▂▁▇▃▁▃▅
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 52%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,693 | 14,072 | +621 | 14,225 | 28,205 | stable (-0.38/hr) |
| Heap InUse | 192.8MB | 157.5MB | +35.3MB | 166.4MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 835.2MB | 837.2MB | -2.0MB | 1289.7MB | 1805.8MB | |
| Heap Objects | 956,673 | 1,097,688 | -141015 | 885,163 | 2,707,946 | |

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
| 2026-06-04 | 17 | 14,168 | 143.4MB | 258.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 10.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 5 | `bytes.growSlice` | 3.52MB |
| 6 | `bufio.NewReaderSize` | 3.51MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `reflect.unsafe_NewArray` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 13.3GB |
| 2 | `segmentio/kafka-go.makePartitions` | 8.51GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 6.54GB |
| 4 | `reflect.unsafe_NewArray` | 3.75GB |
| 5 | `experiment/local.(*Client).EvaluateV2` | 2.97GB |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 2.96GB |
| 7 | `internal/evaluation.mergeMetadata` | 2.85GB |
| 8 | `reflect.MakeSlice` | 2.02GB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.01GB |
| 10 | `database/sql.convertAssignRows` | 1.82GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 6.70GB | 6.31GB | 5.52GB | 1.54MB |
| `evaluation.mergeMetadata` | 2.85GB | 2.70GB | 2.37GB | 1.00MB |
| `local.(*Client).EvaluateV2` | 11.26GB | 10.59GB | 9.22GB | 1.54MB |
| `local.topologicalSort` | 1.56GB | 1.47GB | 1.26GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 12.82GB | 12.06GB | 10.47GB | 1.54MB |
| `localEvaluation.GetFeatureFlagPayload` | 14.47MB | 8.77MB | 16.94MB | 0B |
| `localEvaluation.getMapOfValue` | 12.82GB | 12.06GB | 10.47GB | 1.54MB |
| `utils.ParseFeatureFlag` | 113.30MB | 100.86MB | 97.33MB | 0B |

**Total FF alloc (current snapshot):** 48.14GB  |  **24h avg:** 39.42GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 966/968 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.9MB | 37/968 | `███████░░░░░░░░ 48%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.29MB | 24/968 | `███████░░░░░░░░ 47%` |
| 4 | `runtime.mallocgc` | 13.52MB | 962/968 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 12.06MB | 39/968 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/968 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/968 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/968 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 964/968 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/968 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 95.53GB | 959/968 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 66.16GB | 309/968 | `██████████░░░░░ 69%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 65.45GB | 310/968 | `██████████░░░░░ 68%` |
| 4 | `internal/evaluation.mergeMetadata` | 64.97GB | 304/968 | `██████████░░░░░ 68%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 50.79GB | 913/968 | `███████░░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 41.33GB | 958/968 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.67GB | 291/968 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.57GB | 297/968 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 23.29GB | 949/968 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 22.92GB | 911/968 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
