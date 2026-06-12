# Overview: prod
*Last updated: 2026-06-12 19:07 IST*
*Data range: 2026-05-15T16:03 to 2026-06-12T19:07 (3486 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,844 | avg: 14,442 | max: 84,644 | trend: INCREASING (+3.38/hr))
```
▁▁▁▃▂▂▁▁▁▁▁▁▁▁▁▁▁▁▃▅▄▅▃▂▂▃▄▂▅▁▂▁▂▁▁▂▁▁▁▄▂▃▂▂▂▃▂▆█▅▄▄▃▃▃▃▃▅▃▄▁▂▃▁▁▃▂▁▁▁▁▁▁▁▁▂▃▁▃▁▁▁▁▃▃▁▁▁▂▂▃▁▂▂▃▂
```

**Heap InUse** (current: 155.2MB | avg: 238.6MB | max: 3154.1MB | trend: stable (+0.09MB/hr))
```
▅▅▅▆▆█▅▆▅▂▁▁▂▂▁▂▁▁▄▅▃▅▆▂▂▃▅▄▄▂▂▂▂▁▃▃▂▅▂▃▂▃▄▃▃▂▄▇▅▅▃▄▄▄▅▄▄▄▃▄▄▃▃▄▃▃▃▂▃▃▄▂▁▂▃▂▄▂▃▁▃▂▂▃▃▂▁▂▂▄▂▃▄▃▄▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,844 | 15,112 | -268 | 14,442 | 84,644 | INCREASING (+3.38/hr) |
| Heap InUse | 155.2MB | 213.2MB | -58.0MB | 238.6MB | 3154.1MB | stable (+0.09MB/hr) |
| Heap Sys | 694.9MB | 694.3MB | +0.6MB | 2634.1MB | 6883.9MB | |
| Heap Objects | 420,949 | 788,817 | -367868 | 1,024,238 | 17,165,538 | |

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
| 2026-06-08 | 288 | 16,327 | 305.6MB | 2130.6MB |
| 2026-06-09 | 288 | 16,163 | 304.7MB | 1487.7MB |
| 2026-06-10 | 287 | 16,453 | 305.9MB | 1442.9MB |
| 2026-06-11 | 288 | 16,393 | 314.0MB | 1403.5MB |
| 2026-06-12 | 230 | 16,083 | 266.5MB | 1418.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 13.41MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `runtime.mallocgc` | 8.01MB |
| 6 | `bytes.growSlice` | 4.02MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.01MB |
| 9 | `bufio.NewReaderSize` | 2.01MB |
| 10 | `reflect.mapassign_faststr0` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 9.78GB |
| 2 | `fmt.Sprintf` | 6.79GB |
| 3 | `jackskj/carta.getUniqueId` | 5.09GB |
| 4 | `reflect.growslice` | 5.03GB |
| 5 | `reflect.unsafe_NewArray` | 5.0GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 4.78GB |
| 7 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 4.72GB |
| 8 | `reflect.unsafe_New` | 4.26GB |
| 9 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 3.77GB |
| 10 | `fmt.Sprint` | 3.31GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 711.86MB | 701.67MB | 507.44MB | 0B |
| `evaluation.mergeMetadata` | 371.09MB | 367.09MB | 264.04MB | 0B |
| `local.(*Client).EvaluateV2` | 1.08GB | 1.06GB | 786.55MB | 0B |
| `local.topologicalSort` | 161.06MB | 156.47MB | 114.22MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1017.07MB | 999.61MB | 727.76MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 176.48MB | 172.40MB | 119.29MB | 0B |
| `localEvaluation.getMapOfValue` | 1017.07MB | 999.61MB | 727.76MB | 0B |
| `utils.ParseFeatureFlag` | 1021.57MB | 1003.61MB | 730.58MB | 512.56kB |

**Total FF alloc (current snapshot):** 5.45GB  |  **24h avg:** 3.88GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 52.6MB | 68/3486 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 47.12MB | 94/3486 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3137/3486 | `██████████░░░░░ 69%` |
| 4 | `runtime.mallocgc` | 32.0MB | 3137/3486 | `█████████░░░░░░ 60%` |
| 5 | `database/sql.convertAssignRows` | 24.89MB | 118/3486 | `███████░░░░░░░░ 47%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3486 | `█████░░░░░░░░░░ 34%` |
| 7 | `bytes.growSlice` | 15.65MB | 2477/3486 | `████░░░░░░░░░░░ 29%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3486 | `████░░░░░░░░░░░ 26%` |
| 9 | `net/http.(*Transport).dialConn` | 14.04MB | 81/3486 | `████░░░░░░░░░░░ 26%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3486 | `███░░░░░░░░░░░░ 20%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3486 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3486 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3486 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 72.99GB | 1922/3486 | `████████░░░░░░░ 58%` |
| 5 | `reflect.growslice` | 63.48GB | 2698/3486 | `███████░░░░░░░░ 50%` |
| 6 | `segmentio/kafka-go.makePartitions` | 62.74GB | 2860/3486 | `███████░░░░░░░░ 50%` |
| 7 | `jackskj/carta.getUniqueId` | 56.25GB | 2714/3486 | `██████░░░░░░░░░ 44%` |
| 8 | `reflect.unsafe_New` | 54.13GB | 2478/3486 | `██████░░░░░░░░░ 43%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/3486 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 48.65GB | 2183/3486 | `█████░░░░░░░░░░ 38%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
