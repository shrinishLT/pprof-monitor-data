# Overview: prod
*Last updated: 2026-06-11 00:06 IST*
*Data range: 2026-05-15T16:03 to 2026-06-11T00:05 (2970 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,761 | avg: 14,126 | max: 84,644 | trend: INCREASING (+3.95/hr))
```
▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▂▂▁▁▂▂▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▃▁▂▂▂▂▂▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▅█▂▂▂▁▁▁▁▁▁
```

**Heap InUse** (current: 293.6MB | avg: 229.1MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▁▂▃▂▃▁▂▁▂▃▃▂▁▁▂▁▂▁▁▂▃▁▂▃▄▃▂▃▃▂▂▁▂▂▃▃▂▃▃▂▁▂▃▂▃▂▁▄▂▂▃▃▃▄▃▁▁▂▄▂▃▂▄▃▂▁▁▁▁▂▃▂▁▁▂▃▂▁▁▂▃▃▂▁▁▅█▆▂▃▂▃▁▂▂▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,761 | 14,827 | -66 | 14,126 | 84,644 | INCREASING (+3.95/hr) |
| Heap InUse | 293.6MB | 270.6MB | +23.0MB | 229.1MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3326.4MB | 3326.1MB | +0.3MB | 2594.2MB | 6883.9MB | |
| Heap Objects | 1,493,991 | 1,315,621 | +178370 | 990,280 | 17,165,538 | |

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
| 2026-06-11 | 2 | 14,794 | 282.1MB | 293.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `bufio.NewReaderSize` | 3.53MB |
| 7 | `bufio.NewWriterSize` | 3.04MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 1.6MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 146.36GB |
| 2 | `reflect.growslice` | 139.43GB |
| 3 | `jackskj/carta.getUniqueId` | 125.36GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 112.93GB |
| 5 | `reflect.unsafe_New` | 110.79GB |
| 6 | `fmt.Sprintf` | 100.72GB |
| 7 | `fmt.(*buffer).writeString` | 87.6GB |
| 8 | `carta/value.NewCell` | 79.19GB |
| 9 | `reflect.unsafe_NewArray` | 74.76GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 60.21GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 7.70GB | 7.69GB | 7.52GB | 0B |
| `evaluation.mergeMetadata` | 4.03GB | 4.03GB | 3.94GB | 0B |
| `local.(*Client).EvaluateV2` | 11.75GB | 11.73GB | 11.47GB | 0B |
| `local.topologicalSort` | 1.63GB | 1.62GB | 1.59GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 11.17GB | 11.15GB | 10.91GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.65GB | 1.65GB | 1.60GB | 0B |
| `localEvaluation.getMapOfValue` | 11.17GB | 11.15GB | 10.91GB | 0B |
| `utils.ParseFeatureFlag` | 11.19GB | 11.17GB | 10.93GB | 0B |

**Total FF alloc (current snapshot):** 60.28GB  |  **24h avg:** 58.87GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 64.46MB | 54/2970 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 53.93MB | 81/2970 | `████████████░░░ 83%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2621/2970 | `████████░░░░░░░ 56%` |
| 4 | `runtime.mallocgc` | 29.78MB | 2621/2970 | `██████░░░░░░░░░ 46%` |
| 5 | `database/sql.convertAssignRows` | 27.89MB | 103/2970 | `██████░░░░░░░░░ 43%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2970 | `████░░░░░░░░░░░ 27%` |
| 7 | `bytes.growSlice` | 15.58MB | 2025/2970 | `███░░░░░░░░░░░░ 24%` |
| 8 | `net/http.(*Transport).dialConn` | 14.56MB | 60/2970 | `███░░░░░░░░░░░░ 22%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2970 | `███░░░░░░░░░░░░ 21%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2970 | `██░░░░░░░░░░░░░ 16%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2970 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2970 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2970 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 54.28GB | 1487/2970 | `██████░░░░░░░░░ 43%` |
| 5 | `experiment/local.topologicalSort` | 51.23GB | 375/2970 | `██████░░░░░░░░░ 40%` |
| 6 | `segmentio/kafka-go.makePartitions` | 45.07GB | 2344/2970 | `█████░░░░░░░░░░ 36%` |
| 7 | `reflect.growslice` | 44.25GB | 2182/2970 | `█████░░░░░░░░░░ 35%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2970 | `█████░░░░░░░░░░ 34%` |
| 9 | `jackskj/carta.getUniqueId` | 38.66GB | 2198/2970 | `████░░░░░░░░░░░ 30%` |
| 10 | `reflect.unsafe_New` | 37.94GB | 1962/2970 | `████░░░░░░░░░░░ 30%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.2x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.7x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.4x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
