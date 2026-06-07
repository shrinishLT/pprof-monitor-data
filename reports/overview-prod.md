# Overview: prod
*Last updated: 2026-06-08 05:10 IST*
*Data range: 2026-05-15T16:03 to 2026-06-08T05:10 (2168 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,677 | avg: 13,262 | max: 84,644 | trend: INCREASING (+3.74/hr))
```
▂▄▂▂▂▂▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▂▁▁▁▁▃▄▁▁▁▁▁▆▆▄▅▁▁▁▁▁▁▁▂▂▂▂▅▂▂▄▂▂▃▇█▅▂▄▁▂▁▁▁▁▁▁▁▂▁▄▁▁▁▃▅▃▂▂▂▄▃▄▁▁▁▁▃▁▁▁▁▃▄
```

**Heap InUse** (current: 287.1MB | avg: 198.8MB | max: 3154.1MB | trend: stable (+0.06MB/hr))
```
▂▃▆▂▆▂▃▂▃▃▅▅▄▃▄▅▅▄▄▁▁▂▂▂▇▅▄▄▇▅▄▅▃▄▆▄▆▇▃▂▁▁▁▁▁▃▁▃▁▄▂▂▃▂▁▃▇▅▃▅█▁▄▅▆▆▃▅▁▃▂▂▂▃▆▅▂▅▄▃▂▆▃▄▆▁▂▁▄▃▁▃▅▃▆▆
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,677 | 14,538 | +139 | 13,262 | 84,644 | INCREASING (+3.74/hr) |
| Heap InUse | 287.1MB | 286.7MB | +0.4MB | 198.8MB | 3154.1MB | stable (+0.06MB/hr) |
| Heap Sys | 3225.1MB | 3225.8MB | -0.7MB | 2329.6MB | 6883.9MB | |
| Heap Objects | 977,851 | 1,535,977 | -558126 | 895,449 | 17,165,538 | |

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
| 2026-06-07 | 288 | 15,421 | 234.3MB | 1942.9MB |
| 2026-06-08 | 63 | 14,403 | 233.8MB | 310.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 49.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `bytes.growSlice` | 3.52MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.01MB |
| 7 | `reflect.mapassign_faststr0` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `segmentio/kafka-go.makePartitions` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 54.44GB |
| 2 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 41.21GB |
| 3 | `reflect.growslice` | 38.07GB |
| 4 | `jackskj/carta.getUniqueId` | 32.53GB |
| 5 | `reflect.unsafe_New` | 29.54GB |
| 6 | `reflect.unsafe_NewArray` | 27.86GB |
| 7 | `fmt.(*buffer).writeString` | 23.44GB |
| 8 | `carta/value.NewCell` | 21.05GB |
| 9 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 19.36GB |
| 10 | `fmt.Sprintf` | 19.07GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.46GB | 1.46GB | 1.39GB | 0B |
| `evaluation.mergeMetadata` | 776.19MB | 774.19MB | 736.63MB | 0B |
| `local.(*Client).EvaluateV2` | 2.22GB | 2.21GB | 2.10GB | 0B |
| `local.topologicalSort` | 302.19MB | 301.18MB | 282.42MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.21GB | 2.21GB | 2.10GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 233.63MB | 231.13MB | 226.02MB | 0B |
| `localEvaluation.getMapOfValue` | 2.21GB | 2.21GB | 2.10GB | 0B |
| `utils.ParseFeatureFlag` | 2.21GB | 2.21GB | 2.10GB | 0B |

**Total FF alloc (current snapshot):** 11.60GB  |  **24h avg:** 11.00GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 85.72MB | 37/2168 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 64.17MB | 64/2168 | `███████████░░░░ 74%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1819/2168 | `██████░░░░░░░░░ 42%` |
| 4 | `database/sql.convertAssignRows` | 31.61MB | 86/2168 | `█████░░░░░░░░░░ 36%` |
| 5 | `runtime.mallocgc` | 20.69MB | 1819/2168 | `███░░░░░░░░░░░░ 24%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2168 | `███░░░░░░░░░░░░ 20%` |
| 7 | `bytes.growSlice` | 14.45MB | 1317/2168 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `net/http.(*Transport).dialConn` | 13.47MB | 37/2168 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2168 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 10.48MB | 38/2168 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2168 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2168 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2168 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2168 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2168 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2168 | `███░░░░░░░░░░░░ 22%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2168 | `███░░░░░░░░░░░░ 21%` |
| 8 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 20.84GB | 685/2168 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `segmentio/kafka-go.makePartitions` | 16.31GB | 1542/2168 | `█░░░░░░░░░░░░░░ 13%` |
| 10 | `reflect.growslice` | 14.27GB | 1380/2168 | `█░░░░░░░░░░░░░░ 11%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.5x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.4x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.1x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.4x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.3x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.0x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.0x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.8x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.5x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (3.1x avg)
