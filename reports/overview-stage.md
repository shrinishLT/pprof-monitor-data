# Overview: stage
*Last updated: 2026-06-04 07:00 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T07:00 (965 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,086 | avg: 14,225 | max: 28,205 | trend: stable (-0.38/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▃▁▃▄▁█▃▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▂▂▁▃▁▅▁▁▁▁▁▁▁▁▁▁▁▁▃▁▄▁▂▁▁▂▄▁▁▁▂▁▁▅▁▁▁▁▁▂▁▁▁▁▁▁▁▂▂▁▁▁▅▁
```

**Heap InUse** (current: 165.8MB | avg: 166.5MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▃▃▃▃▁▃▄▁▂▂▂▂▄▃▄▃▁▅▄▂▃▂▃▄▄▃▄▄▅▃▄▁▂▅▃▄▄▂▃▄▂▂▃▃▁▃▃▄▁▂▂▂▁▂▁▄▂▄▂▄▄▁▄▂▂▁▁▄▃▂▂▄▃▂▂█▄▂▄▄▃▁▁▁▃▁▁▂▃▃▂▂▂▁▇▃
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,086 | 14,541 | -455 | 14,225 | 28,205 | stable (-0.38/hr) |
| Heap InUse | 165.8MB | 258.6MB | -92.8MB | 166.5MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 837.3MB | 837.3MB | +0.0MB | 1291.1MB | 1805.8MB | |
| Heap Objects | 1,163,640 | 982,502 | +181138 | 885,439 | 2,707,946 | |

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
| 2026-06-04 | 14 | 14,142 | 141.9MB | 258.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 10.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `segmentio/kafka-go.makePartitions` | 4.01MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 6 | `reflect.unsafe_NewArray` | 2.53MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 1.5MB |
| 10 | `reflect.mapassign_faststr0` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 12.78GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 6.27GB |
| 3 | `segmentio/kafka-go.makePartitions` | 5.84GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 2.78GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 2.77GB |
| 6 | `internal/evaluation.mergeMetadata` | 2.69GB |
| 7 | `reflect.unsafe_NewArray` | 2.58GB |
| 8 | `go-sql-driver/mysql.(*binaryRows).readRow` | 1.92GB |
| 9 | `database/sql.convertAssignRows` | 1.74GB |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 1.46GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 6.29GB | 4.69GB | 5.33GB | 0B |
| `evaluation.mergeMetadata` | 2.69GB | 1.99GB | 2.29GB | 0B |
| `local.(*Client).EvaluateV2` | 10.56GB | 7.85GB | 8.90GB | 0B |
| `local.topologicalSort` | 1.46GB | 1.08GB | 1.21GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 12.03GB | 8.95GB | 10.10GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 8.77MB | 6.16MB | 18.20MB | 0B |
| `localEvaluation.getMapOfValue` | 12.03GB | 8.95GB | 10.10GB | 0B |
| `utils.ParseFeatureFlag` | 83.76MB | 71.84MB | 95.90MB | 0B |

**Total FF alloc (current snapshot):** 45.16GB  |  **24h avg:** 38.05GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 963/965 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.9MB | 37/965 | `███████░░░░░░░░ 48%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.29MB | 24/965 | `███████░░░░░░░░ 47%` |
| 4 | `runtime.mallocgc` | 13.53MB | 959/965 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 12.06MB | 39/965 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/965 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/965 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/965 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 961/965 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/965 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 95.8GB | 956/965 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 66.78GB | 306/965 | `██████████░░░░░ 69%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 66.06GB | 307/965 | `██████████░░░░░ 68%` |
| 4 | `internal/evaluation.mergeMetadata` | 65.59GB | 301/965 | `██████████░░░░░ 68%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 50.92GB | 910/965 | `███████░░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 41.45GB | 955/965 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.67GB | 291/965 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.57GB | 297/965 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 23.36GB | 946/965 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 22.97GB | 908/965 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
