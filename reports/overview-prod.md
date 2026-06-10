# Overview: prod
*Last updated: 2026-06-11 03:05 IST*
*Data range: 2026-05-15T16:03 to 2026-06-11T03:05 (3006 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,267 | avg: 14,133 | max: 84,644 | trend: INCREASING (+3.84/hr))
```
▁▁▁▁▁▂▁▁▁▁▁▃▁▂▂▂▂▂▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▅█▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 285.1MB | avg: 229.5MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▂▃▃▂▁▂▃▂▃▂▁▄▂▂▃▃▃▄▃▁▁▂▄▂▃▂▄▃▂▁▁▁▁▂▃▂▁▁▂▃▂▁▁▂▃▃▂▁▁▅█▆▂▃▂▃▁▂▂▂▂▁▂▁▁▂▂▂▂▂▃▂▂▂▂▂▂▁▁▁▁▃▃▃▂▁▁▁▂▂▁▁▂▁▂▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,267 | 14,687 | -420 | 14,133 | 84,644 | INCREASING (+3.84/hr) |
| Heap InUse | 285.1MB | 277.5MB | +7.6MB | 229.5MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3338.0MB | 3337.8MB | +0.2MB | 2603.1MB | 6883.9MB | |
| Heap Objects | 1,740,809 | 1,308,081 | +432728 | 991,949 | 17,165,538 | |

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
| 2026-06-11 | 38 | 14,750 | 262.9MB | 317.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `compress/flate.NewWriter` | 6.17MB |
| 6 | `segmentio/kafka-go.makePartitions` | 4.04MB |
| 7 | `bufio.NewWriterSize` | 4.03MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 1.6MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 150.38GB |
| 2 | `reflect.growslice` | 142.65GB |
| 3 | `jackskj/carta.getUniqueId` | 128.73GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 114.45GB |
| 5 | `reflect.unsafe_New` | 113.79GB |
| 6 | `fmt.Sprintf` | 103.36GB |
| 7 | `fmt.(*buffer).writeString` | 89.24GB |
| 8 | `carta/value.NewCell` | 81.39GB |
| 9 | `reflect.unsafe_NewArray` | 76.85GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 62.18GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 7.93GB | 7.92GB | 7.78GB | 0B |
| `evaluation.mergeMetadata` | 4.15GB | 4.14GB | 4.07GB | 0B |
| `local.(*Client).EvaluateV2` | 12.09GB | 12.08GB | 11.86GB | 0B |
| `local.topologicalSort` | 1.67GB | 1.67GB | 1.64GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 11.51GB | 11.50GB | 11.28GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.68GB | 1.68GB | 1.66GB | 0B |
| `localEvaluation.getMapOfValue` | 11.51GB | 11.50GB | 11.28GB | 0B |
| `utils.ParseFeatureFlag` | 11.53GB | 11.52GB | 11.30GB | 512.56kB |

**Total FF alloc (current snapshot):** 62.05GB  |  **24h avg:** 60.88GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.39MB | 56/3006 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 52.2MB | 84/3006 | `████████████░░░ 83%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2657/3006 | `████████░░░░░░░ 58%` |
| 4 | `runtime.mallocgc` | 30.06MB | 2657/3006 | `███████░░░░░░░░ 48%` |
| 5 | `database/sql.convertAssignRows` | 27.21MB | 106/3006 | `██████░░░░░░░░░ 43%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3006 | `████░░░░░░░░░░░ 28%` |
| 7 | `bytes.growSlice` | 15.43MB | 2055/3006 | `███░░░░░░░░░░░░ 24%` |
| 8 | `net/http.(*Transport).dialConn` | 14.56MB | 60/3006 | `███░░░░░░░░░░░░ 23%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3006 | `███░░░░░░░░░░░░ 22%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3006 | `██░░░░░░░░░░░░░ 16%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3006 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3006 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3006 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 55.68GB | 1523/3006 | `██████░░░░░░░░░ 44%` |
| 5 | `experiment/local.topologicalSort` | 51.23GB | 375/3006 | `██████░░░░░░░░░ 40%` |
| 6 | `segmentio/kafka-go.makePartitions` | 46.63GB | 2380/3006 | `█████░░░░░░░░░░ 37%` |
| 7 | `reflect.growslice` | 45.81GB | 2218/3006 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/3006 | `█████░░░░░░░░░░ 34%` |
| 9 | `jackskj/carta.getUniqueId` | 40.08GB | 2234/3006 | `████░░░░░░░░░░░ 32%` |
| 10 | `reflect.unsafe_New` | 39.28GB | 1998/3006 | `████░░░░░░░░░░░ 31%` |

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
