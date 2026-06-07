# Overview: prod
*Last updated: 2026-06-07 19:20 IST*
*Data range: 2026-05-15T16:03 to 2026-06-07T19:20 (2050 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,144 | avg: 13,202 | max: 84,644 | trend: INCREASING (+4.05/hr))
```
▄▃▃▃▃▃▃▃▃▃▅▅▅▇█▇▂▁▁▂▂▁▃▂▃▁▁▂▁▁▁▁▂▁▁▁▁▁▂▁▁▁▂▂▁▂▂▁▁▁▁▂▁▃▄▂▃▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁
```

**Heap InUse** (current: 188.5MB | avg: 196.8MB | max: 3154.1MB | trend: stable (+0.05MB/hr))
```
▆▅▆▇▇▄▄▅▆▅▆▇▅▆▆▆▃▃▃▃▂▅▇▅▄▃▃▂▆▅▃▂▅▅▂▄▂▂▅▂▂▄▃▄▂▃▆▂█▅▅▄▂▅▅▆▄▁▃▂▅▅▃▄▁▅▂▅▁▁▃▃▃▄▁▂▃▃▃▄▂▁▃▁▂▁▂▃▃▃▁▁▄▅▄▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,144 | 14,081 | +63 | 13,202 | 84,644 | INCREASING (+4.05/hr) |
| Heap InUse | 188.5MB | 266.0MB | -77.5MB | 196.8MB | 3154.1MB | stable (+0.05MB/hr) |
| Heap Sys | 3220.7MB | 3220.8MB | -0.1MB | 2278.2MB | 6883.9MB | |
| Heap Objects | 589,020 | 1,745,447 | -1156427 | 885,624 | 17,165,538 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 68 | 16,073 | 267.1MB | 501.2MB |
| 2026-05-22 | 50 | 16,200 | 234.4MB | 962.7MB |
| 2026-05-23 | 48 | 14,757 | 174.9MB | 359.1MB |
| 2026-05-24 | 48 | 14,694 | 189.5MB | 689.3MB |
| 2026-05-25 | 48 | 15,445 | 248.9MB | 478.8MB |
| 2026-05-26 | 46 | 15,843 | 216.2MB | 639.8MB |
| 2026-05-27 | 47 | 11,771 | 179.8MB | 615.8MB |
| 2026-05-28 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-05-29 | 49 | 370 | 6.8MB | 333.9MB |
| 2026-05-30 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-05-31 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-06-01 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-06-02 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-06-03 | 54 | 2,097 | 29.7MB | 299.4MB |
| 2026-06-04 | 288 | 16,555 | 265.7MB | 2823.8MB |
| 2026-06-05 | 287 | 15,969 | 239.1MB | 3154.1MB |
| 2026-06-06 | 288 | 15,841 | 221.6MB | 1932.8MB |
| 2026-06-07 | 233 | 15,705 | 233.9MB | 1942.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 49.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 5.02MB |
| 6 | `compress/flate.NewWriter` | 3.53MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `reflect.mapassign_faststr0` | 1.0MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 548.84kB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 41.09GB |
| 2 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 40.03GB |
| 3 | `reflect.growslice` | 34.25GB |
| 4 | `jackskj/carta.getUniqueId` | 29.48GB |
| 5 | `reflect.unsafe_New` | 26.44GB |
| 6 | `fmt.(*buffer).writeString` | 21.34GB |
| 7 | `reflect.unsafe_NewArray` | 20.99GB |
| 8 | `carta/value.NewCell` | 18.92GB |
| 9 | `fmt.Sprintf` | 16.45GB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 14.21GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.14GB | 1.14GB | 1.08GB | 0B |
| `evaluation.mergeMetadata` | 605.65MB | 605.65MB | 567.68MB | 0B |
| `local.(*Client).EvaluateV2` | 1.73GB | 1.73GB | 1.64GB | 0B |
| `local.topologicalSort` | 236.85MB | 236.85MB | 224.87MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.74GB | 1.74GB | 1.66GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 172.79MB | 172.79MB | 154.25MB | 0B |
| `localEvaluation.getMapOfValue` | 1.74GB | 1.74GB | 1.66GB | 0B |
| `utils.ParseFeatureFlag` | 1.74GB | 1.74GB | 1.66GB | 0B |

**Total FF alloc (current snapshot):** 9.08GB  |  **24h avg:** 8.61GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 85.72MB | 37/2050 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 66.16MB | 62/2050 | `███████████░░░░ 77%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1701/2050 | `██████░░░░░░░░░ 42%` |
| 4 | `database/sql.convertAssignRows` | 34.17MB | 79/2050 | `█████░░░░░░░░░░ 39%` |
| 5 | `runtime.mallocgc` | 18.69MB | 1701/2050 | `███░░░░░░░░░░░░ 21%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2050 | `███░░░░░░░░░░░░ 20%` |
| 7 | `bytes.growSlice` | 15.03MB | 1253/2050 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `net/http.(*Transport).dialConn` | 13.47MB | 37/2050 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2050 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 10.48MB | 38/2050 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2050 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2050 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2050 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2050 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2050 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2050 | `███░░░░░░░░░░░░ 22%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2050 | `███░░░░░░░░░░░░ 21%` |
| 8 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 16.77GB | 567/2050 | `██░░░░░░░░░░░░░ 13%` |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 14.23GB | 969/2050 | `█░░░░░░░░░░░░░░ 11%` |
| 10 | `segmentio/kafka-go.makePartitions` | 13.7GB | 1424/2050 | `█░░░░░░░░░░░░░░ 10%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.6x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.4x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.1x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.4x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.4x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.0x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.0x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.9x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.5x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (3.2x avg)
