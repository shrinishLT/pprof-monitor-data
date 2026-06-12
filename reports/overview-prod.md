# Overview: prod
*Last updated: 2026-06-12 06:01 IST*
*Data range: 2026-05-15T16:03 to 2026-06-12T06:00 (3329 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,718 | avg: 14,337 | max: 84,644 | trend: INCREASING (+3.49/hr))
```
▂▂▁▁▁▁▁▁▁▁▁▅▅▆█▆▄▃▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 276.3MB | avg: 237.1MB | max: 3154.1MB | trend: stable (+0.10MB/hr))
```
▂▃▁▁▁▁▂▁▁▁▁▄▄▆█▆▄▃▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▂▁▁▁▁▂▁▂▁▁▁▂▁▁▁▁▁▁▁▂▁▁▁▁▁▂▁▁▂▁▁▂▂▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,718 | 14,753 | -35 | 14,337 | 84,644 | INCREASING (+3.49/hr) |
| Heap InUse | 276.3MB | 266.2MB | +10.1MB | 237.1MB | 3154.1MB | stable (+0.10MB/hr) |
| Heap Sys | 3344.2MB | 3343.8MB | +0.4MB | 2673.4MB | 6883.9MB | |
| Heap Objects | 1,190,858 | 1,152,686 | +38172 | 1,018,274 | 17,165,538 | |

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
| 2026-06-12 | 73 | 14,846 | 258.7MB | 361.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `bytes.growSlice` | 3.52MB |
| 6 | `runtime/pprof.writeHeapInternal` | 2.93MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `encoding/json.(*decodeState).literalStore` | 2.04MB |
| 9 | `bufio.NewReaderSize` | 2.02MB |
| 10 | `bufio.NewWriterSize` | 2.02MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 187.62GB |
| 2 | `reflect.growslice` | 187.41GB |
| 3 | `jackskj/carta.getUniqueId` | 169.87GB |
| 4 | `reflect.unsafe_New` | 149.93GB |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 146.27GB |
| 6 | `fmt.Sprintf` | 138.06GB |
| 7 | `fmt.(*buffer).writeString` | 117.41GB |
| 8 | `carta/value.NewCell` | 107.06GB |
| 9 | `reflect.unsafe_NewArray` | 95.69GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 84.89GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 10.34GB | 10.33GB | 10.24GB | 0B |
| `evaluation.mergeMetadata` | 5.39GB | 5.39GB | 5.34GB | 0B |
| `local.(*Client).EvaluateV2` | 15.75GB | 15.74GB | 15.59GB | 0B |
| `local.topologicalSort` | 2.19GB | 2.19GB | 2.17GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 15.03GB | 15.03GB | 14.87GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 2.16GB | 2.16GB | 2.15GB | 0B |
| `localEvaluation.getMapOfValue` | 15.03GB | 15.03GB | 14.87GB | 0B |
| `utils.ParseFeatureFlag` | 15.06GB | 15.05GB | 14.89GB | 0B |

**Total FF alloc (current snapshot):** 80.95GB  |  **24h avg:** 80.12GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 57.1MB | 62/3329 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 49.07MB | 90/3329 | `████████████░░░ 85%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2980/3329 | `█████████░░░░░░ 64%` |
| 4 | `runtime.mallocgc` | 32.27MB | 2980/3329 | `████████░░░░░░░ 56%` |
| 5 | `database/sql.convertAssignRows` | 26.19MB | 111/3329 | `██████░░░░░░░░░ 45%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3329 | `████░░░░░░░░░░░ 31%` |
| 7 | `bytes.growSlice` | 15.5MB | 2340/3329 | `████░░░░░░░░░░░ 27%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3329 | `███░░░░░░░░░░░░ 24%` |
| 9 | `net/http.(*Transport).dialConn` | 13.92MB | 74/3329 | `███░░░░░░░░░░░░ 24%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3329 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3329 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3329 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3329 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 70.12GB | 1846/3329 | `████████░░░░░░░ 56%` |
| 5 | `reflect.growslice` | 61.85GB | 2541/3329 | `███████░░░░░░░░ 49%` |
| 6 | `segmentio/kafka-go.makePartitions` | 61.26GB | 2703/3329 | `███████░░░░░░░░ 48%` |
| 7 | `jackskj/carta.getUniqueId` | 54.7GB | 2557/3329 | `██████░░░░░░░░░ 43%` |
| 8 | `reflect.unsafe_New` | 52.93GB | 2321/3329 | `██████░░░░░░░░░ 42%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/3329 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 47.14GB | 2068/3329 | `█████░░░░░░░░░░ 37%` |

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
