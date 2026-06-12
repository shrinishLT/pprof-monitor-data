# Overview: prod
*Last updated: 2026-06-12 05:31 IST*
*Data range: 2026-05-15T16:03 to 2026-06-12T05:30 (3323 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,419 | avg: 14,337 | max: 84,644 | trend: INCREASING (+3.50/hr))
```
▁▁▁▁▁▂▂▂▁▁▁▁▁▁▁▁▁▅▅▆█▆▄▃▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 275.6MB | avg: 237.1MB | max: 3154.1MB | trend: stable (+0.10MB/hr))
```
▁▂▁▁▂▃▂▃▁▁▁▁▂▁▁▁▁▄▄▆█▆▄▃▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▂▁▁▁▁▂▁▂▁▁▁▂▁▁▁▁▁▁▁▂▁▁▁▁▁▂▁▁▂▁▁▂▂▁▁▁▁▁▁▂▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,419 | 14,585 | -166 | 14,337 | 84,644 | INCREASING (+3.50/hr) |
| Heap InUse | 275.6MB | 223.6MB | +52.0MB | 237.1MB | 3154.1MB | stable (+0.10MB/hr) |
| Heap Sys | 3343.8MB | 3343.3MB | +0.5MB | 2672.2MB | 6883.9MB | |
| Heap Objects | 1,610,826 | 811,362 | +799464 | 1,018,249 | 17,165,538 | |

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
| 2026-06-12 | 67 | 14,864 | 259.3MB | 361.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `bufio.NewWriterSize` | 2.52MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `bytes.growSlice` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 186.86GB |
| 2 | `reflect.growslice` | 182.42GB |
| 3 | `jackskj/carta.getUniqueId` | 166.14GB |
| 4 | `reflect.unsafe_New` | 146.44GB |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 144.9GB |
| 6 | `fmt.Sprintf` | 137.56GB |
| 7 | `fmt.(*buffer).writeString` | 114.38GB |
| 8 | `carta/value.NewCell` | 104.6GB |
| 9 | `reflect.unsafe_NewArray` | 95.3GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 84.42GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 10.32GB | 10.32GB | 10.21GB | 0B |
| `evaluation.mergeMetadata` | 5.38GB | 5.38GB | 5.33GB | 0B |
| `local.(*Client).EvaluateV2` | 15.71GB | 15.71GB | 15.54GB | 0B |
| `local.topologicalSort` | 2.19GB | 2.19GB | 2.16GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 15.00GB | 14.99GB | 14.82GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 2.16GB | 2.16GB | 2.15GB | 0B |
| `localEvaluation.getMapOfValue` | 15.00GB | 14.99GB | 14.82GB | 0B |
| `utils.ParseFeatureFlag` | 15.02GB | 15.02GB | 14.84GB | 0B |

**Total FF alloc (current snapshot):** 80.77GB  |  **24h avg:** 79.87GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 57.1MB | 62/3323 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 49.07MB | 90/3323 | `████████████░░░ 85%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2974/3323 | `█████████░░░░░░ 64%` |
| 4 | `runtime.mallocgc` | 32.24MB | 2974/3323 | `████████░░░░░░░ 56%` |
| 5 | `database/sql.convertAssignRows` | 26.19MB | 111/3323 | `██████░░░░░░░░░ 45%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3323 | `████░░░░░░░░░░░ 31%` |
| 7 | `bytes.growSlice` | 15.53MB | 2334/3323 | `████░░░░░░░░░░░ 27%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3323 | `███░░░░░░░░░░░░ 24%` |
| 9 | `net/http.(*Transport).dialConn` | 13.92MB | 74/3323 | `███░░░░░░░░░░░░ 24%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3323 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3323 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3323 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3323 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 69.87GB | 1840/3323 | `████████░░░░░░░ 55%` |
| 5 | `reflect.growslice` | 61.56GB | 2535/3323 | `███████░░░░░░░░ 49%` |
| 6 | `segmentio/kafka-go.makePartitions` | 60.98GB | 2697/3323 | `███████░░░░░░░░ 48%` |
| 7 | `jackskj/carta.getUniqueId` | 54.44GB | 2551/3323 | `██████░░░░░░░░░ 43%` |
| 8 | `reflect.unsafe_New` | 52.69GB | 2315/3323 | `██████░░░░░░░░░ 42%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/3323 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 46.95GB | 2062/3323 | `█████░░░░░░░░░░ 37%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
